<template>
  <div v-if="storeItems.length">
    <div v-for="storeItem in storeItems" :key="storeItem">
      <div v-for="item in storeItem" :key="item" >
        <div
          class="flex flex-col justify-center text-center items-center box-content h-36 w-36 p-4 bg-gradient-to-b from-transparent via-transparent to-slate-50/10 hover:bg-gradient-to-b hover:from-transparent hover:via-transparent hover:to-slate-50/30"
        >
          <h1 class="text-white">{{ item.attributes.title }}</h1>
          <h1 class="text-white">{{ item.attributes.description }}</h1>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { reactive, ref, onMounted } from "vue";

const storeItems = reactive([]);
const imageLink = "http://localhost:1337/storeitems/";

onMounted(() => {
  fetch("http://localhost:1337/api/store-items/")
    .then((res) => res.json())
    .then((data) => {
      storeItems.push(data.data);
      console.log(data.data);
    })
    .catch((err) => {
      console.log(err);
    });
});
</script>
