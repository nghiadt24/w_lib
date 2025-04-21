<script setup lang="ts">
    import "@phosphor-icons/web/regular";
</script>

<template>
    <div class="InputSearch">
        <i class="ph ph-magnifying-glass"></i>
        <input class="wInput" type="text" placeholder="Search..">
    </div>
</template>

<style scoped lang="scss">
    // @import '@/style/color.css';
    .InputSearch {
        position: relative;
        // max-width: 240px;
    }
    .InputSearch i {
        position: absolute;
        top: 50%;
        left: 12px;
        transform: translateY(-50%);
        color: var(--color-icon-gray);
        font-size: 16px;
        pointer-events: none;
    }
    .wInput {
        background-color: var(--color-bg-white);
        border: 1px solid var(--color-border-neutral-light);
        height: 32px;
        padding: 10px 12px 10px 36px;
        border-radius: 6px;
        width: 100%;
        &:hover {
            border: 1px solid var(--color-border-primary);
            transition: ease-in-out 0.5s
        }
        &:focus {
            border: 1px solid var(--color-border-primary);
            outline: none;
            box-shadow: 0px 0px 0px 2px rgba(36, 135, 103, 0.15);
            transition: ease-in-out 0.5s
        }
    }
</style>