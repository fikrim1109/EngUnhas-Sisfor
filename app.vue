<template>
  <div>
    <header>
      <section>
        <div class="text-xs text-white font-bold bg-blue-950 h-6 pt-0.5">
          <NuxtLink class="ml-40 mr-20 hover:text-red-600" to="/">UNHAS</NuxtLink>
          <NuxtLink class="mr-96 hover:text-red-600" to="/">COT</NuxtLink>
          <NuxtLink class="ml-96 hover:text-red-600" to="/">PETA SITUS</NuxtLink>
          <NuxtLink class="ml-20 mr-40 hover:text-red-600" to="/">AKSES CEPAT</NuxtLink>
        </div>

        <div class="bg-blue-900 overflow-hidden relative">
          <img class="w-20 h-24 ml-10 float-left mr-5 mt-5 mb-5" src="./assets/images/Logo Resmi Unhas.png" />
          <h1 class="font-bold text-white text-4xl mt-9">FAKULTAS TEKNIK</h1>
          <h1 class="font-medium text-white text-base">
            UNIVERSITAS HASANUDDIN
          </h1>

          <div class="border-2 absolute top-11 right-14 border-solid">
            <label for="searching"></label>
            <input class="bg-transparent text-white border-none outline-none w-72 h-12 ml-2" type="search" id="searching"
              placeholder="&nbsp;Cari" />
            <button>
              <img class="w-5 h-5 float-right mt-2 mr-5" src="./assets/images/icon _search_.png" />
            </button>
          </div>
        </div>

        <div class="bg-red-600 space-x-11 h-12 pt-3">
          <NuxtLink class="font-bold text-white text-xs ml-11 hover:text-blue-950" to="/Beranda">BERANDA</NuxtLink>
          <NuxtLink class="font-bold text-white text-xs hover:text-blue-950" to="/Profil">PROFIL</NuxtLink>
          <NuxtLink class="font-bold text-white text-xs hover:text-blue-950" to="/SumberDaya">SUMBER DAYA</NuxtLink>
          <NuxtLink class="font-bold text-white text-xs hover:text-blue-950" to="/Akademik">AKADEMIK</NuxtLink>
          <NuxtLink class="font-bold text-white text-xs hover:text-blue-950" to="/Kemahasiswaan">KEMAHASISWAAN</NuxtLink>
          <NuxtLink class="font-bold text-white text-xs hover:text-blue-950" to="/RisetInovasi">RISET DAN INOVASI</NuxtLink>
          <NuxtLink class="font-bold text-white text-xs hover:text-blue-950" to="/Kemitraan">KEMITRAAN</NuxtLink>
          <NuxtLink class="font-bold text-white text-xs hover:text-blue-950" to="/Gpm">GPM-PR</NuxtLink>
          <NuxtLink class="font-bold text-white text-xs hover:text-blue-950" to="/Dharma">DHARMA WANITA</NuxtLink>
          <NuxtLink class="" to="/"><img class="w-5 h-5 inline-block" src="./assets/images/Vector.png" /></NuxtLink>
        </div>
      </section>
    </header>

    <main>
      <NuxtPage />
    </main>

    <footer>
      <section class="bg-blue-900 h-full">
        <div class="overflow-hidden mb-10">
          <img class="h-12 ml-16 float-left mr-4 mt-14 mb-5" src="./assets/images/Logo Resmi Unhas.png" />
          <h1 class="font-bold text-white text-xl mt-14">FAKULTAS TEKNIK</h1>
          <h1 class="font-medium text-white text-xs">UNIVERSITAS HASANUDDIN</h1>
        </div>

        <div class="flex flex-wrap gap-x-24 mb-16">
          <div class="ml-20">
            <h3 class="font-bold text-sm text-white mb-9">
              INFORMASI LEBIH LANJUT
            </h3>

            <nav>
              <ul class="text-xs text-white">
                <li>
                  <img class="h-3 float-left mr-5" src="./assets/images/lokasi.png" />
                  <NuxtLink to="#">Jalan Poros Malino Km. 6, Bontomarannu. Gowa, Sulawesi
                    Selatan</NuxtLink>
                </li>
                <br />
                <li>
                  <img class="h-3 float-left mr-3" src="./assets/images/email.png" />
                  <NuxtLink to="#">engineering@unhas.ac.id</NuxtLink>
                </li>
                <br />
                <li>
                  <img class="h-3 float-left mr-5" src="./assets/images/call.png" />
                  <NuxtLink to="#">727-727-727-727</NuxtLink>
                </li>
              </ul>
            </nav>
          </div>

          <div class="ml-9">
            <h3 class="font-bold text-sm text-white mb-9">DEPARTEMEN</h3>

            <nav class="flex flex-wrap gap-5">
              <ul class="text-xs text-white">
                <li>
                  <NuxtLink to="#">Teknik Mesin</NuxtLink>
                </li>
                <br />
                <li>
                  <NuxtLink to="#">Teknik Sipil</NuxtLink>
                </li>
                <br />
                <li>
                  <NuxtLink to="#">Teknik Perkapalan</NuxtLink>
                </li>
                <br />
                <li>
                  <NuxtLink to="#">Teknik Elektro</NuxtLink>
                </li>
                <br />
                <li>
                  <NuxtLink to="#">Teknik Arsitektur</NuxtLink>
                </li>
                <br />
                <li>
                  <NuxtLink to="#">Teknik Geologi</NuxtLink>
                </li>
                <br />
              </ul>
              <ul class="text-xs text-white">
                <li>
                  <NuxtLink to="#">Teknik Kelautan</NuxtLink>
                </li>
                <br />
                <li>
                  <NuxtLink to="#">Teknik Sistem Perkapalan</NuxtLink>
                </li>
                <br />
                <li>
                  <NuxtLink to="#">Teknik Perencanaan Wilayah Kota</NuxtLink>
                </li>
                <br />
                <li>
                  <NuxtLink to="#">Teknik Pertambangan</NuxtLink>
                </li>
                <br />
                <li>
                  <NuxtLink to="#">Teknik Informatika</NuxtLink>
                </li>
                <br />
                <li>
                  <NuxtLink to="#">Teknik Lingkungan</NuxtLink>
                </li>
                <br />
              </ul>
            </nav>
          </div>

          <div class="ml-9">
            <h3 class="font-bold text-sm text-white mb-9">TENTANG</h3>

            <nav>
              <ul class="text-xs text-white">
                <li>
                  <NuxtLink to="#">Sejarah</NuxtLink>
                </li>
                <br />
                <li>
                  <NuxtLink to="#">Visi dan Misi</NuxtLink>
                </li>
                <br />
                <li>
                  <NuxtLink to="#">Manajemen</NuxtLink>
                </li>
                <br />
                <li>
                  <NuxtLink to="#">Peta Kampus</NuxtLink>
                </li>
                <br />
                <li>
                  <NuxtLink to="#">Pimpinan Fakultas</NuxtLink>
                </li>
                <br />
              </ul>
            </nav>
          </div>

          <div class="ml-9">
            <h3 class="font-bold text-sm text-white mb-9">DIDUKUNG OLEH</h3>
            <div class="flex flex-wrap gap-3">
              <img class="h-10" src="./assets/images/dukung1.png" />
              <img class="h-7" src="./assets/images/dukung2.png" />
              <img class="h-9" src="./assets/images/dukung3.png" />
            </div>
          </div>
        </div>

        <div class="flex flex-row gap-10">
          <div class="flex flex-wrap gap-x-5 ml-20 pb-5">
            <NuxtLink to="/"><img class="h-5" src="./assets/images/fb.png" /></NuxtLink>
            <NuxtLink to="/"><img class="h-5" src="./assets/images/twitter.png" /></NuxtLink>
            <NuxtLink to="/"><img class="h-5" src="./assets/images/ig.png" /></NuxtLink>
            <NuxtLink to="/"><img class="h-5" src="./assets/images/yt.png" /></NuxtLink>
          </div>

          <div>
            <p class="font-semibold text-white text-sm">
              © 2023 Fakultas Teknik Universitas Hasanuddin
            </p>
          </div>
        </div>
      </section>
    </footer>
  </div>
</template>
