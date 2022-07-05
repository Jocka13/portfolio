<template>
  <div id="app">
    <router-view/>
    <HelloWorld/>
    <Body/>
  </div>
</template>


<script>
import BodyView from "@/views/BodyView";
import Body from "@/components/Body";
export default {
  components: {Body, BodyView}
}
</script>