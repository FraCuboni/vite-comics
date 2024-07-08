<script>
export default{
    name : 'Card',
}
</script>

<template>
    <div class="card">
        <h1>Card</h1>
    </div>
    <div class="card">
        <h1>Card</h1>
    </div>
    <div class="card">
        <h1>Card</h1>
    </div>
    <div class="card">
        <h1>Card</h1>
    </div>
    <div class="card">
        <h1>Card</h1>
    </div>
    <div class="card">
        <h1>Card</h1>
    </div>

    
    <div class="card">
        <h1>Card</h1>
    </div>
    <div class="card">
        <h1>Card</h1>
    </div>
    <div class="card">
        <h1>Card</h1>
    </div>
    <div class="card">
        <h1>Card</h1>
    </div>
    <div class="card">
        <h1>Card</h1>
    </div>
    <div class="card">
        <h1>Card</h1>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/general.scss' as *;
@use '../styles/partials/mixins' as *;
@use '../styles/partials/variables' as *;

.card{
    width: calc(100% / 6 - 10px);
   margin-bottom: 15px;
    background-color: red;
    
    h1{
        color: white;
    }
}
</style>