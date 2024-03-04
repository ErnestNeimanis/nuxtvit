<script setup lang="ts">
import axios from 'axios'

const d = ref<null | any>(null)

async function testax(){
    const r = await axios.get("/api/app")
    
    d.value = r.data
}
testax()
</script>

<template>
    <div>
        about
        <div v-if="d" >
{{ d }}
        </div>
    </div>
</template>