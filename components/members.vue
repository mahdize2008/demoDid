<template>
<!-- START-MEMBERS -->
<div class="py-between-section bg-natural-alpha">
            <div class="container 2xl:px-28 xl:px-20 lg:px-16">
                
                <PublicHeaderSection title="معرفی اعضاء مجموعه ما" subtitle="همه در کنار هم برای یک هدف مشترک"/>
                
                <!-- <div class="swiper swiper-container swiper-members"> -->
                    <Swiper :slides-per-view="4" :space-between="30" :pagination="{el:'.swiper-pagination-members',clickable:'true'}" :modules="[SwiperPagination]" class="max-lg:overflow-visible">
                        <SwiperSlide class="max-lg:w-[200px]">
                            <div
                                class="bg-white group hover:shadow-lighter-hover transition-all rounded-xl xl:p-8 lg:p-6 p-4 !pt-0 xl:mt-20 mt-[65px] flex flex-col items-center">
                                <div
                                    class="block xl:w-[160px] w-[130px] xl:h-[160px] h-[130px] xl:border-10 border-8 border-dark-alpha group-hover:border-primary transition-all rounded-full overflow-hidden mb-6 xl:-mt-20 -mt-[65px]">
                                    <img src="~/assets/img/picture-6.png" class="w-full h-full" alt="">
                                </div>
                                <h3 class="title-public mb-0">
                                    نعیم علیمردانی
                                </h3>
                                <span class="lg:text-2base text-sm font-medium text-dark block lg:mb-8 mb-5">
                                    تولید محتوا
                                </span>
                                <ul class="flex items-center">
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-instagram lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-twitter lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-linkedin lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[200px]">
                            <div
                                class="bg-white group hover:shadow-lighter-hover transition-all rounded-xl xl:p-8 lg:p-6 p-4 !pt-0 xl:mt-20 mt-[65px] flex flex-col items-center">
                                <div
                                    class="block xl:w-[160px] w-[130px] xl:h-[160px] h-[130px] xl:border-10 border-8 border-dark-alpha group-hover:border-primary transition-all rounded-full overflow-hidden mb-6 xl:-mt-20 -mt-[65px]">
                                    <img src="~/assets/img/picture-7.png" class="w-full h-full" alt="">
                                </div>
                                <h3 class="title-public mb-0">
                                    نعیم علیمردانی
                                </h3>
                                <span class="lg:text-2base text-sm font-medium text-dark block lg:mb-8 mb-5">
                                    تولید محتوا
                                </span>
                                <ul class="flex items-center">
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-instagram lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-twitter lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-linkedin lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[200px]">
                            <div
                                class="bg-white group hover:shadow-lighter-hover transition-all rounded-xl xl:p-8 lg:p-6 p-4 !pt-0 xl:mt-20 mt-[65px] flex flex-col items-center">
                                <div
                                    class="block xl:w-[160px] w-[130px] xl:h-[160px] h-[130px] xl:border-10 border-8 border-dark-alpha group-hover:border-primary transition-all rounded-full overflow-hidden mb-6 xl:-mt-20 -mt-[65px]">
                                    <img src="~/assets/img/picture-8.png" class="w-full h-full" alt="">
                                </div>
                                <h3 class="title-public mb-0">
                                    نعیم علیمردانی
                                </h3>
                                <span class="lg:text-2base text-sm font-medium text-dark block lg:mb-8 mb-5">
                                    تولید محتوا
                                </span>
                                <ul class="flex items-center">
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-instagram lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-twitter lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-linkedin lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[200px]">
                            <div
                                class="bg-white group hover:shadow-lighter-hover transition-all rounded-xl xl:p-8 lg:p-6 p-4 !pt-0 xl:mt-20 mt-[65px] flex flex-col items-center">
                                <div
                                    class="block xl:w-[160px] w-[130px] xl:h-[160px] h-[130px] xl:border-10 border-8 border-dark-alpha group-hover:border-primary transition-all rounded-full overflow-hidden mb-6 xl:-mt-20 -mt-[65px]">
                                    <img src="~/assets/img/picture-9.png" class="w-full h-full" alt="">
                                </div>
                                <h3 class="title-public mb-0">
                                    نعیم علیمردانی
                                </h3>
                                <span class="lg:text-2base text-sm font-medium text-dark block lg:mb-8 mb-5">
                                    تولید محتوا
                                </span>
                                <ul class="flex items-center">
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-instagram lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-twitter lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-linkedin lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[200px]">
                            <div
                                class="bg-white group hover:shadow-lighter-hover transition-all rounded-xl xl:p-8 lg:p-6 p-4 !pt-0 xl:mt-20 mt-[65px] flex flex-col items-center">
                                <div
                                    class="block xl:w-[160px] w-[130px] xl:h-[160px] h-[130px] xl:border-10 border-8 border-dark-alpha group-hover:border-primary transition-all rounded-full overflow-hidden mb-6 xl:-mt-20 -mt-[65px]">
                                    <img src="~/assets/img/picture-6.png" class="w-full h-full" alt="">
                                </div>
                                <h3 class="title-public mb-0">
                                    نعیم علیمردانی
                                </h3>
                                <span class="lg:text-2base text-sm font-medium text-dark block lg:mb-8 mb-5">
                                    تولید محتوا
                                </span>
                                <ul class="flex items-center">
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-instagram lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-twitter lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-linkedin lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[200px]">
                            <div
                                class="bg-white group hover:shadow-lighter-hover transition-all rounded-xl xl:p-8 lg:p-6 p-4 !pt-0 xl:mt-20 mt-[65px] flex flex-col items-center">
                                <div
                                    class="block xl:w-[160px] w-[130px] xl:h-[160px] h-[130px] xl:border-10 border-8 border-dark-alpha group-hover:border-primary transition-all rounded-full overflow-hidden mb-6 xl:-mt-20 -mt-[65px]">
                                    <img src="~/assets/img/picture-7.png" class="w-full h-full" alt="">
                                </div>
                                <h3 class="title-public mb-0">
                                    نعیم علیمردانی
                                </h3>
                                <span class="lg:text-2base text-sm font-medium text-dark block lg:mb-8 mb-5">
                                    تولید محتوا
                                </span>
                                <ul class="flex items-center">
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-instagram lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-twitter lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-linkedin lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[200px]">
                            <div
                                class="bg-white group hover:shadow-lighter-hover transition-all rounded-xl xl:p-8 lg:p-6 p-4 !pt-0 xl:mt-20 mt-[65px] flex flex-col items-center">
                                <div
                                    class="block xl:w-[160px] w-[130px] xl:h-[160px] h-[130px] xl:border-10 border-8 border-dark-alpha group-hover:border-primary transition-all rounded-full overflow-hidden mb-6 xl:-mt-20 -mt-[65px]">
                                    <img src="~/assets/img/picture-8.png" class="w-full h-full" alt="">
                                </div>
                                <h3 class="title-public mb-0">
                                    نعیم علیمردانی
                                </h3>
                                <span class="lg:text-2base text-sm font-medium text-dark block lg:mb-8 mb-5">
                                    تولید محتوا
                                </span>
                                <ul class="flex items-center">
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-instagram lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-twitter lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                    <li class="lg:me-8 me-6 last:me-0">
                                        <a href="#" class="hover:text-primary text-light transition-all">
                                            <i class="icon-linkedin lg:text-5xl text-2xl"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>
                        </SwiperSlide>
                    </Swiper>
                <!-- </div> -->
                <div class="swiper-paginations swiper-pagination-members"></div>
            </div>
        </div>
        <!-- END-MEMBERS -->
</template>