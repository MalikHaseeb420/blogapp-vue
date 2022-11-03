<template>
  <div class="data">
    <h1>Personal Details</h1>
    <p><strong>Name: </strong>{{ name }}</p>
    <p><strong>Email: </strong>{{ email }}</p>
    <p><strong>Phone: </strong>{{ phone }}</p>
    <button v-on:click="test()">Click me</button>
  </div>
</template>
<script>
export default {
  name: 'HomePage',
  data() {
    return {
      name: 'Muhammad Haseeb Malik',
      email: 'haseeb.nazeer@devsinc.com',
      phone: '03094022674'
    }
  },
  methods: {
    test() {
      alert('I am clicked')
    }
  }
}
</script>
<style>
.data {
  max-width: 40%;
  margin: 30px auto;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
</style>
