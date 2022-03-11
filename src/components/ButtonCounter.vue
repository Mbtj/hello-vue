<template>
  <h2>Counter: {{ count }}</h2>
  <button @click="increment">Increment</button>
</template>

<script>
export default {
  name: "ButtonCounter",
  props: {
    initialCount: Number,
  },

  data() {
    return {
      count: this.initialCount,
    };
  },

  methods: {
    increment() {
      this.count++;
    },
  },
};
</script>
