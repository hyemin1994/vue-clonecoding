<template>
  <div class="flex flex-col">
    <!--menu title -->
    <div class="border-b border-gray-100 px-3 py-2 font-fold text-lg">홈</div>
    <!--twitting section-->
    <div class="flex">
      <img
        src="http://picsum.photos/200"
        class="w-10 h-10 rounded-full px-3 py-3 hover:opacity-80 cursor-pointer"
      />
      <div class="flex-1 flex-col">
        <textarea
          placeholder="무슨 일이 일어나고 있나요?"
          class="
            w-full
            mt-2
            text-small
            resize-none
            text-bold
            focus-within:outline-none
          "
        ></textarea>
        <div class="text-right mr-5 border-b-8 border-gray-100">
          <button
            class="
              bg-primary
              text-white
              font-bold
              px-4
              py-2
              focus:outline-none
              hover:bg-dark
              rounded-full
              text-sm
              mb-2
            "
          >
            트윗
          </button>
        </div>
      </div>
    </div>
  </div>
  <!--tweets-->
  <div
    class="flex px-3 py-3 border-b border-gray-100"
    v-for="tweet in 10"
    :key="tweet"
  >
    <img
      src="http://picsum.photos/200"
      class="w-10 h-10 rounded-full hover:opcacity-80 cursor-pointer"
    />
    <div class="flex-1 flex flex-col ml-3">
      <div class="text-sm space-x-1">
        <span class="font-bold">조국</span>
        <span>@ididid</span>
        <span>7분</span>
      </div>
      <!--tweet body -->
      <div>내용</div>
      <!--tweet actions-->
      <div class="flex justify-between">
        <div class="text-gray-500 hover:bg-blue-50 rounded-full p-2">
          <font-awesome-icon
            :icon="['fas', 'comment']"
            class="hover:text-primary"
          />
          <span class="ml-1">11</span>
        </div>
        <div class="text-gray-500 hover:bg-blue-50 rounded-full p-2">
          <font-awesome-icon
            :icon="['fas', 'retweet']"
            class="hover:text-primary"
          />
          <span class="ml-1">11</span>
        </div>
        <div class="text-gray-500 hover:bg-blue-50 rounded-full p-2">
          <font-awesome-icon
            :icon="['fas', 'heart']"
            class="hover:text-red-300"
          />
          <span class="ml-1">11</span>
        </div>
        <div class="text-gray-500 hover:bg-blue-50 rounded-full p-2">
          <font-awesome-icon
            :icon="['fas', 'share-square']"
            class="hover:text-red-300"
          />
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