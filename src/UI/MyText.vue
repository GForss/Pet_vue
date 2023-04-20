<template>
    <div class="text">
        <slot></slot>
    </div>
</template>

<script>
    export default {
        name: 'my-text'
    }
</script>

<style lang="scss" scoped>
.text {
    width: 25%;
    color: white;
    font-size: 1em;
}

@media (min-width: 768px) and (max-width: 1024px) {
    .text {
        width: 50%;
    }
}
</style>