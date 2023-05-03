<template>
  <div id="app">
    <h1>Chuck Jokes Vue 🚀</h1>
    <ul>
      <li v-for="(fact, index) in chuck" :key="index">{{ fact.value }} </li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      chuck: [
        {
          value: 'Chuck Norris can skydive into outer space.',
        },
        {
          value: 'The chief export of Chuck Norris is pain.',
        },
        {
          value:
            "Chuck Norris doesn't read books. He stares them down until he gets the information he wants.",
        },
        {
          value: 'Time waits for no man. Unless that man is Chuck Norris.',
        },
        {
          value: 'If you spell Chuck Norris in Scrabble, you win. Forever.',
        },
      ],
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

* {
  list-style-type: none;
}
h1 {
  color: #76add0;
}

li {
  margin-bottom: 1rem;
  border: 1.5px solid #92c5fc;
  padding: 1rem;
  border-radius: 9px;
}
</style>
