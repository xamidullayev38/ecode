<template>
    <nav class="nav">
        <div class="nav__content">
            <img src="@/assets/img/logo.png" alt="">
            <ul class="nav__list">
                <li>
                    <a href="" class="nav__list-link">
                        Product
                    </a>
                </li>
                <li>
                    <a href="" class="nav__list-link">
                        Use cases
                    </a>
                </li>
                <li>
                    <a href="" class="nav__list-link">
                        Pricing 
                    </a>
                </li>
                <li>
                    <a href="" class="nav__list-link">
                        Company
                    </a>
                </li>
                <li>
                    <a href="" class="nav__list-link">
                        Developers
                    </a>
                </li>
            </ul>
            <div class="nav__content-links">
                <a href="" class="link__glob">
                    Contact sales
                </a>
                <a href="" class="link__glob">
                    Start building
                </a>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    
}
</script>

<style>
    .nav__content{
        padding: 20px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .nav__list{
        display: flex;
        align-items: center;
        gap: 36px;
    }
    .nav__list-link{
        color: black;
        font-size: 15px;
        line-height: 18px;
    }
    .nav__content-links{
        display: flex;
        column-gap: 25px;
    }
</style>