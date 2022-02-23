<template>
  <header>
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-md-12 py-4">
          <div class="card">
            <div class="card-header text-center">
              <h3>PostBook</h3>
              <a class="button-link" href="/admin/home">Back Office</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  mounted() {
    console.log("Header mounted.");
  },
};
</script>

<style lang="scss" scoped>
.card {
  background-color: rgb(255, 113, 91);
  color: #ffffff;
  border-radius: 10px;

  .card-header {
    position: relative;
    border-radius: 10px;

    a {
      position: absolute;
      right: 15px;
      top: 20%;
      // transform: translate(0, -50%);
    }
  }
}
</style>
