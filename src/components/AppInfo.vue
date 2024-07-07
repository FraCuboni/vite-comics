<script>
export default{
    name : 'Info',
}
</script>

<template>
    <div class="container">
        <ul>
            <li>
                <div>
                    <img src="../assets/buy-comics-digital-comics.png" alt="">
                </div>
                <p>DIGITAL COMICS</p>
            </li>
            <li>
                <div>
                    <img src="../assets/buy-comics-merchandise.png" alt="">
                </div>
                <p>MERCHANDISE</p>
            </li>
            <li>
                <div>
                    <img src="../assets/buy-comics-subscriptions.png" alt="">
                </div>
                <p>SUBSCRIPTION</p>
            </li>
            <li>
                <div>
                    <img src="../assets/buy-comics-shop-locator.png" alt="">
                </div>
                <p>COMIC SHOP LOCATOR</p>
            </li>
            <li>
                <div>
                    <img src="../assets/buy-dc-power-visa.svg" alt="">
                </div>
                <p>DC POWER VISA</p>
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
            }

            p{
                color: white;
            }
        }
    }
}
</style>