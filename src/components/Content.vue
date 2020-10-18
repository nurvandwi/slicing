<template>
  <div>
    <div
      class="text-dark font-weight-bolder d-flex justify-content-center my-5"
    >
      <h1>Our Story</h1>
    </div>
    <div class="container">
      <div class="card mb-3">
        <div class="row no-gutters">
          <div class="col-md-6 img-height">
            <img src="../assets/story-1.png" class="card-img" alt="#" />
          </div>
          <div class="col-md-6 m-auto">
            <div class="card-body ">
              <p class="card-text font-italic">
                Every love story is beautiful, but ours is the best one. I loved
                her since the first time I saw her. My mother told me to pick
                the very best one, and I did. True love stories never have
                endings.
              </p>
              <p class="card-text">
                <small class="text-muted">-- Pras</small>
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="card mb-3 py-5">
        <div class="row no-gutters ">
          <div class="col-md-6 m-auto">
            <div class="card-body ">
              <p class="card-text font-italic">
                A great marriage doesn’t happen when the “Perfect Couple” gets
                together. It happens when an imperfect couple gets together and
                learns to enjoy each other’s differences.
              </p>
              <p class="card-text">
                <small class="text-muted">-- Kania</small>
              </p>
            </div>
          </div>
          <div class="col-md-6 img-height">
            <img src="../assets/story-2.png" class="card-img" alt="#" />
          </div>
        </div>
      </div>
      <div class="margin-top-custom">
        <div class="row d-flex">
          <div class="col-4">
            <img src="../assets/story-3.png" class="rounded col-12" alt="..." />
          </div>
          <div class="col-4">
            <img
              src="../assets/story-3.png"
              class="rounded col-12 "
              alt="..."
            />
          </div>
          <div class="col-4">
            <img src="../assets/story-3.png" class="rounded col-12" alt="..." />
          </div>
        </div>
      </div>
      <div class="m-auto col-8 col-md-7">
        <p class="text-center quotes-text my-5">
          We’re two humans, here having temptations on both of our hands. We’re
          one with waves, dance with the tides,
          <span>
            sync in kisses. Only when i look into your eyes, is how i can see
            how beautiful the horizon was</span
          >
        </p>
        <hr style="width:10%; border:1px solid #d3d3d3 " />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500&display=swap");

h1,
p {
  font-family: "Montserrat", sans-serif;
}

span {
  display: inline-block;
}

.quotes-text {
  letter-spacing: 0.02em;
  font-size: 20px;
  line-height: 29px;
  font-weight: 300;
}

.img-height {
  height: 340px;
}

.margin-top-custom {
  margin-top: 7rem !important;
}

.card {
  border: none;
}
</style>