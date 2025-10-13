<template>
    <div class="mx-auto w-1/2 p-4">
        <div>
            <PostItem></PostItem>
        </div>
    </div>
</template>

<script setup>

useHead({
  title: 'My App',
  meta: [
    { name: 'description', content: 'My amazing site.' },
  ],
  bodyAttrs: {
    class: 'test',
  },
})

definePageMeta({
    layout: 'main'
})

</script>

<style scoped>


</style>