<script setup lang="ts">
    import { ref } from 'vue'
    const v = ref('hello world')

    let t = ref('hello vue')
</script>

<template>
    <div>
        <div>
            {{v}}
        </div>
    </div>
</template>

<style lang="scss" scoped>

</style>