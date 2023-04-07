<script setup></script>

<template>
  <main>
    <div class="card">
      <RouterView />
    </div>    
  </main>
</template>

<style lang="postcss" scoped>
main {
  @apply flex h-screen items-center justify-center bg-gradient-to-tr from-blue-300 via-green-200 to-yellow-300;

  & .card {
    @apply flex h-5/6 min-h-fit w-11/12 flex-col items-center gap-16 overflow-auto rounded-lg bg-white p-8 shadow-lg;
  }
}
</style>
