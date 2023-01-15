<template>
  <div class="flex h-screen container mx-auto">
    <div
      class="
        w-20
        lg:w-1/4
        pt-5
        lg:ml-5
        flex flex-col
        justify-between
        border-r border-gray-200
      "
    >
      <Sidebar />
    </div>

    <div class="flex-1 h-screen">
      <div class="flex-1 border-r border-gray-100 overflow-y-auto">
        <Notifications />
      </div>
    </div>
    <Trends />
  </div>
</template>

<script>
import Home from "./pages/Home.vue";
import Sidebar from "./components/Sidebar.vue";
import Notifications from "./pages/notifications.vue";
import Trends from "./components/Trends.vue";

export default {
  components: { Home, Sidebar, Notifications, Trends },
  setup() {},
};
</script>

<style>
</style>
