<template>
  <div class="home">
    <Nav></Nav>

    <div class="wall">
      <p>Fostering the Mutual Growth of the<span>Cyberspace</span></p>
      <button><a href="">join us</a></button>
    

    </div>

    <div class="about-container">
      <div class="frame-1">
          <img class="vertical-bar-2" :src="verticlbar2">
          <div class="about">About us</div>
      </div>
      <p>CEANet, the Cybersecurity Education and Awareness 
          Network, is on a mission to empower and educate students 
          and individuals about the critical importance of 
          cybersecurity. Our goal is to equip the younger 
          generation with the knowledge and skills needed to 
          navigate the ever-evolving digital landscape securely.
      </p>

    </div>


    <img :src="Group1" alt="group 1">
    
    <div class="left-shield"></div>
    <div class="right-shield"></div>

    <img class="what-illustartion" :src="Whatwedoillustartion" alt="">

    <div class="frame-1 what">
      <img class="vertical-bar-2" :src="verticlbar2">
      <div class="about">What we do</div>
    </div>

    <div class="what-container">
      <img :src="Virtual" alt="">
      <img :src="Physical" alt="">
      <img :src="Careersupport" alt="">
      <p class="what-we-do-text">Virtual Engagements</p>
      <p class="what-we-do-text">Outdoor Engagements</p>
      <p class="what-we-do-text">Career Networking</p>
      
    </div>

    <div class="frame-2">

      <div class="frame-2-bar"></div>
      <div class="frame-2-1">
          <p class="be">become a member</p>
          <p class="be2">Ceanet’s membership is 
          open to all from diverse backgound and profession.</p>
      </div>
      <div class="frame-2-bar"></div>
    </div>
 
    <div class="pp-grid">    
        <div class="pp-container">
          <div class="pp-header">
              <a href="https://forms.gle/DTQA6qEuvYAnZaeQ7"><p class="pp-text">Packet Pioneers</p></a>
          </div>
          <div class="pp-frame">
              <p class="pp-logo-text">These are entry individuals with least privieges 
            and are of larger numbers. They have direct impact 
            of the community’s resources and influence, reflecting
              the community’s prospect and 
            serving as the frame for wide reaching activities.
            </p>
            <img class="pp-logo" :src="packetpioneers" alt="packet pioneers">
            <img class="pp" :src="PP" alt="">
          </div>
            
        </div>
        
        <div class="pp-container">
          <div class="pp-header">
              <a href=""><p class="pp-text gate">Gateway Mentors</p></a>
          </div>
          <div class="pp-frame">
            <p class="pp-logo-text">These individuals with extra 
                privileges from diverse backgrounds, skill set 
                and locations who are actively participating in 
                the community’s process and developments. Offering 
                hands and a link between the 
                Network Architects and Packet Pioneers.</p>
            <img class="pp-logo" :src="GatewayMentors" alt="packet pioneers">
            <img class="gm" :src="gm" alt="">

          </div>
        </div>

    </div>

    <Footer></Footer>
  </div>
</template>

<script>
// @ is an alias to /src
import Nav from '@/components/Nav.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'HomeView',
  components: {
    Nav,
    Footer
  },
  data() {
    return {
      verticlbar2: require('@/assets/images/verticl-bar-2.png'),
      Group1: require('@/assets/images/Group 1.png'),
      Whatwedoillustartion: require('@/assets/images/What-we-do-illustartion.svg'),
      verticlbar2: require('@/assets/images/verticl-bar-2.png'),
      Virtual: require('@/assets/images/Virtual.svg'),
      Physical: require('@/assets/images/Physical.svg'),
      Careersupport: require('@/assets/images/Career-support.svg'),
      packetpioneers: require('@/assets/images/packet pioneers 1.svg'),
      PP: require('@/assets/images/PP.svg'),
      GatewayMentors: require('@/assets/images/Gateway Mentors 1.svg'),
      gm: require('@/assets/images/gm.svg'),

    }
  }
}
</script>


<style scoped>

* {
  box-sizing: border-box;
  
}

a {
  text-decoration: none;
}


.wall {
    max-width: inherit;
    height: 846px;
    background-image: url('/src/assets/images/Rectangle\ 7.png');
    border: 1px solid #190340;
    background-repeat: no-repeat;
    background-size: cover;
}

.wall p {
    color: white;
    font-size: 96px;
    font-style: normal;
    font-weight: bolder;
    line-height: normal;
    margin-top: 83px;
    margin-left: 115px;
    width: 881px;
}

.wall span{
    color: #3c3;
    font-size: 96px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
    margin-top: 83px;
    margin-left: 115px;
    width: 881px;
    margin-left: 20px;
}

.wall button {
    position: relative;
    top: 36px;
    left: 1040px;
    /* width: 133px; */
    height: 57px;
    background-color: #3C3;
    font-family: Saira;
    text-transform: uppercase;
    border: 1px solid #3C3;
    border-radius: 10px;
    font-size: 36px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
    
}

.wall button a {
    color: white;
    text-decoration: none;
    font-family: Saira;
}


.left-shield {
    position: absolute;
    top: 1300px;
    width: 470px;
    height: 626px;
    background-image: url('/src/assets/images/left-shield.png');
     background-repeat: no-repeat;
    /* border: 1px solid red; */
    z-index: -1;
}

