<script setup>

</script>

<template>
  <main>
    <div class="card">
      <RouterView />
    </div>
  </main>
   <p class="score">Score: 100</p>
</template>

<style lang="postcss" scoped>
 main{
   @apply flex h-screen justify-center  bg-gradient-to-r from-green-300 via-yellow-300 to-pink-300
   &.card{
    @apply min-h-fit w-11/12 flex-col items-center gap-16 overflow-auto rounded-lg bg-white p-8 shadow-lg;
   }
 }  
.score{
  @apply absolute bottom-6 right-8 text-2xl font-bold uppercase text-slate-700;
}
</style>
