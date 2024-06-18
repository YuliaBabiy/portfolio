<template>
  <div>
    <header>
      <nav class="container flex gap-5">
        <h2><NuxtLink to="/">Logo</NuxtLink></h2>
        <ul class="flex gap-5">
          <li><NuxtLink to="/">About</NuxtLink></li>
          <li><NuxtLink to="/">Projects</NuxtLink></li>
        </ul>
        <button class="custom-class">Let's talk</button>
      </nav>
    </header>
    <div class="container">
      <slot/>
    </div>
  </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>