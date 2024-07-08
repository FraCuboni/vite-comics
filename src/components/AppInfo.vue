<script>
export default{
    name : 'Info',

    data(){
        return{
            datas : [
                {
                    img : '../../src/assets/buy-comics-digital-comics.png',
                    text : 'DIGITAL COMICS',
                },
                {
                    img : '../../src/assets/buy-comics-merchandise.png',
                    text : 'MERCHANDISE',
                },
                {
                    img : '../../src/assets/buy-comics-subscriptions.png',
                    text : 'SUBSCRIPTION',
                },
                {
                    img : '../../src/assets/buy-comics-shop-locator.png',
                    text : 'COMIC SHOP LOCATOR',
                },
                {
                    img : '../../src/assets/buy-dc-power-visa.svg',
                    text : 'DC POWER VISA',
                },
            ]
        }
    }
}
</script>

<template>
    <div class="container">
        <ul>
            <li v-for="(element,index) in datas" :key="index">
                <div>
                    <img :src="element.img" alt="">
                </div>
                <p>{{ element.text }}</p>
            </li>
        </ul>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/general.scss' as *;
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

.container{
    background-color: $brand_primary;
    padding: $section_padding;

    ul{
        display: flex;
        justify-content: space-between;

        li{
            display: flex;
            align-items: center;

            div{
                width: 60px;
                aspect-ratio: 1/1;
                padding-right: 5px;

                display: flex;
                justify-content: center;
                align-items: center;

                img{
                    max-height: 100%;
                }
            }

            p{
                color: white;
            }
        }
    }
}
</style>