<template>
  <h1>About Page</h1>
  <hr>
  <h2>{{ name }}</h2>
  <button @click="OnChangedName">
    Cambiar nombre 
  </button>
</template>

<script>
export default {
    data() {
        return {
            name: 'Johan'
        }
    },
    methods: {
        OnChangedName() {
            this.name = 'John'
        }
    }
}
</script>