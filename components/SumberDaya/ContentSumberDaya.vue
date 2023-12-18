<template>
    <div>
      <section>
        <!-- Tampilan header halaman -->
        <h1 class="text-3xl font-bold mb-4">Halaman Tenaga Kependidikan</h1>
        <p class="text-lg">TENAGA KEPENDIDIKAN</p>
      </section>
  
      <!-- Tampilan tabel Tenaga Kependidikan -->
      <section class="mt-8">
        <table class="border-collapse border border-green-800 w-full">
          <thead>
            <tr class="bg-green-200">
              <th class="border border-green-600 px-4 py-2">No</th>
              <th class="border border-green-600 px-4 py-2">Nama</th>
              <th class="border border-green-600 px-4 py-2">Jabatan</th>
              <th class="border border-green-600 px-4 py-2">NIP</th>
              <th class="border border-green-600 px-4 py-2">Golongan</th>
            </tr>
          </thead>
          <tbody>
            <tr v-for="(pegawai, index) in tenagaKependidikan" :key="pegawai.NIP">
              <td class="border border-green-600 px-4 py-2">{{ index + 1 }}</td>
              <td class="border border-green-600 px-4 py-2">{{ pegawai.Nama }}</td>
              <td class="border border-green-600 px-4 py-2">{{ pegawai.Jabatan }}</td>
              <td class="border border-green-600 px-4 py-2">{{ pegawai.NIP }}</td>
              <td class="border border-green-600 px-4 py-2">{{ pegawai.Golongan }}</td>
            </tr>
          </tbody>
        </table>
      </section>
    </div>
  </template>
  
  <script>
  import axios from 'axios';
  
  export default {
    data() {
      return {
        tenagaKependidikan: []
      };
    },
    mounted() {
      this.fetchData();
    },
    methods: {
      fetchData() {
        const apiUrl = 'http://localhost:8055/admin/content/pages/27a23e79-6e2f-4221-869d-084917f03227';
  
        axios.get(apiUrl)
          .then(response => {
            const content = response.data.data.content;
  
            // Membuat regex untuk menangkap blok informasi
            const regex = /((?:\w+\t+)+)\n([\s\S]*?)\n(\d+)/gm;
            let match;
            const tenagaKependidikan = [];
  
            while ((match = regex.exec(content)) !== null) {
              const headers = match[1].trim().split('\t');
              const data = match[2].trim().split('\t');
              const no = match[3];
  
              const pegawai = {};
              headers.forEach((header, index) => {
                pegawai[header] = data[index];
              });
  
              tenagaKependidikan.push({
                No: no,
                ...pegawai
              });
            }
  
            this.tenagaKependidikan = tenagaKependidikan;
          })
          .catch(error => {
            console.error('Error fetching data:', error);
          });
      }
    }
  };
  </script>
  