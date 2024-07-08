<script>
export default{
    name : 'FooterTop',

    data(){
        return{
            links: [
            {
                name: 'DC COMICS',
                links: [
                    'Characters',
                    'Comics',
                    'Movies',
                    'TV',
                    'Games',
                    'Videos',
                    'News'
                ]
            },
            {
                name: 'SHOP',
                links: [
                    'Shop DC',
                    'Shop DC Collectibles'
                ]
            },
            {
                name: 'DC',
                links: [
                    'Terms Of Use',
                    'Privacy policy (New)',
                    'Ad Choices',
                    'Advertising',
                    'Jobs',
                    'Subscriptions',
                    'Talent Workshops',
                    'CPSC Certificates',
                    'Ratings',
                    'Shop Help',
                    'Contact Us'
                ]
            },
            {
                name: 'SITES',
                links: [
                    'DC',
                    'MAD Magazine',
                    'DC Kids',
                    'DC Universe',
                    'DC Power Visa'
                ]
            }
        ]
        }
    }
}
</script>

<template>
    <div class="container">

        <div class="box-1">
                <ul v-for="list in links">
                    <li><h3>{{ list.name }}</h3></li>
                    <li v-for="link in list.links"><p>{{ link }}</p></li>
                </ul>
            
        </div>

        <div class="box-2">
            <div>
                <img src="../assets/dc-logo-bg.png" alt="">
            </div>
        </div>

    </div>
</template>

<style lang="scss" scoped>
@use '../styles/general.scss' as *;
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

.container{
    padding: $section_padding;
    color: white;
    background-image: url(../assets/footer-bg.jpg);
    background-size: cover;

    display: flex;
    justify-content: space-between;
    overflow: hidden;

    .box-1{
        display: flex;
        flex-direction: column;
        gap: 40px;
        flex-wrap: wrap;
        max-height: 300px;

        ul li{

            h3{
                padding: 5px 0;
            }

            p{
                padding: 1px 0;
            }


        }
    }

    .box-2{
        flex-grow: 1;
        position: relative;
        justify-content: space-between;

        div{
            height: 180%;
                position: absolute;
                aspect-ratio: 1/1;
                transform: translate(-20%, -50%);
                right: 0;
                top: 50%;

        }
    }
}
</style>