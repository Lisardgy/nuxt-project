<template>
  <div class="h-[100vh] w-[100vw] flex flex-row text-center justify-center items-center">
    <div class="flex flex-col gap-4">
      <div class="text-[36px]">{{ helloWorld }}</div>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis
        voluptatibus odio quidem provident corporis temporibus nam commodi,
        deleniti ipsum inventore?
      </p>
      <Lorem20 />
    </div>
  </div>
</template>

<script lang="ts" setup>
const helloWorld = ref("Hello world");
</script>
