<template>
  <div class="app">
    <h3> vmexit </h3>
    <div class="info">
      <h3 class="hello"> Hello! </h3>
      <div style="margin-top: -2%;">
        <p>
           I'm Alexander. I do low level programming and reverse-engineering.
        </p>
        <center style="display: inline-block;">
          <Skill url="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"/>
          <Skill url="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/php/php.png"/>
          <Skill url="https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/ISO_C%2B%2B_Logo.svg/1822px-ISO_C%2B%2B_Logo.svg.png"/>
          <Skill url="https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/C_Programming_Language.svg/1200px-C_Programming_Language.svg.png"/>
          <Skill url="https://static.cdnlogo.com/logos/c/27/c.svg"/>
          <Skill url="https://seeklogo.com/images/N/nodejs-logo-FBE122E377-seeklogo.com.png"/>
          <br>
          <Skill url="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1184px-Vue.js_Logo_2.svg.png"/>
          <Skill url="https://cdn.pixabay.com/photo/2017/01/31/15/33/linux-2025130_1280.png"/>
          <Skill url="https://styles.redditmedia.com/t5_2qh2d/styles/communityIcon_xagsn9nsaih61.png?width=256&s=1e4cf3a17c94aecf9c127cef47bb259162283a38"/>
          <Skill url="https://www.docker.com/sites/default/files/d8/2019-07/vertical-logo-monochromatic.png"/>
        </center>
        <br><br><br> <!-- I know this is ugly! -->
        <a class="btn" href="https://github.com/justvmexit">Check out my projects!</a>
      </div>
    </div>
    
  </div>
</template>

<script>
import Skill from '@/components/Skill.vue'

export default {
  name: 'App',
  components: {
    Skill
  },
  data() {
    return {
      hover: false,
    };
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter&display=swap');

.btn {
  margin-top: 125%;
  border-radius: 8px;
  background-color: #1163e6;
  text-decoration: none;
  color: white;
  padding: 20px;
  transition: .2s ease-in-out;
}

body {
  background-color: #06070a;
  color: white;
  font-family: 'Inter', sans-serif;
  overflow: hidden;
}

.info {
  justify-content: center;
  align-items: center;
  text-align: center;
}

.hello {
  font-weight: 700;
  font-size: 40px;
}

p {
  font-weight: 500;
  font-size: 20px;
}

label {
  font-weight: 500;
  font-size: 14px;
}

</style>
