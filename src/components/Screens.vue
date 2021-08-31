<template>
  <div class="screens">
    <div class="container">
      <h2>{{$t('screens.h2')}}</h2>
      <p>{{$t('screens.p')}}</p>
      <div class="btns">
        <button class="app_store">
          <i class="fab fa-apple fa-2x"></i>
          <div>
            <span>{{$t('screens.span1')}}</span>
            <span>{{$t('screens.span2')}}</span>
          </div>
        </button>
        <button class="google_play">
          <i class="fab fa-google-play fa-2x"></i>
          <div>
            <span>{{$t('screens.span3')}}</span>
            <span>{{$t('screens.span4')}}</span>
          </div>
        </button>
      </div>
      <div class="cover">
        <img src="../assets/screens.png" alt="" srcset="" />
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
p {
  padding: 40px 15%;
}
button {
  margin: 10px;
  outline: none;
  border: navajowhite;
  border-radius: 5px;
  display: inline-flex;
  flex-wrap: wrap;
  align-items: center;
  height: 60px;
  text-align: left;
}
.app_store,
.google_play {
  color: #fff;
  width: 220px;
  line-height: 1;

  > div {
    margin: 0 10px;
  }
  span:nth-child(2) {
    display: block;
    font-size: 22px;
    font-weight: bold;
  }
}
.app_store {
  background-color: #fcc825;
}
.google_play {
  background-color: #336b69;
}
i {
  margin: 10px;
  color: #fff;
}
img {
  max-width: 100%;
}
</style>