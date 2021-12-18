<template>
  <div class="bg-slate-800 min-h-screen">
    <nav class="w-full p-4 bg-slate-800/20 sticky top-0 backdrop-blur">
      <div class="flex items-center justify-between">
        <div>
          <img
            style="width: 100px; height: 50px"
            src="../assets/images/group2.svg"
            alt=""
            class=""
          />
        </div>

        <!-- Mobile toggle -->
        <div>
          <button @click="drawer">
            <svg
              class="h-8 w-8 fill-current text-white"
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
    </nav>

    <div class="container mx-auto p-4">
      <div class="bg-red-400 h-20"></div>
      <div class="bg-red-400 h-20 mt-4"></div>
      <div class="bg-red-400 h-20 mt-4"></div>
      <div class="bg-red-400 h-20 mt-4"></div>
      <div class="bg-red-400 h-20 mt-4"></div>
      <div class="bg-red-400 h-20 mt-4"></div>
      <div class="bg-red-400 h-20 mt-4"></div>
      <div class="bg-red-400 h-20 mt-4"></div>
      <div class="bg-red-400 h-20 mt-4"></div>
      <div class="bg-red-400 h-20 mt-4"></div>
      <div class="bg-red-400 h-20 mt-4"></div>
      <div class="bg-red-400 h-20 mt-4"></div>
      <div class="bg-red-400 h-20 mt-4"></div>
    </div>
  </div>
</template>
<script>
export default {
  name: "nameDefault",
  fetch() {},
  data() {
    return {};
  },
  methods: {},
  computed: {},
};
</script>