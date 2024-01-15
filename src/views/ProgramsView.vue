<template>
    <div>


        <Nav/>
        <img class="left-shield-pp" :src="leftshield" alt="">

        <img class="right-shield-pp" :src="rightshield" alt="">

        <p class="fost">Fostering the Mutual Growth of the Cyberspace</p>

        <img class="programs-ill" :src="programsIll" alt="">


        <div class="frame-2">

            <div class="frame-2-bar"></div>
            <div class="frame-2-1">
                <p class="be">PROGRAMS</p>
            
            </div>
            <div class="frame-2-bar"></div>
        </div>

        <p class="virtual">Virtual Engagements</p>

        <p class="virtual-txt">Within the diverse range of virtual engagements, 
            we accommodate different learning styles, levels of expertise, 
            and interests within the field, fostering a dynamic and inclusive 
            learning environment for our members and the public.</p>

        <div class="virtual-container">
            
            <div class="pro-vir-box">
                <div class="head-background"><p>Q & A SESSIONS</p></div>
                <img class="icon" :src="qanda" alt="">
                <p class="vir-box-text"> Host sessions online (Twitter, LinkedIn etc.) to answer 
                    audience questions about cybersecurity best practices, 
                    recent threats, or general advice.</p>
            </div>

            <div class="pro-vir-box">
                <div class="head-background"><p>Webinars</p></div>
                <img class="icon" :src="web" alt="">
                <p class="vir-box-text">We collaborate with 
                    cybersecurity experts and professionals for 
                    live interviews or webinars discussing recent 
                    threats, industry updates, or practical security tips.</p>
            </div>

            <div class="pro-vir-box">
                <div class="head-background"><p>educational series</p></div>
                <img class="icon" :src="edu" alt="">
                <p class="vir-box-text">We release a series of educational 
                    infographics covering different aspects of cybersecurity, 
                    progressing periodocally to keep our audience engaged and 
                    learning.</p>
            </div>

            <div class="pro-vir-box">
                <div class="head-background"><p>AMA SESSIONS</p></div>
                <img class="icon" :src="ama" alt="">
                <p class="vir-box-text">Conduct weekly AMAs where your audience can ask 
                    questions directly related to cybersecurity, privacy concerns, or 
                    technology-related queries.</p>
            </div>

            <div class="pro-vir-box">
                <div class="head-background"><p>there is a word</p></div>
                <img class="icon" style="position: relative; bottom: 20px" :src="there" alt="">
                <p class="vir-box-text" style="position: relative; top:-60px">We share  a word on a weekly basisi and delve into it very properly.</p>
            </div>

            <div class="pro-vir-box" style="padding: 10px 0">
                <div class="head-background"><p style="font-size:22px">Cybersecurity challenges</p></div>
                <img class="icon" :src="chal" alt="">
                <p class="vir-box-text">We provide games or challenges encouraging 
                    our audience to improve their security practices, such as creating 
                    strong passwords or enabling multi-factor authentication</p>
            </div>
            
            

        </div>

        <p class="virtual top1">outdoor engagements</p>
        <p class="virtual-txt top2">We provide that excitement and novelty into 
            cybersecurity education and networking, making learning more 
            engaging and memorable while fostering a strong sense of 
            community within the field</p>

        <div class="outdoor-container">
            <div class="pro-vir-box" style="padding: 10px 0">
                <div class="head-background"><p style="font-size:22px">workshops</p></div>
                <img class="icon" :src="work" alt="">
                <p class="vir-box-text">We offer hands-on learning in cybersecurity through interactive 
                    exercises, skill-building activities, and technical deep dives. Focus on applied 
                    knowledge, and in-depth exploration of case studies.</p>
            </div>

            <div class="pro-vir-box" style="padding: 10px 0">
                <div class="head-background"><p style="font-size:22px">community outreACH</p></div>
                <img class="icon" :src="com" alt="">
                <p class="vir-box-text">Engage in outdoor community outreach events, collaborating 
                    with local organizations or schools to educate and inspire the next generation 
                    about cybersecurity careers.</p>
            </div>

            <div class="pro-vir-box" style="padding: 10px 0">
                <div class="head-background"><p style="font-size:22px">MEETUPS</p></div>
                <img class="icon" :src="meet" alt="">
                <p class="vir-box-text"> We organize gatherings where cybersecurity 
                    professionals network, exchange ideas, build relationships, and 
                    fostering collaboration.</p>
            </div>

        </div>
        <p class="virtual top3">CAREER SUPPORT</p>
        <p class="virtual-txt top4">We offer these resources and support mechanisms 
            to the community can significantly contribute to the growth and 
            development of individual members pursuing careers in this field.</p>

        <div class="career-container">
            <div class="pro-vir-box" style="padding: 10px 0">
                <div class="head-background"><p style="font-size:22px">support groups</p></div>
                <img class="icon" :src="sup" alt="">
                <p class="vir-box-text"> We organize gatherings where cybersecurity 
                    professionals network, exchange ideas, build relationships, and 
                    fostering collaboration.</p>
            </div>

            <div class="pro-vir-box" style="padding: 10px 0">
                <div class="head-background"><p style="font-size:22px">industry insights</p></div>
                <img class="icon" :src="ind" alt="">
                <p class="vir-box-text"> We organize gatherings where cybersecurity 
                    professionals network, exchange ideas, build relationships, and 
                    fostering collaboration.</p>
            </div>

            <div class="pro-vir-box" style="padding: 10px 0">
                <div class="head-background"><p style="font-size:22px">networking forums</p></div>
                <img class="icon" :src="net" alt="">
                <p class="vir-box-text"> We organize gatherings where cybersecurity 
                    professionals network, exchange ideas, build relationships, and 
                    fostering collaboration.</p>
            </div>

        </div>

        <footer>

            <Footer/>
        </footer>

        

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
           leftshield: require('@/assets/images/left-shield-pp.svg'),
           rightshield: require('@/assets/images/right-shield-pp.svg'),
           programsIll: require('@/assets/images/programs-illustration.png'),

           qanda: require('@/assets/images/Q&A.png'),
           web: require('@/assets/images/webinars.png'),
           edu: require('@/assets/images/educational-series.png'),
           ama: require('@/assets/images/ama.png'),
           there: require('@/assets/images/there.png'),
           chal: require('@/assets/images/challenge.png'),

           work: require('@/assets/images/work.png'),
           com: require('@/assets/images/com.png'),
           meet: require('@/assets/images/meet.png'),

           sup: require('@/assets/images/sup.png'),
           ind: require('@/assets/images/ind.png'),
           net: require('@/assets/images/net.png'),
           

        }
    }
}
</script>



