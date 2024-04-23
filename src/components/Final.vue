<template>
    <section class="final">
        <div class="final__content">
            <h4 class="final__content-title">
                Ready to get started?
            </h4>
            <p class="final__content-subtitle">
                Start exploring our APIs for free with our Starter plan or get in touch to have us put together a custom plan for your company.
            </p>
            <div class="final__content-links">
            <a href="" class="link__glob">Start building    →</a>
            <a href="" class="link__glob">Contact sales  →</a>
        </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>
    .final{
        padding: 80px 56px;
        background: #F5F3EE;
    }
    .final__content{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        padding: 57px 64px;
        border-radius: 24px;
        background: white;
    }
    .final__content-title{
        font-size: 25px;
        line-height: 28px;
        padding-bottom: 32px;
    }
    .final__content-subtitle{
        font-size: 18px;
        line-height: 28px;
        padding-bottom: 50px;
        text-align: center;
    }
    .final__content-links{
        display: flex;
        column-gap: 28px;
    }
</style>