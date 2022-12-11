<template
  v-motion
  :initial="{ opacity: 0, y: 100 }"
  :enter="{ opacity: 1, y: 0, scale: 1 }"
  :variants="{ custom: { scale: 2 } }"
  :hovered="{ scale: 1.2 }"
  :delay="200"
>
  <h1>Filaberta</h1>
  <div class="links">
    <NuxtLink to="/kittens">Back</NuxtLink>
    <NuxtLink to="/contact">Contact us</NuxtLink>
  </div>
</template>
<style>
.links {
  display: flex;
  flex-direction: row;
  justify-content: center;
}
</style>