.right-shield {
    position: absolute;
    top: 1980px;
    left: 1150px;
    background-image: url('/src/assets/images/right-shield.png');
    width: 470px;
    height: 626px;
    z-index: -1;
    background-repeat: no-repeat;
}

.right-shield + img {
    position: relative;
    right: 450px;
    top: 350px;
    /* border: 1px solid red; */
}


.about-container {
    position: relative;
    /* border: 1px solid black; */
    width: 500px;
    top: 160px;
    left: 90px;
}
.frame-1 {
    position: relative;
    /* top: 161px; */
    width: 400px;
    display: flex;
    align-items: center;
}
.vertical-bar-2 {
    position: relative;

}

.about {
    padding: 10px;
    border-radius: 10px;
    background: #190340;
    color: white;
    font-size: 30px;
    font-family: 'Red Hat Text';
    font-style: normal;
    font-weight: 800;
    line-height: normal;
    text-transform: uppercase;
    text-align: center;
    position: relative;
    margin-left: 20px;
    display: inline-block;
  
}

.frame-1 + p {
    color: #000;
    position: relative;
    /* top: 130px; */
    width: 544px;
    height: 360px;
    text-align: justify;
    font-size: 28px;
    font-style: normal;
    font-weight: 400;
    line-height: 162.122%;
}


.about-container + img {
    position: relative;
    left: 754px;
    /* border: 1px solid red; */
    bottom: 420px;
}

.frame-2 {
    margin: auto;
    width: 1182px;
    height: 175px;
    /* border: 1px solid red; */
    position: relative;
    top: 164px;
    display: flex;
    flex-direction: row;
    gap: 25px;

}

.be {
    color: #FFF;
    text-align: center;
    font-size: 36px;
    font-style: bold;
    font-weight: bolder;
    line-height: normal;
    text-transform: uppercase;
    position: relative;
    margin-top: 10px;
    margin-bottom: 0;
}

.be2 {
    color: #FFF;
    font-size: 30px;
    font-style: normal;
    font-weight: 800;
    line-height: normal;
    position: relative;
    margin-top: 0;
    text-align: center;
}

.what {
    position: relative;
    top: -200px;
    left: 730px;
}

.what-container {
    width: 590px;
    height: 262px;
    position: relative;
    left: 730px;
    top: -70px;
    display: grid;
    grid-template-columns: repeat(3, 1fr) ;
    grid-template-rows: repeat(3, 1fr);
    /* border: 1px solid red; */
}

.what-we-do-text {
    width: 163px;
    height: 60px;
    color: #000;
    text-align: center;
    font-family: Red Hat Text;
    font-size: 24px;
    font-style: normal;
    font-weight: 500;
    line-height: 30px; /* 125% */
    /* border: 1px solid red; */
}

.frame-2-bar{
    background-color: #3C3;
    width: 11px;
    height: 175px;
    position: relative;
}


.frame-2-1 {
    margin-top: 30px;
    padding: 20px 10px 30px 10px;
    background-color: #190340;
    border-radius: 10px;
    width: 1110px;
    bottom: 17px;
    /* height: 113px; */
    position: relative;
}

.pp-grid {
    display: grid;
    position: relative;
    gap: 20px;
    margin-left: -8px;
    /* margin: auto; */
    /* grid-template-rows: repeat(2, 1fr); */
    grid-template-columns: repeat(2, 1fr);
}

.pp-container {
    
}

.pp-frame {
    position: relative;
    top: 220px;
    left: 80px;
    width: 500px;
    height: 410px;
    background-color: white;
    border-radius: 25px;
    display: inline-block;
    padding: 30px;
    transition: 1s;
    border: 2px solid #D3F4D3;
}


.pp-frame:hover {
    box-shadow: 14px 8px 25.6px 11px #D3F4D3;
    transition: 1s;
}

.pp-header {
    position: relative;
    top: 245px;
    left: 165px;
    width: 324px;
    height: 58px;
    background-color: #3C3;
    border-radius: 5px;
    padding: 5px 25px;
    bottom: 25px;
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 2;
}

.pp-text {
    width: 251px;
    height: 41px;
    position: relative;
    color: #190340;
    font-family: Red Hat Text;
    font-size: 32px;
    font-style: normal;
    text-align: center;
    font-weight: 500;
    line-height: normal;
}

.pp {
    position: relative;
    display: block;
    height: 30px;
    width: 156px;
    top: -260px;
    left: -56px;
    transition: 2.5s;
}


.gate {
    width: 264px;
}


.gm {
    position: relative;
    display: block;
    height: 30px;
    width: 156px;
    top: -260px;
    right: 32px;
    transition: 2.5s;
}

.pp-logo {
    position: relative;
    top: -230px;
    left: 70px;
    width: 290px;
    height: 335px;
    justify-self: center;
    /* align-self: center; */
    z-index: 2;
    transition: 2.5s;
    
}


.pp-frame:hover img{
    opacity: 0;
    /* transition: 1.5s; */
} 


.pp-logo-text {
  position: relative;
  top: -20px;
  width: 432px;
  height: 196px;
  /* text-align: center; */
  color: #000;
  font-family: Red Hat Text;
  font-size: 28px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  letter-spacing: 0.28px;
  opacity: 0;
  z-index: 3;

}

.pp-frame:hover .pp-logo-text {
    opacity: 1;
    transition: 1s ease;
}
</style>
