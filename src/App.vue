<template>
  <div class="flex w-full justify-center">
    <img alt="Vue logo" src="./assets/logo.png" />
  </div>
  <HelloWorld msg="Hello Vue 3.0 + Vite + Typescript + TailwindCSS" />
</template>

<script lang="ts">
  import { defineComponent } from 'vue'

  import HelloWorld from '/@/components/HelloWorld.vue'

  export default defineComponent({
    name: 'App',
    components: {
      HelloWorld,
    },
  })
</script>
