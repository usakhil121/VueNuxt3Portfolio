<template>
    <div>
        
        this is about page
    </div>
    <div>
        <button @click="enableCustomLayout">Update the layout</button>
    </div>
</template>

<script setup>
 function enableCustomLayout(){
    setPageLayout('another')
 }


    useHead({
        title:'about'
    })

</script>