<template>
  <nav class="navbar navbar-expand-lg navbar-light mt-2">
    <div class="container-fluid">
      <a class="navbar-brand fs-5" href="#">fnurrahmah</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-lg-auto">
          <li class="nav-item">
            <router-link to="/"><a href="#">Projects</a></router-link>
          </li>
          <li class="nav-item">
            <router-link to="/about"><a href="#">About</a></router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavbarComp",
  methods: {},
};
</script>

<style scoped>
a {
  text-decoration: none;
  color: #42494f;
  font-size: 1rem;
  font-weight: 400;
  transition: 0.3s;
}
a:hover {
  color: #ff90e8;
}
.active a {
  color: #ff90e8;
  font-weight: 500;
}
.exact-active-link a {
  color: #ff90e8;
  font-weight: 500;
}
.navbar .container-fluid {
  border: none;
}
.navbar-brand {
  font-weight: 600;
}
.nav-item {
  margin-top: 24px;
}
.nav-item:nth-child(2) {
  padding-right: 0;
  margin-bottom: 16px;
}
.nav-item router-link-active,
.nav-item router-link-exact-active {
  color: #ff90e8;
}

@media (min-width: 768px) {
  .navbar {
    padding: 24px;
  }
}

@media (min-width: 992px) {
  .nav-item {
    padding: 0 24px;
    margin-top: 0px;
  }
  .nav-item:nth-child(2) {
    margin-bottom: 0px;
  }
}
</style>
