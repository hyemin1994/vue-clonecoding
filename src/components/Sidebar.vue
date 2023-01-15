<template>
  <!-- sidebar 위 -->
  <div>
    <div class="flex flex-col items-center lg:items-start">
      <!--logo icon-->
      <div class="text-3xl text-primary ml-4 mb-3">
        <font-awesome-icon :icon="['fab', 'twitter']" />
      </div>
      <!--sidemenu icons-->
      <div class="flex flex-col items-start space-y-1">
        <div class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full">
          <span class="text-2xl fa-fw"
            ><font-awesome-icon :icon="['fas', 'home']"
          /></span>
          <span class="text-lg ml-5 hidden lg:inline-block">홈</span>
        </div>
        <div class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full">
          <span class="text-2xl fa-fw"
            ><font-awesome-icon :icon="['fas', 'glasses']"
          /></span>
          <span class="text-lg ml-5">탐색하기</span>
        </div>
        <div class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full">
          <span class="text-2xl fa-fw"
            ><font-awesome-icon :icon="['fas', 'heart']"
          /></span>
          <span class="text-lg ml-5">알림</span>
        </div>
        <div class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full">
          <span class="text-2xl fa-fw"
            ><font-awesome-icon :icon="['fas', 'cat']"
          /></span>
          <span class="text-lg ml-5">쪽지</span>
        </div>
        <div class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full">
          <span class="text-2xl fa-fw"
            ><font-awesome-icon :icon="['fas', 'dog']"
          /></span>
          <span class="text-lg ml-5">북마크</span>
        </div>
        <div class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full">
          <span class="text-2xl fa-fw"
            ><font-awesome-icon :icon="['fas', 'cow']"
          /></span>
          <span class="text-lg ml-5">리스트</span>
        </div>
        <div class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full">
          <span class="text-2xl fa-fw"
            ><font-awesome-icon :icon="['fas', 'horse']"
          /></span>
          <span class="text-lg ml-5">프로필</span>
        </div>
        <div class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full">
          <span class="text-2xl fa-fw"
            ><font-awesome-icon :icon="['fas', 'fa-ellipsis-h']"
          /></span>
          <span class="text-lg ml-5">더보기</span>
        </div>
      </div>
      <div class="w-full lg:pr-3 pr-3">
        <button
          class="bg-primary text-white w-full h-12 rounded-full hover:bg-dark"
        >
          <span class="hidden lg:inline-block">twit</span>
          <font-awesome-icon :icon="['fas', 'fa-plus']" class="lg:hidden" />
        </button>
      </div>
    </div>
  </div>
  <!-- sidebar 아래 -->
  <div>
    <div class="mb-3 mr-3">
      <button
        class="
          text-black
          w-full
          h-12
          rounded-full
          hover:bg-dark
          px-2
          py-1
          flex
          item-center
          lg:flex
          hidden
          mb-3
        "
      >
        <img src="http://picsum.photos/100" class="w-10 h-10 rounded-full" />
        <div class="lg:ml-2 hidden lg:block">
          <div class="text-sm font-bold">hyemin</div>
          <div class="text-xs">@hyemin</div>
        </div>
        <img
          src="http://picsum.photos/100"
          class="
            lg:ml-auto lg:block lg:w-10 lg:h-10
            hidden
            rounded-full
            text-xs
          "
        />
      </button>
      <div class="lg:hidden flex justify-center">
        <img
          src="http://picsum.photos/100"
          class="w-10 h-10 rounded-full text-xs cursor-pointer hover:opacity-80"
        />
      </div>
    </div>
  </div>
</template>