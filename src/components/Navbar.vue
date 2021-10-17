<template>
  <nav class="bg-black shadow-lg">
    <div class="max-w-6xl mx-auto px-4">
      <div class="flex justify-between">
        <div class="flex space-x-7">
          <div class="hidden md:flex items-center space-x-1">
            <a
              href=""
              class="py-4 px-2 text-green-500 hover:text-green-500 font-semibold "
              >SummerCamp 2021</a
            >
            <a
              href=""
              class="py-4 px-2 text-green-500 font-semibold hover:text-green-500 transition duration-300"
              >Subscribe</a
            >
          </div>
        </div>

        <!-- Mobile menu button -->
        <div class="md:hidden flex items-center">
          <button class="outline-none mobile-menu-button">
            <svg
              class=" w-6 h-6 text-gray-500 hover:text-green-500 "
              x-show="!showMenu"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path d="M4 6h16M4 12h16M4 18h16"></path>
            </svg>
          </button>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
  methods: {
    showMenu() {
      this.showMenu = !this.showMenu;
    },
  },
};
</script>

<style></style>
