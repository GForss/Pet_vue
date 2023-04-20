<template>
    <header class="header">
        <my-text-animation />
        <my-burger />
    </header>
    <main class="main">
        <section class="about">
            <my-photo />
            <my-description />
        </section>
        <section>
            <my-heading>Опыт в проектах</my-heading>
            <my-prodjects />
        </section>
        <section>
            <my-heading>Опыт работы</my-heading>
            <my-experience />
        </section>
        <section>
            <my-heading>Цели</my-heading>
            <my-purposes />
        </section>
    </main>
    <footer>
        <my-heading>Контакты</my-heading>
        <div class="positions">
            <my-text>Свяжитесь со мной через любой канал связи, наше взаимодействие приведет к плодотворному сотрудничеству.</my-text>
            <my-contacts />
            <my-scroll-button />
        </div>
    </footer>
</template>

<script>
import MyTextAnimation from '@/UI/MyTextAnimation.vue';
import MyBurger from '@/UI/MyBurger.vue';
import MyDescription from './UI/MyDescription.vue';
import MyProdjects from '@/UI/MyProdjects.vue';
import MyHeading from '@/UI/MyHeading.vue';
import MyPhoto from '@/UI/MyPhoto.vue';
import MyExperience from '@/UI/MyExperience.vue';
import MyPurposes from '@/UI/MyPurposes.vue';
import MyGif from '@/UI/MyGif.vue';
import MyText from '@/UI/MyText.vue';
import MyContacts from '@/UI/MyContacts.vue';
import MyScrollButton from '@/UI/MyScrollButton.vue';

    export default {
        data() {
            return {
            show: false,
            }
        },
        components: {
            MyTextAnimation, MyBurger, MyDescription, MyProdjects, MyHeading, MyPhoto, MyExperience, MyPurposes, MyGif, MyText, MyContacts, MyScrollButton
        },
        methods: {
            // trackScroll() {
            //     if (window.pageYOffset > 50) {
            //         this.show = true;
            //         console.log('123');
            //     } else {
            //         this.show = false;
            //     }
            // } 
        }
    }
</script>

<style lang="scss" scoped>
@font-face {
  font-family: NasalizationRg-Regular; /* Гарнитура шрифта */
  src: url(../fonts/NasalizationRg-Regular.woff2); /* Путь к файлу со шрифтом */
}

* {
    margin: 0;
    padding: 0;
    font-family: NasalizationRg-Regular;
    padding-left: calc(50% - 1500px / 2);
    padding-right: calc(50% - 1500px / 2);
}

.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.main {
    margin-top: 50px;
}

.about {
    display: flex;
    align-items: center;
    gap: 100px;
}

.positions {
    display: flex; 
    align-items: center;
    justify-content: center;
    gap: 60px;
}
</style>