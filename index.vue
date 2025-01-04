<template>
  <div class="biodata">
    <h1>Biodata</h1>
    <div class="card">
      <h2>Nama: {{ biodata.name }}</h2>
      <p>Umur: {{ biodata.age }} tahun</p>
      <p>Alamat: {{ biodata.address }}</p>
      <p>Email: {{ biodata.email }}</p>
      <p>Telepon: {{ biodata.phone }}</p>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      biodata: {
        name: "risti",
        age: 18,
        address: "Jl.Padasuka Nagrak",
        email: "ristinuraulia124@gmail.com",
        phone: "0895326321085",
      },
    };
  },
};
</script>

<style scoped>
.biodata {
  font-family: Arial, sans-serif;
  margin: 20px auto;
  max-width: 600px;
  text-align: center;
}

.card {
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 20px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  background: #f9f9f9;
}

h1 {
  color: #333;
  margin-bottom: 20px;
}

h2 {
  margin-bottom: 10px;
  color: #444;
}

p {
  color: #555;
  margin: 5px 0;
}
</style>