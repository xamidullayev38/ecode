<template>
  <footer class="footer">
    <div class="footer__content">
        <div class="footer__search">
            <div class="footer__search-box">
                <div class="img__box">
                <img src="@/assets/img/e-mail.svg" alt="" class="footer__search-img">
                </div>
            <p class="footer__search-text">
                <b>Lead the transition to open energy</b> <br>
                Subscribe to our monthly newsletter for the latest insights and inspiration
            </p>
            </div>
            <div class="footer__search-item">
                <input type="text" placeholder="E-mail address">
            <a href="" class="link__glob">
                Sign up   →
            </a>
            </div>
        </div>
        <div class="footer__content-cards">
            <div class="footer__content-card">
                <a href="" class="footer__content-link">
                    Products
                </a>
                <a href="" class="footer__content-link">
                    Connect
                </a>
                <a href="" class="footer__content-link">
                    Optimize
                </a>
                <a href="" class="footer__content-link">
                    Aggregate
                </a>
                <a href="" class="footer__content-link">
                    Pricing
                </a>
            </div>
            <div class="footer__content-card">
                <a href="" class="footer__content-link">
                    Developers
                </a>
                <a href="" class="footer__content-link">
                    API reference
                </a>
                <a href="" class="footer__content-link">
                    Getting started
                </a>
                <a href="" class="footer__content-link">
                    Features guides 
                </a>
                <a href="" class="footer__content-link">
                    Reference articles
                </a>
            </div>
            <div class="footer__content-card">
                <a href="" class="footer__content-link">
                    Company
                </a>
                <a href="" class="footer__content-link">
                    About us
                </a>
                <a href="" class="footer__content-link">
                    Blog
                </a>
                <a href="" class="footer__content-link">
                    Careers 
                </a>
                <a href="" class="footer__content-link">
                    Contact us
                </a>
            </div>
            <div class="footer__content-card">
                <a href="" class="footer__content-link">
                    Use cases
                </a>
                <a href="" class="footer__content-link">
                    Smart charging
                </a>
                <a href="" class="footer__content-link">
                    Energy management and insights 
                </a>
                <a href="" class="footer__content-link">
                    Demand response
                </a>
                <a href="" class="footer__content-link">
                    E-mobility
                </a>
                <a href="" class="footer__content-link">
                    EV fleet management
                </a>
            </div>
        </div>
    </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style>
    .footer__content{
        padding: 24px 0;
    }
    .footer__search{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding-bottom: 90px;
    }
    .img__box{
        padding: 8px;
        background: #E1FDAE;
        border-radius: 8px;
    }
    .footer__search-box{
        display: flex;
        align-items: center;
        column-gap: 16px;
    }
    .footer__search-item{
        display: flex;
        column-gap: 32px;
    }
    input{
        border-radius: 8px;
        width: 260px;
        height: 40px;
        border: 1px solid #DAD5C6;
        padding: 4px;
    }
    .footer__content-cards{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .footer__content-card{
        display: flex;
        flex-direction: column;
        gap: 8px;
    }
    .footer__content-link{
        color: #423F35;
        font-size: 15px;
    }
</style>