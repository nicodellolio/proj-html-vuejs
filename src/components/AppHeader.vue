<script>
export default {
    name: 'AppHeader',

    data() {
        return {
            dropdown: false,
            h_menu_items: [
                'Home',
                'Pages',
                'Courses',
                'Features',
                'Blog',
                'Shop',
            ],
            dropdown_items: [
                'Start Here',
                'Success Story',
                'About me',
                'About us 01',
                'About us 02',
                'About us 03',
                'Contact me',
                'Contact us',
                'Purchase Guide',
                'Privacy Policy',
                'Terms of Service'
            ]
        }
    },
    methods:{
        dropdown_show(h_item){
            if (h_item == 'Pages' && this.dropdown == false) {
                this.dropdown = true

            } else if(this.dropdown == true) {
                this.dropdown = false      
            }
        },

    }
}
</script>

<template>
    
    <div class="main-header">
        <div class="logo">
            <img src="/images/dark-logo.png" alt="">
        </div>

        <nav class="nav">
            <ul>
                <li v-for="h_item in h_menu_items">
                    <a @click="dropdown_show(h_item)" href="#">
                        {{ h_item }}
                        <i class="fa-solid fa-chevron-down"></i>
                    </a>
                </li>
                <li><i class="fa-regular fa-circle-user"></i></li>
            </ul>
        </nav>

        
        <div class="input-box">
            <input type="text" placeholder="Search..">
            <i class="fa fa-search" aria-hidden="true"></i>
        </div>
    </div>

    <ul v-show="dropdown" class="dropdown-list">
        <li v-for="dropdown_item in dropdown_items">
        {{ dropdown_item }}</li>
    </ul>
    
</template>

<style>
    @import url(/src/assets/partials/css/_header.css);
</style>
