<template>
  <header>
    <div class="container">
      <a href="https://ozbio.com/" title="Орловский Завод Бурового Инструмента и Оборудования – Орёл, Россия"
         rel="home">
        <img src="../assets/img/logo_ru_white.png" style="height:93px; width:334px;" alt="OZBIO">
      </a>
    </div>
    <div class="navigation_menu affix-top" data-spy="affix" data-offset-top="95" id="enigma_nav_top">
      <span id="header_shadow"></span>
      <div class="container navbar-container">
        <nav class="navbar navbar-default " role="navigation">
          <div id="menu" class="collapse navbar-collapse ">
              <ul id="menu-osnovnoe" class="nav navbar-nav">
                <li><a href="#">Главная</a></li>
                <li><a href="#/products/">Схема производства</a></li>
                <li><a href="#/services/">Загруженность станков</a></li>
                <li><a href="#/about/">Задания</a></li>
                <li><a href="#/dealers/">База данных</a></li>
              </ul>
            </div>
        </nav>
      </div>
    </div>
  </header>
  <!--    <header>-->
  <!--        <a href="#" @click.prevent="changePage('Index')">-->
  <!--            <img src="../assets/img/logo.png" alt="Codeforces" title="Codeforces"/>-->
  <!--        </a>-->
  <!--        <div class="languages">-->
  <!--            <a href="#"><img src="../assets/img/gb.png" alt="In English" title="In English"/></a>-->
  <!--            <a href="#"><img src="../assets/img/ru.png" alt="In Russian" title="In Russian"/></a>-->
  <!--        </div>-->
  <!--        <div class="enter-or-register-box">-->
  <!--            <template v-if="user">-->
  <!--                {{ user.name }}-->
  <!--                |-->
  <!--                <a href="#" @click.prevent="onLogout">Logout</a>-->
  <!--            </template>-->
  <!--            <template v-else>-->
  <!--                <a href="#" @click.prevent="changePage('Enter')">Enter</a>-->
  <!--                |-->
  <!--                <a href="#" @click.prevent="changePage('Register')">Register</a>-->
  <!--            </template>-->
  <!--        </div>-->
  <!--        <nav>-->
  <!--            <ul>-->
  <!--                <li><a href="#" @click.prevent="changePage('Index')">Home</a></li>-->
  <!--                <li><a href="#" @click.prevent="changePage('Users')">Users</a></li>-->
  <!--            </ul>-->
  <!--        </nav>-->
  <!--    </header>-->
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>

</style>
