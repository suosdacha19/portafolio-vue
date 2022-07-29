<template>
  <div class="flex h-screen">
    <!-- Menu -->
    <div class="flex flex-col justify-between w-1/6 bg-black">
      <div class="">
        <img class="foto_pefil" src="images/perfil.jpg" alt="Perfil">
        <span>Daniel Suescun</span>
      </div>
      <div class="bg-green-600">#2</div>
      <div class="bg-pink-400">#3</div>
    </div>
    <!-- Router view -->
    <div class="w-5/6 bg-blue-600">
      <RouterView/>
    </div>
  </div>
</template>

<style>
.foto_pefil {
  width: 175px;
  height: 175px;
  border-radius: 100%;
}
</style>