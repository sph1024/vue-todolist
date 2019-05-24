<template>
  <div id="app">
    <!-- <router-view/> -->
    <div id="cover"></div>
    <Header></Header>
    <Todo></Todo>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/header.vue';
import Todo from './components/todo.vue';
import Footer from './components/footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Todo,
    Footer
  }
}
</script>

<style lang="scss" scoped>
#app{
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;  
}
#cover{
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  background-color: #999;
  z-index: -1;
  opacity: .2;
}
</style>

