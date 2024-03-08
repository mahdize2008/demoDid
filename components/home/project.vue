<template>
<!-- START-PROJECT -->
<div class="pt-between-section">
            <div class="container 2xl:px-28 xl:px-20 lg:px-16 flex flex-wrap items-center">
                
                <PublicHeaderSection title="معرفی پروژه های استودیو" subtitle="کیفیت را به همه چیز ترجیح میدهیم" link="مشاهده آرشیو"/>
                
                
                <!-- <div class="swiper swiper-container swiper-project"> -->
                    <Swiper :slides-per-view="1" :pagination="{el:'.swiper-pagination-project',clickable:'true'}" :modules="[SwiperPagination]" class="lg:h-[600px] h-[500px]">
                        <SwiperSlide>
                            <div class="flex flex-wrap items-start h-full">
                                <div class="lg:h-full h-1/2 lg:w-1/2 w-full flex flex-wrap">
                                    <a href="#" class="block group h-1/2 w-1/2 relative swiper-project-item transition-all">
                                        <img src="~/assets/img/picture-4.png" class="w-full h-full object-cover" alt="">
                                        <div
                                            class="header-title-public absolute top-0 start-0 text-white bg-dark/50 w-full h-0 transition-all duration-500 flex flex-col items-center justify-center opacity-0 group-hover:opacity-100 group-hover:h-full z-10">
                                            پروژه 1
                                            <i class="icon-add text-white font-normal lg:text-12xl text-7xl mt-4"></i>
                                        </div>
                                    </a>
                                    <a href="#" class="block h-1/2 w-1/2 relative swiper-project-item transition-all group">
                                        <img src="~/assets/img/picture-5.png" class="w-full h-full object-cover" alt="">
                                        <div
                                            class="header-title-public absolute top-0 start-0 text-white bg-dark/50 w-full h-0 transition-all duration-500 flex flex-col items-center justify-center opacity-0 group-hover:opacity-100 group-hover:h-full z-10">
                                            پروژه 1
                                            <i class="icon-add text-white font-normal lg:text-12xl text-7xl mt-4"></i>
                                        </div>
                                    </a>
                                    <a href="#"
                                        class="block h-1/2 w-full relative swiper-project-item transition-all group max-lg:-order-1">
                                        <img src="~/assets/img/picture-3.png" class="w-full h-full object-cover" alt="">
                                        <div
                                            class="header-title-public absolute top-0 start-0 text-white bg-dark/50 w-full h-0 transition-all duration-500 flex flex-col items-center justify-center opacity-0 group-hover:opacity-100 group-hover:h-full z-10">
                                            پروژه 1
                                            <i class="icon-add text-white font-normal lg:text-12xl text-7xl mt-4"></i>
                                        </div>
                                    </a>
                                </div>
                                <a href="#"
                                    class="block lg:h-full h-1/2 lg:w-1/2 w-full relative swiper-project-item transition-all group">
                                    <img src="~/assets/img/picture-3.png" class="w-full h-full object-cover" alt="">
                                    <div
                                        class="header-title-public absolute top-0 start-0 text-white bg-dark/50 w-full h-0 transition-all duration-500 flex flex-col items-center justify-center opacity-0 group-hover:opacity-100 group-hover:h-full z-10">
                                        پروژه 1
                                        <i class="icon-add text-white font-normal lg:text-12xl text-7xl mt-4"></i>
                                    </div>
                                </a>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide>
                            <div class="flex flex-wrap items-start h-full">
                                <div class="lg:h-full h-1/2 lg:w-1/2 w-full flex flex-wrap">
                                    <a href="#" class="block group h-1/2 w-1/2 relative swiper-project-item transition-all">
                                        <img src="~/assets/img/picture-4.png" class="w-full h-full object-cover" alt="">
                                        <div
                                            class="header-title-public absolute top-0 start-0 text-white bg-dark/50 w-full h-0 transition-all duration-500 flex flex-col items-center justify-center opacity-0 group-hover:opacity-100 group-hover:h-full z-10">
                                            پروژه 1
                                            <i class="icon-add text-white font-normal lg:text-12xl text-7xl mt-4"></i>
                                        </div>
                                    </a>
                                    <a href="#" class="block h-1/2 w-1/2 relative swiper-project-item transition-all group">
                                        <img src="~/assets/img/picture-5.png" class="w-full h-full object-cover" alt="">
                                        <div
                                            class="header-title-public absolute top-0 start-0 text-white bg-dark/50 w-full h-0 transition-all duration-500 flex flex-col items-center justify-center opacity-0 group-hover:opacity-100 group-hover:h-full z-10">
                                            پروژه 1
                                            <i class="icon-add text-white font-normal lg:text-12xl text-7xl mt-4"></i>
                                        </div>
                                    </a>
                                    <a href="#"
                                        class="block h-1/2 w-full relative swiper-project-item transition-all group max-lg:-order-1">
                                        <img src="~/assets/img/picture-3.png" class="w-full h-full object-cover" alt="">
                                        <div
                                            class="header-title-public absolute top-0 start-0 text-white bg-dark/50 w-full h-0 transition-all duration-500 flex flex-col items-center justify-center opacity-0 group-hover:opacity-100 group-hover:h-full z-10">
                                            پروژه 1
                                            <i class="icon-add text-white font-normal lg:text-12xl text-7xl mt-4"></i>
                                        </div>
                                    </a>
                                </div>
                                <a href="#"
                                    class="block lg:h-full h-1/2 lg:w-1/2 w-full relative swiper-project-item transition-all group">
                                    <img src="~/assets/img/picture-3.png" class="w-full h-full object-cover" alt="">
                                    <div
                                        class="header-title-public absolute top-0 start-0 text-white bg-dark/50 w-full h-0 transition-all duration-500 flex flex-col items-center justify-center opacity-0 group-hover:opacity-100 group-hover:h-full z-10">
                                        پروژه 1
                                        <i class="icon-add text-white font-normal lg:text-12xl text-7xl mt-4"></i>
                                    </div>
                                </a>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide>
                            <div class="flex flex-wrap items-start h-full">
                                <div class="lg:h-full h-1/2 lg:w-1/2 w-full flex flex-wrap">
                                    <a href="#" class="block group h-1/2 w-1/2 relative swiper-project-item transition-all">
                                        <img src="~/assets/img/picture-4.png" class="w-full h-full object-cover" alt="">
                                        <div
                                            class="header-title-public absolute top-0 start-0 text-white bg-dark/50 w-full h-0 transition-all duration-500 flex flex-col items-center justify-center opacity-0 group-hover:opacity-100 group-hover:h-full z-10">
                                            پروژه 1
                                            <i class="icon-add text-white font-normal lg:text-12xl text-7xl mt-4"></i>
                                        </div>
                                    </a>
                                    <a href="#" class="block h-1/2 w-1/2 relative swiper-project-item transition-all group">
                                        <img src="~/assets/img/picture-5.png" class="w-full h-full object-cover" alt="">
                                        <div
                                            class="header-title-public absolute top-0 start-0 text-white bg-dark/50 w-full h-0 transition-all duration-500 flex flex-col items-center justify-center opacity-0 group-hover:opacity-100 group-hover:h-full z-10">
                                            پروژه 1
                                            <i class="icon-add text-white font-normal lg:text-12xl text-7xl mt-4"></i>
                                        </div>
                                    </a>
                                    <a href="#"
                                        class="block h-1/2 w-full relative swiper-project-item transition-all group max-lg:-order-1">
                                        <img src="~/assets/img/picture-3.png" class="w-full h-full object-cover" alt="">
                                        <div
                                            class="header-title-public absolute top-0 start-0 text-white bg-dark/50 w-full h-0 transition-all duration-500 flex flex-col items-center justify-center opacity-0 group-hover:opacity-100 group-hover:h-full z-10">
                                            پروژه 1
                                            <i class="icon-add text-white font-normal lg:text-12xl text-7xl mt-4"></i>
                                        </div>
                                    </a>
                                </div>
                                <a href="#"
                                    class="block lg:h-full h-1/2 lg:w-1/2 w-full relative swiper-project-item transition-all group">
                                    <img src="~/assets/img/picture-3.png" class="w-full h-full object-cover" alt="">
                                    <div
                                        class="header-title-public absolute top-0 start-0 text-white bg-dark/50 w-full h-0 transition-all duration-500 flex flex-col items-center justify-center opacity-0 group-hover:opacity-100 group-hover:h-full z-10">
                                        پروژه 1
                                        <i class="icon-add text-white font-normal lg:text-12xl text-7xl mt-4"></i>
                                    </div>
                                </a>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide>
                            <div class="flex flex-wrap items-start h-full">
                                <div class="lg:h-full h-1/2 lg:w-1/2 w-full flex flex-wrap">
                                    <a href="#" class="block group h-1/2 w-1/2 relative swiper-project-item transition-all">
                                        <img src="~/assets/img/picture-4.png" class="w-full h-full object-cover" alt="">
                                        <div
                                            class="header-title-public absolute top-0 start-0 text-white bg-dark/50 w-full h-0 transition-all duration-500 flex flex-col items-center justify-center opacity-0 group-hover:opacity-100 group-hover:h-full z-10">
                                            پروژه 1
                                            <i class="icon-add text-white font-normal lg:text-12xl text-7xl mt-4"></i>
                                        </div>
                                    </a>
                                    <a href="#" class="block h-1/2 w-1/2 relative swiper-project-item transition-all group">
                                        <img src="~/assets/img/picture-5.png" class="w-full h-full object-cover" alt="">
                                        <div
                                            class="header-title-public absolute top-0 start-0 text-white bg-dark/50 w-full h-0 transition-all duration-500 flex flex-col items-center justify-center opacity-0 group-hover:opacity-100 group-hover:h-full z-10">
                                            پروژه 1
                                            <i class="icon-add text-white font-normal lg:text-12xl text-7xl mt-4"></i>
                                        </div>
                                    </a>
                                    <a href="#"
                                        class="block h-1/2 w-full relative swiper-project-item transition-all group max-lg:-order-1">
                                        <img src="~/assets/img/picture-3.png" class="w-full h-full object-cover" alt="">
                                        <div
                                            class="header-title-public absolute top-0 start-0 text-white bg-dark/50 w-full h-0 transition-all duration-500 flex flex-col items-center justify-center opacity-0 group-hover:opacity-100 group-hover:h-full z-10">
                                            پروژه 1
                                            <i class="icon-add text-white font-normal lg:text-12xl text-7xl mt-4"></i>
                                        </div>
                                    </a>
                                </div>
                                <a href="#"
                                    class="block lg:h-full h-1/2 lg:w-1/2 w-full relative swiper-project-item transition-all group">
                                    <img src="~/assets/img/picture-3.png" class="w-full h-full object-cover" alt="">
                                    <div
                                        class="header-title-public absolute top-0 start-0 text-white bg-dark/50 w-full h-0 transition-all duration-500 flex flex-col items-center justify-center opacity-0 group-hover:opacity-100 group-hover:h-full z-10">
                                        پروژه 1
                                        <i class="icon-add text-white font-normal lg:text-12xl text-7xl mt-4"></i>
                                    </div>
                                </a>
                            </div>
                        </SwiperSlide>
                    </Swiper>
                <!-- </div> -->
                <div class="swiper-paginations swiper-pagination-project"></div>
            </div>
        </div>
        <!-- END-PROJECT -->
</template>