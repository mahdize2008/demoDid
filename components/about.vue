<template>
    <!-- START-ABOUT-US -->
    <div class="bg-natural-alpha pb-between-section" :class="!ltr ? 'py-between-section !mb-0':''">
        <div class="container 2xl:px-28 xl:px-20 lg:px-16">
            <div class="flex flex-wrap items-center xl:-m-6 lg:-m-4">
                <div class="xl:w-[47%] w-full xl:p-6 lg:p-4 max-lg:mb-5">
                    <div class="header-section">
                        <h2 class="header-title-public">
                            <!-- درباره ما بیشتر بدانید -->
                            {{ title }}
                        </h2>
                        <h4 class="header-subtitle-public">
                            <!-- از سال 1390 همراه شما هستیم -->
                            {{ subtitle }}
                        </h4>
                    </div>
                    <p class="text-public lg:mb-10 mb-4">
                        {{ text }}
                    </p>
                    <div class="flex flex-wrap sm:items-center">
                        <a href="#" class="btn-public btn-modern lg:me-10 me-4 max-sm:my-4">
                            {{ btnTitle }}
                            <i class="icon-left-arrow"></i>
                        </a>
                        <a href="#" v-if="videoTitle" class="lg:text-base text-sm text-dark font-semibold flex items-center py-1">
                            <i class="icon-film-reel lg:text-lg text-md text-primary lg:me-4 me-2.5"></i>
                            {{ videoTitle }}
                        </a>
                    </div>
                </div>
                <div class="xl:w-[53%] w-full xl:p-6 lg:p-4" :class="ltr ? '-order-1' : ''">
                    <a href=""
                        class="block lg:p-4 p-3 border-natural group border-3 rounded-xl w-full overflow-hidden relative">
                        <img src="~/assets/img/picture-2.png" class="rounded-2xl w-full" alt=""><!-- :src="videoSRC" -->
                        <div href="#" class="absolute top-1/2 start-1/2 -translate-y-1/2 translate-x-1/2 ">
                            <div
                                class="play-button relative w-[68px] h-[68px] rounded-full bg-light/30 text-white group-hover:bg-white group-hover:text-dark transition-all duration-500 flex items-center justify-center z-20">
                                <i class="icon-play text-3xl"></i>
                                <span></span>
                            </div>
                        </div>
                    </a>
                </div>
            </div>
        </div>
    </div>
    <!-- END-ABOUT-US -->
</template>

<script setup>
let { title, subtitle, text, videoTitle, btnTitle, videoSRC , ltr } = defineProps(['title', 'subtitle', 'text', 'videoTitle', 'btnTitle', 'videoSRC','ltr'])
</script>