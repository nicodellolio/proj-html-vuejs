<script>
export default {
    name: 'AppJumbotron',

    data() {
        return {
        }
    }
}
</script>

<template>

    <section class="jumbotron">
        <div class="jumbo-top">

            <div class="jumbo-text">
                <h1>Distant learning for further expansion</h1>

                <p>Learning is a life-long journey that in fact we never find the terminate stop. Stop searching,
                    enjoy the process.
                </p>

                <button>
                    <i class="fa-solid fa-download"> </i>
                    Download free guide
                </button>

                <aside>Have questions?
                    <span class="free-sample">
                        Get Free Sample
                        <i class="fa-solid fa-arrow-right"></i>
                    </span>
                </aside>
            </div>

            <div class="jumbo-image">
                <img class="main-image" src="/images/about-me-profile-ohm4dxoearqbxny7q3bq1pzbdgofdx0tobbeqcvzd0.jpg"
                    alt="">
                <img class="square-dashed-up" src="/images/maxcoach-shape-07-100x100.png" alt="">
                <img class="square-dashed-down" src="/images/maxcoach-shape-07-100x100.png" alt="">
                <img class="square-dashed-right" src="/images/maxcoach-shape-07-150x150.png" alt="">

                <img class="circle-jumbo" src="/images/maxcoach-shape-02.png" alt="">
                <i class="fa-regular fa-circle"></i>
            </div>

        </div>

        <div class="jumbo-sponsor">
            <img src="/images/client-logo-01.png" alt="">
            <img src="/images/client-logo-02.png" alt="">
            <img src="/images/client-logo-03.png" alt="">
            <img src="/images/client-logo-04.png" alt="">
            <img src="/images/client-logo-05.png" alt="">
            <img src="/images/client-logo-06.png" alt="">
        </div>

        <div class="quick-access">
            <ul class="quick-access-items">
                <li><img src="/images/set-square-drawing.svg" alt=""></li>
                <li><i class="fa-solid fa-life-ring"></i></li>
                <li><i class="fa fa-book" aria-hidden="true"></i></li>
                <li><i class="fa-solid fa-cart-shopping"></i></li>
            </ul>
        </div>
    </section>
</template>

<style lang="css">
    @import url(/src/assets/partials/css/_jumbotron.css);
</style>