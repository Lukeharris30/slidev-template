<template>
    <div>
        <SramButton @click="counter++">{{label}}</SramButton>
        {{counter}}
    </div>
</template>

<script setup>
import {ref} from 'vue'
import {SramButton} from '@sramplm/sram-ui'
const counter = ref(0);
const props = defineProps({
    label: ''
})
</script>

<style lang="scss" scoped>

</style>