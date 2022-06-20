<template>
  <div class="container">
    <div class="row">
      <div class="col-md-4 bg-info">
        <div class="row d-block">
          <div class="col-12"><h1>HERBALIST SIMULATOR</h1></div>
          <div class="col-12">
            <h3>All Assets</h3>
            <h2>Herbs: {{ player.score }}</h2>
            <h2>Herbs Per Click</h2>
            <h2>Herbs per Second</h2>
          </div>
          <div class="col-12"></div>
        </div>
      </div>
      <div
        class="col-md-4 d-flex justify-content-center align-items-center bg-white"
      >
        <img
          class="rounded-circle bg-dark img-fluid w-50 btn herb-btn"
          src="https://austindye.github.io/clicker-game/leaf.png"
          alt=""
        />
      </div>
      <div class="col-md-4 bg-success">
        <div class="row">
          <div class="col-3 text-center">
            <p class="fs-5 text-center">Equipment</p>
            <div class="btn btn-info btn-lg my-3">X</div>
            <div class="btn btn-info btn-lg my-3">X</div>
            <div class="btn btn-info btn-lg my-3">X</div>
            <div class="btn btn-info btn-lg my-3">X</div>
          </div>
          <div class="col-3 text-center">
            <p class="fs-5 text-center">Herblore</p>
            <div class="btn btn-info btn-lg my-3">X</div>
            <div class="btn btn-info btn-lg my-3">X</div>
            <div class="btn btn-info btn-lg my-3">X</div>
            <div class="btn btn-info btn-lg my-3">X</div>
          </div>
          <div class="col-3 text-center">
            <p class="fs-5 text-center">Character</p>
            <div class="btn btn-info btn-lg my-3">X</div>
            <div class="btn btn-info btn-lg my-3">X</div>
            <div class="btn btn-info btn-lg my-3">X</div>
            <div class="btn btn-info btn-lg my-3">X</div>
          </div>
          <div class="col-3 text-center">
            <p class="fs-5 text-center">Shop</p>
            <div class="btn btn-info btn-lg my-3">X</div>
            <div class="btn btn-info btn-lg my-3">X</div>
            <div class="btn btn-info btn-lg my-3">X</div>
            <div class="btn btn-info btn-lg my-3">X</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style scoped lang="scss">
.row {
  height: 100vh;
}
</style>
