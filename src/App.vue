<template>
  <div class="flex h-screen">
    <div class="w-1/4  pt-5 ml-5 flex flex-col justify-between border-r border-gray-200">
      <!-- sidebar 위 -->  
      <div>
        <!--logo icon-->
        <div class="text-3xl text-primary ml-4 mb-3"><font-awesome-icon icon="fa-solid fa-user-secret" /></div>
        <!--sidemenu icons-->  
        <div class="flex flex-col items-start space-y-1">
            <div class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full">
              <span class="text-2xl fa-fw"><font-awesome-icon icon="fa-solid fa-user-secret" /></span>
              <span class="text-lg ml-5">홈</span>
            </div>
            <div class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full">
              <span class="text-2xl fa-fw"><font-awesome-icon icon="fa-solid fa-user-secret" /></span>
              <span class="text-lg ml-5">탐색하기</span>
            </div>
            <div class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full">
              <span class="text-2xl fa-fw"><font-awesome-icon icon="fa-solid fa-user-secret" /></span>
              <span class="text-lg ml-5">알림</span>
            </div>
            <div class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full">
              <span class="text-2xl fa-fw"><font-awesome-icon icon="fa-solid fa-user-secret" /></span>
              <span class="text-lg ml-5">쪽지</span>
            </div>
            <div class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full">
              <span class="text-2xl fa-fw"><font-awesome-icon icon="fa-solid fa-user-secret" /></span>
              <span class="text-lg ml-5">북마크</span>
            </div>
            <div class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full">
              <span class="text-2xl fa-fw"><font-awesome-icon icon="fa-solid fa-user-secret" /></span>
              <span class="text-lg ml-5">리스트</span>
            </div>
            <div class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full">
              <span class="text-2xl fa-fw"><font-awesome-icon icon="fa-solid fa-user-secret" /></span>
              <span class="text-lg ml-5">프로필</span>
            </div>
            <div class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full">
              <span class="text-2xl fa-fw"><font-awesome-icon icon="fa-solid fa-user-secret" /></span>
              <span class="text-lg ml-5">더보기</span>
            </div>
        </div>
        <div class = "mr-3 mt-3">
          <button class="bg-primary text-white w-full h-12 rounded-full hover:bg-dark">Tweet</button>
        </div>
      </div>
      <!-- sidebar 아래 -->
      <div>
        <div class = "mr-3 mb-3">
          <button class="text-black w-full h-12 rounded-full hover:bg-dark px-2 py-1 flex item-center">
            <img src="http://picsum.photos/100" class="w-10 h-10 rounded-full"/>
            <div class="ml-2">
              <div class="text-sm font-bold">hyemin</div>
              <div class="text-xs">@hyemin</div>
            </div>
            <img src="http://picsum.photos/100" class="ml-auto w-10 h-10 rounded-full text-xs"/>
          </button>
        </div>
      </div>
    </div>
      <div class="flex-1"></div>

  </div>
</template>

<script>

export default {
}
</script>

<style>

</style>
