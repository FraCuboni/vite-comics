<script>
export default{
    name : 'Header',

    data(){
        return{
            logo : '',
            links :[
                {
                    text:'CHARACTERS',
                    url:'#',
                },
                {
                    text:'COMICS',
                    url:'#',
                },
                {
                    text:'MOVIES',
                    url:'#',
                },
                {
                    text:'TV',
                    url:'#',
                },
                {
                    text:'MOVIES',
                    url:'#',
                },
                {
                    text:'COLLECTIBLES',
                    url:'#',
                },
                {
                    text:'VIDEOS',
                    url:'#',
                },
                {
                    text:'FANS',
                    url:'#',
                },
                {
                    text:'NEWS',
                    url:'#',
                },
                {
                    text:'SHOP',
                    url:'#',
                },
            ]
        }
    }
}
</script>

<!-- html -->
<template>
    <div class="container">

        <div class="logo">
            <img src="../assets/dc-logo.png" alt="">
        </div>
        
        <ul>
            <li v-for="(link, index) in links" :key="index">{{ link.text }}</li>
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
            background-color: red;
        }
    }
}

</style>