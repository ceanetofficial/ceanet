<template>
    <div class="about">
        <Nav/>


        <div class="wall2">
            <img :src="Group1" alt="group 1">
        </div>

            

        <div class="frame1">

            <div class="frame-1-bar"></div>
            <div class="frame-1-1">
                <p class="p">About us</p>
            </div>
            <div class="frame-1-bar"></div>
        </div>

        <p class="what-we">WHAT WE BELIEVE IN</p>

        <p class="abt-t">Cybersecurity is an interesting and uplifting 
            area of digital life.
            At CEANet, we believe that cybersecurity education 
            should be accessible to all, irrespective of creed, 
            class, gender. We offer engaging workshops, 
            interactive training sessions, and comprehensive 
            resources to make cybersecurity concepts 
            understandable and relatable to students and 
            community members from diverse backgrounds. 
            By raising awareness about cyber threats and
            safe online practices, we're 
            building a resilient digital society.
        </p>

        <div class="net-arc">
            <p>NETWORK ARCHITECTS</p>
        </div>

        <div class="net-arc-text">
            <p class="arc-p">This is our visionary founders that provide the strategic vision and leadership the community. As Network Architects, they to guide the community through it mission to empower individuals with cybersecurity knowledge.</p>
            <p class="arc-p"> In essence, they lay the founding stones to which the lower levels of community - Gateway Mentors and Packet Pioneers -  involvements are being operated. </p>
        </div>

        <div class="net-arc-container-1">
            <div class="net-arc-frame">
                <div class="inner-frame-1"> 
                    <img class="net-arc-logo" :src="netArc" alt="">

                    <div class="link-icon-background">

                        <a href="https://www.linkedin.com/company/ceanetofficial/"><img class="linkedin" :src="linkedin" alt="LinkedIn icon"></a>

                    </div>
                    
                </div>

                <div class="inner-frame-2">
                    <p class="net-arc-name">YUSUF ABDULRAHMAN</p>
                    <p class="net-arc-position">[CTO/Co-Founder]</p>

                </div>

            </div>

            <div class="net-arc-frame">
                <div class="inner-frame-1"> 
                    <img class="net-arc-logo" :src="netArc" alt="">

                    <div class="link-icon-background">

                        <a href="https://www.linkedin.com/company/ceanetofficial/"><img class="linkedin" :src="linkedin" alt="LinkedIn icon"></a>

                    </div>
                    
                </div>

                <div class="inner-frame-2">
                    <p class="net-arc-name">YUSUF ABDULRAHMAN</p>
                    <p class="net-arc-position">[CTO/Co-Founder]</p>

                </div>

            </div>

            <div class="net-arc-frame">
                <div class="inner-frame-1"> 
                    <img class="net-arc-logo" :src="netArc" alt="">

                    <div class="link-icon-background">

                        <a href="https://www.linkedin.com/company/ceanetofficial/"><img class="linkedin" :src="linkedin" alt="LinkedIn icon"></a>

                    </div>
                    
                </div>

                <div class="inner-frame-2">
                    <p class="net-arc-name">YUSUF ABDULRAHMAN</p>
                    <p class="net-arc-position">[CTO/Co-Founder]</p>

                </div>

            </div>


        </div>
        <div class="net-arc-container-1">

             <div class="net-arc-frame">
                <div class="inner-frame-1"> 
                    <img class="net-arc-logo" :src="netArc" alt="">

                    <div class="link-icon-background">

                        <a href="https://www.linkedin.com/company/ceanetofficial/"><img class="linkedin" :src="linkedin" alt="LinkedIn icon"></a>

                    </div>
                    
                </div>

                <div class="inner-frame-2">
                    <p class="net-arc-name">YUSUF ABDULRAHMAN</p>
                    <p class="net-arc-position">[CTO/Co-Founder]</p>

                </div>

            </div>

            <div class="net-arc-frame">
                <div class="inner-frame-1"> 
                    <img class="net-arc-logo" :src="netArc" alt="">

                    <div class="link-icon-background">

                        <a href="https://www.linkedin.com/company/ceanetofficial/"><img class="linkedin" :src="linkedin" alt="LinkedIn icon"></a>

                    </div>
                    
                </div>

                <div class="inner-frame-2">
                    <p class="net-arc-name">YUSUF ABDULRAHMAN</p>
                    <p class="net-arc-position">[CTO/Co-Founder]</p>

                </div>

            </div>



        </div>

        <img class="left-shield-pp" :src="leftshield" alt="">

        <img class="right-shield-pp" :src="rightshield" alt="">

        <Footer/>
    </div>


</template>



<script>

import Nav from '@/components/Nav.vue'
import Footer from '@/components/Footer.vue'


export default {
  components: {
    Nav,
    Footer
  },
  data() {
    return {
        Group1: require('@/assets/images/about-illustration.png'),
        netArc: require('@/assets/images/netArc.svg'),
        linkedin: require('@/assets/images/linkedin.svg'),
        leftshield: require('@/assets/images/left-shield-pp.svg'),
        rightshield: require('@/assets/images/right-shield-pp.svg'),

    }
  }
}
</script>


