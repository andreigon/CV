<script lang="ts">
import SideContact from './components/SideBar/SideContact.vue'
import SideImage from './components/SideBar/SideImage.vue'
import SideEducation from './components/SideBar/SideEducation.vue'
import MainHeader from './components/MainBar/MainHeader.vue'
import MainProfile from './components/MainBar/MainProfile.vue'
import MainExperience from './components/MainBar/MainExperience.vue'
import MainSkills from './components/MainBar/MainSkills.vue'
import { defineComponent } from 'vue'
import 'normalize.css/normalize.css'


export default defineComponent({
  name: 'MyResume',
  components: {
    SideImage,
    SideContact,
    SideEducation,
    MainHeader,
    MainProfile,
    MainExperience,
    MainSkills
  }
})
</script>

<template>
  <div id="container">
    <!-- SIDE BAR -->
    <div class="side_Bar">
      <SideImage />
      <h1 class="h_Side">Контакты</h1>
      <SideContact />
      <h1 class="h_Side">Образование</h1>
      <SideEducation />
    </div>

    <!-- MAIN BAR -->
    <div class="main">
      <MainHeader />
      <div id="info"></div>
      <h1 class="h_Main">О Себе</h1>
      <MainProfile />
      <h1 class="h_Main">Стаж</h1>
      <MainExperience />
      <h1 class="h_Main">Skills</h1>
      <MainSkills />
    </div>
  </div>
</template>

<style scoped>
.clicked {
  transform: rotate(180deg);
}

#container {
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva,
    Verdana, sans-serif;
  text-shadow: none;
  font-style: normal;
  overflow: scroll;
  /* width: auto;
  height: auto; */
  display: flex;
  padding: 0;
  margin: 0;
}

/* SIDE BAR*/
.side_Bar {
  /* display: block; */

  /* border: none;
  box-sizing: border-box; */
  position: absolute;
  background-color: rgb(44, 50, 62);
  width: 25%;
  height: 100%;
  padding-bottom: 25%;
  color: rgb(211, 211, 211);
  /* min-width: fit-content; */
}

.h_Side {
  height: auto;
  width: 100%;
  display: flex;
  position: relative;
  align-items: center;
  justify-content: flex-start;
  background-color: rgb(66, 70, 82);
  color: rgb(219, 219, 219);
}

.h_Side::before {
  content: '';
  width: 14px;
  height: 40px;
  background-color: rgb(253, 192, 7);
  position: relative;
  margin-right: 5px;
}

/* MAIN BAR*/
.main {
  position: absolute;
  box-sizing: border-box;
  border: none;
  margin-left: 20%;
  padding: 0;
  background-color: rgb(255, 255, 255);
  /* min-width:70%; */
  height: 100%;
}

.h_Main {
  height: auto;
  width: 100%;
  display: flex;
  position: relative;
  align-items: center;
  justify-content: flex-start;
  background-color: rgb(235, 235, 235);
}

.h_Main::before {
  content: '';
  width: 14px;
  height: 40px;
  background-color: rgb(253, 192, 7);
  position: relative;
  margin-right: 5px;
}

span {
  display: block;
  margin: 0 auto;
}
</style>
