<template>
   <div>Hello from Vue {{value }}</div>
</template>
<style lang="sass">
div
   height: 100%
   width: 100%
   display: grid
   place-items: center
   font-size: 60px
</style>
<script lang="ts">
export default {
   name: "App",
   data(){
      return {
         value : 1
      }
   }
}
</script>
