<template>
  <div class="w-11/12 h-auto border-y border-gray-600 flex justify-center items-center flex-col my-4">
    <nav class="text-black font-semibold capitalize text-lg">
      <ul class="flex flex-row justify-center items-center w-full">
        <li v-for="category in categories.data" :key="category.id" class="p-2 hover:bg-gray-300 hover:italic">
          <NuxtLink :to="{name: 'categories-id', params: {id: category.id}}">
          {{  category.attributes.name }}
          </NuxtLink>
        </li>
      </ul>
    </nav>
  </div>
</template>
<script>
import categoriesQuery from "~/apollo/queries/category/categories";

export default {
      data() {
        return {
          categories: {
            data: [],
          },
        };
      },
      apollo: {
        categories: {
          prefetch: true,
          query: categoriesQuery,
        },
      },
    };
</script>
