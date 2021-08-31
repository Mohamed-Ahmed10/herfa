<template>
  <div class="how">
    <div class="container">
      <h2>{{$t('how.h2')}}</h2>
        <p>{{$t('how.p1')}}</p>
      <div class="row">
        <div class="col">
          <div class="how_content">
            <i class="fas fa-search fa-3x"></i>
            <h3>{{$t('how.h3')}}</h3>
            <p>{{$t('how.p2')}}</p>
          </div>
        </div>
        <div class="col">
          <div class="products">
            <div class="product">
              <img
              src="../assets/jewelry.png"
              alt="this is image for jewelry"
              srcset=""
            />
              <span>{{$t('how.product1')}}</span>
            </div>
            <div class="product">
              <img
              src="../assets/pride.png"
              alt="this is image for pride"
              srcset=""
            />
              <span>{{$t('how.product2')}}</span>
            </div>
            <div class="product">
              <img
              src="../assets/drow.png"
              alt="this is image for drow"
              srcset=""
            />
              <span>{{$t('how.product3')}}</span>
            </div>
            <div class="product">
              <img
              src="../assets/doll.png"
              alt="this is image for doll"
              srcset=""
            />
              <span>{{$t('how.product4')}}</span>
            </div>
            <div class="product">
              <img
              src="../assets/reel.png"
              alt="this is image for reel"
              srcset=""
            />
              <span>{{$t('how.product5')}}</span>
            </div>
            <div class="product">
              <img
              src="../assets/sewing.png"
              alt="this is image for sewing"
              srcset=""
            />
              <span>{{$t('how.product6')}}</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.how {
  h2 {
    margin: 20px 0;
  }
  p {
    margin: 30px 0;
  }
  .row {
    justify-content: center;

    .how_content {
      text-align: left;
      margin: 0 11%;

      i {
        color: #1fbaba;
      }
    }
  }
  .products {
    width: 80%;
    padding: 10% 0;
    background-color: #fcc825;
    box-shadow: 5px 5px 4px #eee;

    .product {
      width: 46%;
      background: #fff;
      margin: 5px;
      padding: 10px;
      display: inline-flex;
      justify-content: flex-start;
      align-items: center;
      flex-wrap: nowrap;

      img {
        height: 40px;
      }
      span
      {
        margin: 0  10px;
      }
    }
  }
}
</style>