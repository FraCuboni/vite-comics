<script>
export default{
    name : 'Card',

    props : {
        details : Object
    }

}
</script>

<template>
    <div class="card">
        <div class="img-container">
            <img :src="details.thumb" alt="">
        </div>
        <p>{{details.series}}</p>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/general.scss' as *;
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

.card{
    width: calc(100% / 6 - 10px);
   margin-bottom: 15px;
    
    .img-container{
        width: 100%;
        aspect-ratio: 1/1;
        overflow: hidden;
    }

    p{
        color: white;
        padding:10px 0 ;
        word-wrap: break-word;
        font-size: 25px;
        font-weight: 300;
        text-transform: uppercase;
    }
}
</style>