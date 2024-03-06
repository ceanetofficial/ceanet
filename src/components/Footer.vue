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
                <a class="footer-links-head" href="/">home</a>
                <a class="footer-links-head" href="/programs">program</a>
                <a class="footer-links-head" href="">catalog</a>
                <a class="footer-links-head" href="/about">about</a>

                <a class="footer-links-item" href="/#about">About Us</a>
                <a class="footer-links-item" href="programs#virtual">Virtual</a>
                <a class="footer-links-item" href="">Past</a>
                <a class="footer-links-item" href="">Founders</a>

                <a class="footer-links-item" href="/#what">What We Do</a>
                <a class="footer-links-item" href="programs#outdoor">Outdoor</a>
                <a class="footer-links-item" href="">Active</a>
                <a class="footer-links-item" href="">Mission</a>

                <a class="footer-links-item" href="/#become">Become a Member</a>
                <a class="footer-links-item" href="programs#career">Career Networking</a>
                <a class="footer-links-item" href="">Upcoming</a>
                <a class="footer-links-item" href="">Vision</a>
                


            </div>
            
            <a href="https://www.linkedin.com/company/ceanetofficial/"><img :src="linkedin" alt="LinkedIn icon"></a>
            <a href="https://twitter.com/ceanetofficial"><img :src="twitter" alt="twitter_x icon"></a>
            <a href=""><img :src="whatsapp" alt=""></a>
            <div class="email-phone">
                <a class="email" ><img :src="email" alt=""></a>
                <a href="mailto:ceanetofficial@gmail.com">ceanetofficial@gmail.com</a>

                <a class="phone" ><img :src="telephone" alt=""></a>
                <a href="tel:+234-80-3456-7890">08034567890</a>


            </div>
            
            <div class="foot-join">
                <a href="/partner#partner-with-us" class="footer-link2">partner with us</a>
                <a href="/partner#join-us" class="footer-link2">join us</a>
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
    padding: 0 131px;
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
    width: 565px;
    height: 150px;
    position: absolute;
    display: grid;
    /* gap: 5px; */
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(4, 1fr);
    right: 131px;
    margin-top: -230px;

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
    font-size: 15px;
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
  
}

.email + a {
    display: inline;
    position: relative;
    color: #FFF;
    font-size: 24px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    bottom: 20px;
}

.phone {
    display: inline;
    position: relative;
}

.phone + a {
    display: inline;
    position: relative;
    bottom: 10px;
    color: #FFF;
    font-size: 24px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    bottom: 20px;

}

.email-phone {
    position: absolute;
    right: 131px;
    width: 400px;
    bottom: 100px;
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
    justify-content: center;
    /* width: 600px; */
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
    width: 100%;

}

.line1 + p {
    position: relative;
    bottom: 20px;
    color: #FFF;
    font-size: 24px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    /* left: 435px; */
    /* width: 500px; */
    text-align: center;

}


</style>