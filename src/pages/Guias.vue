<template>
    <div class="row">
        <div class="col-xs-12 col-sm-6 col-md-4 q-pa-lg" >
            <div class="bar q-mb-md q-mt-md q-ml-none q-pl-none">
                <p style="font-family: 'Cinzel Decorative', cursive; font-size: 22px
            ">Tips del Dia</p>
            </div>
            <div class="q-pa-md row items-start q-gutter-md">
                    <q-card class="my-card cardBG">
                        <q-card-section>
                            <p><strong>Evita dejar los aparatos enchufados:</strong>Recuerda que los aparatos que esten enchufados consumen energia,por loque es importante desenchufarlos. </p>
                        </q-card-section>
                    </q-card>
            </div>

            <div class="q-pa-md row items-start q-gutter-md" >
                    <q-card class="my-card cardBG">
                        <q-card-section>
                            <p><strong>Aprovecha la luz natural:</strong>Para reducir el consumo de luz electrica,abre las ventanas y sube las persianas para que entre la luz del sol entre tu casa.</p>
                        </q-card-section>
                    </q-card>
            </div>

            <div class="q-pa-md row items-start q-gutter-md">
                    <q-card class="my-card cardBG">
                        <q-card-section>
                            <p><strong>Planta arboles:</strong>Los arboles producen oxigeno y son esenciales para la naturaleza, asi que planta un arbolen tu casa o en la comunidad donde vives.</p>
                        </q-card-section>
                    </q-card>
            </div>
        </div>
        <div class="col-xs-12 col-sm-6 col-md-4 q-pa-lg " >
            <div class="bar q-mb-md q-mt-md q-ml-none q-pl-none">
                <p style="font-family: 'Cinzel Decorative', cursive; font-size: 22px
            ">Apps Recomendadas</p>
            </div>
            <!-- Nueva card -->
            <q-card  class="my-card">    
                <!-- <a href="https://www.gob.mx/semarnat/archivo/articulos"> -->
                <q-img src="https://images.squarespace-cdn.com/content/52658d2ae4b0aea8493046f5/1382403029077-T9QJIZXROMN4GY52XGGK/climate_logo.png?format=1000w&content-type=image%2Fpng" basic>
                <div class="absolute-bottom text-subtitle2 text-center">
                    Climate<br>Esta app te ayuda a descubrir y compartir acciones para cuidar el medio ambiente
                </div>
            </q-img>
            <!-- </a> -->
            </q-card>
            <q-card  class="my-card q-mt-lg">   
            <!-- <a href="https://www.gob.mx/semarnat/archivo/articulos"> -->
                <q-img src="https://pbs.twimg.com/profile_images/496381366557089793/ZaoVGcMN.png" basic>
                <div class="absolute-bottom text-subtitle2 text-center">
                    GoodGuide<br>Te ayuda a encontrar y ver reviews de productos seguros y eco-friendly
                </div>
            </q-img>
            <!-- </a> -->
            </q-card>


            <!-- <q-card  class="my-card">    <a href="https://www.gob.mx/semarnat/archivo/articulos">
                <q-img src="https://images.squarespace-cdn.com/content/52658d2ae4b0aea8493046f5/1382403029077-T9QJIZXROMN4GY52XGGK/climate_logo.png?format=1000w&content-type=image%2Fpng" basic>
                <div class="absolute-bottom text-subtitle2 text-center">
                    Climate<br>Esta app te ayuda a descubrir y compartir acciones para cuidar el medio ambiente
                </div>
            </q-img></a>
            </q-card>
            </div> -->
        </div>
        <div class="col-xs-12 col-sm-6 col-md-4 q-pa-lg " >
            <div class="bar q-mb-md q-mt-md q-ml-none q-pl-none">
                <p style="font-family: 'Cinzel Decorative', cursive; font-size: 22px
            ">Guias Recomendadas</p>
            </div>


            <q-card  class="my-card q-mt-lg">   
            <!-- <a href="https://www.gob.mx/semarnat/archivo/articulos"> -->
                <q-img src="https://cdn2.iconfinder.com/data/icons/artificial-intelligence-ai-color/64/articulated-robot-arm-automation-Cartesian-mechanical-assembly-512.png" basic>
                <div class="absolute-bottom text-subtitle2 text-center">
                    Usa este organizador para calcular que tanto contaminas y como mejorar
                </div>
            </q-img>
            <!-- </a> -->
            </q-card>
            <q-card  class="my-card q-mt-md ">    
                <!-- <a href="https://www.gob.mx/semarnat/archivo/articulos"> -->
                <q-img src="https://elandroidelibre.elespanol.com/wp-content/uploads/2015/09/location_marker_gps_shutterstock-840x566.jpg" basic>
                <div class="absolute-bottom text-subtitle2 text-center">
                    Descubre centros de recoleccion de plastico cerca de tu casa.
                </div>
            </q-img>
            <!-- </a> -->
            </q-card>
        </div>


    </div>
</template>

<script>
export default {

}
</script>

<style>
.cardBG{
    background: rgb(29,36,30);
    background: linear-gradient(210deg, rgb(212, 212, 212) 11%, rgba(55,167,66,0.6082808123249299) 50%, rgb(212, 212, 212) 100%);
    color: rgb(3, 3, 3);
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size: 1.2rem;
}
.myimg{
    width: 2rem !important;
}
.bar{
    font-size: 1rem;
    text-align: center;
    border: 1px solid rgba(255, 255, 255, 0.945);
    width: 92%;
    height: 2rem;
    border-radius: 2rem;
    background: rgb(29,36,30);
    background: linear-gradient(90deg, rgb(212, 212, 212) 11%, rgba(55,167,66,0.6082808123249299) 50%, rgb(212, 212, 212) 100%);

}

</style>
<style lang="sass" scoped>
.my-card
    width: 100%
    max-width: 300px
</style>