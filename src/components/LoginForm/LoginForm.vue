<template>
  <section>
    <div class="  grid grid-col-1 place-content-center  p-16" >
        <div class="block mx-auto md:hidden">
            <img src="../assets/logo.png" alt="Logo" class="logo w-[198px] h-[97px] object-cover mb-9">
        </div>
        <div class="w-full md:py-20">
            <div class="text-center">
                <h1 class="text-dpurple f-lora text-[32px] mb-3 font-bold">
                    Welcome Back
                </h1>
                <p class="text-grey f-noto text-base font-normal">
                    Enter your email address and password to access your account.
                </p>
            </div>
            <form action="" class="py-6 f-noto">
                <div class="mb-6 flex flex-col gap-2">
                    <label for="" class="text-dgrey">Email Address<span class="text-red-600">*</span></label>
                    <input type="text" class="form-input rounded-lg bg-white border border-[#dddddd] px-[10px] py-[13px]" placeholder="Enter your email">
                </div>
                <div class="mb-4 flex flex-col gap-2">
                    <label for="">Password<span class="text-red-600">*</span></label>
                    <div class="flex justify-between rounded-lg overflow-hidden  bg-white border border-[#dddddd] ">
                        
                        <input type="text" class="form-input w-full p-0 px-[10px] py-[13px]" placeholder="Enter your password">
                        <div class="border px-3 py-4 bg-[#f7f7f7]">
                            <svg width="23" height="16" viewBox="0 0 23 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M14.5 8C14.5 8.79565 14.1839 9.55871 13.6213 10.1213C13.0587 10.6839 12.2956 11 11.5 11C10.7044 11 9.94129 10.6839 9.37868 10.1213C8.81607 9.55871 8.5 8.79565 8.5 8C8.5 7.20435 8.81607 6.44129 9.37868 5.87868C9.94129 5.31607 10.7044 5 11.5 5C12.2956 5 13.0587 5.31607 13.6213 5.87868C14.1839 6.44129 14.5 7.20435 14.5 8Z" stroke="#7D7D7D" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            <path d="M1.5 8C3.1 3.903 6.836 1 11.5 1C16.164 1 19.9 3.903 21.5 8C19.9 12.097 16.164 15 11.5 15C6.836 15 3.1 12.097 1.5 8Z" stroke="#7D7D7D" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>

                        </div>
                    </div>
                </div>

                <div class="flex justify-between f-noto ">
                    <div class="">
                        <div class="relative flex gap-x-3">
                            <div class="flex h-6 items-center">
                                <input id="remember-me" name="remember-me" type="checkbox" class="h-4 w-4 rounded border-gray-300 text-dpurple focus:text-dpurple">
                            </div>
                            <div class="text-sm leading-6">
                                <label for="remember-me" class="font-normal  text-[#7d7d7d] ">Remember Me</label>
                               
                            </div>
                        </div>
                    </div>
                    <div class="">
                        <a href="#" class="text-dpurple font-normal text-sm decoration-none">Forgot Password?</a>
                    </div>
                </div>
                <div class="flex items-stretch mt-8 mb-2">
                    <button class="bg-dpurple px-[24px] rounded-lg py-[11px] text-white text-sm f-noto w-full">Sign in</button>
                </div>
                <p class="text-center text-base f-noto">Dont have an account? <a href="#" class="text-dpurple font-semibold text-sm decoration-none">Sign Up?</a></p>
            </form>
        </div>
    </div>
  </section>
</template>

<script>
export default {
    name: "LoginForm",
     data() {
        return {
            count: 0
        }
    }

}
</script>

<style>

</style>