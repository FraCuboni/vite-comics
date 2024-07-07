<script>
export default{
    name : 'Content',
}
</script>

<template>
    <div class="container">
        <h1>->Content goes Here<-</h1>

    </div>
</template>

<style lang="scss" scoped>
@use '../styles/general.scss' as *;
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

.container{
    background-color: black;
    padding: $section_padding;
    
    h1{
        color: white;
    }
}
</style>