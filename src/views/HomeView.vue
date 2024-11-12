<script setup lang="ts">

</script>

<template>
  <main>
    <div className="h-screen back flex justify-center items-center bg-cover bg-center" :style="{ backgroundImage: `linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('./dark.jpeg')` }" >
      <div class="pointer-events-none  fixed absolute top-2 md:rounded-md sm:rounded-md lg:rounded-md rounded-md  ">
  </div>
        <div className="space-y-5">
          <p className="text-yellow-600 font-bold text-5xl flex flex-col items-center">
            <span>{{"Cadeau Parfait "}}</span>
          </p>
          <p className="text-white font-semibold text-2xl flex flex-col items-center">Bienvenue.</p>
           <a href="" className="button--scroll animation animation--infinite animation--up-down "><svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="-275 398.7 44.2 44.2">
          <path fill="#FBBF24" d="M-275 420.8c0-12.2 9.9-22.1 22.1-22.1s22.1 9.9 22.1 22.1c0 12.2-9.9 22.1-22.1 22.1s-22.1-9.9-22.1-22.1zm42.7 0c0-11.4-9.2-20.6-20.6-20.6-11.4 0-20.6 9.2-20.6 20.6 0 11.4 9.2 20.6 20.6 20.6 11.4 0 20.6-9.3 20.6-20.6zM-260.6 418c0-.2.1-.4.2-.5.3-.3.8-.3 1.1 0l6.8 6.8 6.8-6.8c.3-.3.8-.3 1.1 0 .3.3.3.8 0 1.1l-7.3 7.3c-.3.3-.8.3-1.1 0l-7.3-7.3c-.3-.2-.3-.4-.3-.6z" />
        </svg></a>
          <p className="text-white text-lg flex flex-col text-center">{{ "Nous sommes ravis de vous accueillir aujourd'hui. Notre plateforme va bientôt prendre son envol, prête à vous offrir un meilleur service." }}</p>
        </div>
      </div>
  </main>
</template>
