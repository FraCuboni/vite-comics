<script>
export default{
    name : 'FooterBottom',
}
</script>

<template>
    <div class="container">


        <div class="box">
            <button>SIGN-UP NOW!</button>
        </div>

        <div class="box">
            <ul>
                <li>
                    <p>follow us</p>
                </li>
                <li class="logo">
                    <img src="../assets/footer-facebook.png" alt="">
                </li>
                <li class="logo">
                    <img src="../assets/footer-pinterest.png" alt="">
                </li>
                <li class="logo">
                    <img src="../assets/footer-periscope.png" alt="">
                </li>
                <li class="logo">
                    <img src="../assets/footer-twitter.png" alt="">
                </li>
                <li class="logo">
                    <img src="../assets/footer-youtube.png" alt="">
                </li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/general.scss' as *;
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

.container{
    background-color: $dark_text;
    padding: $section_padding;
    color: white;

    display: flex;
    justify-content: space-between;

    .box{

        button{
            background-color: rgba($color: #000000, $alpha: 0);
            color: white;
            border: 1px solid $brand_primary;
            padding: 0.5rem;
        }

        ul{
            display: flex;
            align-items: center;
            gap: 10px;

            li{
                p{
                    color: $brand_primary ;
                }

            }
        }
    }
}
</style>