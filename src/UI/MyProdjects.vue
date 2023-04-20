<template>
    <div class="experience__projects">
        <div class="experience__projects_descriptions">Проект "Подготовка рабочих кадров с использованием методики WorldSkills" с Корпоративной академией Росатома
        Информационное и техническое сопровождение курсов для отраслевых экспертов. Первая и вторая линия технической поддержки слушателей.</div>
        <div class="experience__projects_descriptions">Проект "Системы электронного повышения квалификации педагогических работников и руководителей образовательных организаций Московской области"
        Разработка мультимедийного и интерактивного контента.
        Размещен на ЦОДах Правительства Московской области</div>
        <div class="experience__projects_descriptions">Руководитель группы разработчиков "Современная цифровая образовательная среда".
        Разработка 5 онлайн-курсов для федеральной платформы "Мое образование".</div>
        <div class="experience__projects_descriptions">Руководитель группы технического сопровождения Стажировки управленческих команд в московской области «Эффективные механизмы управления качеством образования на региональном и муниципальных уровнях» совместно с ФГАОУ ДПО «Академия Минпросвещения России»</div>
    </div>
</template>

<script>
    export default {
        name: 'my-prodjects'
    }
</script>

<style lang="scss" scoped>
.experience__projects {
display: flex;
flex-wrap: wrap;
justify-content: center;
gap: 50px;
}

.experience__projects_descriptions {
    position: relative;
    width: 25%;
    background: linear-gradient(to left, rgb(126, 43, 217), rgb(36, 0, 255), rgb(126, 43, 217));
    box-shadow: rgba(0, 0, 0, 0.6) 0px 15px 25px;
    border-radius: 15px;
    padding: 50px;
    background-size: 200%;
    transition: .5s;
    font-size: 1.1em;
}

.experience__projects_descriptions:after {
    content: "";
    position: absolute;
    border: 2px solid rgb(252, 120, 255);
    border-radius: 15px;
    left: -8%;
    top: -8%;
    width: 100%;
    height: 100%;
}

.experience__projects_descriptions:hover {
    background-position: right;
}

</style>