<template>
    <div>
        <SramDocumentTemplate :manual="publication"/>
    </div>
</template>

<script setup>
import {SramDocumentTemplate} from '@sramplm/sram-ui'
import data from '../data/publication.json'

const publication = data
</script>

<style lang="scss" >

</style>