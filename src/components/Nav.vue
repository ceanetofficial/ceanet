<template>
    <nav>
      <router-link to="/home" class="no-bottom-border"><img :src="logo" alt="CEANet logo"></router-link>
      <ul>
        <li><router-link to="/programs">programs</router-link></li>
        <li><router-link to="/catalog">catalog</router-link></li>
        <li><router-link to="/about">about</router-link></li>
        <img :src="line" alt="">
        <li class="last-child"><router-link to="/partner">Join us</router-link></li>
      </ul>
    </nav>
  </template>
  


<script>
export default {
  data() {
    return {
      // Import your image and assign it to a data property
      logo: require('@/assets/images/ceanet white trans logo 1.svg'),
      line: require('@/assets/images/nav-vertical-bar.svg')
    };
  }
}
</script>


<style scoped>

* {
  box-sizing: border-box;
}
nav {
  max-width: 100%;
  height: 134px;
  padding: 50px 133px;
  background-color: #0C0021;
  display: flex;
  justify-content: center;
  align-items: center;

}


nav ul {
    list-style: none;
    display: flex;
    float: right;
    gap: 50px;
    margin: 0 auto;
    margin-right: 0;
    align-items: center;
    justify-content: center;
}

nav li a {
    display: inline-block;
    color: white;
    text-transform: uppercase;
    font-size: 18px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
    text-decoration: none;
}

nav a:hover {
    border: none;
    border-bottom: 2px solid #3C3;
    border-radius: 5px;
} 

.no-bottom-border {
    
}


.no-bottom-border:hover {
    border-bottom: none;
    transform: scale(1.1);
    /*transform: rotate(10deg);*/
    transition: 0.3s ease-in-out;

}

.router-link-active {
  color: #3C3; 
}

.router-link-active:hover {
    border-bottom: 2px solid white;

} 

nav ul img {
    color: white;
    margin-right: 20px; 
    margin-left: -20px;
    
}


nav .last-child {
    margin-left: -50px;
    border: 2px solid #3C3;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 10px;
    padding: 10px;

}


</style>