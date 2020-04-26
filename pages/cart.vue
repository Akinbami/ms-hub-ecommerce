<template>
<div class="cart">
    <div class="cart__title">
        Cart - 1 item
    </div>

    <div class="cart__items">
        <div class="cart__left">
            <div class="cart__image">
                <img src="~/assets/images/home/default_name(2).png" class="image">
            </div>
            <div class="cart__details">
                <div class="item__title">
                    Garren 22.4' Club Chair
                </div>
                <div class="item__color">
                   <span>Color:</span> <span>Red</span>
                </div>
                <div class="item__size">
                   <span>Size:</span> <span>2 x 5 x 3</span>
                </div>
            </div>
        </div>
        <div class="cart__right">
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
          <!-- <br/>
          <div>Remove</div> -->
        </div>
    </div>
    <div class="cart__actions">
        <div class="cart__main"></div>
        <div class="cart__side">
            <div class="order">
                <div class="order__type">
                    Order Total:
                </div>
                <div class="order__total">
                   ₦40,000
                </div>
            </div>
    <div class="order__button">
            <button class="proceed">Proceed to checkout</button>
             <button class="continue">Continue shopping</button>
    </div>
        </div>

    </div>
</div>

</template>

<script>
import mini_header from '~/components/guest/mini-header'
export default {
    data () {
    return {
      tab:'details',
      amount:0
    }
  },
  components: {
   mini_header
  }
}
</script>

<style>

</style>
