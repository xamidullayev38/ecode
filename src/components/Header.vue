<template>
  <header class="header">
    <div class="header__left">
        <h1>
            Infrastructure for green energy apps
        </h1>
        <p class="header__left-subtitle">
            Companies of all sizes, from startups to the largest energy companies in the world, use Enode's APIs to create new green energy apps and services.
        </p>
        <div class="header__left-links">
            <a href="" class="link__glob">Start building</a>
            <a href="" class="link__glob">Contact sales</a>
        </div>
    </div>
    <div class="header__right">
        <img src="@/assets/img/img2.png" alt="" class="header__right-img">
    </div>
  </header>
</template>

<script>
export default {

}
</script>

<style>
    .header{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 80px 0 30px;
    }
    .header__left{
        width: 600px;
    }
    h1{
        font-size: 72px;
        line-height: 64px;
        letter-spacing: 4.32px;
    }
    .header__left-subtitle{
        font-size: 18px;
        line-height: 28px;
        color: #423F35;
        padding: 14px 0 38px;

    }
    .header__left-links{
        display: flex;
        column-gap: 20px
    }
</style>