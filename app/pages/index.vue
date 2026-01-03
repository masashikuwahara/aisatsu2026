<template>
  <div class="min-h-screen flex items-center justify-center bg-gray-50 bg-[url('/images/pattern-ume.svg')] bg-repeat">
    <div class="text-center space-y-5">
      <img
        src="/images/horse-2026.jpg"
        alt="午年のイラスト"
        class="fade-up mx-auto w-32 md:w-40 opacity-90"
      />

      <p class="fade-up text-gray-400">
        賀正
      </p>

      <h1 class="fade-up text-3xl md:text-4xl font-bold text-gray-800">
        あけましておめでとうございます
      </h1>

      <p class="fade-up-delay text-lg text-gray-600">
        今年もよろしくお願いします
      </p>

      <p class="fade-up-delay text-sm text-gray-500">
        皆さまにとって健やかで実り多い一年になりますように。
      </p>
    </div>
  </div>
</template>

<script setup lang="ts">
  useHead({
    title: '2026年 新年のご挨拶',
  })
</script>