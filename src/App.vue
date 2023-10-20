<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/events">Events</RouterLink>
        <RouterLink to="/stay">Travel and Hotels</RouterLink>
        <RouterLink to="/photos">Photos</RouterLink>
        <RouterLink to="/registry">Registry</RouterLink>
      </nav>
    </div>
  </header>

  <main>
    <RouterView />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  /* margin-top: 2rem; */
  background-color: var(--vt-c-white);
}

nav a {
  color: var();
  text-decoration: none;
  color: var(--vt-c-black);
  min-width: 100px;
  font-size: 20px
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
  color: var(--vt-c-black) !important
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  /* border-left: 1px solid var(--color-border); */
}

nav a:first-of-type {
  /* border: 0; */
}

@media (min-width: 1024px) {
nav a {
  min-width: 200px
}
}
</style>
