<template>
  <div class="container-fluid">
    <NavbarComp />
    <main>
      <!-- Column 1 -->
      <div class="row row-cols-1 row-cols-md-2 mb-4">
        <div class="col col-md-5 p-3 my-auto text-center">
          <img src="../assets/frame-1.jpg" class="rounded-3" />
        </div>
        <div class="col my-auto text-center text-md-start py-3">
          <h5 class="card-title fw-bold lh-base">Sukses Selalu Landing Page</h5>
          <div class="mb-4">
            <span class="badge border border-dark rounded-pill px-3 py-2 mt-2 me-2 text-dark">HTML</span>
            <span class="badge border border-dark rounded-pill px-3 py-2 mt-2 me-2 text-dark">CSS</span>
            <span class="badge border border-dark rounded-pill px-3 py-2 mt-2 me-2 text-dark">Javascript</span>
            <span class="badge border border-dark rounded-pill px-3 py-2 mt-2 me-2 text-dark">Bootstrap</span>
          </div>

          <div class="d-lg-flex gap-lg-3">
            <div class="btn-preview my-3 my-lg-0">
              <a href="https://suksesselalu-landing-page.netlify.app/" target="_blank" class="btn btn-front">View Demo</a>
              <a href="" class="btn btn-back">View Demo</a>
            </div>
            <div class="btn-preview">
              <a href="https://github.com/fnurrahmah125/suksesselalu" target="_blank" class="btn btn-front">View Github</a>
              <a href="" class="btn btn-back">View Github</a>
            </div>
          </div>
        </div>
      </div>

      <!-- Column 2 -->
      <div class="row row-cols-1 row-cols-md-2 mb-4">
        <div class="col col-md-5 p-3 my-auto text-center">
          <img src="../assets/frame-2.jpg" class="rounded-3" />
        </div>
        <div class="col my-auto text-center text-md-start py-3">
          <h5 class="card-title fw-bold lh-base">Appointment Form</h5>
          <div class="mb-4">
            <span class="badge border border-dark rounded-pill px-3 py-2 mt-2 me-2 text-dark">HTML</span>
            <span class="badge border border-dark rounded-pill px-3 py-2 mt-2 me-2 text-dark">CSS</span>
            <span class="badge border border-dark rounded-pill px-3 py-2 mt-2 me-2 text-dark">Javascript</span>
            <span class="badge border border-dark rounded-pill px-3 py-2 mt-2 me-2 text-dark">Bootstrap</span>
          </div>

          <div class="d-lg-flex gap-lg-3">
            <div class="btn-preview my-3 my-lg-0">
              <a href="https://appointment-form.netlify.app/" target="_blank" class="btn btn-front">View Demo</a>
              <a href="" class="btn btn-back">View Demo</a>
            </div>
            <div class="btn-preview">
              <a href="https://github.com/fnurrahmah125/appointment-form" target="_blank" class="btn btn-front">View Github</a>
              <a href="" class="btn btn-back">View Github</a>
            </div>
          </div>
        </div>
      </div>

      <!-- Column 3 -->
      <div class="row row-cols-1 row-cols-md-2 mb-4">
        <div class="col col-md-5 p-3 my-auto text-center">
          <img src="../assets/frame-3.jpg" class="rounded-3" />
        </div>
        <div class="col my-auto text-center text-md-start py-3">
          <h5 class="card-title fw-bold lh-base">Simple Quiz App</h5>
          <div class="mb-4">
            <span class="badge border border-dark rounded-pill px-3 py-2 mt-2 me-2 text-dark">HTML</span>
            <span class="badge border border-dark rounded-pill px-3 py-2 mt-2 me-2 text-dark">CSS</span>
            <span class="badge border border-dark rounded-pill px-3 py-2 mt-2 me-2 text-dark">Javascript</span>
            <span class="badge border border-dark rounded-pill px-3 py-2 mt-2 me-2 text-dark">Vue JS</span>
          </div>

          <div class="d-lg-flex gap-lg-3">
            <div class="btn-preview my-3 my-lg-0">
              <a href="https://fnurrahmah-simple-quiz-app.netlify.app/" target="_blank" class="btn btn-front">View Demo</a>
              <a href="" class="btn btn-back">View Demo</a>
            </div>
            <div class="btn-preview">
              <a href="https://github.com/fnurrahmah125/quiz-app" target="_blank" class="btn btn-front">View Github</a>
              <a href="" class="btn btn-back">View Github</a>
            </div>
          </div>
        </div>
      </div>

      <!-- Column 4 -->
      <div class="row row-cols-1 row-cols-md-2 mb-4">
        <div class="col col-md-5 p-3 my-auto text-center">
          <img src="../assets/frame-4.jpg" class="rounded-3" />
        </div>
        <div class="col my-auto text-center text-md-start py-3">
          <h5 class="card-title fw-bold lh-base">Simple Weather App</h5>
          <div class="mb-4">
            <span class="badge border border-dark rounded-pill px-3 py-2 mt-2 me-2 text-dark">HTML</span>
            <span class="badge border border-dark rounded-pill px-3 py-2 mt-2 me-2 text-dark">CSS</span>
            <span class="badge border border-dark rounded-pill px-3 py-2 mt-2 me-2 text-dark">Javascript</span>
          </div>

          <div class="d-lg-flex gap-lg-3">
            <div class="btn-preview my-3 my-lg-0">
              <a href="https://fnurrahmah-simple-weather-app.netlify.app/" target="_blank" class="btn btn-front">View Demo</a>
              <a href="" class="btn btn-back">View Demo</a>
            </div>
            <div class="btn-preview">
              <a href="https://github.com/fnurrahmah125/weather-app" target="_blank" class="btn btn-front">View Github</a>
              <a href="" class="btn btn-back">View Github</a>
            </div>
          </div>
        </div>
      </div>
    </main>
  </div>
  <FooterComp />
</template>

<script>
import NavbarComp from "../components/NavbarComp.vue";
import FooterComp from "../components/FooterComp.vue";

export default {
  name: "HomePage",
  components: {
    NavbarComp,
    FooterComp,
  },
};
</script>

<style scoped>
.container-fluid {
  border: 0.0625rem solid #000;
  border-radius: 0.25rem;
  background-color: #fff;
}
img {
  width: min(100%, 430px);
}
a {
  text-decoration: none;
}
main {
  padding: 20px 10px;
}
.row {
  border-radius: 0.25rem;
  box-shadow: 0px 4px 30px rgba(0, 0, 0, 0.05);
}
.btn-preview {
  position: relative;
}
.btn {
  width: 100%;
  border-radius: 0.25rem;
  background-color: #000;
}
.btn-front {
  position: absolute;
  z-index: 2;
  color: #fff;
  transition: 0.35s;
}
.btn-back {
  position: relative;
  color: #000;
  background-color: #000;
}
.btn-front:hover {
  color: #000;
  border: 1px solid #000;
  background-color: #ff90e8;
  transform: translate(-5px, -5px);
}

@media (min-width: 768px) {
  main {
    padding: 24px;
  }
}
</style>
