<template>
  <div id="products">
    <div class="container">
      <h4>{{$t('products.h4')}}</h4>
      <div class="row">
        <div class="col">
          <div class="box">
            <img
              src="../assets/jewelry.png"
              alt="this is image for jewelry"
              srcset=""
            />
            <span>{{$t('products.product1')}}</span>
          </div>
        </div>
        <div class="col">
          <div class="box">
            <img
              src="../assets/pride.png"
              alt="this is image for pride"
              srcset=""
            />
            <span>{{$t('products.product2')}}</span>
          </div>
        </div>
        <div class="col">
          <div class="box">
            <img
              src="../assets/drow.png"
              alt="this is image for drow"
              srcset=""
            />
            <span>{{$t('products.product3')}}</span>
          </div>
        </div>
        <div class="col">
          <div class="box">
            <img
              src="../assets/doll.png"
              alt="this is image for doll"
              srcset=""
            />
            <span>{{$t('products.product4')}}</span>
          </div>
        </div>
        <div class="col">
          <div class="box">
            <img
              src="../assets/reel.png"
              alt="this is image for reel"
              srcset=""
            />
            <span>{{$t('products.product5')}}</span>
          </div>
        </div>
        <div class="col">
          <div class="box">
            <img
              src="../assets/sewing.png"
              alt="this is image for sewing"
              srcset=""
            />
            <span>{{$t('products.product6')}}</span>
          </div>
        </div>
        <div class="col">
          <div class="box">
            <img
              src="../assets/wicker.png"
              alt="this is image for wicker"
              srcset=""
            />
            <span>{{$t('products.product7')}}</span>
          </div>
        </div>
        <div class="col">
          <div class="box">
            <img
              src="../assets/phone.png"
              alt="this is image for phone"
              srcset=""
            />
            <span>{{$t('products.product8')}}</span>
          </div>
        </div>
        <div class="col">
          <div class="box">
            <img
              src="../assets/accessories.png"
              alt="this is image for accessories"
              srcset=""
            />
            <span>{{$t('products.product9')}}</span>
          </div>
        </div>
        <div class="col">
          <div class="box">
            <img
              src="../assets/wood.png"
              alt="this is image for wood"
              srcset=""
            />
            <span>{{$t('products.product10')}}</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
#products {
  margin: 40px 0;

  h4 {
    margin: 40px 0;
  }

  .box {
    display: flex;
    flex-wrap: nowrap;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    height: 170px;
    width: 170px;
    margin: 15px 5px ;
    padding: 20px 0;
    box-shadow: 5px 4px 5px #eee, -5px -5px 5px #eee;
    cursor: pointer;
    img {
      max-width: 50%;
    }
    span {
      text-transform: capitalize;
    }
    &:hover span {
      color: #fcc825;
      cursor: context-menu;
    }
  }
}
</style>

<script>
export default {
  name: "Products",
};
</script>