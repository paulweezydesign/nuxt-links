<template>
  <NuxtExampleLayout example="routing/nuxt-link" class="example">
    <nav>
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/about"> About </NuxtLink>
      <NuxtLink to="/kittens"> Kittens </NuxtLink>
    </nav>
    <NuxtPage />
  </NuxtExampleLayout>
</template>

<style>
.example a {
  font-family: Arial, Helvetica, sans-serif;
  padding: 0.5rem;
  display: inline-block;
}
h1 {
  font-size: 3rem;
  font-weight: 900;
}
</style>
