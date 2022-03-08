<template>
  <div class="home">
    <HomeTitle/>

    <MainForm/>
  </div>
</template>

<script>
import HomeTitle from './HomeTitle.vue'
import MainForm from './HomeForm'

export default {
  name: 'HomeView',
  components: { HomeTitle, MainForm }
}
</script>
