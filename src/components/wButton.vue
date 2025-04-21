<script setup lang="ts">

</script>

<template>
    <button :class="['wButton',variantClass,]">Button</button>
</template>

<style scoped lang="scss">
    .wButton {
        background-color: var(--color-bg-primary);
        color: var(--color-content-on-primary);
        display: flex;
        padding: 0px 12px;
        justify-content: center;
        align-items: center;
        gap: 8px;
        height: 32px;
        border-radius: 6px;
        font-family: "Roboto", sans-serif;
        font-size: 14px;
        font-size: 14px;
        font-style: normal;
        font-weight: 400;
        line-height: 22px;
    }
    .wButton--primary {
        background-color: var(--color-bg-primary);
        color: var(--color-content-on-primary);
    }
    .wButton--secondary {
        background-color: var(--color-bg-white);
        color: var(--color-content-on-bright);
        border: 1px solid var(--color-border-neutral-light);
    }
</style>