<template>
  <footer>
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-md-12">
          <div class="card">
            <div class="card-body text-center">
              Developed by
              <a class="button-link" href="https://github.com/MarcoCusenza"
                >Marco Cusenza</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  mounted() {
    console.log("Footer mounted.");
  },
};
</script>

<style lang="scss" scoped>
.card {
  background-color: rgb(255, 113, 91);
  color: #ffffff;
  border-radius: 10px;
  .card-body {
    border-radius: 10px;
  }
}
</style>
