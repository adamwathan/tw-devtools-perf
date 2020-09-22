<template>
  <div class="p-8 min-h-screen grid place-items-center">
    <h1 class="text-7xl font-extrabold text-center">
      <span class="bg-gradient-to-r from-blue-400 to-purple-500 bg-clip-text text-transparent">
        Hello from Tailwind!
      </span>
    </h1>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
}
</script>
