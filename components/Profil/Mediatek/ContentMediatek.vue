<template>
  <div>
    <section class="w-4/5 mx-auto overflow-hidden mb-24">
      <div class="w-3/5 h-[464px]">
        <div class="flex flex-wrap pt-12 pb-10">
          <img class="w-24 mr-5" src="../../../assets/images/instagram.png" />
          <NuxtLink to="https://www.instagram.com/teknik.unhas/"
            ><h2 class="font-medium text-xl text-blue-900 pt-9">
              @teknik.unhas
            </h2></NuxtLink
          >
        </div>
        <div class="flex flex-wrap pb-10">
          <img class="w-24 mr-5" src="../../../assets/images/facebook.png" />
          <NuxtLink to="https://www.facebook.com/mediatekftuh/"
            ><h2 class="font-medium text-xl text-blue-900 pt-9">
              Mediatek FT-Unhas
            </h2></NuxtLink
          >
        </div>
        <div class="flex flex-wrap">
          <img class="w-24 mr-5" src="../../../assets/images/youtube2.png" />
          <NuxtLink
            to="https://www.youtube.com/channel/UC82mgDdDj_TC13JEMN5cJfQ"
            ><h2 class="font-medium text-xl text-blue-900 pt-9">
              Fakultas Teknik UNHAS Official
            </h2></NuxtLink
          >
        </div>
      </div>
      <div
        class="h-[464px] w-1/4 bg-blue-900 absolute right-[147px] top-[736px]"
      >
        <nav>
          <ul class="text-sm text-white font-bold ml-10 mt-10">
            <li>
              <NuxtLink to="/Profil">SEJARAH SINGKAT &nbsp;&nbsp;></NuxtLink>
            </li>
            <br />
            <br />
            <li>
              <NuxtLink to="/VisiMisi"
                >VISI, MISI DAN SASARAN &nbsp;&nbsp;></NuxtLink
              >
            </li>
            <br />
            <br />
            <li>
              <NuxtLink to="/Manajemen">MANAJEMEN &nbsp;&nbsp;></NuxtLink>
            </li>
            <br />
            <br />
            <li>
              <NuxtLink to="/StrukturOrganisasi"
                >STRUKTUR ORGANISASI &nbsp;&nbsp;></NuxtLink
              >
            </li>
            <br />
            <br />
            <li>
              <NuxtLink to="/RencanaUtama"
                >RENCANA UTAMA &nbsp;&nbsp;></NuxtLink
              >
            </li>
            <br />
            <br />
            <li>
              <NuxtLink to="/PetaKampus">PETA KAMPUS &nbsp;&nbsp;></NuxtLink>
            </li>
            <br />
            <br />
            <li class="bg-red-600 w-1 h-7">
              <NuxtLink class="absolute left-14 top-[403px]" to="/Mediatek">MEDIATEK &nbsp;&nbsp;></NuxtLink>
            </li>
            <br />
            <br />
          </ul>
        </nav>
      </div>
    </section>
  </div>
</template>