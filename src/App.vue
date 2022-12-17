<template>
   <div class="flex w-full min-h-screen font-sans bg-gray-100">
    <SideBar />
    <main class="flex flex-col flex-1 gap-3 p-4">
      <header>
        <h1 class="text-3xl font-semibold leading-loose text-gray-700">POS System</h1>
      </header>
      <hr class="border-red-700" />
      <Card />
      <Table />
    </main>
    <aside class="flex flex-col gap-y-6 pt-6 pr-6 w-96">
      <RightSide />
    </aside>
  </div>
</template>

<script setup lang="ts">
import SideBar from './components/SideBar.vue'

import RightSide from './components/RightSide.vue'
import Table from './components/Table.vue';
import Card from './components/Card.vue';

</script>

