<template>
<!-- START-MAIN-COMPANIES -->
<div class="pb-between-section bg-natural-alpha">
            <div class="container 2xl:px-28 xl:px-20 lg:px-16">
                
                <PublicHeaderSection title="همکاران و شرکای تجاری" subtitle="یک روز خوب همراه با هم"/>
                
                <div class="swiper swiper-container swiper-companies">
                    <Swiper :slides-per-view="4" :pagination="{el:'.swiper-pagination-companies',clickable:'true'}" :modules="[SwiperPagination]" :space-between="30" class="max-lg:overflow-visible">
                        <SwiperSlide class="max-lg:w-[250px]">
                            <a href="#"
                                class="block group hover:shadow-lighter-hover bg-white rounded-xl p-2 transition-all">
                                <div
                                    class="bg-natural-alpha group-hover:bg-white transition-all lg:h-[190px] h-[150px] rounded-xl flex items-center justify-center">
                                    <img src="~/assets/img/brand-1.png" class="max-h-[120px]" alt="">
                                </div>
                                <h3 class="title-public lg:pt-8 pt-6 lg:pb-6 pb-4 text-center mb-0">
                                    گروه صنعتی گلرنگ
                                </h3>
                            </a>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[250px]">
                            <a href="#"
                                class="block group hover:shadow-lighter-hover bg-white rounded-xl p-2 transition-all">
                                <div
                                    class="bg-natural-alpha group-hover:bg-white transition-all lg:h-[190px] h-[150px] rounded-xl flex items-center justify-center">
                                    <img src="~/assets/img/brand-2.png" class="max-h-[120px]" alt="">
                                </div>
                                <h3 class="title-public lg:pt-8 pt-6 lg:pb-6 pb-4 text-center mb-0">
                                    فروشگاه هایپرمی
                                </h3>
                            </a>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[250px]">
                            <a href="#"
                                class="block group hover:shadow-lighter-hover bg-white rounded-xl p-2 transition-all">
                                <div
                                    class="bg-natural-alpha group-hover:bg-white transition-all lg:h-[190px] h-[150px] rounded-xl flex items-center justify-center">
                                    <img src="~/assets/img/brand-3.png" class="max-h-[120px]" alt="">
                                </div>
                                <h3 class="title-public lg:pt-8 pt-6 lg:pb-6 pb-4 text-center mb-0">
                                    گروه آموزشی گاج
                                </h3>
                            </a>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[250px]">
                            <a href="#"
                                class="block group hover:shadow-lighter-hover bg-white rounded-xl p-2 transition-all">
                                <div
                                    class="bg-natural-alpha group-hover:bg-white transition-all lg:h-[190px] h-[150px] rounded-xl flex items-center justify-center">
                                    <img src="~/assets/img/brand-4.png" class="max-h-[120px]" alt="">
                                </div>
                                <h3 class="title-public lg:pt-8 pt-6 lg:pb-6 pb-4 text-center mb-0">
                                    گروه صنعتی دوو
                                </h3>
                            </a>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[250px]">
                            <a href="#"
                                class="block group hover:shadow-lighter-hover bg-white rounded-xl p-2 transition-all">
                                <div
                                    class="bg-natural-alpha group-hover:bg-white transition-all lg:h-[190px] h-[150px] rounded-xl flex items-center justify-center">
                                    <img src="~/assets/img/brand-2.png" class="max-h-[120px]" alt="">
                                </div>
                                <h3 class="title-public lg:pt-8 pt-6 lg:pb-6 pb-4 text-center mb-0">
                                    فروشگاه هایپرمی
                                </h3>
                            </a>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[250px]">
                            <a href="#"
                                class="block group hover:shadow-lighter-hover bg-white rounded-xl p-2 transition-all">
                                <div
                                    class="bg-natural-alpha group-hover:bg-white transition-all lg:h-[190px] h-[150px] rounded-xl flex items-center justify-center">
                                    <img src="~/assets/img/brand-3.png" class="max-h-[120px]" alt="">
                                </div>
                                <h3 class="title-public lg:pt-8 pt-6 lg:pb-6 pb-4 text-center mb-0">
                                    گروه آموزشی گاج
                                </h3>
                            </a>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[250px]">
                            <a href="#"
                                class="block group hover:shadow-lighter-hover bg-white rounded-xl p-2 transition-all">
                                <div
                                    class="bg-natural-alpha group-hover:bg-white transition-all lg:h-[190px] h-[150px] rounded-xl flex items-center justify-center">
                                    <img src="~/assets/img/brand-4.png" class="max-h-[120px]" alt="">
                                </div>
                                <h3 class="title-public lg:pt-8 pt-6 lg:pb-6 pb-4 text-center mb-0">
                                    گروه صنعتی دوو
                                </h3>
                            </a>
                        </SwiperSlide>
                    </Swiper>
                </div>
                <div class="swiper-paginations swiper-pagination-companies"></div>
            </div>
        </div>
        <!-- END-MAIN-COMPANIES -->
</template>