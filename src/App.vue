<template>
    <div>
        <icon :data="vueSvg" original></icon>
    </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue'
import vueSvg from './assets/svg-icon/vue.svg'

export default defineComponent({
    name: 'App',
    data() {
        return {
            vueSvg
        }
    }
})
</script>