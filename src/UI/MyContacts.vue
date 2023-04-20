<template>
    <div class="container__contacts">
        <div class="container__contacts_connection">
            <img class="icon shake-top" src="../../img/iphone.png" alt="">
            <a href="tel:89855178903">8-985-517-89-03</a>
        </div>
        <div class="container__contacts_connection">
            <img class="icon" src="../../img/tg.png" alt="">
            <a target="_blank" href="https://t.me/GForss">@GForss</a>
        </div>
        <div class="container__contacts_connection">
            <img class="icon" src="../../img/tm.png" alt="">
            <a href="mailto:konst665@gmail.com?subject=Предложение по работе!">konst665@gmail.com</a>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'my-contacts'
    }
</script>

<style lang="scss" scoped>
.container__contacts {
    display: flex;
    // flex-direction: column;
    justify-content: center;
    flex-wrap: wrap;
    gap: 30px;
}

.container__contacts_connection {
        display: flex;
        align-items: center;
}

.icon {
    width: 60px;
    margin-right: 25px;
}

a {
    text-decoration: none;
    color: white;
}

@keyframes shake-top {
    0%,
    100% {
      -webkit-transform: rotate(0deg);
              transform: rotate(0deg);
      -webkit-transform-origin: 50% 0;
              transform-origin: 50% 0;
    }
    10% {
      -webkit-transform: rotate(2deg);
              transform: rotate(2deg);
    }
    20%,
    40%,
    60% {
      -webkit-transform: rotate(-4deg);
              transform: rotate(-4deg);
    }
    30%,
    50%,
    70% {
      -webkit-transform: rotate(4deg);
              transform: rotate(4deg);
    }
    80% {
      -webkit-transform: rotate(-2deg);
              transform: rotate(-2deg);
    }
    90% {
      -webkit-transform: rotate(2deg);
              transform: rotate(2deg);
    }
  }
  
  .shake-top {
      -webkit-animation: shake-top 2s cubic-bezier(0.455, 0.030, 0.515, 0.955) infinite both;
              animation: shake-top 2s cubic-bezier(0.455, 0.030, 0.515, 0.955) infinite both;
  } 
</style>