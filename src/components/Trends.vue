<template>
  <div class="lg:w-1/4 hidden lg:block px-4 py-2">
    <!--trend serach input-->
    <div class="relative">
      <input
        type="text"
        placeholder="검색"
        class="
          pl-10
          bg-gray-100
          rounded-full
          w-full
          h-10
          focus:outline-none
          text-sm
          focus:ring-1 focus:ring-primary
        "
      />
      <font-awesome-icon
        :icon="['fas', 'fa-search']"
        class="absolute left-0 mt-3 ml-3 text-sm text-light"
      />
    </div>
    <!--trend for me-->
    <div class="w-full rounded-lg bg-gray-100 mt-3">
      <div
        class="
          flex
          items-center
          justify-between
          px-3
          py-3
          ml-2
          mr-2
          border-b border-gray-500
        "
      >
        <span class="text-xl font-bold">나를 위한 트렌드</span>
        <font-awesome-icon
          :icon="['fas', 'fa-cog']"
          class="text-center text-primary hover:bg-blue-50 cursor-pointer"
        />
      </div>
      <div class="border-b border-gray-100" v-for="trend in 3" :key="trend">
        <div
          class="
            flex
            justify-between
            p-3
            border-b border-gray-300
            hover:outline-dotted hover:rounded-lg
          "
        >
          <div class="flex-1 flex flex-col w-full">
            <div class="text-4">대한민국에서 트렌드 중</div>
            <div class="text-sm font-bold mb1">러블리즈</div>
            <div class="text-1">3,454트윗</div>
          </div>
          <font-awesome-icon :icon="['fas', 'fa-cog']" />
        </div>
      </div>
      <div>
        <div
          class="
            text-sm
            px-5
            py-2
            mb-3
            text-primary
            hover:bg-gray-500
            rounded-full
          "
        >
          더 보기
        </div>
      </div>
    </div>
    <div class="w-full rounded-lg bg-gray-100 mt-3">
      <div class="flex">
        <div class="flex flex-col">
          <div class="flex"></div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>

<style>
</style>