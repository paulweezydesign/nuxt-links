<template>
  <defaultLayout>
  <nav class='grid grid-cols-2 md:grid-cols-4 items-center px-[6%] py-4 text-xl '>
      <NuxtLink 
      class='text-3xl font-black'
      to="/">Nuxt App</NuxtLink>
     <div class='hidden md:col-span-2 md:flex md:justify-evenly '>
      <NuxtLink to="/about"> About </NuxtLink>
      <NuxtLink to="/kittens"> Kittens </NuxtLink>
      <NuxtLink to="/resources">Resources</NuxtLink>
     </div>
     <div class='hidden md:flex md:justify-end'>
      <NuxtLink to="/contact">Contact us</NuxtLink>
      </div>
      <div class="">
      
      </div>
    </nav>
  <section class='grid grid-cols-1 place-items-center h-screen'>
  
    <NuxtPage />
</section>
  </defaultLayout>
</template>
<script>
import Layout from './layouts/default';
</script>
<style>
h1 {
  font-size: 3rem;
  font-weight: 900;
}
</style>
