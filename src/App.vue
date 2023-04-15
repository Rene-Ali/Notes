<script setup>
import NotesView from './components/NotesView.vue';
</script>

<template>
  <header>
    <div width="500">
      <img alt="Time logo" class="logo" src="./assets/2023.png" width="250" height="250" />
    </div>
    <div class="icon">
      <!-- <v-btn class="ma-2"> 
        <v-icon start icon="mdicopyright"></v-icon><strong>René-Ali Günürün</strong>
      </v-btn>  -->
    </div>
  </header>

  <main>
    <NotesView />
  </main>
</template>


<style scoped>
header {
  display: flex;
  text-align: center;
  justify-content: center;
  align-items: center;
  place-items: center;
  min-width: 500px;
  background-color: rgb(255, 255, 204);
}

.logo {
  display: block;
  /* margin: 0 auto 2rem; */
}

main {
  background-color: rgb(4, 223, 243);
}

.icon {
  position: absolute;
  bottom: 25px;
  text-align: center;
}

.ma-2 {
  background-color:rgb(4, 223, 243);
  color: white;
  padding: 10px;
}
</style>
