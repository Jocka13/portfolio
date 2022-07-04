<template>
  <div id="app">
    <router-view/>
    <HelloWorld/>
  </div>
</template>


<script>
import BodyView from "@/views/BodyView";
export default {
  components: {BodyView}
}
</script>