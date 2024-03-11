<template>
  <main class="grid grid-cols-2 gap-0 h-screen">
    <div class="bg-lpurple rounded-[20px] hidden md:block px-16 pt-6 pb-16">
      <img src="../assets/logo.png" alt="Logo" class="logo w-[198px] h-[97px] object-cover mb-9">
      <img src="../assets/Loginimage.png" class="rounded-[20px] loginImage" alt="">
      <div class="text-center f-lora mt-8">
        <h1 class="text-dpurple f-lora text-xl">
          Team Achieve
        </h1>
        <p class="text-grey font-bold text-lg">
          Your perfect solution for funding your  desires
        </p>
      </div>
    </div>
    <div class="">
      <LoginForm/>
    </div>
  </main>
</template>

<script setup>
import LoginForm  from '@/components/LoginForm/LoginForm.vue';

</script>

<style lang="scss">
  main{
    h1{
     font-weight: 900;
    }
    .loginImage{
      width: 100%;
      height:417px;
      object-fit: cover;
    }
  }
</style>