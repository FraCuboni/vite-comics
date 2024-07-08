<script>
import Card from '../components/Card.vue'
export default{
    name : 'Content',
    components : {
        Card,
    }
}
</script>

<template>
    <div class="container">
        <Card/>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/general.scss' as *;
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

.container{
    background-color: black;
    padding: $section_padding;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    
    h1{
        color: white;
    }
}
</style>