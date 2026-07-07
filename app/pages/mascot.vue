<script setup lang="ts">
useSeoMeta({
  title: 'Our Mascot - Pip',
  description: 'Pip is our mascot and the heart of our community!',
})
</script>

<template>
  <UPage>
    <UContainer>
      <UPageBody>
        <div class="my-8">
          <NuxtImg
            src="/pip-reference.png"
            alt="Reference sheet for Pip, the Pups In The Park mascot."
            class="w-full rounded-4xl shadow-xl"
          />
        </div>

        <div class="my-12 text-center max-w-3xl mx-auto">
          <ProseP class="text-xl">
            Pip is our mascot and the heart of our community!
          </ProseP>
        </div>

        <div class="my-16 text-center">
          <ProseP class="text-sm text-muted uppercase tracking-widest">
            Coming Soon
          </ProseP>
        </div>
      </UPageBody>
    </UContainer>
  </UPage>
</template>
