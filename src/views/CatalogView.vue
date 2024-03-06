<template>
<div class="catalog">
    <Nav/>

    <div id="comingSoon" class="coming-soon-container">
        <h2>Coming Soon</h2>
        <p>Stay tuned for something amazing!</p>
        <!-- Optional: Add a signup form or a countdown timer -->
        <p id="countdown"></p>
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
    }
}





</script>


<style scoped>


.coming-soon-container {
  text-align: center;
  padding: 50px;
  background-color: #f4f4f4; /* Light grey background */
  color: #333; /* Dark text color */
  margin-top: 50px;
  height: 300px;
  /* Further styling as needed */
}


</style>