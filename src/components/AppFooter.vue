<script>
export default {
    name: 'AppFooter',

    data() {
        return {
            contact_info: [
                "382 Ne 191st St # 87394 Miami, FL 33179-3899",
                '+ 1 (305) 547-9909 (9am - 5pm EST, Monday - Friday)',
                'support@maxcoach.com'
            ],
            explore_items: [
                'Start here',
                'Blog',
                'About us',
                'Success story',
                'Courses',
                'Contact us'
            ],
            info_items: [
                'Membership',
                'Purchase guide',
                'Privacy Policy',
                'Terms of services'
            ]
        }
    }
}
</script>

<template>

    <div class="main-footer">
        <section class="footer-box">
            <div class="address">
                <h3>Address</h3>
                <ul>
                    <li v-for="contactItem in contact_info">
                        {{ contactItem }}
                    </li>
                </ul>
                
                <img src="/public/images/socials.png" alt="">
            </div>
            
            <div class="explore">
                <h3>Explore</h3>
                <ul>
                    <li v-for="explore_item in explore_items">
                        <a href="">{{ explore_item }}
                        </a>
                    </li>
                </ul>
            </div>

            <div class="information">
                <h3>Information</h3>
                <ul>
                    <li v-for="info_item in info_items">
                        <a href="">{{ info_item }}</a>
                    </li>
                </ul>
            </div>
        </section>
        <div class="credits">
            @ 2020 Maxcoach. All Rights Reserved
        </div>

        <div class="go-up">
            <a href="">
                <i class="fa fa-arrow-up" aria-hidden="true"></i>
            </a>
        </div>
    </div>


</template>

<style scoped></style>
