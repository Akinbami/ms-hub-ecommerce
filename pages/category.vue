<template>
  <div>
    <mini_header />

    <div class="cover">
      <div class="cover__container">
        <h2>Shop your Lifestyle</h2>
        <p>
          Find the perfect furniture that is<br />
          both stylish and functional
        </p>
        <button>Shop Furniture</button>
      </div>
    </div>
    <div class="categories">
      <div class="category__title">
        Shop by Category
      </div>
      <div class="category">
        <div class="category__box">
          <img src="~/assets/images/home/default_name(-4.png" class="image" />
          <div class="category__name">
            <a href="/products">Living Room Furniture</a>
          </div>
        </div>
        <div class="category__box">
          <img src="~/assets/images/home/default_name(-4.png" class="image" />
          <div class="category__name">
            <a href="/products">Bedroom Furniture</a>
          </div>
        </div>
        <div class="category__box">
          <img src="~/assets/images/home/default_name(-4.png" class="image" />
          <div class="category__name">
            <a href="/products">Kitchen Furniture</a>
          </div>
        </div>
        <div class="category__box">
          <img src="~/assets/images/home/default_name(-4.png" class="image" />
          <div class="category__name">
            <a href="/products">Accent Furniture</a>
          </div>
        </div>
        <div class="category__box">
          <img src="~/assets/images/home/default_name(-4.png" class="image" />
          <div class="category__name">
            <a href="/products">Office Furniture</a>
          </div>
        </div>
        <div class="category__box">
          <img src="~/assets/images/home/default_name(-4.png" class="image" />
          <div class="category__name">
            <a href="/products">Entry Furniture</a>
          </div>
        </div>
        <div class="category__box">
          <img src="~/assets/images/home/default_name(-4.png" class="image" />
          <div class="category__name">
            <a href="/products">Outdoor Furniture</a>
          </div>
        </div>
        <div class="category__box">
          <img src="~/assets/images/home/default_name(-4.png" class="image" />
          <div class="category__name">
            <a href="/products">Bar Furniture</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import mini_header from "~/components/guest/mini-header";
export default {
  components: {
    mini_header
  }
};
</script>

<style></style>
