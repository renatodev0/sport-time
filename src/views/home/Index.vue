<template>
    <div class="">
        <div class="home">
            <small class="display-3"> 🏀🏈⚽ </small>
            <p class="display-1 text-primary"> SPORTIME </p>  
        </div>
    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
    mounted() {
        document.querySelector('body').setAttribute('style', 'background:#000')
    },
}
</script>

<style scoped>
.home{
  margin: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  font-family: 'Oswald', sans-serif;
}
</style>
