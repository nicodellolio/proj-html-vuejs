<script>
    export default{
        name: 'AppHeader'
    }
</script>

<template>
    <div class="debug">
        <div class="main-header">
            <div class="logo">
                <img src="/images/dark-logo.png" alt="">
            </div>
            
            <nav class="nav">
                <ul>
                    <li>Home 
                        <i class="fa-solid fa-chevron-down"></i>
                    </li>
                    <li>Pages 
                        <i class="fa-solid fa-chevron-down"></i>
                    </li>                    
                    <li>Courses 
                        <i class="fa-solid fa-chevron-down"></i>
                    </li> 
                    <li>Features 
                        <i class="fa-solid fa-chevron-down"></i>
                    </li> 
                    <li>Blog 
                        <i class="fa-solid fa-chevron-down"></i>
                    </li> 
                    <li>Shop 
                        <i class="fa-solid fa-chevron-down"></i>
                    </li> 
                    <li><i class="fa-regular fa-circle-user"></i></li>
                </ul>
            </nav>
            
            <div class="input-box">
                <input type="text" placeholder="Serch..">
                <i class="fa fa-search" aria-hidden="true"></i>
            </div>
        </div>
        
    </div>
</template>

<style scoped>

</style>
