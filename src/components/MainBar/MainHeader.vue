<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'MainHeader',
  data() {
    return {}
  }
})
</script>

<template>
  <div class="header">
    <h2><span> Гончар Андрей</span></h2>

    <h3><span> FrontEnd Разработчик</span></h3>
  </div>
</template>

<style scoped>
.description {
  display: flex;
  box-sizing: border-box;
  border: none;
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

.header {
  /* position: ; */
  margin: 0 35%;
  align-items: center;
  justify-content: center;
  padding: 0 auto;
  width: auto;
  display: block;
  font-size: 120%;
  /* margin-left: 50%;
    margin-right: 50%; */
}
.profile {
  position: relative;
  margin: 0 2%;
}
</style>
