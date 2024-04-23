<template>
  <div class="connect__content">
        <div class="connect__content-left">
            <span class="title__glob">
                Connect
            </span>
            <h3 class="connect__content-title">
                One powerful API, hundreds of EVs and energy devices
            </h3>
            <p class="connect__content-subtitle">
                Easily connect to and control your customers’ electric vehicles, thermostats, solar panels and more.
            </p>
            <div class="connect__item">
                <div class="connect__item-box">
                    <img src="@/assets/img/check.svg" alt="">
                    <p class="connect__item-text">
                        One API for over 20+ hardware brands
                    </p>
                </div>
                <div class="connect__item-box">
                    <img src="@/assets/img/check.svg" alt="">
                    <p class="connect__item-text">
                        100+ devices supported and counting
                    </p>
                </div>
                <div class="connect__item-box box__third">
                    <img src="@/assets/img/check.svg" alt="">
                    <p class="connect__item-text">
                        SDKs and ready-built connection flows
                    </p>
                </div>
            </div>
            <a href="" class="connect__content-link">
                Learn more
            </a>
        </div>
        <div class="connect__right">
            <img src="@/assets/img/img2.png" alt="">
        </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
    .connect__content{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .connect__content-title{
        width: 536px;
        font-size: 39px;
        line-height: 40px;
        letter-spacing: 2px;
        color: #002203;
    }
    .connect__content-subtitle{
        font-size: 18px;
        line-height: 28px;
        color: #423F35;
        padding: 42px 0 29px;
    }
    .connect__item-box{
        display: flex;
        align-items: center;
        gap: 10px;
        padding-bottom: 8px;
    }
    .connect__content-link{
        color: #002203;
        font-weight: 600;
        padding: 4px 16px;
        border-radius: 20px;
        background: #00ff3c30;
    }
    .box__third{
        padding-bottom: 50px;
    }
</style>