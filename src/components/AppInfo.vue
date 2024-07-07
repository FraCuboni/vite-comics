<script>
export default{
    name : 'Info',
}
</script>

<template>
    <div class="container">
        <ul>
            <li>INFO</li>
            <li>INFO</li>
            <li>INFO</li>
            <li>INFO</li>
            <li>INFO</li>
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
    }
}
</style>