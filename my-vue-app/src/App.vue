<template>
  <div>
    <HeaderComponent title="Текст!" />
    <HeaderComponent title="Текст!!" />
    <MessageComponent title="test1" message="Lorem Lorem" />
    <MessageComponent title="test2" message="Lorem2 Lorem2" />
  </div>
</template>

<script>
import MessageComponent from "./components/MessageComponent.vue ";
import HeaderComponent from "./components/Header.vue ";

export default {
  name: "App",
  components: {
    HeaderComponent,
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
</style>
