<template>
  <div class="md:flex items-center justify-center min-h-screen container">
    <div class="img-section bg-[#F8EAFF] hidden md:block shrink-0">
      <img src="@/assets/logo.svg" alt="logo" class="pt-6 pl-11 pb-12" />
      <div class="px-10 lg:px-16 pb-[52px] flex flex-col items-center gap-6">
        <img src="@/assets/login-team.png" />
        <div class="flex items-center flex-col">
          <h4 class="text-[#61227D] font-bold text-[20px]">
            Team Achieve
          </h4>
          <p class="text-[#5E5E5E] text-lg font-bold">
            Your perfect solution for funding your desires
          </p>
        </div>
      </div>
    </div>
    <div class="flex flex-col justify-center items-center mt-10 mb-40 basis-1/2 shrink-0 md:mx-16">
      <img src="@/assets/logo.svg" alt="logo" class="md:hidden mb-10" />
      <div class="flex items-center flex-col">
        <h2 class="text-[#61227D] font-bold text-[24px] md:text-[32px] mb-1">Welcome Back</h2>
        <p class="text-[#5E5E5E] text-sm text-center">Enter your email address and password to access your account.</p>
      </div>
      <div class="w-full">
        <form action="" class="w-full">
          <div class="mb-6">
            <label for="email" class="text-[#3E3E3E] mb-2">Email Address</label>
            <input type="email" id="email" placeholder="Enter your email" />
          </div>
          <div class="mb-2">
            <label for="password" class="text-[#3E3E3E] mb-2">Password</label>
            <input type="password" id="password" placeholder="Enter your password" />
          </div>
          <div class="flex justify-between mb-10">
            <div class="text-[#7D7D7D] text-sm">
              <input type="checkbox" id="remember" class="!w-min">
              <label for="remember">
                Remember me
              </label>
            </div>
            <div>
              <a href="#" class="text-[#61227D] text-sm">
                Forgot Password?
              </a>
            </div>
          </div>
          <div class="flex flex-col items-center">
            <button class="w-full py-3 px-6 bg-[#61227D] text-white rounded-lg mb-2.5">
              Sign In
            </button>
            <div>
              <span>
                Don’t have an account?
              </span>
              <span class="text-[#61227D]">
                Sign Up
              </span>
            </div>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
input {
  @apply rounded-lg border border-solid border-[#C6C6C6] py-[13px] px-2.5 w-full;
}
</style>