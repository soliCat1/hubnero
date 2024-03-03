<template>
  <div id="app">
    <SidebarItem />
    <div class="wrapper">
      <HeaderItem />
      <TeamComponent />
    </div>
  </div>
</template>

<script>
import SidebarItem from './components/SidebarItem.vue';
import HeaderItem from './components/HeaderItem.vue';
import TeamComponent from '@/components/TeamComponent.vue'

export default {
  name: 'App',
  components: {
    SidebarItem,
    HeaderItem,
    TeamComponent
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

#app {
  font-family: "Commissioner", sans-serif;
  color: #2a355a;
  display: flex;
}

.wrapper {
  width: 100%;
}
</style>
