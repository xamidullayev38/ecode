<template>
  <div class="case__content">
    <div class="case__content-top">
        <p class="case__content-title">
            Use cases
        </p>
        <div class="case__content-blocks">
            <div class="case__content-block">
            <div class="img__bg">
                <img src="@/assets/img/charge.svg" alt="">
            </div>
            <p class="case__content-text">
                Smart charging <br><br>
                Optimize the charging of your customers EV with the click of a button
            </p>
            <a href="" class="case__content-link">
                Learn more...
            </a>
            </div>
            <div class="case__content-block">
            <div class="img__bg">
                <img src="@/assets/img/time.svg" alt="">
            </div>
            <p class="case__content-text">
                Energy management and insights <br><br>

                Give your customers insight about their energy consumption
            </p>
            <a href="" class="case__content-link">
                Learn more...
            </a>
            </div>
            <div class="case__content-block">
            <div class="img__bg">
                <img src="@/assets/img/demand.svg" alt="">
            </div>
            <p class="case__content-text">
                Demand response <br><br>

                Unlock the ability to participate in flexibility markets
            </p>
            <a href="" class="case__content-link">
                Learn more...
            </a>
            </div>
            <div class="case__content-block">
            <div class="img__bg">
                <img src="@/assets/img/car.svg" alt="">
            </div>
            <p class="case__content-text">
                E-mobility <br><br>

                Provide smart route planning and rich EV data during public charging
            </p>
            <a href="" class="case__content-link">
                Learn more...
            </a>
            </div>
        </div>
    </div>
    <div class="case__content-bottom">
        <p class="case__content-title">
            Industries and applications
            <a href="" class="case__content-link">
                Learn more...
            </a>
        </p>
        <div class="case__content-blocks">
            <div class="case__content-block">
            <div class="img__bg">
                <img src="@/assets/img/energy.svg" alt="">
            </div>
            <p class="case__content-text">
                Energy companies <br><br>
                Create engaging energy apps that increase retention and enable demand response revenue streams
            </p>
            <a href="" class="case__content-link">
                Learn more...
            </a>
            </div>
            <div class="case__content-block">
            <div class="img__bg">
                <img src="@/assets/img/phone.svg" alt="">
            </div>
            <p class="case__content-text">
                Energy startups and apps <br><br>

                Build the next wave of green energy apps, connecting directly to your users' hardware
            </p>
            <a href="" class="case__content-link">
                Learn more...
            </a>
            </div>
            <div class="case__content-block">
            <div class="img__bg">
                <img src="@/assets/img/e-mobility.svg" alt="">
            </div>
            <p class="case__content-text">
                E-mobility providers <br><br>

                Get real-time EV and charging data across multiple OEMs into your apps and services
            </p>
            <a href="" class="case__content-link">
                Learn more...
            </a>
            </div>
            <div class="case__content-block">
            <div class="img__bg">
                <img src="@/assets/img/circles.svg" alt="">
            </div>
            <p class="case__content-text">
                DERMS <br><br>

                Create residential DR programs with direct access to user's EVs, thermostats and more
            </p>
            <a href="" class="case__content-link">
                Learn more...
            </a>
            </div>
        </div>
        <div class="case__content-blocks">
            <div class="case__content-block">
            <div class="img__bg">
                <img src="@/assets/img/car.svg" alt="">
            </div>
            <p class="case__content-text">
                EV fleet managers <br><br>
                Get SoC and location from your entire fleet in real time - at a fraction of the cost compared to OBD
            </p>
            <a href="" class="case__content-link">
                Learn more...
            </a>
            </div>
            <div class="case__content-block">
            <div class="img__bg">
                <img src="@/assets/img/key.svg" alt="">
            </div>
            <p class="case__content-text">
                Utility and grid owners <br><br>

                Anticipate grid constraints with aggregated EV data and build demand response programs at scale
            </p>
            <a href="" class="case__content-link">
                Learn more...
            </a>
            </div>
            <div class="case__content-block">
            <div class="img__bg">
                <img src="@/assets/img/house.svg" alt="">
            </div>
            <p class="case__content-text">
                Smart home providers <br><br>

                Integrate EVs, thermostats and other energy hardware into your solution - no hardware hub required
            </p>
            <a href="" class="case__content-link">
                Learn more...
            </a>
            </div>
            <div class="case__content-block">
            <div class="img__bg">
                <img src="@/assets/img/loader.svg" alt="">
            </div>
            <p class="case__content-text">
                Don’t see your industry? <br><br>

                We also partner with other types of companies. Reach out to learn what we can build together!
            </p>
            <a href="" class="case__content-link">
                Learn more...
            </a>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
    .case__content{
        padding: 110px 0px;
        row-gap: 80px;
    }
    .case__content-top{
        padding-bottom: 100px;
    }
    .case__content-bottom{
        display: flex;
        flex-direction: column;
        row-gap: 66px;
    }
    .case__content-blocks{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .case__content-block{
        max-width: 250px;

    }
    .case__content-title{
        font-size: 24px;
        line-height: 28px;
        color: #002203;
        padding-bottom: 80px;
        display: flex;
        justify-content: space-between;
    }
    .img__bg{
        width: 40px;
        height: 40px;
        background: #E1FDAE;
        margin-bottom: 20px;
        border-radius: 8px;
        padding: 8px;
    }.case__content-text{
        padding-bottom: 16px;
        font-size: 15px;
        color: #423F35;
    }
    .case__content-link{
        color: #00780C;
        font-size: 15px;
    }
</style>