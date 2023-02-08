<template>
    <a 
    :href="href" 
    target="_blank" 
    class="ml-3 px-3 py-2 rounded border-2 border-transparent text-white bg-indigo-500 hover:bg-indigo-500 transition-colors">
    
        <slot>View Original Source</slot>
    </a>
</template>

<script setup>
const props = defineProps({
    href: String
})
</script>