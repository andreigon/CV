<script lang="ts">

</script>

<template>
    <div class="all_Skill">
    <div class="one_Skill">
        <div class="name_Skill">HTML</div>

        <div class="point">
        <span class="circle"></span> <span class="circle"></span> <span class="circle"></span>
        <span class="circle"></span>
        </div>
    </div>
    <div class="one_Skill">
        <div class="name_Skill">CSS</div>

        <div class="point">
        <span class="circle"></span> <span class="circle"></span> <span class="circle"></span>
        <span class="circle"></span>
        </div>
    </div>
    <div class="one_Skill">
        <div class="name_Skill">JavaScript</div>
        <div class="point">
        <span class="circle"></span> <span class="circle"></span> <span class="circle"></span>
        <span class="empty_Circle"></span>
        </div>
    </div>
    <div class="one_Skill">
        <div class="name_Skill">GIT</div>
        <div class="point">
        <span class="circle"></span> <span class="circle"></span> <span class="circle"></span>
        <span class="empty_Circle"></span>
        </div>
    </div>
    <div class="one_Skill">
        <div class="name_Skill">Vue.Js</div>
        <div class="point">
        <span class="circle"></span> <span class="circle"></span>
        <span class="circle empty empty_Circle"></span> <span class="empty_Circle"></span>
        </div>
    </div>
    <div class="one_Skill">
        <div class="name_Skill">Photoshop</div>
        <div class="point">
        <span class="circle"></span> <span class="circle"></span> <span class="circle"></span>
        <span class="empty_Circle"></span>
        </div>
    </div>
    </div>

</template>

<style scoped>
    .skills {
  position: relative;
  padding: 0 auto;
}

.one_Skill {
  display: flex;

  padding: 0 35%;
  margin-bottom: 10px;
  align-items: center;
  justify-content: center;
  height: 23px;
}
.circle {
  display: inline-block;
  box-sizing: border-box;
  background-color: rgb(253, 192, 7);
  width: 23px;
  height: 23px;
  border-radius: 11.5px;
}

.empty_Circle {
  display: inline-block;
  box-sizing: border-box;
  background-color: rgb(225, 225, 225);
  width: 23px;
  height: 23px;
  border-radius: 10px;
  margin-left: 1%;
}

.name_Skill {
  display: block;
  min-width: 110px;
  font-size: 20px;
  padding: 0;
  margin: 0;
  justify-content: center;
  align-items: center;

}
.point {
  display: flex;
  box-sizing: border-box;
  min-width: 110px;
  align-items: center;
  justify-content: center;
  height: 100%;
}
</style>