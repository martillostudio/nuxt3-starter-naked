<template>
  <div class="flex flex-col min-h-svh">
    <Header />

    <!-- Main -->
    <main class="relative z-10 flex flex-col flex-1 h-full max-w-full">
      <slot />
    </main>

    <Footer />
  </div>
</template>
