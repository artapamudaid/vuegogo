<template>
  <div class="home">
    <h3>My Activities</h3>
    <div class="pekerjaan-rumah">
      <div v-for="tugasSaya in tugas" v-bind:key="tugasSaya.id" class="tugas">
        <p>{{ tugasSaya.nama }}</p>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
  data: function () {
    return {
      tugas: [
      {
        id: 1,
        nama: 'Menyapu Rumah'
      },
      {
        id: 2,
        nama: 'Menguras Bak Mandi'
      },
      {
        id: 3,
        nama: 'Mencuci Piring'
      }
    ]
    }
  },
  components: {
  }
}
</script>
