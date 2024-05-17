<template>
  <NuxtLoadingIndicator :throttle="200" :height="2" :color="'#000000'" />
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

<style>
.page-enter-active,
.page-leave-active {
  @apply transition-opacity duration-300;
}
.page-enter-from,
.page-leave-to {
  @apply opacity-0;
}
</style>
