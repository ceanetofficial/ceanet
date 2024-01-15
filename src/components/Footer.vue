<template>
        <div class="footer-container">
        <footer>
            <img class="footer-logo" :src="logo" alt="">
    
            <p>We're thrilled to have you on board! To stay updated
                with our latest news, events, and cybersecurity
                insights, make sure to follow us on Twitter and
                LinkedIn.
            </p>


            <div class="footer-links">
                <a class="footer-links-head" href="">home</a>
                <a class="footer-links-head" href="">program</a>
                <a class="footer-links-head" href="">catalog</a>
                <a class="footer-links-head" href="">about</a>

                <a class="footer-links-item" href="">About Us</a>
                <a class="footer-links-item" href="">Virtual</a>
                <a class="footer-links-item" href="">Past</a>
                <a class="footer-links-item" href="">Founders</a>

                <a class="footer-links-item" href="">What We Do</a>
                <a class="footer-links-item" href="">Outdoor</a>
                <a class="footer-links-item" href="">Active</a>
                <a class="footer-links-item" href="">Mission</a>

                <a class="footer-links-item" href="">Become a Member</a>
                <a class="footer-links-item" href="">Career Networking</a>
                <a class="footer-links-item" href="">Upcoming</a>
                <a class="footer-links-item" href="">Vision</a>
                


            </div>
            
            <a href="https://www.linkedin.com/company/ceanetofficial/"><img :src="linkedin" alt="LinkedIn icon"></a>
            <a href="https://twitter.com/ceanetofficial"><img :src="twitter" alt="twitter_x icon"></a>
            <a href=""><img :src="whatsapp" alt=""></a>
            <a class="email" href=""><img :src="email" alt=""></a>
            <p>ceanetofficial@gmail.com</p>
            <a class="phone" href=""><img :src="telephone" alt=""></a>
            <p>+2348112233444</p>
            <div class="foot-join">
                <a href="" class="footer-link2">partner with us</a>
                <a href="" class="footer-link2">join us</a>
            </div>
            
            <img class="line1" :src="line" alt="">
            <p>(c) 2023 All Rights Reserved</p>
    
        </footer>

    </div>
</template>


<script>
export default {
  data() {
    return {
      // Import your image and assign it to a data property
      logo: require('@/assets/images/ceanet white trans logo 1.svg'),
      line: require('@/assets/images/Line 1.png'),
      linkedin: require('@/assets/images/linkedin.svg'),
      twitter: require('@/assets/images/twitter_x.svg'),
      whatsapp: require('@/assets/images/whatsapp_icon.svg'),
      email: require('@/assets/images/email_icon 1.svg'),
      telephone: require('@/assets/images/telephone_icon 1.svg')
    };
  }
}
</script>




<style scoped>

* {
    box-sizing: border-box;
}
.footer-container {
    position: relative;

}

footer {
    /* height: 447px; */
    width:100%;
    background-color: #0C0021;
    color: white;
    position: relative;
    top: 80px;
    padding-left: 131px;
}

.footer-logo {
    position: relative;
    top: 21px;
    /* left: 131px; */
    margin-bottom: 0;
}

.footer-logo + p {
    color: #FFF;
    font-family: Saira;
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    width: 430px;
    height: 130px;
    position: relative;
    top: 13px;
    /* left: 131px; */
    /* border: 1px solid red; */
}

.footer-links {
    width: 465px;
    height: 110px;
    position: absolute;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(4, 1fr);
    left: 900px;
    bottom: 320px;
}

.footer-links-head {
    color: #FFF;
    font-family: Saira;
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    text-decoration-line: underline;
    text-transform: uppercase;
}

.footer-links-head:hover {
    color: #3C3;
}

.footer-links-item {
    color: #989898;
    font-family: Red Hat Display;
    font-size: 13px;
    font-style: normal;
    font-weight: 500;
    line-height: normal;
}

.footer-links-item:hover {
    color: #3C3;
}

footer img {
    position: relative;
    /* margin-top: 10px; */
    margin-right: 19px;
    /* font-size: 25px; */
    /* left: 131px; */

}

.email {
    position: relative;
    margin-left: 580px;
    margin-bottom: 99px;
    margin-top: 30px;
    bottom: 10px;
}

.email + p {
    display: inline;
    position: relative;
    color: #FFF;
    font-size: 24px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    bottom: 30px;
}

.phone {
    display: inline;
    position: relative;
    margin-left: 780px;
    bottom: 20px;
}

.phone + p {
    display: inline;
    position: relative;
    bottom: 10px;
    color: #FFF;
    font-size: 24px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    bottom: 40px;

}

footer a {
    text-decoration: none;
    color: white;
}

.foot-join {
    position: relative;
    display: flex;
    gap: 10px;
    bottom: 10px;
    left: 456px;
}

.footer-link2 {
    position: relative;
    color: #989898;
    font-family: Saira;
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    text-decoration-line: underline;
    text-transform: uppercase;
    display: inline-block;
    /* bottom: 12px; */
}

.footer-link2:hover {
    color: #3C3;
} 

.line1 {
    position: relative;
    /* left: 131px; */
    bottom: 10px;

}

.line1 + p {
    position: relative;
    bottom: 20px;
    color: #FFF;
    font-size: 24px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    left: 435px;
}


</style>