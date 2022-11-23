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
  @apply flex h-screen items-center justify-center bg-[radial-gradient(ellipse_at_top,_var(--tw-gradient-stops))] from-slate-900 via-purple-900 to-slate-900;
  & .card {
    @apply flex h-5/6 min-h-fit w-11/12 flex-col items-center gap-16 overflow-auto rounded-lg bg-cyan-900 p-8 shadow-lg;
  }
}
</style>
