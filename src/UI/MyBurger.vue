<template>
    <div @click="show = !show" class="burger">
        <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" fill="currentColor" class="bi bi-menu-button-wide-fill" viewBox="0 0 16 16">
            <path d="M1.5 0A1.5 1.5 0 0 0 0 1.5v2A1.5 1.5 0 0 0 1.5 5h13A1.5 1.5 0 0 0 16 3.5v-2A1.5 1.5 0 0 0 14.5 0h-13zm1 2h3a.5.5 0 0 1 0 1h-3a.5.5 0 0 1 0-1zm9.927.427A.25.25 0 0 1 12.604 2h.792a.25.25 0 0 1 .177.427l-.396.396a.25.25 0 0 1-.354 0l-.396-.396zM0 8a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V8zm1 3v2a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-2H1zm14-1V8a1 1 0 0 0-1-1H2a1 1 0 0 0-1 1v2h14zM2 8.5a.5.5 0 0 1 .5-.5h9a.5.5 0 0 1 0 1h-9a.5.5 0 0 1-.5-.5zm0 4a.5.5 0 0 1 .5-.5h6a.5.5 0 0 1 0 1h-6a.5.5 0 0 1-.5-.5z"/>
        </svg>
    </div>
    <div v-if="show" class="burger-menu">
        <ul>
            <li><a target="_blank" href="https://gforss.github.io/counters/">Калькулятор коммунальных показаний</a></li>
            <li><a target="_blank" href="https://gforss.github.io/GrinAtom/">Росатом металлургия</a></li>
            <li><a href="#">3</a></li>
            <li><a href="#">4</a></li>
        </ul>
    </div>
</template>

<script>
    export default {
        data() {
            return {
            name: 'my-burger',
            show: false
            }
        }
    }
</script>

<style lang="scss" scoped>
.burger {
    cursor: pointer;
    color: rgb(36, 0, 255);
}
.burger-menu {
    padding: 15px;
    border-radius: 25px;
    position: absolute;
    background: #00172a;
    top: 65px;
    right: calc(50% - 1500px / 2);
    width: 300px;
    font-size: 1.5em;
    box-shadow: rgba(0, 0, 0, 0.6) 0px 15px 25px;
}

ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

li {
    margin-top: 10px;
}

a {
    text-decoration: none;
    color: teal;
}
</style>