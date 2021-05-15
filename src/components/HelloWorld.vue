<template>
  <div class="flex w-full items-center justify-center mt-8">
    <div class="flex flex-col items-center space-y-2">
      <h1 class="text-xl">{{ msg }}</h1>
      <button
        class="bg-indigo-500 text-white px-3 py-1 rounded font-bold"
        @click="count++"
      >
        count is: {{ count }}
      </button>
      <p>
        Edit <code>components/HelloWorld.vue</code> to test hot module
        replacement.
      </p>
    </div>
  </div>
</template>

<script lang="ts">
  import { defineComponent } from 'vue'
  export default defineComponent({
    name: 'HelloWorld',
    props: {
      msg: { type: String, default: '' },
    },
    data() {
      return {
        count: 0,
      }
    },
  })
</script>
