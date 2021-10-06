<template>
  <div id="app">
    <Header />
    <div class="flex">
      <div class="content">
        <side-bar></side-bar>
        <container></container>
        <right-nav></right-nav>
      </div>
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import SideBar from "./components/SideBar.vue";
import Container from "./components/Container.vue";
import RightNav from "./components/Aside.vue";
export default {
  name: "app",
  components: {
    Header,
    SideBar,
    Container,
    RightNav,
  },
};
</script>

<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
#app {
  font-size: 18px;
  text-transform: capitalize;
  font-family: "Open Sans";
  overflow-x: hidden;
  color: rgba(244, 244, 245, 0.6);
  background: radial-gradient(farthest-side ellipse at 10% 0, #333867, #17193b);
  background-attachment: fixed;
  background-size: cover;
  background-repeat: no-repeat;
  position: relative;
}
.content {
  width: calc(100% - 300px);
  padding: 0px 16px;
  display: flex;
  position: relative;
  right: 0;
}
span{
    font-weight: 300 !important;
}
ul {
    list-style-type: none;
}
p{
    margin: 0px 10px;
    font-size: 12px;
}
</style>
