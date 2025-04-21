<script setup>
    import logo from '@/assets/svg/logo.svg';
    import Input from '@/components/Input.vue';
    import wButton from '@/components/wButton.vue';
      window.addEventListener('scroll', () => {
        const nav = document.querySelector('.mainNav');
        if (window.scrollY > 20) {
            nav.classList.add('scrolled');
        } else {
            nav.classList.remove('scrolled');
        }
    });

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
                    <Input />
                    <wButton>Visit Webcake</wButton>
                </div>
            </div>
        </div>
    </nav>
</template>

<style scoped lang="scss">
.mainNav {
    background-color: transparent;
    transition: background-color 0.5s ease-in-out;
}
.mainNav.scrolled {
    background-color: var(--color-bg-white);
}
.navList {
    gap: 16px;
    justify-content: center;
    align-items: center;
}
.navItem {
    padding: 8px 16px;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 8px;
    font-family: "Roboto", sans-serif;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 22px;
    color: var(--color-content-neutral-medium);
}
</style>
