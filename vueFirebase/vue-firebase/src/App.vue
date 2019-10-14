<template>
  <div id="app" class="principal">
    <span>APP</span>
    <entranda></entranda>
  </div>
</template>

<script>
  import entrada from "@/views/entrada.vue";
  export default {
      comments:{entrada}
  }
</script>

<style>
html{
  font-size: 62.5% !important;
}
.principal{
  background-color: red;
  padding: 10px;
  color: white;
  border-radius: 5px;
  font-size: 3rem;
  text-align: center
}

</style>
