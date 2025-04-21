<script setup>
    import wButton from '@/components/wButton.vue';
</script>

<template>
    <section class="heroSection">
        <div class="container flex mx-auto justify-between items-center py-2">
            <div class="grid grid-cols-12">
                <div class="col-span-4 heroTitleWrap">
                    <h1 class="heroTitle">Design. Develop. Deliver.</h1>
                    <p class="heroSubtitle">A comprehensive design system built for teams creating sales-focused websites and landing pages on Webcake. By streamlining design and development workflows, it helps you move faster from concept to conversion — without sacrificing visual consistency or scalability.</p>
                    <div class="heroButtons flex gap-4">
                        <wButton variant="wButton-secondary">Get Started</wButton>
                        <wButton>Documentation</wButton>
                    </div>
                </div>
                <div class="col-span-8 heroImageWrap">
                    <img src="https://content.pancake.vn/web-media/af/c7/35/46/08b7df5b5ec6c5ae0d5b25b53b1a9746ca6e4912f901a752dbe50a4f-w:1249-h:587-l:234972-t:image/png.png" alt="Hero Image" class="heroImage" />
                </div>
            </div> 
        </div>
    </section>
</template>

<style scoped lang="scss">
    .heroSection {
        height: 100vh;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background-attachment: fixed;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        background-image: url('https://content.pancake.vn/web-media/51/55/70/1b/7437112d6089dd92a939647695871a34f9aea19eee4b54c4f8a95181-w:1920-h:1080-l:106046-t:image/png.png');
    }
    .heroTitleWrap {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: flex-start;
        gap: 16px;
        padding-bottom: 64px;
    }
    .heroTitle {
        font-family: Roboto;
        font-size: 48px;
        font-style: normal;
        font-weight: 600;
        line-height: 64px;
        color: var(----color-content-on-bright, #474747);
    }
    .heroSubtitle {
        font-family: Roboto;
        font-size: 20px;
        font-style: normal;
        font-weight: 400;
        line-height: 32px;
        color: var(----color-content-neutral-light, #6D6D6D);
    }
</style>