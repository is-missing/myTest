<template>
    <div>
        这是bb组件
    </div>
</template>

<script setup>
import { ref, reactive, toRefs } from 'vue'
import { useRoute, useRouter } from 'vue-router';
const router = useRouter()
const route = useRoute()
const data = reactive({

})
</script>

<style scoped></style>