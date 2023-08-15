<template>
  <div class="w-full flex-col flex items-center bg-[#121212] text-white p-4">
    <div
      class="max-w-screen-lg w-full flex-row flex items-center justify-between"
    >
      <img
        class="w-5 h-5"
        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQMI1lrVWc1-T2A8yEQVhIOjQIikN43sE-WJju9PNMkcA&s"
      />
      <div v-for="item in navButtons" class="whitespace-nowrap text-[12px]">
        <button>{{ item.label }}</button>
      </div>
      <span class="material-icons cursor-pointer">search</span>
      <span class="material-icons cursor-pointer">shopping_bag</span>
    </div>
    <div
      class="max-w-screen-lg w-full flex-row flex items-center justify-between mt-4"
    >
      <div class="flex-col flex">
        <div class="text-[#828282] text-[12px]">13” model with M1 chip</div>
        <div class="text-[21px] font-semibold">MacBook Air</div>
      </div>
      <div class="flex-row flex items-center text-[12px] gap-4">
        <div class="text-[#828282]">Overview</div>
        <div v-for="item in overViewButtons" class="whitespace-nowrap">
          <button>{{ item.label }}</button>
        </div>
        <button class="bg-[#0071e3] rounded-xl px-2 py-1">Buy</button>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
const navButtons = [
  {
    label: "Store",
    route: "",
  },
  {
    label: "Mac",
    route: "",
  },
  {
    label: "Ipad",
    route: "",
  },
  {
    label: "Iphone",
    route: "",
  },
  {
    label: "Watch",
    route: "",
  },
  {
    label: "Vision",
    route: "",
  },
  {
    label: "Airpods",
    route: "",
  },
  {
    label: "Tv & Home",
    route: "",
  },
  {
    label: "Entertainment",
    route: "",
  },
  {
    label: "Accessories",
    route: "",
  },
  {
    label: "Support",
    route: "",
  },
];
const overViewButtons = [
  {
    label: "Tech Specs",
    route: "",
  },
  {
    label: "Compare",
    route: "",
  },
  {
    label: "New to Mac",
    route: "",
  },
];
</script>
