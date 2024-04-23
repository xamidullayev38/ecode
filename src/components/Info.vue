<template>
    <div class="info__content">
    <span class="title__glob">
      By developers, for developers
    </span>
    <h3 class="info__content-title">
      A single API for hundreds of green energy devices
    </h3>
    <p class="info__content-subtitle">
        Access and control 100s of EV models and energy devices through a few lines of code, and save months of tedious integration work.
    </p>
    <div class="connect__item">
                <div class="connect__item-box">
                    <img src="@/assets/img/check.svg" alt="">
                    <p class="connect__item-text">
                        A single RESTful API for all connections
                    </p>
                </div>
                <div class="connect__item-box">
                    <img src="@/assets/img/check.svg" alt="">
                    <p class="connect__item-text">
                        Web and native SDKs for hardware connection
                    </p>
                </div>
                <div class="connect__item-box box__third">
                    <img src="@/assets/img/check.svg" alt="">
                    <p class="connect__item-text">
                        Enterprise grade security by design
                    </p>
                </div>
    </div>
    <a href="" class="info__content-link">
      Read our docs
    </a>
  </div>
</template>

<script>
export default {

}
</script>

<style>
  .info__content{
    padding: 100px;
    background: #000;
  }
  .info__content-title{
    font-size: 39px;
    line-height: 40px;
    letter-spacing: 2px;
    color: white;
    width: 480px;
  }
  .info__content-subtitle{
    font-size: 18px;
    line-height: 28px;
    color: #DAD5C6;
    padding: 42px 0 29px;
    width: 480px;
  }
  .connect__item{
    color: #DAD5C6;
  }
  .info__content-link{
    background: #00780C;
    color: white;
    padding: 1px 8px;
    border-radius: 20px;
  }
</style>