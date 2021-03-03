<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-1 side-bar fixed">
        <div class="logo mt-5">Logo Here</div>
        <Nav/>
      </div>
      <div class="col-md-11 main">
          <top-nav/>
          <div class="row">
              <div class="col-md-8 content">
                  dskdjskdjskdjskd
              </div>
              <div class="col-md-4 right-sidebar">
                  jskdjsk
              </div>
          </div>
           
      </div>
    </div>
  </div>
</template>

<script>
import Nav from "./Nav/nav.vue";
import TopNav from './Nav/topNav.vue';
export default {
  components: {
    Nav,
    TopNav,
  },
};
</script>

<style  scoped>
.side-bar {
  background: #fff;
  width: 100%;
  height: 100vh;
  border-top-right-radius: 50px;
  border-bottom-right-radius: 50px;
}

.content{
    height: 87vh;
}

.right-sidebar{
    background: yellow;
    height: 87vh;
}
</style>