<template>
    <div class="skill">
        <img :src="url" height="40">
    </div>
</template>


<script>
export default {
  name: 'Skill',
  props: {
      url: String
  }
}
</script>

<style scoped>
    .skill {
        background-color: #0a0f17;
        width: 50px;
        height: 45px;
        border-radius: 8px;
        margin: 5px;
        display: inline-block;
        align-items: center;
        align-self: center;
        justify-content: center;
    }
</style>