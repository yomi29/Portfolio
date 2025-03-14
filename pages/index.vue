<template>
  <div class="bg-[#0e0f0f] h-screen text-gray-300">
    <!-- Nav bar -->
    <nav class="p-4 rounded-md flex items-center justify-between px-[80px]">
      <!-- logo -->
      <div class="">
        <span class="hover:text-gray-400 text-2xl">
          Adebi<small class="text-2xl text-yellow-400">mpe</small></span
        >
      </div>

      <!-- nav links -->
      <div>
        <ul class="flex items-center gap-5">
          <li>
            <a
              class="hover:text-gray-400 text-lg hover:text-yellow-400 hover:underline"
              href="#about"
              >About</a
            >
          </li>
          <li>
            <a
              class="hover:text-gray-400 text-lg hover:text-yellow-400 hover:underline"
              href="#works"
              >Works</a
            >
          </li>
          <li>
            <a
              class="hover:text-gray-400 text-lg hover:text-yellow-400 hover:underline"
              href="#testimonials"
              >Testimonials</a
            >
          </li>
          <li>
            <a
              class="hover:text-gray-400 text-lg hover:text-yellow-400 hover:underline"
              href="#contact-me"
              >Contact Me</a
            >
          </li>
        </ul>
      </div>
    </nav>
    <hr />
    <!-- Main content -->
    <main class="mt-20 max-w-[1200px] mx-auto">
      <!-- hero section -->
      <div class="flex items-center justify-between h-full">
        <!-- Left side contents -->
        <div class="flex flex-col justify-center h-[400px] w-[600px] space-y-5">
          <h1 class="text-7xl">Hi I'm Adebimpe</h1>
          <p class="text-lg text-gray-400">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Suscipit
            reiciendis, aliquam provident rerum soluta ipsam amet praesentium
            dicta est ea velit quisquam id ipsum odio corporis quas itaque aut
            maxime.
          </p>

          <!-- button and social link  -->
          <div>
            <button
              type="button"
              class="border rounded-full py-3 px-5 hover:bg-shadow-xl text-lg text-gray-300 hover:bg-gray-300 hover:text-black"
            >
              View Portfolio
            </button>
          </div>
        </div>

        <!-- Right side contents -->
        <div class="">
          <!-- profile picture -->
          <div class="w-[400px] shadow-xl">
            <img
              src="~/assets/images/profile-image.jpg"
              class="object-center object-cover w-full mx-auto h-[500px] shadow-2xl rounded-[500px]"
              alt="adebimpe profile picture"
            />
          </div>
        </div>
      </div>

      <!--  -->
    </main>
  </div>
</template>

<script lang="ts" setup></script>

<style scoped>
hr {
  border-color: white;
  opacity: 0.2;
}
</style>
