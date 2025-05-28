<template>
    <div class="hidden lg:block">
<Navbar/>

  <div class="w-4/5 mx-auto flex text-white">
    <div class="flex w-1/5 mx-20 mt-10">
<img src="/furmiture1.jpeg" alt="" class="mr-4 w-7/8 h-120">
<img src="/furmiture2.avif" alt="" class="mr-4 w-7/8">
<img src="/furniture3.jpg" alt="" class="w-7/8">
    </div>
    <div class="mt-30 ml-100">
        <h1 class="text-3xl font-bold">Designed for creators, <br> built with clarity . </h1>
        <p class="font-light text-xs mt-10">3D modeling shouldn't be a guessing game. <br> Every model here comes packed with verified specs, <br> previews, and use-case info </p>
        <div class="flex mt-10">
            <button class="border-2 border-white px-4 py-2 rounded-md text-sm text-white">Weekly Drop</button>
            <button class="bg-blue-600 px-4 py-2 rounded-md text-sm ml-4">Browse Asset</button>
        </div>
    </div>
  </div>
  <footer>
    <div class="w-1/3 ml-240 flex ">
<p class="text-white mr-2 font-light">Support For Your Choice Of Tool</p>
<div class=" h-10 rounded-md">
    <img src="/240_F_475316746_xjRzj14YhIFG6FNgHsTUkWnFv5j440as.jpg" alt="" class="h-10 rounded-md border-2 border-white">
</div>
    </div>
  </footer>
<hr class="text-white mt-4">
    </div>
      <div class="lg:hidden md:hidden sm:block z-0">
        <Navbar/>

  <div class="  text-white">
    <div class="w-1/2 ml-6 flex mt-10 ">
<img src="/furmiture1.jpeg" alt="" class="mr-4 w-1/2 h-50">
<img src="/furmiture2.avif" alt="" class="mr-4 w-1/2 h-50 ">
<img src="/furniture3.jpg" alt="" class="2/3 w-1/2 h-50">
    </div>
    <div class="mt-30 ml-5">
        <h1 class="text-3xl font-bold">Designed for creators, <br> built with clarity . </h1>
        <p class="font-light text-xs mt-10">3D modeling shouldn't be a guessing game. <br> Every model here comes packed with verified specs, <br> previews, and use-case info </p>
        <div class="flex mt-10">
            <button class="border-2 border-white px-4 py-2 rounded-md text-sm text-white">Weekly Drop</button>
            <button class="bg-blue-600 px-4 py-2 rounded-md text-sm ml-4">Browse Asset</button>
        </div>
    </div>
  </div>
  <footer>
    <div class="w-11/11 mt-30 ml-2  flex ">
<p class="text-white mr-2 font-light">Support For Your Choice Of Tool</p>
<div class=" h-10 rounded-md">
    <img src="/240_F_475316746_xjRzj14YhIFG6FNgHsTUkWnFv5j440as.jpg" alt="" class="h-10 rounded-md border-2 border-white">
</div>
    </div>
  </footer>
<hr>
      </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue"
export default {
 components: {
   Navbar
 },
};
</script>