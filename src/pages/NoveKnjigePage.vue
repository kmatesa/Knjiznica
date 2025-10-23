<template>
  <q-page padding>

     <q-toolbar class="bg-grey-9 text-white">
      <q-toolbar-title>Nove knjige</q-toolbar-title>
     </q-toolbar>
     
     <div class="q-pa-md row items-start q-gutter-md">

    <q-card class="my-card">
      <img src="https://ezop-antikvarijat.hr/wp-content/uploads/2019/11/001-8-scaled-e1681368662998.jpg">

      <q-card-section>
        <div class="text-h6">Preobrazba</div>
        <div class="text-subtitle2">Franz Kafka</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
       {{ lorem1 }}
      </q-card-section>
    </q-card>


    <q-card class="my-card">
        <img src="https://znanje.hr/product-images/c04d81d7-06a5-4f00-b12d-2a0fb65abe73.jpg">

        <q-card-section>
          <div class="text-h6">Lovac u žitu</div>
          <div class="text-subtitle2">J.D.Salinger</div>
        </q-card-section>

        <q-card-section class="q-pt-none">
        {{ lorem2}}
        </q-card-section>
      </q-card>


    <q-card class="my-card">
      <img src="https://cdn.quasar.dev/img/mountains.jpg">

      <q-card-section>
        <div class="text-h6">Our Changing Planet</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
       {{ lorem }}
      </q-card-section>
    </q-card>


    <q-card class="my-card">
      <img src="https://www.rijeka.hr/wp-content/uploads/2023/12/Nova-knji%C5%BEnica-4-901x600.jpg">

      <q-card-section>
        <div class="text-h6">Our Changing Planet</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
       {{ lorem }}
      </q-card-section>
    </q-card>

    </div>
  </q-page>
</template>

<script>
export default {
  setup () {
    return {
      lorem: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
      lorem1:'Preobrazba Franza Kafke je pripovijetka o trgovačkom putniku Gregorui Samsi koji se jednog jutra budi pretvoren u golemog kukca. Djelo istražuje teme otuđenja, obiteljskih odnosa i gubitka identiteta kroz surrealne događaje, a radnja se odvija u njegovoj sobi unutar stana njegove obitelji, gdje njegova obitelj reagira strahom i zgražanjem.',
      lorem2:'Knjiga Lovac u žitu američkog pisca J. D. Salingera iz 1951. godine. Riječ je o klasičnom romanu o odrastanju i pobuni, koji je desetljećima zadržao svoju popularnost. Glavni lik, tinejdžer Holden Caulfield, postao je ikona generacije koja preispituje društvene norme i licemjerje svijeta odraslih.'
   
    }
  }
}

</script>

<style lang="sass" scoped>
.my-card
  width: 100%
  max-width: 250px
</style>
