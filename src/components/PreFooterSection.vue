<script>

export default {
    name: 'PreFooterSection',

    data() {
        return {
            bestBlogsItems: [
                "Become a Better Blogger: Content Planning",
                "Promoting Your Online Business on Pinterest",
                "Gratification and Game-Based Learning",
                "Designing on Online Course from Experts's Perspective.",
                "Why Online Courses Are the Future of Education"
            ]
        }
    }
}
</script>

<template>
    <section class="our-numbers">
        <div class="number">

        </div>

        <div class="number">
            <h2>Successfully trained</h2>
            <h1>1790</h1>
            <h3>enrolled learners</h3>
        </div>

        <div class="number">
            <h2>Proudly Received</h2>
            <h1>19</h1>
            <h3>Countrywide awards</h3>
        </div>

        <div class="number">
            <h2>Firmly established</h2>
            <h1>24</h1>
            <h3>Local Branches</h3>
        </div>

        <div class="number">
            <h2>Getting Featured on</h2>
            <h1>1090</h1>
            <h3>Blog Posts</h3>
        </div>

        <div class="number">
        </div>
    </section>

    <section class="best-blogs">

        <div class="blogs-box">
            <div class="best-blog bb-text">
                <h3>Enjoyable insights</h3>
                <h1>Most Viewed </h1>
                <h1>Best Blogs</h1>
                <ul>
                    <li v-for="bbItem in bestBlogsItems">
                        <i class="fa fa-arrow-right" aria-hidden="true"></i>
                        {{ bbItem }}
                    </li>
                </ul>
            </div>

            <div class="best-blog">
                <img src="/images/artist-blog-03-480x352.jpeg" alt="">

                <h3>Artist</h3>
                <h4>Brush Strokes Energize Trees in Paintings</h4>

                <span><i class="fa fa-calendar" aria-hidden="true"></i>
                    May, 15, 2020
                </span> <span><i class="fa fa-eye" aria-hidden="true"></i>
                    688 views
                </span>
            </div>

            <div class="best-blog">
                <img src="/images/artist-blog-01-480x352.jpg" alt="">

                <h3>Artist</h3>
                <h4>Pocket-Sized Notebooks Hold Miniature Paintings</h4>

                <span><i class="fa fa-calendar" aria-hidden="true"></i>
                    May, 15, 2020
                </span> <span><i class="fa fa-eye" aria-hidden="true"></i>
                    603 views
                </span>
            </div>
        </div>
    </section>

    <section class="newsletter">
        <div class="newsletter-head">
            <h1>Subscribe </h1>
            <h1>Newsletters</h1>

            <p>Enter your email address to register to our newsletter subscription delivered on a regular basis</p>
        </div>
        <div class="input-box">
            <input type="text" placeholder="Enter your email">
            <button>Subscribe</button>
        </div>

        <img class="shape rombo-dashed" src="/images/maxcoach-shape-09.png" alt="">

        <img class="shape circle" src="/images/maxcoach-shape-02.png" alt="">

        <i class="shape fa-regular fa-circle" aria-hidden="true"></i>
    </section>

</template>

<style lang="css">
    @import url(/src/assets/partials/css/_preFooterSection.css);
</style>