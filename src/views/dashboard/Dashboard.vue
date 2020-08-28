<template>
  <div>
    <h2>This is dashboard</h2>
    <div id="nav">
      <router-link to="/admin/productmanage">Product manage</router-link> |
      <router-link to="/admin/orders">Orders</router-link> |
      <router-link to="/admin/coupons">Coupons</router-link> |
      <router-link to="/">Back to front</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
