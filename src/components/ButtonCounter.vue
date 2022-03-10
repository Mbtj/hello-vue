<template>
  <h2>Counter: {{ count }}</h2>
  <button @click="count++">Increment</button> 
</template>

<script>
export default {
  name: "ButtonCounter",
  props: {
    count: Number
  }
}
</script>
