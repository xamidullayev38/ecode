<template>
  <div class="future__content">
    <span class="title__glob">
        Our platform
    </span>
    <h2 class="future__content-title">
        The A-Z of what you need to build the future of green energy apps
    </h2>
    <div class="futere__content-item">
        <div class="item__left">
            <p class="future__content-text">
            A fully renewable energy system is dependent on flexible demand that can adapt to the intermittent supply from wind and solar. To create this flexibility, we need to connect to and control the fast-growing demand from electric vehicles, heat pumps, and other energy hardware. <br><br><br><br>
            <span class="title__glob">Connect API</span><br><br>
            handles the complex task of connecting to and controlling all energy hardware OEMs across electric vehicles, thermostats, solar inverters, and home batteries.
        </p>
        </div>
        <div class="item__right">
            <p class="future__content-text">
            <span class="title__glob">Optimize</span><br>
            <br>
            
            Our features, including smart EV charging, help your users consume energy in an innovative, more sustainable way. <br><br><br>
            <span class="title__glob">Aggregate</span><br><br>
            And our engine lets you control all of your users' energy hardware as a single virtual power plant.
            <br><br>
            That way, you can focus on building the best green energy apps the world has seen.
        </p>
        </div>
    </div>
    <div class="box__img">
        <img src="@/assets/img/img1.png" alt="">
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
    .future__content{
        padding: 80px 0;

    }
    .future__content-title{
        font-size: 39px;
        line-height: 40px;
        letter-spacing: 2px;
        width: 650px;
        padding-bottom: 75px;
    }
    .futere__content-item{
        display: flex;
        justify-content: space-between;
        padding-bottom: 135px;
    }
    
    .item__left{
        width: 470px;
    }
    .item__right{
        width: 470px;
    }
    .future__content-text{
        font-size: 18px;
        line-height: 28px;
        color: #423F35;
    }
</style>