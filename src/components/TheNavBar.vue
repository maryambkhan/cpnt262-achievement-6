<template>
  <nav class="bg-red-400">
    <div class="max-w-6xl mx-auto px-4">
      <div class="flex justify-between">
        <div class="flex space-x-4">
          <!--logo-->
          <div>
            <a href="#" class="flex items-center py-5 px-2">
              <svg
                class="h-6 w-6 mr-2 text-blue-400"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8"
                />
              </svg>
              <span class="font-bold">DEV</span>
            </a>
          </div>

          <!--primary nav-->
          <div class="flex items-center space-x-1">
            <a href="#" class="py-5 px-3 text-black hover:text-red-900"
              >Home
            </a>
            <a href="#" class="py-5 px-3 text-black hover:text-red-900">Work</a>
            <a href="#" class="py-5 px-3 text-black hover:text-red-900"
              >About Us</a
            >
            <a href="#" class="py-5 px-3 text-black hover:text-red-900"
              >Contact Us</a
            >
          </div>
        </div>

        <!--secondary nav-->
        <div class="flex items-center space-x-1">
          <a
            href="#"
            class="
              py-2
              px-3
              bg-purple-400
              hover:bg-purple-600
              rounded
              transition
              duration-300
            "
            >Login
          </a>
          <a
            href="#"
            class="
              py-2
              px-3
              bg-purple-400
              hover:bg-purple-600
              rounded
              transition
              duration-300
            "
            >SignUp</a
          >
        </div>
      </div>
    </div>
  </nav>
</template>