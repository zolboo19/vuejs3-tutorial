<template>
  <div>
    <h2>Форумд тавтай морилно уу!</h2>
  </div>
  <div v-for="thread in threads" :key="thread.id"> {{thread.title}}</div>

</template>
<script>
import forumData from '@/forumData.json'
export default {
  name: 'PageHome',
  data() {
    return {
      threads: forumData.threads
    }
  }

}
</script>
<style>

</style>
