<template>
  <q-layout view="hHh lpR fFf" class="body1" breakpoint="600">

    <q-header elevated class="myBg text-white" height-hint="98">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar>
            <img src="statics/icons/favicon-32x32.png">
          </q-avatar>
          Keep In Mind
        </q-toolbar-title>
      </q-toolbar>

      <q-tabs align="left">
        <q-route-tab to="/" exact clickable v-ripple label="Inicio" />
        <q-route-tab to="/noticias" label="Noticias" />
        <q-route-tab to="/foro" label="Foro" />
        <q-route-tab to="/guias" label="Guias" />
      </q-tabs>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

  </q-layout>
</template>

<script>
export default {
  data () {
    return {
    }
  }
}
</script>

<style lang="scss">
    .myBg {
        background: #00bf8f;  /* fallback for old browsers */
        background: -webkit-linear-gradient(to right, #001510, #00bf8f);  /* Chrome 10-25, Safari 5.1-6 */
        background: linear-gradient(to right, #001510, #00bf8f); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

    // background: rgb(29,36,30);
    // background: linear-gradient(90deg, rgba(29,36,30,1) 11%, rgba(55,167,66,0.6082808123249299) 50%, rgba(25,23,20,0.3449754901960784) 100%);

    }
    .body1{background-image: url("https://i1.pickpik.com/photos/829/884/835/wood-background-texture-distressed-preview.jpg");}
</style>