<template>
  <div class="flex flex-col items-center justify-center w-11/12 h-auto my-4 border-gray-600 border-y">
    <nav class="text-lg font-semibold text-black capitalize">
      <ul class="flex flex-row items-center justify-center w-full">
        <li v-for="category in categories.data" :key="category.id" class="px-2 py-1 hover:bg-gray-200 hover:italic">
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
