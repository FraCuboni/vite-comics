<script>
export default{
    name : 'FooterTop',
}
</script>

<template>
    <div class="container">
        <div class="box">
            <ul>
                <h3>title</h3>
                <li>abc</li>
                <li>abc</li>
                <li>abc</li>
                <li>abc</li>
                <li>abc</li>
                <li>abc</li>
            </ul>
            <ul>
                <h3>title</h3>
                <li>abc</li>
                <li>abc</li>
                <li>abc</li>
                <li>abc</li>
                <li>abc</li>
                <li>abc</li>
            </ul>
            <ul>
                <h3>title</h3>
                <li>abc</li>
                <li>abc</li>
                <li>abc</li>
                <li>abc</li>
                <li>abc</li>
                <li>abc</li>
            </ul>
            <ul>
                <h3>title</h3>
                <li>abc</li>
                <li>abc</li>
                <li>abc</li>
                <li>abc</li>
                <li>abc</li>
                <li>abc</li>
            </ul>
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
}
</style>