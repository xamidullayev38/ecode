<template>
  <div class="connect__content">
        <div class="connect__content-left">
            <img src="@/assets/img/img3.png" alt="" class="optimize__img">
        </div>
        <div class="connect__right">
                        <span class="title__glob">
                Optimize
            </span>
            <h3 class="connect__content-title">
                Enable smart energy use cases for your customers
            </h3>
            <p class="connect__content-subtitle">
                Ready-made building blocks to help your customers consume energy in a smarter, more sustainable way.
            </p>
            <div class="connect__item">
                <div class="connect__item-box">
                    <img src="@/assets/img/check.svg" alt="">
                    <p class="connect__item-text">
                        Out-of-the-box smart charging APIs
                    </p>
                </div>
                <div class="connect__item-box">
                    <img src="@/assets/img/check.svg" alt="">
                    <p class="connect__item-text">
                        Statistics and insights APIs
                    </p>
                </div>
                <div class="connect__item-box box__third">
                    <img src="@/assets/img/check.svg" alt="">
                    <p class="connect__item-text">
                        Endpoints to build your own features
                    </p>
                </div>
            </div>
            <a href="" class="connect__content-link">
                Learn more
            </a>
        </div>
  </div>
  <div class="connect__content">
        <div class="connect__content-left">
            <span class="title__glob">
                Aggregate
            </span>
            <h3 class="connect__content-title">
                Accelerate the transition to a sustainable future
            </h3>
            <p class="connect__content-subtitle">
                Aggregation of flexible demand is key to a grid powered by renewable energy. By aggregating your customer's energy loads you can smooth out intermittencies caused by renewables. It also provides new revenue streams for your business.
            </p>
            <div class="connect__item">
                <div class="connect__item-box">
                    <img src="@/assets/img/check.svg" alt="">
                    <p class="connect__item-text">
                        Participate in flexibility markets
                    </p>
                </div>
                <div class="connect__item-box">
                    <img src="@/assets/img/check.svg" alt="">
                    <p class="connect__item-text">
                        Unlock new revenue streams
                    </p>
                </div>
                <div class="connect__item-box box__third">
                    <img src="@/assets/img/check.svg" alt="">
                    <p class="connect__item-text">
                        Monitoring, demand response and reporting APIs
                    </p>
                </div>
            </div>
            <a href="" class="connect__content-link">
                Learn more
            </a>
        </div>
        <div class="connect__right">
 
            <img src="@/assets/img/img4.png" alt="" class="optimize__img">
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
        column-gap: 30px;
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