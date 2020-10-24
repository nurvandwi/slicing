<template>
  <div class=" background-gray mt-3">
    <div
      class="container margin-top-custom 
}"
      style=" z-index: 10000;"
    >
      <div class="card mb-3 py-5">
        <div class="row no-gutters ">
          <div class="col-md-6 m-auto">
            <div class="card-body ">
              <p class="card-text font-36 text-white font-weight-bold">
                Stay focused on saving money
              </p>
              <p class="card-text text-justify text-white">
                It is important to stay focused on saving money in any way you
                can. We help you monitor your spending habits so you can easily
                spot and cut any unnecessary expenses. Simply join today to get
                started!
              </p>
              <div class="d-flex ml-auto py-5">
                <img
                  class="icon-store pr-4"
                  src="../assets/ion-logo-google-playstore.png"
                  alt=""
                />
                <img
                  class="icon-store pr-4"
                  src="../assets/ion-logo-apple-appstore.png"
                  alt=""
                />
                <img
                  class="icon-store"
                  src="../assets/simple-icons_windows.png"
                  alt=""
                />
              </div>
            </div>
          </div>

          <div class="col-md-6 img-height">
            <img src="../assets/v1.png" class="card-img" alt="#" />
            <img src="../assets/v2.png" class="card-img img-overlay" alt="#" />
            <img src="../assets/v4.png" class="card-img img-top " alt="#" />
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

@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500&display=swap");

h1,
p {
  font-family: "Montserrat", sans-serif;
}

.margin-top-custom {
  margin-top: 30vh;
}

.icon-store {
  width: auto;
  height: 55px;
}

.img-top {
  z-index: 3;
  position: relative;
  top: -790px;
  right: -3vw;
  height: 51vh;
}

.img-overlay {
  z-index: 2;
  position: relative;
  top: -387px;
  right: -5vw;
}

span {
  display: inline-block;
}

.text-red {
  color: red;
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

.font-36 {
  font-size: 36px;
}

.margin-top-custom {
  margin-top: 7rem !important;
}

.card {
  border: none;
  background: none;
}

.margin-top-custom {
  margin-top: 30vh;
}

.background-gray {
  background-color: #ed4c5c;
}
</style>