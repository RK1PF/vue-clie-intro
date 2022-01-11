<template>
  <div class="counter">
    <h1>{{ counter }}</h1>
    <button @click="count(1)">Increment</button>
    <button @click="count(-1)">Decrement</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      counter: 0,
    };
  },
  methods: {
  count (x) {
      this.counter += x
  }
  },
};
</script>
<style>
a {
  padding: 1em;
}
</style>
