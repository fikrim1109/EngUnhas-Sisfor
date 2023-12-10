<template>
  <div>
    <section class="w-4/5 mx-auto">
      <div>
        <nav class="mb-7">
          <ul class="text-2xl text-blue-950 font-bold flex flex-wrap gap-x-40">
            <li>
              <NuxtLink class="ml-12" to="/Akademik"
                >DEPARTEMEN &nbsp;></NuxtLink
              >
            </li>
            <li>
              <NuxtLink class="ml-2" to="/ProgramMagister"
                >PROGRAM MAGISTER &nbsp;></NuxtLink
              >
            </li>
            <li>
              <NuxtLink class="ml-3" to="/ProgramDoktor"
                >PROGRAM DOKTOR &nbsp;></NuxtLink
              >
            </li>
          </ul>
        </nav>
        <nav class="mb-24">
          <ul class="text-2xl text-blue-950 font-bold flex flex-wrap gap-x-32">
            <li>
              <NuxtLink class="ml-5" to="/ProgramProfesi"
                >PROGRAM PROFESI &nbsp;></NuxtLink
              >
            </li>
            <li>
              <NuxtLink class="ml-16" to="/Akreditasi">AKREDITASI &nbsp;></NuxtLink>
              <div class="bg-red-600 w-72 h-1 mt-2"></div>
            </li>
            <li>
              <NuxtLink to="/KalenderPen"
                >KALENDER PENDIDIKAN &nbsp;></NuxtLink
              >
            </li>
          </ul>
        </nav>
      </div>
    </section>
  </div>
</template>