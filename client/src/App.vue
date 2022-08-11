<script setup>
import HomeView from "./views/HomeView.vue";
import Header from "./components/Header.vue";
</script>

<template>
  <div class="main-background">
    <header>
      <Header />
    </header>

    <main>
      <router-view />
    </main>
  </div>
  <!-- <footer>
  </footer> -->
</template>
