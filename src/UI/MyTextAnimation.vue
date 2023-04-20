<template>
    <div class="text-animation">
       <div class="text">Frontend junior developer</div>
       <div class="slash"></div>
    </div>
</template>

<script>
    export default {
        name: 'my-text-animation'
    }
</script>

<style lang="scss" scoped>
.text-animation {
    display: flex;
    gap: 30px;
    font-size: 3em;
    font-family: "Rubik Mono One", sans-serif;
    text-shadow: 10px 10px 30px rgb(36, 0, 255), -10px -10px 30px rgb(126, 43, 217);
    -webkit-text-fill-color: transparent;
    letter-spacing: 5px;
    cursor: pointer;
    -webkit-text-stroke: 2px rgb(36, 0, 255);
}

.slash {
    width: 10px;
    -webkit-animation-name: colorCode;
    animation-name: colorCode;
    -webkit-animation-duration: 1s;
    animation-duration: 1s;
    -webkit-animation-iteration-count: infinite;
    animation-iteration-count: infinite;
}

@-webkit-keyframes colorCode {
    from {
        background: transparent;
    }

    50% {
        background: rgb(36, 0, 255);
    }

    to {
        background: transparent;
    }
}

@keyframes colorCode {
    from {
        background: transparent;
    }

    50% {
        background: rgb(36, 0, 255);
    }

    to {
        background: transparent;
    }
}
</style>