<template>
  <div id="UploadImage" class="flex flex-col items-start space-y-8">
    <div>
      <h1 class="text-xl uppercase font-bold text-[#273e65]">
        Gestion des images
      </h1>
      <hr class="border-t-2 border-[#ffac3f] mt-2" />
    </div>
    <!-- Section Contenu Dynamique -->
    <div
      class="max-h-[80vh] overflow-auto w-full flex items-center justify-center"
    >
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
