<template>
        <button v-bind="$attrs">
            <slot />
        </button>
</template>
<script lang="ts">
    export default {
        inheritAttrs:false
    }
</script>