htmlCopy code
<!-- App.vue -->
<template>
  <div id="app">
    <game-board></game-board>
  </div>
</template>

<script>
import GameBoard from './components/Board.vue';

export default {
  components: {
    GameBoard
  }
};
</script>

