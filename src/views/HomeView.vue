<script setup>
import EyeIcon from '@/components/icons/EyeIcon.vue'
</script>

<template>
  <main class="h-max md:min-h-screen w-full grid md:grid-cols-2">
    <section class="md:bg-[#F8EAFF] h-max md:h-full">
      <div class="py-16">
        <img src="/image 30.png" />
      </div>
      <div class="hidden md:flex flex-col items-center justify-center gap-5">
        <img class="md:block hidden" src="/image 31.png" />
        <p class="text-3xl font-semibold text-[#61227D]">Team Achieve</p>
        <p class="text-2xl font-medium">Your solution to finding your desires</p>
      </div>
    </section>
    <section class="flex flex-col gap-y-16 items-center justify-center md:h-full px-10 md:px-24">
      <div class="flex flex-col items-center justify-center">
        <p class="text-[32px] text-[#61227D] font-bold">Welcome Back</p>
        <p class="text-2xl font-medium text-center">
          Enter your email address and password to access your account.
        </p>
      </div>
      <form class="w-full flex flex-col gap-y-10">
        <div class="flex flex-col gap-5 w-full">
          <label class="text-2xl" for="email">
            Email Address <span class="text-red-400">*</span>
          </label>
          <input
            type="text"
            class="text-2xl p-5 h-[50px] outline-none border border-[#dddddd] rounded-lg"
            placeholder="Enter your Email Address"
          />
        </div>
        <div class="flex flex-col gap-5 w-full">
          <label class="text-2xl" for="email"> Password <span class="text-red-400">*</span> </label>
          <div
            class="h-[50px] border border-[#dddddd] rounded-lg overflow-hidden flex items-center"
          >
            <input
              type="text"
              class="text-2xl p-5 h-full outline-none border-0 grow max-w-[95%]"
              placeholder="Enter your password"
            />
            <button class="bg-[#F7F7F7] w-[50px] h-full flex items-center justify-center border-l">
              <EyeIcon />
            </button>
          </div>
          <div class="flex items-center justify-between">
            <div class="flex items-center gap-3">
              <input type="checkbox" class="w-[20px] h-[20px] accent-[#61227D]" />
              <p class="text-2xl font-medium">Remember me</p>
            </div>
            <div class="flex items-center gap-3">
              <p class="text-2xl font-medium text-[#61227D]">Forgot password</p>
            </div>
          </div>
        </div>
        <div class="flex flex-col gap-y-5 items-center justify-center">
          <button
            class="w-full h-[45px] bg-[#61227D] rounded-lg flex items-center justify-center text-white text-2xl"
          >
            Sign in
          </button>
          <p class="text-2xl">Don’t have an account? <span class="text-[#61227D]">Sign up</span></p>
        </div>
      </form>
    </section>
  </main>
</template>
