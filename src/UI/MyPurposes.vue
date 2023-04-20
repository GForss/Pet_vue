<template>
    <div class="circle">
        <div class="circle__goals">Углубленное изучение верстки, препроцессоры, продвинутая работа с анимацией</div>
        <div class="circle__goals">JavaScript про ECMAScript, фреймворки</div>
        <div class="circle__goals">Изучение профессиональной литературы, не ограничиваться курсами</div>
        <div class="circle__goals">Устроиться на работу Frontend разработчиком</div>
        <div class="circle__goals">Прокачивать свои навыки, дорасти до Senior Frontend разрабботчика и расти дальше</div>
    </div>
</template>

<script>
    export default {
        name: 'my-purposes'
    }
</script>

<style lang="scss" scoped>
.circle {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
    color: white;
}

.circle__goals {
    width: 300px;
    height: 300px;
    border: 1px solid rgb(126, 43, 217);
    box-shadow: rgba(0, 0, 0, 0.6) 0px 15px 25px;
    border-radius: 50%;
    transition: 1s;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 10px;
}

.circle__goals:hover {
    box-shadow: 10px 10px 10px rgb(126, 43, 217);;
    text-shadow: rgba(0, 0, 0, 0.6) 0px 15px 25px;
}

</style>