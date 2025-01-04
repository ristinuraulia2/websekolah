<template>
  <div class="container-fluid">
    <div class="row my-5">

      <div class="col-lg-12 mb-5">
        <div class="crounded-5">
          <img src="~/assets/img/guru.jpg" alt="gambar" style="width: 80%; height: 50%;" />
        </div>
      </div>

      <div class="col-lg-12">
        <div class="sambutan rounded-5">
          <div class="sambutan-content">
            <img src="~/assets/img/kepalasekolah.jpg" alt="Kepala Sekolah" class="kepala-sekolah-img" />

            <p><strong>- Kurniawan, S.Pd, M.Pd.</strong></p>

          </div>
        </div>
      </div>

    </div>
  </div>
</template>

<style scoped>
.card {
  height: 400px;
  box-shadow: 1px 1px 10px #424242;
  width: 50vw;
  max-width: 10000px;
  padding-left: 100px;
  padding-right: 100px;

}

.kepala-sekolah-img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
}


@media (max-width: 768px) {
  .sambutan-content {
    align-items: center;
  }

  .card {
    width: 90vw;
    padding-left: 50px;
    padding-right: 50px;
  }
}
</style>