<style>
@import url('https://fonts.googleapis.com/css2?family=Red+Hat+Display:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,300;1,400;1,500;1,600;1,700;1,800&family=Red+Hat+Text:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600&family=Saira:ital,wght@0,100;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap');

* {
    box-sizing: border-box;
    font-family: 'Red Hat Display', sans-serif;
    /* border: 1px solid red; */
}


.wall2 {
    max-width: inherit;
    height: 846px;
    background-image: url(/src/assets/images/about-wall.png); 
    /* border: 1px solid #190340; */
    display: flex;
    justify-content: center;
    align-items: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.wall2 img {
    width: 900px;
    height: 690px;
    /* display: none; */
}

.about-us-container{
    max-width: inherit;
    height: 846px;
    background-color: #190340;
}

.frame1 {
    margin: auto;
    width: 470px;
    height: 175px;
    /* border: 1px solid red; */
    position: relative;
    display: flex;
    flex-direction: row;
    gap: 25px;
    align-items: center;
    justify-self: center;

}

.p {
    color: white;
    text-align: center;
    font-size: 64px;
    font-style: normal;
    font-weight: 800;
    line-height: 130.315%; /* 83.402px */
    letter-spacing: 0.64px;
    text-transform: uppercase;
    /* margin-top: 10px; */
    /* margin-bottom: 0; */
}


.frame-1-bar{
    background-color: #3C3;
    width: 11px;
    height: 122px;
    position: relative;
}


.frame-1-1 {
    background-color: #0C0021;
    border-radius: 10px;
    width: 430px;
    height: 123px;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
}

.what-we {
    padding: 10px;
    border-radius: 10px;
    background: #0C0021;
    color: white;
    font-size: 30px;
    font-family: 'Red Hat Text';
    font-style: normal;
    font-weight: 800;
    line-height: normal;
    text-transform: uppercase;
    text-align: center;
    position: relative;
    margin-left: 133px;
    display: inline-block;

}

.abt-t {
    
    color: black;
    font-size: 28px;
    margin-left: 133px;
    margin-top: -10px;
    font-style: normal;
    font-weight: 400;
    line-height: 40px;
    /* width: 1183px; */
    margin-right: 133px;
    /* height: 234px; */
    text-align: justify;
}

.net-arc{
    color: #190340;
    background: #F5F5F5;
    padding: 10px;
    border-radius: 13px;
    display: flex;
    position: relative;
    font-weight: 800;
    font-size: 44px;
    align-items: center;
    width: 800px;
    text-align: center;
    justify-content: center;
    height: 85px;
    margin: auto;
    margin-top: 100px;
    box-shadow: 0px 0px 13.199999809265137px 0px rgba(0, 0, 0, 0.25);

    
}


.net-arc-text {
    border-radius: 70px;
    /* width: 1441px; */
    /* height: 340px; */
    padding: 50px 100px;
    background-color: #F5F5F5;
    color: #190340;
    text-align: center;
    font-weight: 400;
    font-size: 28px;
    position: relative;
    display: block;
    /* justify-content: center; */
    /* align-items: center; */
    margin: auto;
    margin-top: 20px;
}

.arc-p {
    position: relative;
    /* width: 1148px; */
    display: flex;
    text-align: center;
}

.net-arc-container-1 {
    position: relative;
    display: flex;
    flex-direction: row;
    margin: 133px;
    justify-content: space-evenly;
}


.net-arc-frame {
    width: 360px;
    height: 400px;
    border: 20px solid white;
    border-radius: 30px;
    box-shadow: 0px 0px 6.300000190734863px 1px #00000033;
    display: flex;
    position: relative;
    flex-direction: column;
}


.inner-frame-1 {
    position: relative;
    display: flex;
    background-color: #F5F5F5;
    border-radius: 20px 20px 0 0;
    width: 100%;
    height: 75%;
    justify-content: center;
    align-items: center;
}


.net-arc-logo {
    position: relative;
    width: 190px;
    height: 230px;
}


.link-icon-background {
    background-color: #0C0021;
    border-radius: 100px 0 0 100px;
    width: 77px;
    height: 43px;
    position: absolute;
    margin-top: 200px;
    margin-left: 243px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.linkedin {
    position: relative;
    width: 35px;
    height: 35px;
    margin-top: 3px;
}

.inner-frame-2 {
    position: relative;
    /* display: flex; */
    background-color:  #0C0021;
    border-radius: 0 0 20px 20px;
    width: 100%;
    height: 25%;
    text-align: center;
    /* justify-content: center;
    align-items: center; */
}

.net-arc-name {
    color: white;
    font-family: Red Hat Display;
    font-size: 20px;
    font-weight: 500;
    line-height: 28px;
    letter-spacing: 0em;

}

.net-arc-position {
    color: #3C3;
    font-family: Red Hat Display;
    font-size: 16px;
    font-weight: 500;
    line-height: 23px;
    letter-spacing: 0em;
    margin-top: -15px;

}


.left-shield-pp {
    position: absolute;
    top: 1140px;
    left: 1700px;
    z-index: -1;
    opacity: 1;
}

.right-shield-pp {
    position: absolute;
    top: 1852px;
    right: 1535px;
    z-index: -1;
    opacity: 0.2;
}

</style>