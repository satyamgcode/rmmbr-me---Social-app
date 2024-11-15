<script setup>
import tree from '~/assets/images/tree.png'
</script>

<template>
<div class="bg-black text-white h-screen">
<div>
    <img :src="tree" alt="" class="h-44 w-[434px]">
    <p></p>
</div>
<div>
    <slot></slot>
</div>
</div>
</template>