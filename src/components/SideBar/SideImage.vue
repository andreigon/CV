<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'SideImage',
  data() {
    return {
      photoUrl: '@/assets/321.jpg'
    }
  }
  // getRotate() {
  //   this.clicked = !this.clicked
  // }
})
</script>
<!-- @click="getRotate":class="{ clicked }" -->
<template>
  <div class="photoimage">
    <img
      class="photoimage-photo1"
      src="@/assets/321.jpg"
      alt="JPG ERORR"
      title="Frontend Developer"
    />
  </div>
</template>

<style scoped>
.photoimage {
  display: flex;
  position: relative;
  border: none;
  box-sizing: border-box;
  width: 100%;
  height:40%;
}

.clicked {
  transform: rotate(180deg);
}

.photoimage .photoimage-photo1 {
  width: 100%;
  height: 100%;
  object-fit: cover;
  position: absolute;
  top: 0;
  left: 0;
  display: block;
}
</style>