<style scoped>

* {
    box-sizing: border-box;
}


.left-shield-pp {
    position: absolute;
    top: 1187px;
    left: 1248px;
}

.right-shield-pp {
    position: absolute;
    top: 1852px;
    right: 1535px;
}

.fost {
    position: relative;
    top: 144px;
    left: 124px;
    color: #000;
    font-family: Red Hat Text;
    font-size: 36px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
    width: 454px;
    /* border: 1px solid red; */
}

.programs-ill {
    position: relative;
    top: -100px;
    left: 456px;
    /* border: 1px solid red; */
}

.frame-2 {
    width: 502px;
    height: 125px;
    /* border: 1px solid red; */
    position: relative;
    top: 40px;
    margin: auto;
    display: flex;
    flex-direction: row;
    gap: 25px;
    justify-content: center;
}

.be {
    position: relative;
    color: #FFF;
    bottom: 40px;
    text-align: center;
    font-family: Red Hat Display;
    font-size: 64px;
    font-style: normal;
    font-weight: 800;
    line-height: 130.315%; /* 83.402px */
    letter-spacing: 0.64px;
}


.frame-2-bar{
    background-color: #3C3;
    width: 11px;
    height: 124px;
    position: relative;
}


.frame-2-1 {
    /* padding: 20px; */
    background-color: #190340;
    border-radius: 10px;
    width: 430px;
    height: 123px;
    position: relative;
}

.virtual {
    color: #000;
    text-align: center;
    font-family: Red Hat Text;
    font-size: 32px;
    font-style: normal;
    font-weight: 500;
    line-height: 30px; /* 93.75% */
    text-decoration-line: underline;
    text-transform: uppercase;
    position: relative;
    top: 100px;
}

.virtual-txt {
    color: #190340;
    text-align: center;
    font-family: Red Hat Text;
    font-size: 24px;
    position: relative;
    top: 80px;
    width: 1120px;
    font-style: normal;
    font-weight: 500;
    margin: auto;
    line-height: 30px; /* 125% */
}

.virtual-container {
    width: 1180px;
    height: 730px;
    /* border: 1px solid red; */
    position: relative;
    margin: auto;
    top: 100px;
    display: grid;
    gap: 30px;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(2, 1fr);
}

.top1 {
    top: 250px;
}

.top2 {
    top: 240px;
}

.top3 {
    top: 450px;
}

.top4 {
    top: 450px;
}

.career-container {
    position: relative;
    top: 700px;
    position: relative;
    margin: auto;
    top: 500px;
    width: 1180px;
    /* height: 346px; */
    /* border: 1px solid red; */
    display: grid;
    gap: 30px;
    grid-template-columns: repeat(3, 1fr);
}

.outdoor-container {
    position: relative;
    margin: auto;
    top: 300px;
    width: 1180px;
    /* border: 1px solid red; */
    display: grid;
    gap: 30px;
    grid-template-columns: repeat(3, 1fr);
}

.pro-vir-box {
    background-image: url('@/assets/images/engagment-background.png');
    background-size: cover;
    position: relative;
    border-radius: 10px;
    display: flex;
    flex-direction: column;
    gap: 30px;
    /* justify-items: center; */
    padding: 10px;
}   


.head-background {
    position: relative;
    display: inline-block;
    padding: 5px 10px;
    border-radius: 10px;
    background-color: #0C0021;
    /* top: 20px; */
    margin: 0 auto;
    height: 40px;

}

.head-background p {
    color: #FFF;
    font-family: Red Hat Text;
    font-size: 24px;
    font-style: normal;
    font-weight: 500;
    line-height: 30px; /* 125% */
    text-transform: uppercase;
    margin: auto;
    


}

.icon {
    position: relative;
    /* top: -95px; */
    margin: auto;
    display: block;
    /* top: 50px; */
    
}

.vir-box-text {
    color: #190340;
    text-align: center;
    font-family: Red Hat Text;
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: 30px; /* 150% */
    width: 288px;
    margin: auto;
}


footer {
    position: relative;
    top: 550px;
}
</style>