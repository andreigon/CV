<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'MainProfile',
  data() {
    return {}
  }
})
</script>

<template>
  <span class="profile">
    Рассматривая смену профессии. Я окончил онлайн курсы по основам frontend-разработки. В данный
    момент ищу возможность совершенствовать и применять уже имеющиеся знания. В работе с кодом я
    увлечен и внимателен, так как хочу и дальше развиваться во frontend-разработке. Своё свободное
    время предпочитаю уделять пленочной фотографии и велопрогулкам.
  </span>
</template>

<style scoped>
.profile {
  position: relative;
  margin: 0 2%;
}
</style>
