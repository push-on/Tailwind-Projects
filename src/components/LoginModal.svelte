<!-- Global Container -->
<div class="h-screen flex justify-center items-center">
  <!-- Card Container -->
  <div class=" flex bg-slate-800 rounded-xl relative">
    <div class="group absolute bg-slate-700 hover:bg-slate-600 text-slate-50 rounded-full p-1 right-3 top-3">
      <svg
        class="w-6 h-6 duration-500 group-hover:rotate-180	"
        fill="none"
        stroke="currentColor"
        viewBox="0 0 24 24"
        xmlns="http://www.w3.org/2000/svg"
        ><path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M6 18L18 6M6 6l12 12" /></svg>
    </div>
    <!-- content -->
    <div class="flex flex-col px-16 py-20 max-w-lg space-y-10">
      <div class="space-y-5">
        <h1 class="text-3xl font-serif font-semibold">Log In</h1>
        <p class="text-slate-400">
          Log in to your account to upload or download pictures, videos or
          music.
        </p>
      </div>
      <input
        type="text"
        placeholder="Enter your email address"
        class="bg-slate-900 p-5 rounded-lg outline-none border-none" />
      <div class="flex justify-between ">
        <button class="text-cyan-500 hover:text-cyan-400"
          >Forgot Password?</button>
        <div
          class="group flex space-x-5 bg-cyan-800 hover:bg-cyan-700 py-5 px-7 rounded-lg cursor-pointer">
          <button>Next</button>
          <svg
            class="w-6 h-6 duration-200 group-hover:translate-x-2"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
            ><path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M14 5l7 7m0 0l-7 7m7-7H3" /></svg>
        </div>
      </div>
      <div class="flex flex-col space-y-5">
        <div class="border-t border-slate-500 " />
        <div
          class="text-center text-slate-400 hover:text-cyan-400 cursor-pointer">
          Or log in with
        </div>
        <div class="flex justify-center space-x-5">
          <div
            class="border rounded border-slate-500 hover:border-slate-400 space-x-3 px-7 py-3 flex">
            <img src="/src/assets/facebook.png" alt="" class="w-7" /><button
              >Facebook</button>
          </div>
          <div
            class="border rounded border-slate-500 hover:border-slate-400 space-x-3 px-7 py-3 flex">
            <img src="/src/assets/google.png" alt="" class="w-7" /><button
              >Google</button>
          </div>
        </div>
      </div>
    </div>
    <img
      src="src/assets/img00.jpg"
      alt=""
      class=" w-96 object-cover rounded-r-xl hidden md:block" />
  </div>
</div>
