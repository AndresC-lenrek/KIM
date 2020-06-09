<template>
  <q-page class="q-pa-lg ">
      |<h5 class="p-font q-mt-none q-mb-md" style="font-family: 'Cinzel Decorative', cursive; font-size: 42px; color: white; text-align: center;">Noticias Destacadas</h5>
  <div class="q-pa-md">
    <q-carousel
      arrows
      animated
      v-model="slide"
      height="450px"
      infinite
      autoplay
      transition-prev="slide-right"
      transition-next="slide-left"
    >
      <q-carousel-slide name="first" img-src="https://www.salvalaselva.org/photos/article/wide/xl/collage-zug-dav-maya-ruine-ek-balan-yucatan.jpg">
        <div class="absolute-bottom custom-caption">
          <div class=" myfont">Tren maya, ¿cómo afectará el medio ambiente y los derechos de las comunidades?</div>
          <div class="text-subtitle1"><a target="_blank" href="https://www.greenpeace.org/mexico/blog/4419/tren-maya-como-afectara-el-medio-ambiente-y-los-derechos-de-las-comunidades/"><q-btn class="glossy" color="teal" label="Saber más" /></a></div>
        </div>
      </q-carousel-slide>
      <q-carousel-slide name="second" img-src="https://imagenes.milenio.com/frpYVdTDy5sDiwJXf1VpEWYsxao=/958x596/https://www.milenio.com/uploads/media/2020/01/10/nuevamente-amanece-ciudad-monterrey-mala_87_0_508_316.JPG">
        <div class="absolute-bottom custom-caption">
          <div class=" myfont">Nuevamente amanece la ciudad de Monterrey con mala calidad del aire. </div>
          <div class="text-subtitle1"><a target="_blank"  href="https://www.milenio.com/politica/comunidad/mala-calidad-del-aire-continua-en-nuevo-leon" _blank><q-btn class="glossy" color="teal" label="Saber más" /></a></div>
        </div>
      </q-carousel-slide>
      <q-carousel-slide name="third" img-src="https://www.geoenciclopedia.com/wp-content/uploads/2019/08/Datos_sobre_el_Sahara.jpg">
        <div class="absolute-bottom custom-caption">
          <div class=" myfont">Países de África construyen muro de árboles para evitar expansión del Sahara </div>
          <div class="text-subtitle1"><a  target="_blank" href="https://elpais.com/elpais/2020/05/12/planeta_futuro/1589279924_166617.html" _blank ><q-btn class="glossy" color="teal" label="Saber más" /></a></div>
        </div>
      </q-carousel-slide>
    </q-carousel>
  </div>
  </q-page>
</template>



<script>
export default {
  data () {
    return {
      slide: 'first'
    }
  }
}
</script>

<style lang="scss">
.p-font {
  font-family: 'Rubik Mono One', sans-serif;
  color: rgb(10, 12, 10);
}

.myfont{
  color: white;
  font-family: 'Abril Fatface';
  // font-family: 'Montserrat', sans-serif;
  font-size: 2rem;
  // font-style: bold;v  

}
</style>
<style lang="sass" scoped>
.custom-caption
  text-align: center
  padding: 12px
  color: white
  background-color: rgba(0, 0, 0, .3)
</style>