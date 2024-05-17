<template>
  <div id="app">
    <header-component></header-component>
    <div class="main-content">
      <sidebar-component></sidebar-component>
      <main class="main-view">
        <parent-component></parent-component>
      </main>
    </div>
    <footer-component></footer-component>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import SidebarComponent from './components/SidebarComponent.vue';
import ParentComponent from './components/ParentComponent.vue';

export default {
  components: {
    HeaderComponent,
    FooterComponent,
    SidebarComponent,
    ParentComponent
  }
}
</script>

<style>
body {
  font-family: Arial, sans-serif;
  background-color: #f8f9fa;
  color: #333;
  margin: 0;
  padding: 0;
}

#app {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.main-content {
  display: flex;
  flex: 1;
}

.main-view {
  flex: 1;
  padding: 20px;
}

h1, h2, h3 {
  margin-bottom: 10px;
}

p {
  margin: 5px 0;
}
</style>
