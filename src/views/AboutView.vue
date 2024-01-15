<template>
    <div class="about">
        <Nav/>


        <div class="wall2">
                <img :src="Group1" alt="group 1">
            </div>

            <div class="about-us-container">

                <div class="frame1">

                    <div class="frame-1-bar"></div>
                    <div class="frame-1-1">
                        <p class="p">About us</p>
                    </div>
                    <div class="frame-1-bar"></div>
                </div>

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

            </div>



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
    border: 1px solid #190340;
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
    color: #190340;
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
    background-color: white;
    border-radius: 10px;
    width: 430px;
    height: 123px;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
}

.abt-t {
    margin: auto;
    margin-top: 90px;
    color: white;
    text-align: center;
    font-size: 34px;
    font-style: normal;
    /* border: 1px solid red; */
    font-weight: 400;
    line-height: 141%; /* 47.94px */
    width: 1183px;
    height: 300px;
}

</style>