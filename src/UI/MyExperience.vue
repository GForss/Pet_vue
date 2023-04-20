<template>
    <div class="discription">
        На данный момент продолжаю обучение в GeekBrains на факультете разработки на JavaScript, но хочу уже применять свои навыки не только на тестовых задачках по программированию, но и на реальных задачах в команде сильных специалистов, имея возможность расти и развиваться профессионально.
    </div>
    <div class="work">
            <ul class="work__list">
              <li class="work__element"><p class="work__element_description">Замещения должности начальника управления</p></li>
              <li class="work__element"><p class="work__element_description">Опыт работы с HTML5, CSS3 (опыт адаптивной верстки) на основе дизайн-макетов, JavaScript</p></li>
              <li class="work__element"><p class="work__element_description">Tailwind, Sass</p></li>
              <li class="work__element"><p class="work__element_description">Контроль версий (GitHub GitLab)</p></li>
              <li class="work__element"><p class="work__element_description">Базовые знания Photoshop, Figma</p></li>
              <li class="work__element"><p class="work__element_description">Работа над web-проектами (корпоративные сайты, лендинги, сайты с каталогом, посадочные страницы, шаблоны) улучшение функционала с соблюдением валидной верстки и кроссбраузерности, поиск и исправление ошибок, размещение новых блоков, написание собственных решений с использованием CMS: Bitrix, Joomla, Wordpress.</p></li>
              <li class="work__element"><p class="work__element_description">Ответственный подход к качеству кода и его документированию, работа с документами и отчетами в системах CRM, подготовка технического задания для закупки оборудования и разработке информационных систем по ГОСТ Р1.5-2002, ГОСТ 34.602-89, ГОСТ Р1.5-2002;</p></li>
              <li class="work__element"><p class="work__element_description">Работа с системами LMS (WebTutor, Moodle): запуск систем с нуля, производство электронных курсов с высокой степенью мультимедийной поддержки (видеомонтаж, работа в Adobe Premiere Pro, студийная запись видео, работа со студией JALINGA, звукообработка)</p></li>
              <li class="work__element"><p class="work__element_description">Обучение преподавателей и менеджеров: лекции в аудиториях, написание методических материалов для обучения;</p></li>
              <li class="work__element"><p class="work__element_description">Работа по организации и технической поддержке систем видеоконференцсвязи: TrueConf, Zoom, Mirapolis, Вебинар.ру и др.</p></li>
              <li class="work__element"><p class="work__element_description">Работа над web-проектами (корпоративные сайты, лендинги, сайты с каталогом, посадочные страницы, шаблоны) улучшение функционала с соблюдением валидной верстки и кроссбраузерности, поиск и исправление ошибок, размещение новых блоков, написание собственных решений с использованием CMS: Bitrix, Joomla, Wordpress.</p></li>
            </ul>
          </div>
</template>

<script>
    export default {
        name: 'my-experience'
    }
</script>

<style lang="scss" scoped>
.discription {
    color: white;
    padding: 25px;
    border-radius: 25px;
    box-shadow: rgba(0, 0, 0, 0.6) 0px 15px 25px;
}
.work {
    color: white;
    margin-top: 50px;
    padding: 25px;
    border-radius: 25px;
    box-shadow: rgba(0, 0, 0, 0.6) 0px 15px 25px;
}
.work__list {
    position: relative;
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.work__element {
    position: relative;
    list-style: none;
    margin-bottom: 10px 0;
    padding-left: 25px;
    height: 100%;

.work__element_description {
    z-index: 10;
    padding-left: 12px;
    color: white;
}
}

.work__element::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 34px;
    height: 100%;
    background: transparent;
    border: 2px solid #7e2bd9;
    border-radius: 34px;
    transition: .5s, width .5s;
    transition-delay: .5s, 0s;
    box-sizing: border-box;
}

.work__element:hover::before {
    width: 100%;
}
</style>