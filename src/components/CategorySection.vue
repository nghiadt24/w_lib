<script setup lang="ts">
    import wButton from '@/components/wButton.vue';
</script>

<template>
    <section class="CategrorySection">
        <div class="container CategroryContainer">
            <div class="CategroryItemWrapper grid grid-cols-12">
                <div class="CategroryItem col-span-6">
                    <img src="https://content.pancake.vn/web-media/cf/ea/18/93/6de76844b44b62ece0aeb80c2de9dc8cc3016d2e18ae9f9efaefc8a9-w:780-h:202-l:9236-t:image/png.png" alt="Category Image" class="CategroryImage" />
                    <div class="CategroryContent">
                        <h2 class="CategroryTitle">Branding</h2>
                        <wButton>Get Started</wButton>
                    </div>
                </div>
                <div class="CategroryItem col-span-6">
                    <img src="https://content.pancake.vn/web-media/d8/41/4d/a5/a61176ebf91279c8aba6bdf96eba37befc8efc5253c61bb2043351eb-w:780-h:202-l:6808-t:image/png.png" alt="Category Image" class="CategroryImage" />
                    <div class="CategroryContent">
                        <h2 class="CategroryTitle">Foundation</h2>
                        <wButton>Get Started</wButton>
                    </div>
                </div>
            </div>
            <div class="CategroryItemWrapper grid grid-cols-12">
                <div class="CategroryItem col-span-6">
                    <img src="https://content.pancake.vn/web-media/9f/f2/a9/af/94040ad04fa944a3150819644998991293160b81e0faae76f75cacd7-w:780-h:202-l:5654-t:image/png.png" alt="Category Image" class="CategroryImage" />
                    <div class="CategroryContent">
                        <h2 class="CategroryTitle">Components</h2>
                        <wButton>Get Started</wButton>
                    </div>
                </div>
                <div class="CategroryItem col-span-6">
                    <img src="https://content.pancake.vn/web-media/51/e4/a3/c9/b18d27d411d5d1273fa1f4e8df38ccc43399aeef1a3469a38709a1bd-w:780-h:202-l:10066-t:image/png.png" alt="Category Image" class="CategroryImage" />
                    <div class="CategroryContent">
                        <h2 class="CategroryTitle">Resources</h2>
                        <wButton>Get Started</wButton>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
    .CategrorySection {
        background-color: var(--color-bg-white);
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .CategroryContainer {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 24px;
    }
    .CategroryItemWrapper {
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        gap: 24px;
    }
    .CategroryItem {
        display: flex;
        padding: 24px;
        flex-direction: column;
        align-items: flex-start;
        gap: 16px;
        border-radius: 12px;
        border: 1px solid var(--color-border-neutral-light, #E3E3E3);
        background: var(--color-bg-neutral-light, #F6F6F6);
    }
    .CategroryContent {
        align-self: stretch;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-between;
    }
    .CategroryTitle {
        font-family: Roboto;
        font-size: 20px;
        font-style: normal;
        font-weight: 700;
        line-height: 24px;
        color: var(--color-content-on-bright, #474747);
    }
</style>