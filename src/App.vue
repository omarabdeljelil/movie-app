<template>
  <div id="nav">
    <router-link to="/">Home</router-link>
  </div>
  <router-view />
  <!-- <div>
    <input v-model="name" type="text" />
    <br />
    <p>
      {{ name }}
    </p>
    <hr>
    <button @click="incrementCounter" >increment </button>
    {{counter}}

  </div> -->
</template>

<script>
// export default {
//   data() {
//     return {
//       name: "omar",
//       counter: 0
//     };
//   },
//   methods: {
//     incrementCounter(){
//       this.counter++;
//     }
//   }
// };
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
