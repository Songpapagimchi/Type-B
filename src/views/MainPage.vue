<template>
        <div class="flex w-full h-3/4 justify-center items-top mt-10">
            <div class="w-full max-w-xs rounded-lg shadow-lg bg-whites-300">
                    <div class="text-lg font-bold px-5">B타입 성향질문을 시작합니다.<br>클릭하세요!</div>
                    <div class="px-5 py-5">
                        <router-link to="/LikertQuestion">
                        <button class="flex h-48 w-full max-w-xs bg-yellow-500 hover:bg-yellow-700 justify-center items-center text-white font-bold rounded-xl">
                            B타입(그림한개,5개척도 답변)</button>
                        </router-link>
                    </div>
   
            </div>
                <!-- <h1 class="font-bold text-xl text-center text-gray-600"> -->
                <!-- <LikertQuestion /> -->
        </div>
</template>
<script setup>
    import QuestionList from '../components/QuestionList.vue'
    import LikertQuestion from '../components/LikertQuestion.vue'
    import VehicleQuestion from '../components/VehicleQuestion.vue'
    
</script>