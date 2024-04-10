<script>
export default {
    name: 'AppHeader',

    data() {
        return {
            h_menu_items: [
                'Home',
                'Pages',
                'Courses',
                'Features',
                'Blog',
                'Shop',
            ]
        }
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
                    <a href="">
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

</template>

<style scoped></style>
