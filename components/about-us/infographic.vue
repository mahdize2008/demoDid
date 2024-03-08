
<template>
    <!-- START-INFOGRAPHIC -->
    <div class="pb-between-section bg-natural-alpha">
        <div class="container 2xl:px-28 xl:px-20 lg:px-16">
            
            <PublicHeaderSection title="اینفوگرافیک تاریخچه کسب و کار" subtitle="همه ما در کنار هم پیشرفت میکنیم"/>
            

            <!-- <div class="swiper swiper-container swiper-infographic "> -->
                <Swiper :slides-per-view="4" :pagination="{el:'.swiper-pagination-infographic',clickable:'true'}" :modules="[SwiperPagination]" :space-between="30" class="max-lg:overflow-visible mb-12">
                    <SwiperSlide class="max-lg:w-[270px]">
                        <div class="p-8 bg-white rounded-2xl">
                            <div class="flex items-center mb-7">
                                <div
                                    class="flex items-center justify-center bg-gradient-danger text-2base me-6 font-semibold w-[38px] h-[38px] rounded-full text-white border-b-[3px] border-primary-dark">
                                    1398
                                </div>
                                <!-- START-ICON-IMG -->
                                <img src="~/assets/img/add-user.png" class="w-[46px]" alt="">
                                <!-- END-ICON-IMG -->
                            </div>
                            <h5 class="subtitle-public">
                                بهار 1398
                            </h5>
                            <h3 class="title-public mb-3">
                                ثبت رسمی شرکت
                            </h3>
                            <p class="text-public text-public-small line-clamp-3">
                                لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان ...
                            </p>
                        </div>
                    </SwiperSlide>
                    <SwiperSlide class="max-lg:w-[270px]">
                        <div class="p-8 bg-white rounded-2xl">
                            <div class="flex items-center mb-7">
                                <div
                                    class="flex items-center justify-center bg-gradient-danger text-2base me-6 font-semibold w-[38px] h-[38px] rounded-full text-white border-b-[3px] border-primary-dark">
                                    1399
                                </div>
                                <!-- START-ICON-IMG -->
                                <img src="~/assets/img/settings-small.png" class="w-[46px]" alt="">
                                <!-- END-ICON-IMG -->
                            </div>
                            <h5 class="subtitle-public">
                                تابستان 1399
                            </h5>
                            <h3 class="title-public mb-3">
                                راه اندازی دفتر
                            </h3>
                            <p class="text-public text-public-small line-clamp-3">
                                لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان ...
                            </p>
                        </div>
                    </SwiperSlide>
                    <SwiperSlide class="max-lg:w-[270px]">
                        <div class="p-8 bg-white rounded-2xl">
                            <div class="flex items-center mb-7">
                                <div
                                    class="flex items-center justify-center bg-gradient-danger text-2base me-6 font-semibold w-[38px] h-[38px] rounded-full text-white border-b-[3px] border-primary-dark">
                                    1401
                                </div>
                                <!-- START-ICON-IMG -->
                                <img src="~/assets/img/star.png" class="w-[46px]" alt="">
                                <!-- END-ICON-IMG -->
                            </div>
                            <h5 class="subtitle-public">
                                پاییز 1401
                            </h5>
                            <h3 class="title-public mb-3">
                                توسعه تیم فنی
                            </h3>
                            <p class="text-public text-public-small line-clamp-3">
                                لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان ...
                            </p>
                        </div>
                    </SwiperSlide>
                    <SwiperSlide class="max-lg:w-[270px]">
                        <div class="p-8 bg-white rounded-2xl">
                            <div class="flex items-center mb-7">
                                <div
                                    class="flex items-center justify-center bg-gradient-danger text-2base me-6 font-semibold w-[38px] h-[38px] rounded-full text-white border-b-[3px] border-primary-dark">
                                    1402
                                </div>
                                <!-- START-ICON-IMG -->
                                <img src="~/assets/img/credit-card.png" class="w-[46px]" alt="">
                                <!-- END-ICON-IMG -->
                            </div>
                            <h5 class="subtitle-public">
                                زمستان 1402
                            </h5>
                            <h3 class="title-public mb-3">
                                شرکاری جدید
                            </h3>
                            <p class="text-public text-public-small line-clamp-3">
                                لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان ...
                            </p>
                        </div>
                    </SwiperSlide>
                    <SwiperSlide class="max-lg:w-[270px]">
                        <div class="p-8 bg-white rounded-2xl">
                            <div class="flex items-center mb-7">
                                <div
                                    class="flex items-center justify-center bg-gradient-danger text-2base me-6 font-semibold w-[38px] h-[38px] rounded-full text-white border-b-[3px] border-primary-dark">
                                    1398
                                </div>
                                <!-- START-ICON-IMG -->
                                <img src="~/assets/img/add-user.png" class="w-[46px]" alt="">
                                <!-- END-ICON-IMG -->
                            </div>
                            <h5 class="subtitle-public">
                                بهار 1398
                            </h5>
                            <h3 class="title-public mb-3">
                                ثبت رسمی شرکت
                            </h3>
                            <p class="text-public text-public-small line-clamp-3">
                                لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان ...
                            </p>
                        </div>
                    </SwiperSlide>
                    <SwiperSlide class="max-lg:w-[270px]">
                        <div class="p-8 bg-white rounded-2xl">
                            <div class="flex items-center mb-7">
                                <div
                                    class="flex items-center justify-center bg-gradient-danger text-2base me-6 font-semibold w-[38px] h-[38px] rounded-full text-white border-b-[3px] border-primary-dark">
                                    1398
                                </div>
                                <!-- START-ICON-IMG -->
                                <img src="~/assets/img/add-user.png" class="w-[46px]" alt="">
                                <!-- END-ICON-IMG -->
                            </div>
                            <h5 class="subtitle-public">
                                بهار 1398
                            </h5>
                            <h3 class="title-public mb-3">
                                ثبت رسمی شرکت
                            </h3>
                            <p class="text-public text-public-small line-clamp-3">
                                لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان ...
                            </p>
                        </div>
                    </SwiperSlide>
                    <SwiperSlide class="max-lg:w-[270px]">
                        <div class="p-8 bg-white rounded-2xl">
                            <div class="flex items-center mb-7">
                                <div
                                    class="flex items-center justify-center bg-gradient-danger text-2base me-6 font-semibold w-[38px] h-[38px] rounded-full text-white border-b-[3px] border-primary-dark">
                                    1398
                                </div>
                                <!-- START-ICON-IMG -->
                                <img src="~/assets/img/add-user.png" class="w-[46px]" alt="">
                                <!-- END-ICON-IMG -->
                            </div>
                            <h5 class="subtitle-public">
                                بهار 1398
                            </h5>
                            <h3 class="title-public mb-3">
                                ثبت رسمی شرکت
                            </h3>
                            <p class="text-public text-public-small line-clamp-3">
                                لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان ...
                            </p>
                        </div>
                    </SwiperSlide>
                </Swiper>
            <!-- </div> -->
            <div class="swiper-paginations swiper-pagination-infographic"></div>
        </div>
    </div>
    <!-- END-INFOGRAPHIC -->
</template>