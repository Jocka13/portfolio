<template>
  <div class="row">
    <div class="col col-6">
      <h6 class="fs-5">Details</h6>
      <p class="fw-light fs-6 mb-0">{{info.streeth}}</p>
      <p class="fw-light fs-6 mb-0">{{info.hometown}}</p>
      <p class="fw-light fs-6 mb-0">{{ info.country}}</p>
      <p class="fw-light fs-6 mb-0">{{info.telnumber}}</p>
    </div>
  </div>
</template>

<script>
export default {
name: "Details",
data(){
  return {
    info : {
      streeth : 'Boro Pockov 46',
      hometown : 'Strumica 2400',
      country : 'Macedonia',
      telnumber : '+389 71 395 781'
    }
  }
}

}
</script>

<style scoped>

</style>