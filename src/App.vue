<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/mv.png" width="1728" height="3456" />

    <div class="wrapper">
      <HelloWorld msg="あなたの完璧なスーツを作り上げるためのパートナー" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/repair">Repair</RouterLink>
        <RouterLink to="/access">Access</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  height: auto;
  display: block;
  margin: 3em auto 2rem;
  max-width: 200px;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 0.75rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: flex-start;
    margin-top: 5em;
    padding-right: calc(var(--section-gap) / 2);
    position: sticky;
    top: 0;
    width: 50%;
  }

  .logo {
    margin: 3em 2rem 0 0;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
