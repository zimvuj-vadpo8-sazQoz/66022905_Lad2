<script setup lang="ts">
import Post from './Post.vue';
</script>

<template>
  <section class="border-2  border-sky-500 w-[292px] h-[367px]  rounded  border-dividerLight-light dark:border-dividerLight-dark cursor-pointer ">
    <h2 class="text-[12px] font-bold leading-4 tracking-normal text-left pl-3 pb-0 pt-2 text-textPrimary-light dark:text-textPrimary-dark">RECENT POSTS</h2>
  <a class=" grid grid-cols-1 gap-2  place-items-center  ">
    <Post/>
  </a>
  </section>
</template>
