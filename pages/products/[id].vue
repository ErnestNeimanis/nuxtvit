<script setup>
definePageMeta({
    layout: 'products'
})
const route = useRoute()
const params = ref(route.params)
</script>

<template>
<div>
   this is  {{ params }}
</div>

</template>
