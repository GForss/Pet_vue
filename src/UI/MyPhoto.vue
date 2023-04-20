<template>
    <div class="image">
        <img src="../../img/proger.png" alt="">
    </div>
</template>

<script>
    export default {
        name: 'my-photo'
    }
</script>

<style lang="scss" scoped>
.image {
    width: 400px;
    height: 400px;
    box-shadow: rgba(0, 0, 0, 0.6) 0px 15px 25px;
    position: relative;
    border: 1px solid rgb(126, 43, 217);
    border-image: initial;
    border-radius: 50%;
}
img {
    border-radius: 50%;
    width: 400px;
    height: 400px;
}
</style>