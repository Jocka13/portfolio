<template>
<!--  <nav class="navbar navbar-light bg-light">-->
<!--    <div class="container-fluid">-->
<!--      <span class="navbar-brand mx-auto text-dark">Welcome to my first portfolio, l am Jordan Velkovski</span>-->
<!--    </div>-->
<!--  </nav>-->
  <HelloWorld/>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
