<script>
export default{
    name : 'Header',
}
</script>

<!-- html -->
<template>
    <div class="container">

        <div class="logo">
            <img src="../assets/dc-logo.png" alt="">
        </div>
        
        <ul>
            <li>CHARACTERS</li>
            <li>COMICS</li>
            <li>MOVIES</li>
            <li>TV</li>
            <li>GAMES</li>
            <li>COLLECTIBLES</li>
            <li>VIDEOS</li>
            <li>FANS</li>
            <li>NEWS</li>
            <li>SHOP</li>
        </ul>

    </div>
    
</template>

<style lang="scss" scoped>
@use '../styles/general.scss' as *;
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

.container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    
    color: $brand_primary;
    padding: $section_padding;

    ul{
        display: flex;
        gap: 20px;

        li a{
            color: $brand_primary ;
        }
    }
}

</style>