<template>
    <!--desktop-->
<div class="text-white pt-3 text-sm hidden lg:block">
    <div class="flex w-2/3  ml-80">
        <div class="flex justify-between w-7/10">
            <p class="mr-3">melaOne</p>
<input type="text" name="" id="" class="bg-white w-15/10 rounded-md focus:outline-none" >
<p class="ml-3">Login</p>
        </div>
        <div class="ml-10">
            <button class="bg-blue-600 px-1 rounded-md text-sm">Create Free Account</button>
        </div>
    </div>
    <div class="flex justify-between w-1/3 ml-105 mt-3 text-sm">
        <div>Model</div>
        <div>Material</div>
        <div>scenes</div>
        <div>About</div>
        <div>Shop</div> |
        <div>Blog</div>
        <div>Support</div>
    </div>
    <hr class="mt-3">
</div>  
<!--mobile-->
<div class="lg:hidden md:hidden sm-block text-white">
    <div class="flex w-2/3 mx-auto pt-2">
<div class="mr-2"> 
    melaOne
</div>
<div>
    <input type="text " class="bg-white rounded-md focus:outline-none">
</div>
    </div>
    <div class="flex justify-between mr-10 ml-3 mt-3">
        <div @click="toggleLists">

            <i class="fa-solid fa-bars"></i>
        </div>
<div v-if="showLists">
    //
       <div class=" justify-between w-1/4  mt-10 -ml-10 fixed z-20 font-bold text-sm ">
        <div class="mt-2 bg-blue-400 px-3">Model</div>
        <div class="mt-2 bg-blue-400 px-3">Material</div>
        <div class="mt-2 bg-blue-400 px-3">scenes</div>
        <div class="mt-2 bg-blue-400 px-3">About</div>
        <div class="mt-2 bg-blue-400 px-3">Shop</div> 
        <div class="mt-2 bg-blue-400 px-3">Blog</div>
        <div class="mt-2 bg-blue-400 px-3">Support</div>
    </div>
</div>
<div class="flex">
 <div class="ml-10">
    
            <button class="bg-blue-600 px-1 rounded-md text-sm">Create Free Account</button>
        </div>
        <p class="ml-3">Login</p>
</div>
    </div>
</div>
</template>

<script>
export default {
data() {
    return {
        showLists: false,
    };  
},
methods: {
    toggleLists() {
        this.showLists = !this.showLists;
    }
}}
</script>

<style>

</style>