<script setup>
import NotesView from './components/NotesView.vue';
</script>

<template>
  <header>
    <img alt="Time logo" class="logo" src="./assets/2023.png" width="250" height="250" />
  </header>

  <main>
    <NotesView />
  </main>
</template>

<style scoped>
header {
  text-align: center;
  justify-content: center;
  align-items: center;
  place-items: center;
} 

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
    background-color: chartreuse;
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}

main{
  background-color: rgb(0, 234, 255);
}

</style>
