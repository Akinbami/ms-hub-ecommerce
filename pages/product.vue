<template>
<div>
    <mini_header/>
    <breadcrumb/>
    <div class="product">
      <div class="images">
        <div class="main">
         <img src="~/assets/images/home/default_name(3).png" class="image">
        </div>
        <div class="images__small">
          <img src="~/assets/images/home/default_name(3).png" class="image">
          <img src="~/assets/images/home/default_name(3).png" class="image">
          <img src="~/assets/images/home/default_name(3).png" class="image">
          <img src="~/assets/images/home/default_name(3).png" class="image">
          <img src="~/assets/images/home/default_name(3).png" class="image">
        </div>
      </div>
      <div class="content">
        <div class="category">
          Furniture
        </div>
        <div class="title">
          Garren 22.4' Club Chair
        </div>

        <div class="tabs">
          <div class="tab">
            <div class="tab__title">
              <div class="text">Details</div>
              <div class="icon"><span @click="tab ='details'"><b v-if="tab !== 'details'"><i class="fa fa-plus" aria-hidden="true"></i></b><b v-else><i class="fa fa-minus" aria-hidden="true"></i></b></span></div>
            </div>
            <div class="tab__more" v-show="tab === 'details'">
            Materials
            Lacquered metal with fabric cord

            Dimensions
            KF1: Ø47.5 cm
            KF2: Ø70 cm

            Light source
            KF1: E27 Max 100W (not included)
            KF2: E27 Max 150W (not included)
            The luminaire is compatible with bulbs of energy classes A+++ - E.
            </div>
          </div>
          <div class="tab">
            <div class="tab__title">
              <div class="text">Delivery Information</div>
              <div class="icon"><span @click="tab ='delivery'"><b v-if="tab !== 'delivery'"><i class="fa fa-plus" aria-hidden="true"></i></b><b v-else><i class="fa fa-minus" aria-hidden="true"></i></b></span></div>
            </div>
            <div class="tab__more" v-show="tab === 'delivery'">
            Materials
            Lacquered metal with fabric cord

            Dimensions
            KF1: Ø47.5 cm
            KF2: Ø70 cm

            Light source
            KF1: E27 Max 100W (not included)
            KF2: E27 Max 150W (not included)
            The luminaire is compatible with bulbs of energy classes A+++ - E.
            </div>
          </div>
          <div class="tab">
            <div class="tab__title">
              <div class="text">Reviews</div>
              <div class="icon"><span @click="tab ='reviews'"><b v-if="tab !== 'reviews'"><i class="fa fa-plus" aria-hidden="true"></i></b><b v-else><i class="fa fa-minus" aria-hidden="true"></i></b></span></div>
            </div>
            <div class="tab__more" v-show="tab === 'reviews'">
            Materials
            Lacquered metal with fabric cord

            Dimensions
            KF1: Ø47.5 cm
            KF2: Ø70 cm

            Light source
            KF1: E27 Max 100W (not included)
            KF2: E27 Max 150W (not included)
            The luminaire is compatible with bulbs of energy classes A+++ - E.
            </div>
          </div>
        </div>
        <div class="form__control">
          <label>Size</label>

          <div class="select">
            <select>
              <option>Select size</option>
            </select>
            <i class="fa fa-angle-down" aria-hidden="true"></i>
          </div>
        </div>
        <div class="form__control">
          <label>Colour</label>
          <div class="select">
            <select>
              <option>Select color</option>
            </select>
            <i class="fa fa-angle-down" aria-hidden="true"></i>
          </div>
        </div>
        <div class="form__control">
          <label>Price</label>
          <div class="price">
            ₦40,000
          </div>
        </div>
        <div class="actions">
          <div class="toggle">
            <div class="minus">
              -
            </div>
            <!-- <div class="input"> -->
              <input v-model="amount"/>
            <!-- </div> -->
            <div class="plus">
              +
            </div>
          </div>
          <div class="button">
            <button>Add to cart</button>
          </div>
        </div>
      </div>
    </div>
    <div class="related">
      <div class="related__title">
        Related Products
      </div>
      <div class="related__list">
        <div class="box">
          <img src="~/assets/images/home/default_name(2).png" class="image">
          <div class="box__title">
            Simpsons Max Sofa House
Chair
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating :star-size="15" :show-rating="false" rating="4"></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(2).png" class="image">
          <div class="box__title">
            Simpsons Max Sofa House
Chair
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating :star-size="15" :show-rating="false" rating="4"></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(2).png" class="image">
          <div class="box__title">
            Simpsons Max Sofa House
Chair
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating :star-size="15" :show-rating="false" rating="4"></star-rating>
          </div>
        </div>
        <div class="box">
          <img src="~/assets/images/home/default_name(2).png" class="image">
          <div class="box__title">
            Simpsons Max Sofa House
Chair
          </div>
          <div class="box__amount">
            ₦80,000
          </div>
          <div class="box__rating">
            <star-rating :star-size="15" :show-rating="false" rating="4"></star-rating>
          </div>
        </div>
      </div>
    </div>
</div>
</template>

<script>
import mini_header from '~/components/guest/mini-header'
import breadcrumb from '~/components/guest/breadcrumb'
export default {
   data () {
    return {
      tab:'details',
      amount:0
    }
  },
  components: {
   mini_header,
   breadcrumb
  }
}
</script>

<style>

</style>
