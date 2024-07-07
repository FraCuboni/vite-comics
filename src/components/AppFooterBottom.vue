<script>
export default{
    name : 'FooterBottom',
}
</script>

<template>
    <div class="container">
        <div class="box"><button>button</button></div>
        <div class="box">
            <ul>
                <li>
                    <p>follow us</p>
                </li>
                <li class="logo">LG</li>
                <li class="logo">LG</li>
                <li class="logo">LG</li>
                <li class="logo">LG</li>
                <li class="logo">LG</li>
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
}
</style>