<template>
  <div id="app">
    <div id="nav">
      <nav class="navbar nav-e" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
          <a class="navbar-item " href="/">
            <i class='title'>
              R<small>esort </small>-W<small>ebsite</small>
            </i>
           </a>
        </div>
        <div class="navbar-menu">
          <div class="navbar-end">
            <div class="field is-grouped">
              <P class="control">
                <router-link :to="'home'" class="navbar-item">
                  <a class="text-c">Home</a>
                </router-link>
              </P>
            </div>
            <div class="field is-grouped">
              <P class="control">
                <router-link :to="'events'" class="navbar-item">
                  <a class="text-c">Events</a>
                </router-link>
              </P>
            </div>
            <div class="field is-grouped">
              <P class="control">
                <router-link :to="'Gallery'" class="navbar-item">
                  <a class="text-c">Gallery</a>
                </router-link>
              </P>
            </div>
            <div class="field is-grouped">
              <P class="control">
                <router-link :to="'about'" class="navbar-item">
                  <a class="text-c">Get in Touch!</a>
                </router-link>
              </P>
            </div>
          </div>
        </div>
      </nav>
      <br>
      <router-view/>
      </div>
      <div class="container">
            <div class="footer has-text-light">
                <p>© 2020 Resort Name , All rights reserved.</p>
            </div>
        </div>
  </div>
</template>

<script>
import 'bulma';

export default {
  components: {
  },
};
</script>
<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  -moz-background-color: rgba(70, 64, 64, 0.904);
    -ms-background-color: rgba(70, 64, 64, 0.904);
    -o-background-color: rgba(70, 64, 64, 0.904);
    -webkit-background-color: rgba(70, 64, 64, 0.904);
    background-color: rgba(70, 64, 64, 0.904);
}

#nav {
   padding:  9px 15px;
    -moz-background-color: rgba(70, 64, 64, 0.904);
    -ms-background-color: rgba(70, 64, 64, 0.904);
    -o-background-color: rgba(70, 64, 64, 0.904);
    -webkit-background-color: rgba(70, 64, 64, 0.904);
    background-color: rgba(70, 64, 64, 0.904);
}
.title{
  color: #67A13D;
}
.text-c{
  color: #67A13D;
}
.nav-e{
  background-color: rgba(70, 64, 64, 0.904);
}
</style>
