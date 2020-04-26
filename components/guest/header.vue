<template>
  <header v-if="$route.path === '/'" class="header--neutral">
    <div class="left">
      <div class="logo">
        <a href="/">
          <img
            src="~/assets/images/logo.png"
            style="width:50%;height:90%;margin-top:0px;cursor:pointer"
          />
        </a>
      </div>
      <div class="drop__menu"><a href="category">Categories</a></div>
    </div>
    <div class="center">
      <input type="text" placeholder="Search" />
      <i class="fa fa-search" aria-hidden="true"></i>
    </div>
    <div class="right">
      <div class="account"><a>Account</a></div>
      <div class="menu_cart"><a>Cart</a></div>
    </div>
  </header>
  <header v-else-if="$route.path !== '/'" class="header--color">
    <div class="header--color-container">
      <div class="left">
        <div class="logo">
          <a href="/">
            <img
              src="~/assets/images/logo.png"
              style="width:50%;height:90%;margin-top:3px;cursor:pointer"
            />
          </a>
        </div>
        <div class="drop__menu"><a href="/category">Categories</a></div>
      </div>
      <div class="center">
        <input type="text" placeholder="Search" />
        <i class="fa fa-search" aria-hidden="true"></i>
      </div>
      <div class="right">
        <div class="account"><a>Account</a></div>
        <div class="menu_cart"><a>Cart</a></div>
      </div>
    </div>
  </header>
</template>
<script>
export default {
  components: {},
  data() {
    return {};
  },
  head() {
    return {
      link: []
    };
  },
  methods: {}
};
</script>
<style>
a {
  text-decoration: none;
  color: white;
}
</style>
