<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class = "page">
  <header class = "header">
    <div class="nav-wrapper">
      <nav class = "nav-wrapper__list">
        <RouterLink to="/">Home</RouterLink> |
        <RouterLink to="/do">What we do</RouterLink>
      </nav>
    </div>
  </header>
</div>
  <RouterView />
  <footer class = "footer">What do we do?</footer>
</template>

<style scoped>

.page {
  display: flex;
  flex-direction: column; 
  line-height: 1.5;
  margin:0;
  padding: 0;
  overflow-wrap: break-word;
  box-sizing: border-box;
  -webkit-font-smoothing: antialiased;
  min-height:70vh;
}

</style>
