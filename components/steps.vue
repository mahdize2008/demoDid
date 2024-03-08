<template>
<!-- START-STEPS -->
<div class="py-between-section bg-natural-alpha">
            <div class="container 2xl:px-28 xl:px-20 lg:px-16">
                
                <PublicHeaderSection title="مراحل دریافت خدمات ما" subtitle="صفر تا صد کنار شما هستیم"/>
                
                <!-- <div class="swiper swiper-container swiper-steps"> -->
                    <Swiper :slides-per-view="4" :pagination="{el:'.swiper-pagination-steps',clickable:'true'}" :modules="[SwiperPagination]" :space-between="30" class="max-lg:overflow-visible mb-12">
                        <SwiperSlide class="max-lg:w-[270px]">
                            <div
                                class="p-8 border-natural-gamma hover:bg-white hover:border-white hover:shadow-lighter-hover transition-all rounded-2xl overflow-hidden border-2">
                                <div class="flex items-center mb-7">
                                    <div
                                        class="flex items-center justify-center bg-gradient-danger text-lg me-6 font-bold w-[38px] h-[38px] rounded-full text-white border-b-[3px] border-primary-dark">
                                        1
                                    </div>
                                    <!-- START-ICON-IMG -->
                                    <img src="~/assets/img/add-user.png" class="w-[46px]" alt="">
                                    <!-- END-ICON-IMG -->
                                </div>
                                <h5 class="subtitle-public">
                                    مرحله نخست
                                </h5>
                                <h3 class="title-public mb-3">
                                    ورود یا ثبت نام
                                </h3>
                                <p class="text-public text-public-small line-clamp-3">
                                    لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان
                                    ...
                                </p>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[270px]">
                            <div
                                class="p-8 border-natural-gamma hover:bg-white hover:border-white hover:shadow-lighter-hover transition-all rounded-2xl overflow-hidden border-2">
                                <div class="flex items-center mb-7">
                                    <div
                                        class="flex items-center justify-center bg-gradient-danger text-lg me-6 font-bold w-[38px] h-[38px] rounded-full text-white border-b-[3px] border-primary-dark">
                                        2
                                    </div>
                                    <!-- START-ICON-IMG -->
                                    <img src="~/assets/img/settings-small.png" class="w-[46px]" alt="">
                                    <!-- END-ICON-IMG -->
                                </div>
                                <h5 class="subtitle-public">
                                    مرحله دوم
                                </h5>
                                <h3 class="title-public mb-3">
                                    انتخاب سرویس
                                </h3>
                                <p class="text-public text-public-small line-clamp-3">
                                    لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان
                                    ...
                                </p>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[270px]">
                            <div
                                class="p-8 border-natural-gamma hover:bg-white hover:border-white hover:shadow-lighter-hover transition-all rounded-2xl overflow-hidden border-2">
                                <div class="flex items-center mb-7">
                                    <div
                                        class="flex items-center justify-center bg-gradient-danger text-lg me-6 font-bold w-[38px] h-[38px] rounded-full text-white border-b-[3px] border-primary-dark">
                                        3
                                    </div>
                                    <!-- START-ICON-IMG -->
                                    <img src="~/assets/img/star.png" class="w-[46px]" alt="">
                                    <!-- END-ICON-IMG -->
                                </div>
                                <h5 class="subtitle-public">
                                    مرحله سوم
                                </h5>
                                <h3 class="title-public mb-3">
                                    ورود یا ثبت نام
                                </h3>
                                <p class="text-public text-public-small line-clamp-3">
                                    لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان
                                    ...
                                </p>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[270px]">
                            <div
                                class="p-8 border-natural-gamma hover:bg-white hover:border-white hover:shadow-lighter-hover transition-all rounded-2xl overflow-hidden border-2">
                                <div class="flex items-center mb-7">
                                    <div
                                        class="flex items-center justify-center bg-gradient-danger text-lg me-6 font-bold w-[38px] h-[38px] rounded-full text-white border-b-[3px] border-primary-dark">
                                        4
                                    </div>
                                    <!-- START-ICON-IMG -->
                                    <img src="~/assets/img/credit-card.png" class="w-[46px]" alt="">
                                    <!-- END-ICON-IMG -->
                                </div>
                                <h5 class="subtitle-public">
                                    مرحله نخست
                                </h5>
                                <h3 class="title-public mb-3">
                                    انتخاب پلن ها
                                </h3>
                                <p class="text-public text-public-small line-clamp-3">
                                    لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان
                                    ...
                                </p>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[270px]">
                            <div
                                class="p-8 border-natural-gamma hover:bg-white hover:border-white hover:shadow-lighter-hover transition-all rounded-2xl overflow-hidden border-2">
                                <div class="flex items-center mb-7">
                                    <div
                                        class="flex items-center justify-center bg-gradient-danger text-lg me-6 font-bold w-[38px] h-[38px] rounded-full text-white border-b-[3px] border-primary-dark">
                                        5
                                    </div>
                                    <!-- START-ICON-IMG -->
                                    <img src="~/assets/img/credit-card.png" class="w-[46px]" alt="">
                                    <!-- END-ICON-IMG -->
                                </div>
                                <h5 class="subtitle-public">
                                    مرحله چهارم
                                </h5>
                                <h3 class="title-public mb-3">
                                    پرداخت کنید
                                </h3>
                                <p class="text-public text-public-small line-clamp-3">
                                    لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان
                                    گرافیک است. چاپگرها.
                                </p>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[270px]">
                            <div
                                class="p-8 border-natural-gamma hover:bg-white hover:border-white hover:shadow-lighter-hover transition-all rounded-2xl overflow-hidden border-2">
                                <div class="flex items-center mb-7">
                                    <div
                                        class="flex items-center justify-center bg-gradient-danger text-lg me-6 font-bold w-[38px] h-[38px] rounded-full text-white border-b-[3px] border-primary-dark">
                                        6
                                    </div>
                                    <!-- START-ICON-IMG -->
                                    <img src="~/assets/img/credit-card.png" class="w-[46px]" alt="">
                                    <!-- END-ICON-IMG -->
                                </div>
                                <h5 class="subtitle-public">
                                    مرحله نخست
                                </h5>
                                <h3 class="title-public mb-3">
                                    انتخاب پلن ها
                                </h3>
                                <p class="text-public text-public-small line-clamp-3">
                                    لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان
                                    ...
                                </p>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[270px]">
                            <div
                                class="p-8 border-natural-gamma hover:bg-white hover:border-white hover:shadow-lighter-hover transition-all rounded-2xl overflow-hidden border-2">
                                <div class="flex items-center mb-7">
                                    <div
                                        class="flex items-center justify-center bg-gradient-danger text-lg me-6 font-bold w-[38px] h-[38px] rounded-full text-white border-b-[3px] border-primary-dark">
                                        7
                                    </div>
                                    <!-- START-ICON-IMG -->
                                    <img src="~/assets/img/credit-card.png" class="w-[46px]" alt="">
                                    <!-- END-ICON-IMG -->
                                </div>
                                <h5 class="subtitle-public">
                                    مرحله چهارم
                                </h5>
                                <h3 class="title-public mb-3">
                                    پرداخت کنید
                                </h3>
                                <p class="text-public text-public-small line-clamp-3">
                                    لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان
                                    گرافیک است. چاپگرها.
                                </p>
                            </div>
                        </SwiperSlide>
                    </Swiper>
                <!-- </div> -->
                <div class="swiper-paginations swiper-pagination-steps"></div>
            </div>
        </div>
        <!-- END-STEPS -->
</template>