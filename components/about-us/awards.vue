<template>
    <!-- START-AWARDS -->
    <div class="pb-between-section bg-natural-alpha">
        <div class="container 2xl:px-28 xl:px-20 lg:px-16">
            
            <PublicHeaderSection title="افتخارات و جایزه های گروه ما" subtitle="همه را در کنار شما بدست آورده ایم"/>
            
            <!-- <div class="swiper swiper-container swiper-awards "> -->
                <Swiper :slides-per-view="3" :space-between="30" class="max-lg:overflow-visible">
                    <SwiperSlide class="max-lg:w-[280px]">
                        <div class="bg-white group hover:shadow-lighter-hover transition-all rounded-2xl p-2">
                            <div class="bg-natural-alpha rounded-2xl">
                                <div class="lg:pt-10 pt-6 lg:pb-6 pb-4">
                                    <h2 class="title-public title-public-medium text-center">
                                        جشنواره وب و موبایل
                                    </h2>
                                    <span class="text-sm text-dark font-medium block text-center">
                                        شهریور ماه 1401
                                    </span>
                                </div>
                                <div class="lg:h-[150px] h-[130px] overflow-hidden">
                                    <img src="~/assets/img/award.png" class="mx-auto" alt="">
                                </div>
                            </div>
                        </div>
                    </SwiperSlide>
                    <SwiperSlide class="max-lg:w-[280px]">
                        <div class="bg-white group hover:shadow-lighter-hover transition-all rounded-2xl p-2">
                            <div class="bg-natural-alpha rounded-2xl">
                                <div class="lg:pt-10 pt-6 lg:pb-6 pb-4">
                                    <h2 class="title-public title-public-medium text-center">
                                        جشنواره وب و موبایل
                                    </h2>
                                    <span class="text-sm text-dark font-medium block text-center">
                                        خرداد ماه 1399
                                    </span>
                                </div>
                                <div class="lg:h-[150px] h-[130px] overflow-hidden">
                                    <img src="~/assets/img/award.png" class="mx-auto" alt="">
                                </div>
                            </div>
                        </div>
                    </SwiperSlide>
                    <SwiperSlide class="max-lg:w-[280px]">
                        <div class="bg-white group hover:shadow-lighter-hover transition-all rounded-2xl p-2">
                            <div class="bg-natural-alpha rounded-2xl">
                                <div class="lg:pt-10 pt-6 lg:pb-6 pb-4">
                                    <h2 class="title-public title-public-medium text-center">
                                        جشنواره وب و موبایل
                                    </h2>
                                    <span class="text-sm text-dark font-medium block text-center">
                                        مهر ماه 1396
                                    </span>
                                </div>
                                <div class="lg:h-[150px] h-[130px] overflow-hidden">
                                    <img src="~/assets/img/award.png" class="mx-auto" alt="">
                                </div>
                            </div>
                        </div>
                    </SwiperSlide>
                </Swiper>
            <!-- </div> -->
        </div>
    </div>
    <!-- END-AWARDS -->
</template>