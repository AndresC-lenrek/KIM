<template>
<div class="q-pa-md  row items-start q-gutter-md">
    <div class="bar q-mb-md q-mt-md q-ml-none q-pl-none">
        <p style="font-family: 'Cinzel Decorative'; font-size: 22px"> Discucion </p>
    </div>
    <!-- Nueva card -->
    <q-card  class="my-card">    <a href="https://www.gob.mx/semarnat/archivo/articulos">
        <q-img src="statics\general.png" basic>
        <div class="absolute-bottom text-subtitle2 text-center">
            General
        </div>
    </q-img></a>
    </q-card>
        <q-card class="my-card"><a href="https://www.naturalista.mx/journal">
        <q-img src="statics\noticias.png" basic>
        <div class="absolute-bottom text-subtitle2 text-center">
            Noticias
        </div>
    </q-img></a>
    </q-card>
    <q-card class="my-card"><a href="http://conexionbio.jbb.gov.co/calendario-ambiental-2019/">
        <q-img src="statics\offtopic.png" basic>
        <div class="absolute-bottom text-subtitle2 text-center">
            Offtopic
        </div>
    </q-img></a>
    </q-card>
        <div class="bar q-mb-md q-mt-md q-ml-none q-pl-none">
            <p style="font-family: 'Cinzel Decorative', cursive; font-size: 22px
            ">
            reciclaje
            </p>
        </div>
    <q-card class="my-card"><a href="https://www.pinterest.com.mx/dulce22/ideas-y-reciclado/">
        <q-img src="\statics\ideas.png" basic>
        <div class="absolute-bottom text-subtitle2 text-center">
            Ideas
        </div>
    </q-img></a>
    </q-card>
    <q-card class="my-card"><a href="https://ovacen.com/100-proyectos-ecologicos/">

        <q-img src="statics\proyectos.png" basic>
        <div class="absolute-bottom text-subtitle2 text-center">
            Proyectos
        </div>
    </q-img></a>
    </q-card>

        <div class="bar q-mb-none q-mt-md q-ml-none q-pl-none">
            <p style="font-family: 'Cinzel Decorative', cursive; font-size: 22px
            ">
            Aportes
            </p>
        </div>
    <q-card class="my-card"><a href="https://www.pinterest.es/bichojorozquino/tutoriales-de-reciclaje/">
        <q-img src="\statics\Tutoriales.png" basic>
        <div class="absolute-bottom text-subtitle2 text-center">
            Tutoriales
        </div>
    </q-img></a>
    </q-card>
    <q-card class="my-card"><a href="https://www.compromisoempresarial.com/rsc/2018/01/las-10-mejores-apps-para-cuidar-el-medio-ambiente/">
        <q-img src="\statics\apps.png" basic>
        <div class="absolute-bottom text-subtitle2 text-center">
            Apps y otras paginas
        </div>
    </q-img></a>
    </q-card>
    <q-card class="my-card"><a href="http://www.mercadosdemedioambiente.com/actualidad/10-v-deos-para-la-educaci-n-ambiental/">
        <q-img src="\statics\Videos.png" basic>
        <div class="absolute-bottom text-subtitle2 text-center">
            Videos
        </div>
    </q-img></a>
    </q-card>
</div> 
</template>

<script>
export default {

}
</script>
<style lang="sass" scoped>
.my-card
    background: rgb(29,36,30);
    background: linear-gradient(90deg, rgba(29,36,30,1) 11%, rgba(55,167,66,0.6082808123249299) 50%, rgba(25,23,20,0.3449754901960784) 100%);
    width: 100%;
    max-width: 24rem;
</style>

<style>
.bar{
    font-size: 1rem;
    text-align: center;
    border: 1px solid rgba(255, 255, 255, 0.945);
    width: 100%;
    height: 2rem;
    border-radius: 2rem;
    background: rgb(29,36,30);
    background: linear-gradient(90deg, rgb(212, 212, 212) 11%, rgba(55,167,66,0.6082808123249299) 50%, rgb(212, 212, 212) 100%);;

}
</style>