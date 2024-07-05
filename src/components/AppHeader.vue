<script>
export default{
    name : 'Header',
}
</script>

<!-- html -->
<template>
    <div class="container">

        <div class="logo">DC</div>
        
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
    width: 100%;
    display: flex;
    justify-content: space-between;
    background-color: red;
    color: $brand_primary;

    ul{
        display: flex;
    }
}

</style>