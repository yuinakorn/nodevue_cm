<template>
  <div class="container-fluid pt-3" style="position: relative">
      <div class="row">
        <IsLoading />
      
    </div>
  </div>

</template>

<script>
import IsLoading from "@/components/Loading";
export default {
  components: {
    IsLoading
  },
  name: "Loader",

}
</script>

<style scoped>


</style>