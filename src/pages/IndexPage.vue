<template>
  <div class="row text-center justify-content-center my-3">
    <!-- Card for Frog model -->
    <div class="card col-4 col-md-4 mx-2 my-2" style="width: 20rem">
      <model-viewer
        src="/artifacts/Frog.glb"
        alt="Frog 3D Model"
        camera-controls
        auto-rotate
        style="width: 100%; height: 300px"
      ></model-viewer>
      <div class="card-body">
        <h5 class="card-title">Frog Model</h5>
        <p class="card-text">
          Some quick example text to build on the card title and make up the bulk of the card's
          content.
        </p>
        <a href="#" class="btn btn-primary">View in Full Screen</a>
      </div>
    </div>

    <!-- Card for PUP Trophy model -->
    <div class="card col-4 col-md-4 mx-2 my-2" style="width: 20rem">
      <model-viewer
        src="/artifacts/PUP%20Trophy.glb"
        alt="PUP Trophy 3D Model"
        camera-controls
        auto-rotate
        style="width: 100%; height: 300px"
      ></model-viewer>
      <div class="card-body">
        <h5 class="card-title">PUP Trophy</h5>
        <p class="card-text">
          Some quick example text to build on the card title and make up the bulk of the card's
          content.
        </p>
        <a href="#" class="btn btn-primary">View in Full Screen</a>
      </div>
    </div>

    <!-- Card for Cat Toy model -->
    <div class="card col-4 col-md-4 mx-2 my-2" style="width: 20rem">
      <model-viewer
        src="/artifacts/Cat%20Toy.glb"
        alt="Cat Toy 3D Model"
        scale=".7 .7 .7"
        camera-controls
        auto-rotate
        style="width: 100%; height: 300px"
      ></model-viewer>
      <div class="card-body">
        <h5 class="card-title">Cat Toy</h5>
        <p class="card-text">
          Some quick example text to build on the card title and make up the bulk of the card's
          content.
        </p>
        <a href="#" class="btn btn-primary">View in Full Screen</a>
      </div>
    </div>

    <!-- Card for Cat model -->
    <div class="card col-4 col-md-4 mx-2 my-2" style="width: 20rem">
      <model-viewer
        src="/artifacts/Cat.glb"
        alt="Cat 3D Model"
        camera-controls
        auto-rotate
        scale="1.3 1.3 1.3"
        style="width: 100%; height: 300px"
      ></model-viewer>
      <div class="card-body">
        <h5 class="card-title">Ching ching</h5>
        <p class="card-text">
          Some quick example text to build on the card title and make up the bulk of the card's
          content.
        </p>
        <a href="#" class="btn btn-primary">View in Full Screen</a>
      </div>
    </div>
  </div>
</template>

<script setup>
//
</script>
