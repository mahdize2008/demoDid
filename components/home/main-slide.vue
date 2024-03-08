<template>
    <!-- START-MAIN-SLIDER -->
    <div class="pt-8 bg-natural-alpha">
        <div class="container">
            <Swiper :navigation="{prevEl:'.swiper-prev-services',nextEl:'.swiper-next-services'}" :modules="[SwiperNavigation]" :slides-per-view="1"
                class="relative lg:rounded-3xl rounded-xl overflow-hidden">
                <!-- <div class="swiper-wrapper"> -->
                <SwiperSlide>
                    <div class="lg:h-[380px] h-[280px] lg:p-14 p-6 flex items-center bg-gradient-dark">
                        <img src="~/assets/img/picture-1.png" class="absolute top-0 end-0 w-full h-full -z-10" alt="">
                        <div class="relative z-20">
                            <div class="header-section">
                                <h2 class="header-title-public header-title-public-white">
                                    الفبای توسعه کسب و کار شما
                                </h2>
                                <h4 class="header-subtitle-public header-subtitle-public-white">
                                    ارائه دهنده برترین خدمات طراحی وبسایت
                                </h4>
                            </div>
                            <a href="#" class="btn-public btn-secondary lg:px-12 px-8">
                                مشاهده خدمات
                            </a>
                        </div>
                    </div>
                </SwiperSlide>
                <SwiperSlide>
                    <div class="lg:h-[380px] h-[280px] lg:p-14 p-6 flex items-center bg-gradient-dark">
                        <img src="~/assets/img/picture-2.png" class="absolute top-0 end-0 w-full h-full -z-10" alt="">
                        <div class="relative z-20">
                            <div class="header-section">
                                <h2 class="header-title-public header-title-public-white">
                                    الفبای توسعه کسب و کار شما
                                </h2>
                                <h4 class="header-subtitle-public header-subtitle-public-white">
                                    ارائه دهنده برترین خدمات طراحی وبسایت
                                </h4>
                            </div>
                            <a href="#" class="btn-public btn-secondary lg:px-12 px-8">
                                مشاهده خدمات
                            </a>
                        </div>
                    </div>
                </SwiperSlide>
                <SwiperSlide>
                    <div class="lg:h-[380px] h-[280px] lg:p-14 p-6 flex items-center bg-gradient-dark">
                        <img src="~/assets/img/picture-2.png" class="absolute top-0 end-0 w-full h-full -z-10" alt="">
                        <div class="relative z-20">
                            <div class="header-section">
                                <h2 class="header-title-public header-title-public-white">
                                    الفبای توسعه کسب و کار شما
                                </h2>
                                <h4 class="header-subtitle-public header-subtitle-public-white">
                                    ارائه دهنده برترین خدمات طراحی وبسایت
                                </h4>
                            </div>
                            <a href="#" class="btn-public btn-secondary lg:px-12 px-8">
                                مشاهده خدمات
                            </a>
                        </div>
                    </div>
                </SwiperSlide>
                <!-- </div> -->
                <div class="absolute end-14 top-1/2 -translate-y-1/2 rounded-xl overflow-hidden z-20 max-lg:hidden">
                    <div
                        class="swiper-next-services w-[50px] h-16 bg-white flex items-center justify-center text-dark font-bold cursor-pointer [&.swiper-button-disabled]:text-light/80 border-b border-natural">
                        <i class="icon-up"></i>
                    </div>
                    <div
                        class="swiper-prev-services w-[50px] h-16 bg-white flex items-center justify-center text-dark font-bold cursor-pointer [&.swiper-button-disabled]:text-light/80">
                        <i class="icon-down"></i>
                    </div>
                </div>
            </Swiper>
        </div>
    </div>
    <!-- END-MAIN-SLIDER -->
</template>
