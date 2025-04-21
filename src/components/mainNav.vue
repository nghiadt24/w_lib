<script setup>
    import logo from '@/assets/svg/logo.svg';
</script>
<template>
    <nav class="mainNav">
        <div class="container flex mx-auto justify-between items-center py-2"> 
            <div class="col-6">
                <a href="/" class="logo">
                    <img :src="logo" alt="Logo" />
                </a>
            </div>
            <div class="col-6 ">
                <div class="navList flex justify-end flex-row">
                    <a href="#" class="navItem">
                        Foundation
                    </a>
                    <a href="#" class="navItem">
                        Components
                    </a>
                    <a href="#" class="navItem">
                        Release Notes
                    </a>
                    <a href="#" class="navItem">
                        Resources
                    </a>
                </div>
            </div>
        </div>
    </nav>
</template>

<style scoped lang="scss">
.navList {
    gap: 16px;
}
.navItem {
    padding: 8px 16px;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 8px;
}
</style>
