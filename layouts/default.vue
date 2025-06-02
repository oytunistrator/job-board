<script setup lang="ts"></script>

<template>
  <!-- Main class wraps everything -->
  <main class="relative m-auto w-7xl h-full">
    <HeaderNavBar />
    <!-- Page content -->
    <slot />
  </main>
</template>

<!-- The style here is intentionally global to modify `#__nuxt` -->
<style>
div#__nuxt {
  @apply relative flex w-screen h-full;
}
</style>
