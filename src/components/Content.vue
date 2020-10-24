<template>
  <div class="container">
    <div class="card mb-3 py-5">
      <div class="row no-gutters ">
        <div class="col-md-6 m-auto">
          <div class="card-body ">
            <p class="card-text font-36">
              Contact
            </p>
            <p class="card-text text-justify ">
              Questions or concerns? Just fill out the form below and our
              support team will get back to you within 24 hours
            </p>
            <p class=" text-red">
              <small>
                Learn More
              </small>
            </p>
          </div>
        </div>

        <div class="col-md-6 img-height">
          <video width="600" controls>
            <source
              src="../assets/Pexels Videos 2786540.mp4"
              type="video/mp4"
            />
            <source
              src="../assets/Pexels Videos 2786540.mp4"
              type="video/ogg"
            />
            Your browser does not support HTML5 video.
          </video>
        </div>
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
}
</style>