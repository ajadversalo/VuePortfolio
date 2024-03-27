<template>
  <div class="bg-gray-200 h-screen w-[1024px] ml-auto mr-auto">
    <div class="grid grid-cols-12 gap-2">
      <div class="col-span-6 bg-green-200">
        <div class="bg-purple-200 text-left">
          Menu Items
        </div>
        <div class="mt-32 w-100">
          <NameHeader name="AJ Adversalo"/>
        </div>
      </div>
      <div class="bg-red-200 p-4 col-span-6 h-screen">
        Grid Item 1
      </div>  
    </div>
  </div>
</template>

<script>
import NameHeader from "./NameHeader.vue";

export default {
  name: 'RootContainer',
  components: {    
    NameHeader
  }
}

</script>

<style scoped>
</style>
