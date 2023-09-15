<template>
    <div class="bg-black text-white p-5">
        tailwindu樣板
        <img :src="getImagesAssetsFileURL('vite.png')" alt="">
    </div>
</template>
<script setup lang="ts">
import useUtil from '~~/composables/util';
const { getImagesAssetsFileURL } = useUtil()
</script>