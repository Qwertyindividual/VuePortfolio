<template>
    <div>
     <AnimatedBackground3 />
    </div>
</template>

<script>

import AnimatedBackground3 from '@/components/AnimatedBackground3.vue'
import AOS from 'aos'

    export default {
        components: {
            AnimatedBackground3
        },
        mounted() {
        AOS.init();
  }
    }
</script>

<style scoped>


</style>