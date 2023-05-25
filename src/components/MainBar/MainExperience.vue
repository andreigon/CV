<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'MainSkills',
  data() {
    return {}
  }
})
</script>

<template>
  <div class="experience">
    <div class="all_Company">
      <div class="one_Company">
        <div class="company_Name">
          Конструкции из металла <span class="year">«Prof-Decor» 2019-2021</span>
        </div>
        <span class="position"
          >Старший участка металлообработки
          <span
            >Запуск и наладка производственной линии в сфере металлообработки. Создание и управление
            командой специалистов. Поддержание рабоче-дружеской атмосферы внутри коллектива. Поиск
            нестандартных решений, общение с поставщиками, а также клиентами компании</span
          >
        </span>
      </div>
      <div class="one_Company">
        <div class="company_Name">
          Обработка листовых материалов
          <span class="year">«RIOM» 2018-2019 </span>
        </div>
        <span class="position"
          >Программист-наладчик станков с ЧПУ
          <span
            >Пуско-наладочные работы на новых и уже имеющихся станках с ЧПУ, подготовка управляющих
            программ для работы на них при помощи CAD-программ.</span
          >
        </span>
      </div>
      <div class="one_Company">
        <div class="company_Name">
          Магазин рыболовной экипировки <span class="year">«Farlows» 2016-2018</span>
        </div>
        <span class="position"
          >Контент-менеджер
          <span
            >Работа с сайтом на CMS Bitrix, подготовка изображений в Adobe Photoshop. Наполнение
            сайта контентом, коммуникация с поставщиками.</span
          >
        </span>
      </div>
    </div>
  </div>
</template>

<style scoped>
.experience {
  display: inline-block;
  position: relative;
  /* max-height: 44%; */
}

.all_Company {
  display: block;
  position: relative;
  align-items: center;
  justify-content: center;
  margin: 0 1%;

  max-height: fit-content;
}

.one_Company {
  display: flex;
  align-items: center;
  margin-bottom: 2%;
}
.company_Name {
  min-width: 30%;
  width: 30%;
  height: auto;
}

.year {
  display: block;
}

.empty {
  margin-top: 2%;
  display: block;
  box-sizing: border-box;
}

span {
  display: block;
  margin: 0 auto;
}

.position {
  display: block;
  /* box-sizing: border-box; */
  margin-left: 1%;
  width: auto;
  height: auto;
}
</style>
