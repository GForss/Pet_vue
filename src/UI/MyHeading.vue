<template>
    <div class="heading">
        <slot></slot>
    </div>
</template>

<script>
    export default {
       name: 'my-heading' 
    }
</script>

<style lang="scss" scoped>
.heading {
    display: flex;
    justify-content: center;
    color: white;
    font-size: 3em;
    text-shadow: 10px 10px 30px rgb(36, 0, 255), -10px -10px 30px rgb(126, 43, 217);
    margin: 100px 0;
}
</style>