<script setup>
import { ref } from 'vue';
const num = ref(2);
function clickMe() {
    num.value++
}
</script>

<template>
    <div>
        {{ num }} <!-- 會使用2個大括號來定義值 -->
        <button type="button" v-on:click="clickMe">點我</button>
    </div>
</template>