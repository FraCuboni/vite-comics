<script>
export default{
    name : 'FooterTop',
}
</script>

<template>
    <div class="container">

        <div class="box-1">
            <div class="column">

                <ul>
                    <li><h3>SITES</h3></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                </ul>
                <ul>
                    <li><h3>SITES</h3></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                </ul>

            </div>
            
            <div class="column">

                <ul>
                    <li><h3>SITES</h3></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                </ul>
                
            </div>
            
            <div class="column">

                <ul>
                    <li><h3>SITES</h3></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                    <li><p>abc</p></li>
                </ul>
            
            </div>
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
        min-height: 100px;
        gap: 40px;
        flex: 0 1 auto;

        .column ul li{

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

        div{
                position: absolute;
                aspect-ratio: 1/1;
                transform: translate(-50%, -50%);
                left: 50%;
                top: 50%;

        }
    }
}
</style>