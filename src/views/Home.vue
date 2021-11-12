<template>
  <div class="container text-center">
    <div class="row">
      <div class="col-md-12 border shadow-sm ">
        <img alt="Vue logo" src="../assets/logo.png" class="border  mx-auto" />
        <HelloWorld msg="Welcome to Your Vue.js App" />
      </div>

      <div class="card m-2 p-2" style="width: 18rem">
        <img src="parc.jpg" class="card-img-top" alt="..." />
        <div class="card-body">
          <h2 class="card-text">Véhicule</h2>
        </div>
      </div>

      <div class="card m-2 p-2" style="width: 18rem">
        <img src="parc.jpg" class="card-img-top" alt="..." />
        <div class="card-body">
          <h2 class="card-text">Visite Technique</h2>
        </div>
      </div>

      <div class="card m-2 p-2" style="width: 18rem">
        <img src="parc.jpg" class="card-img-top" alt="..." />
        <div class="card-body">
          <h2 class="card-text">Pérmis circulation</h2>
        </div>
      </div>

      <div class="card m-2 p-2" style="width: 18rem">
        <img src="parc.jpg" class="card-img-top" alt="..." />
        <div class="card-body">
          <h2 class="card-text">Les Agences</h2>
        </div>
      </div>

      <!-- <tete /> -->
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
// import Tete from "@/components/Tete.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    // Tete,
  },
};
</script>
