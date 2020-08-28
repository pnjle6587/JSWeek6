<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About us</router-link> |
    <router-link to="/product">Product</router-link> |
    <router-link to="/cart">Cart</router-link> |
    <router-link to="/admin">Admin</router-link>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data() {
    return {
    };
  },
};
</script>
