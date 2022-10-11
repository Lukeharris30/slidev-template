<template>
    <div>
        <SramNotice :title="heading" :content="content"/>
    </div>
</template>

<script setup>
import {SramNotice} from "@sramplm/sram-ui"
const props = defineProps({
    heading: '',
    content: ''
})

</script>

<style lang="scss" scoped>

</style>