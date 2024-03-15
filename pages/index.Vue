<template>
  <div class="bg-blue-500">
    <h1 class="text-3xl font-bold">Hello World</h1>
    <p>Hey!</p>
  </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  head() {
    return {
      title: 'AWay - Explora caminos por la naturaleza',
      meta: [
        {
          charset: 'utf-8',
        },
        {
          name: 'viewport',
          content: 'width=device-width, initial-scale=1',
        },
        {
          hid: 'description',
          name: 'description',
          description:
            'AWay es una red social para compartir fotos e historias de caminos por la naturaleza alrededor del mundo.',
        },
      ],
    }
  },
})
</script>
