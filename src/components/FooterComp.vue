<template>
  <div class="footer">
    <footer>
      <ul class="list-unstyled d-flex justify-content-center">
        <li>
          <a href="https://github.com/fnurrahmah125"><i class="bi bi-github fs-5"></i></a>
        </li>
        <li>
          <a href="https://wa.me/6285864042799"><i class="bi bi-whatsapp fs-5"></i></a>
        </li>
      </ul>

      <div class="text-center">
        <span>2022 - Created by Fatrini Nurrahmah</span>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "FooterComp",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.footer {
  margin-top: 64px;
}
.bi {
  color: #000;
  padding: 0 12px;
  transition: 0.3s;
}
.bi:hover {
  color: #ff90e8;
}
</style>
