<template>
  <div class=" background-gray">
    <div class="margin-top-custom container ">
      <div class="text-center my-5">
        <h1>Features</h1>
      </div>
      <div
        class="row d-flex justify-content-center"
        data-aos="fade-down"
        data-aos-easing="linear"
        data-aos-duration="1500"
      >
        <div class="col-4">
          <img src="../assets/features1.png" class="rounded col-12" alt="..." />
        </div>
        <div class="col-4">
          <img
            src="../assets/features2.png"
            class="rounded col-12 "
            alt="..."
          />
        </div>
        <div class="col-4">
          <img src="../assets/features3.png" class="rounded col-12" alt="..." />
        </div>
      </div>
      <div class="row my-5 d-flex justify-content-center">
        <div class="col-4 d-flex justify-content-center">
          <div
            class="card text-center"
            data-aos="fade-down"
            data-aos-easing="linear"
            data-aos-duration="1500"
            style="width: 18rem;"
          >
            <div class="card-body">
              <h5 class="card-title">Special title treatment</h5>
              <p class="card-text">
                With supporting text below as a natural lead-in to additional
                content.
              </p>
              <p class="text-danger font-weight-bold">Read More</p>
            </div>
          </div>
        </div>
        <div
          class="col-4 d-flex justify-content-center"
          data-aos="fade-down"
          data-aos-easing="linear"
          data-aos-duration="1500"
        >
          <div class="card text-center" style="width: 18rem;">
            <div class="card-body">
              <h5 class="card-title">Special title treatment</h5>
              <p class="card-text">
                With supporting text below as a natural lead-in to additional
                content.
              </p>
              <p class="text-danger font-weight-bold">Read More</p>
            </div>
          </div>
        </div>
        <div
          class="col-4  d-flex justify-content-center"
          data-aos="fade-down"
          data-aos-easing="linear"
          data-aos-duration="1500"
        >
          <div class="card text-center" style="width: 18rem;">
            <div class="card-body">
              <h5 class="card-title">Special title treatment</h5>
              <p class="card-text ">
                With supporting text below as a natural lead-in to additional
                content.
              </p>
              <p class="text-danger font-weight-bolder">Read More</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.font-30 {
  font-size: 30px;
  font-weight: 300;
}

.card {
  margin-top: -13vh;
  border: none;
  box-shadow: 0px 5px 30px rgba(0, 0, 0, 0.1);
  border-radius: 18px;
}

.margin-top-custom {
  margin-top: 30vh;
}

.background-gray {
  background-color: #fafafa;
}
</style>