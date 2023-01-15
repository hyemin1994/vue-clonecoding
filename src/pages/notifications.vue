<template>
  <div class="flex-1 flex-col h-screen">
    <div class="p-3 font-bold text-lg border-b border-gray-100">알림</div>
    <!--nofitications-->
    <div
      class="
        flex flex-col
        hover:bg-gray-50
        space-y-2
        p-4
        border-b border-gray-100
      "
      v-for="notifitaion in 5"
      :key="notifitaion"
    >
      <div class="flex justify-between">
        <img
          src="http://picsum.photos/100"
          class="w-10 h-10 rounded-full hover:opacity-50 cursor-pointer"
        />
        <font-awesome-icon :icon="['fas', 'ellipsis-h']" />
      </div>
      <div>
        <div><span class="font-bold">김혜민</span> 님의 트윗</div>
        <div>qmffkqmffmqkfmqkfmqkfmkqfmqkfmkqfmk</div>
      </div>
    </div>
  </div>
</template>

<script>
import Trends from "../components/Trends.vue";
export default {
  components: { Trends },
};
</script>

<style>
</style>