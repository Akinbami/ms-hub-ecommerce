<template>
  <div>
    <mini_header />
    <breadcrumb />
    <div class="sort">
      <div class="select">
        <select>
          <option>Sort by: Relevance</option>
        </select>
        <i class="fa fa-angle-down" aria-hidden="true"></i>
      </div>
      <div class="select">
        <select>
          <option>Sort by: Brand</option>
        </select>
        <i class="fa fa-angle-down" aria-hidden="true"></i>
      </div>
      <div class="select">
        <select>
          <option>Sort by: Location</option>
        </select>
        <i class="fa fa-angle-down" aria-hidden="true"></i>
      </div>
      <div class="select">
        <select>
          <option>Sort by: Filter</option>
        </select>
        <i class="fa fa-filter small" aria-hidden="true"></i>
      </div>
    </div>
    <div class="all__products">
      <div class="products__box">
        <div class="box">
          <img src="~/assets/images/home/default_name(2).png" class="image" />
          <div class="box__title">
            <a href="/product">Simpsons Max Sofa House Chair</a>
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating
              :star-size="15"
              :show-rating="false"
              rating="4"
            ></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(3).png" class="image" />
          <div class="box__title">
            <a href="/product">Simpsons Max Sofa House Chair</a>
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating
              :star-size="15"
              :show-rating="false"
              rating="4"
            ></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(-2.png" class="image" />
          <div class="box__title">
            <a href="/product">Simpsons Max Sofa House Chair</a>
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating
              :star-size="15"
              :show-rating="false"
              rating="4"
            ></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(-3.png" class="image" />
          <div class="box__title">
            <a href="/product">Simpsons Max Sofa House Chair</a>
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating
              :star-size="15"
              :show-rating="false"
              rating="4"
            ></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(2).png" class="image" />
          <div class="box__title">
            <a href="/product">Simpsons Max Sofa House Chair</a>
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating
              :star-size="15"
              :show-rating="false"
              rating="4"
            ></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(3).png" class="image" />
          <div class="box__title">
            <a href="/product">Simpsons Max Sofa House Chair</a>
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating
              :star-size="15"
              :show-rating="false"
              rating="4"
            ></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(-2.png" class="image" />
          <div class="box__title">
            <a href="/product">Simpsons Max Sofa House Chair</a>
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating
              :star-size="15"
              :show-rating="false"
              rating="4"
            ></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(-3.png" class="image" />
          <div class="box__title">
            <a href="/product">Simpsons Max Sofa House Chair</a>
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating
              :star-size="15"
              :show-rating="false"
              rating="4"
            ></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(2).png" class="image" />
          <div class="box__title">
            <a href="/product">Simpsons Max Sofa House Chair</a>
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating
              :star-size="15"
              :show-rating="false"
              rating="4"
            ></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(3).png" class="image" />
          <div class="box__title">
            <a href="/product">Simpsons Max Sofa House Chair</a>
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating
              :star-size="15"
              :show-rating="false"
              rating="4"
            ></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(-2.png" class="image" />
          <div class="box__title">
            <a href="/product">Simpsons Max Sofa House Chair</a>
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating
              :star-size="15"
              :show-rating="false"
              rating="4"
            ></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(-3.png" class="image" />
          <div class="box__title">
            <a href="/product">Simpsons Max Sofa House Chair</a>
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating
              :star-size="15"
              :show-rating="false"
              rating="4"
            ></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(2).png" class="image" />
          <div class="box__title">
            <a href="/product">Simpsons Max Sofa House Chair</a>
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating
              :star-size="15"
              :show-rating="false"
              rating="4"
            ></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(3).png" class="image" />
          <div class="box__title">
            <a href="/product">Simpsons Max Sofa House Chair</a>
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating
              :star-size="15"
              :show-rating="false"
              rating="4"
            ></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(-2.png" class="image" />
          <div class="box__title">
            <a href="/product">Simpsons Max Sofa House Chair</a>
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating
              :star-size="15"
              :show-rating="false"
              rating="4"
            ></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(-3.png" class="image" />
          <div class="box__title">
            <a href="/product">Simpsons Max Sofa House Chair</a>
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating
              :star-size="15"
              :show-rating="false"
              rating="4"
            ></star-rating>
          </div>
        </div>
      </div>
    </div>
    <div class="pagination">
      <ul class="page">
        <li class="page--active">
          1
        </li>
        <li>
          2
        </li>
        <li>
          3
        </li>
        <li>
          4
        </li>
        <li>
          5
        </li>
        <li>
          <i class="fa fa-angle-right" aria-hidden="true"></i>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import mini_header from "~/components/guest/mini-header";
import breadcrumb from "~/components/guest/breadcrumb";
export default {
  components: {
    mini_header,
    breadcrumb
  }
};
</script>

<style></style>
