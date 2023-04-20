<template>
    <div @click="goTop" class="scroll__button">
        <img class="up" src="../../img/up.png" alt="">
    </div>
</template>

<script>
export default {
        data() {
            return {
            name: 'my-scroll-button',
            }
        },
        methods: {
            goTop() {
                if (window.pageYOffset > 0) {
                    window.scrollTo(0, 0);
                    // setTimeout(goTop, 0); 
                }
            }         
        }
    }
</script>

<style lang="scss" scoped>
.scroll__button {
    justify-content: center;
    color: #7e2bd9;
    font-size: 4em;
    // position: fixed;
    // top: 75%;
    // left: 87%;
    // padding: 0;
    cursor: pointer;
    // display: none;s
}

.up {
    width: 50px;
    height: 50px;
    cursor: pointer;
}
</style>