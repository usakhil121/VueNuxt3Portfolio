<template>
    <div>
        this is a content page
    </div>
    <div>
        post id is {{ route.params.id }} 
    </div>
</template>

<script setup>
const route = useRoute()
</script>