<template>
  <div class="flex flex-col items-center justify-center gap-4 h-screen aldrich-regular body bg-image-20-opacity">
    <div id="logo" class="rounded-4xl w-40 h-40 bg-white">
      <img src="~/assets/logo.jpg" alt="" class="w-full h-full rounded-4xl" />
    </div>
    <h1 class="font-bold text-2xl text-[#ffc80a]">SENACAR</h1>
    <h2 class="font-bold">ACESSÓRIOS AUTOMOTIVOS</h2>

    <div class="flex flex-row gap-3">
      <a href="https://www.instagram.com/senacar.auto/" target="_blank">
        <UIcon class="size-7" name="line-md:instagram" />
      </a>
      <a href="">
        <UIcon class="size-7" name="material-symbols:mail-outline-rounded" target="_blank" />
      </a>
      <a href="https://www.facebook.com/Senacar.auto">
        <UIcon class="size-7" name="dashicons:facebook" target="_blank" />
      </a>
    </div>

    <UButton class="w-60" label="WhatsApp" icon="mdi-light:message-reply" to="http://wa.me/5591980238532"
      target="_blank" />

    <UButton class="w-60" label="Instagram" color="neutral" icon="line-md:instagram"
      to="https://www.instagram.com/senacar.auto/" target="_blank" />

    <!-- <UButton class="w-60" label="Cardapio Automotivo" color="neutral" icon="mdi-light:instagram"
      to="https://www.instagram.com/senacar.auto/" target="_blank"  /> -->

    <UButton class="w-60" label="Local" color="neutral" icon="mdi-light:map-marker"
      to="https://www.google.com/maps/place/Tv.+Quintino+Bocai%C3%BAva,+1298+-+Reduto,+Bel%C3%A9m+-+PA,+66053-240/@-1.4510339,-48.4902401,17z/data=!3m1!4b1!4m6!3m5!1s0x92a48e9a927b2e03:0xb0b331d108578b03!8m2!3d-1.4510339!4d-48.4876652!16s%2Fg%2F11cpdq75ht?entry=ttu&g_ep=EgoyMDI1MDMzMC4wIKXMDSoASAFQAw%3D%3D"
      target="_blank" />

    <a href="/cardapio_senacar.pdf" download="Cardapio_Senacar.pdf">
      <div class="flex flex-row w-60 h-8 text-black p-1 text-sm items-center bg-neutral-50 rounded-[8px]">
        <UIcon class="size-7" name="mdi:file-pdf-box" target="_blank" />
        Cardápio Automotivo
      </div>
    </a>

    <!-- <iframe
      class="rounded-3xl w-[350px] h-[350px] xl:w-[600px] xl:h-[400px]"
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3988.5389102740733!2d-48.4902401239214!3d-1.4510338985353093!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x92a48e9a927b2e03%3A0xb0b331d108578b03!2sTv.%20Quintino%20Bocai%C3%BAva%2C%201298%20-%20Reduto%2C%20Bel%C3%A9m%20-%20PA%2C%2066053-240!5e0!3m2!1spt-BR!2sbr!4v1743479858294!5m2!1spt-BR!2sbr"
      style="border: 0"
      allowfullscreen=""
      loading="lazy"
      referrerpolicy="no-referrer-when-downgrade"
    ></iframe> -->
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Aldrich&display=swap");

.aldrich-regular {
  font-family: "Aldrich", sans-serif;
  font-weight: 400;
  font-style: normal;
}

/* 
.body {
  background-image: url("~/assets/bg.jpg");
  background-size: cover;
} */

.bg-image-20-opacity::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: url("~/assets/bg.jpg");
  background-size: cover;
  background-position: center;
  opacity: 0.35;
  /* This is the key part */
  z-index: -1;
}
</style>
