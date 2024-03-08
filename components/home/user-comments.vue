
<template>
<!-- START-USER-COMMENTS -->
<div class="pb-between-section bg-natural-alpha">
            <div class="container 2xl:px-28 xl:px-20 lg:px-16">

                
                <PublicHeaderSection title="نظرات کاربران ما" subtitle="اهمیت ویژه به شما داریم"/>
                
                <!-- <div class="swiper swiper-container swiper-user-comments"> -->
                    <Swiper :slides-per-view="2" :pagination="{el:'.swiper-pagination-user-comments',clickable:'true'}" :modules="[SwiperPagination]" :space-between="30">
                        <SwiperSlide>
                            <div
                                class="lg:p-4 p-2 border-dark-alpha/50 hover:bg-white hover:border-white hover:shadow-lighter-hover transition-all border-2 rounded-2xl overflow-hidden">
                                <div class="bg-white rounded-xl lg:p-8 p-5">
                                    <div class="xl:flex items-start lg:mb-8 mb-4">
                                        <div class="xl:me-8 w-fit max-xl:mx-auto shrink-0 max-xl:mb-2">
                                            <div
                                                class="block lg:w-[130px] w-[100px] lg:h-[130px] h-[100px] lg:border-8 border-6 border-light/40 rounded-full overflow-hidden lg:mb-6 mb-3">
                                                <img src="~/assets/img/picture-8.png" class="w-full h-full" alt="">
                                            </div>
                                            <div class="title-public title-public-medium">
                                                مریم خلیل پور
                                            </div>
                                            <span
                                                class="lg:text-2base text-sm font-medium text-dark block max-xl:text-center">
                                                کارشناس سئو
                                            </span>
                                        </div>
                                        <p class="text-public">
                                            لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده
                                            از طراحان
                                            گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که
                                            لازم است و
                                            برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود باشد.
                                            برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف.
                                        </p>
                                    </div>
                                    <div>
                                        <div class="mb-2">
                                            <div class="flex items-center mb-1.5">
                                                <div class="title-public title-public-medium lg:text-md text-base me-4">
                                                    طراحی محصول
                                                </div>
                                                <span class="text-sm text-dark font-medium">
                                                    85 درصد رضایت
                                                </span>
                                            </div>
                                            <div class="p-2 rounded-full bg-natural-alpha">
                                                <div class="bg-primary rounded-full h-1" style="width: 85%;">

                                                </div>
                                            </div>
                                        </div>
                                        <div class="mb-2">
                                            <div class="flex items-center mb-1.5">
                                                <div class="title-public title-public-medium lg:text-md text-base me-4">
                                                    توسعه کسب و کار
                                                </div>
                                                <span class="text-sm text-dark font-medium">
                                                    70 درصد رضایت
                                                </span>
                                            </div>
                                            <div class="p-2 rounded-full bg-natural-alpha">
                                                <div class="bg-primary rounded-full h-1" style="width: 70%;">

                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide>
                            <div
                                class="lg:p-4 p-2 border-dark-alpha/50 hover:bg-white hover:border-white hover:shadow-lighter-hover transition-all border-2 rounded-2xl overflow-hidden">
                                <div class="bg-white rounded-xl lg:p-8 p-5">
                                    <div class="xl:flex items-start lg:mb-8 mb-4">
                                        <div class="xl:me-8 w-fit max-xl:mx-auto shrink-0 max-xl:mb-2">
                                            <div
                                                class="block lg:w-[130px] w-[100px] lg:h-[130px] h-[100px] lg:border-8 border-6 border-light/40 rounded-full overflow-hidden lg:mb-6 mb-3">
                                                <img src="~/assets/img/picture-8.png" class="w-full h-full" alt="">
                                            </div>
                                            <div class="title-public title-public-medium">
                                                نعیم علیمردانی
                                            </div>
                                            <span
                                                class="lg:text-2base text-sm font-medium text-dark block max-xl:text-center">
                                                تولید محتوا
                                            </span>
                                        </div>
                                        <p class="text-public">
                                            لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده
                                            از طراحان
                                            گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که
                                            لازم است و
                                            برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود باشد.
                                            برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف.
                                        </p>
                                    </div>
                                    <div>
                                        <div class="mb-2">
                                            <div class="flex items-center mb-1.5">
                                                <div class="title-public title-public-medium lg:text-md text-base me-4">
                                                    طراحی محصول
                                                </div>
                                                <span class="text-sm text-dark font-medium">
                                                    85 درصد رضایت
                                                </span>
                                            </div>
                                            <div class="p-2 rounded-full bg-natural-alpha">
                                                <div class="bg-primary rounded-full h-1" style="width: 85%;">

                                                </div>
                                            </div>
                                        </div>
                                        <div class="mb-2">
                                            <div class="flex items-center mb-1.5">
                                                <div class="title-public title-public-medium lg:text-md text-base me-4">
                                                    توسعه کسب و کار
                                                </div>
                                                <span class="text-sm text-dark font-medium">
                                                    70 درصد رضایت
                                                </span>
                                            </div>
                                            <div class="p-2 rounded-full bg-natural-alpha">
                                                <div class="bg-primary rounded-full h-1" style="width: 70%;">

                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide>
                            <div
                                class="lg:p-4 p-2 border-dark-alpha/50 hover:bg-white hover:border-white hover:shadow-lighter-hover transition-all border-2 rounded-2xl overflow-hidden">
                                <div class="bg-white rounded-xl lg:p-8 p-5">
                                    <div class="xl:flex items-start lg:mb-8 mb-4">
                                        <div class="xl:me-8 w-fit max-xl:mx-auto shrink-0 max-xl:mb-2">
                                            <div
                                                class="block lg:w-[130px] w-[100px] lg:h-[130px] h-[100px] lg:border-8 border-6 border-light/40 rounded-full overflow-hidden lg:mb-6 mb-3">
                                                <img src="~/assets/img/picture-8.png" class="w-full h-full" alt="">
                                            </div>
                                            <div class="title-public title-public-medium">
                                                مریم خلیل پور
                                            </div>
                                            <span
                                                class="lg:text-2base text-sm font-medium text-dark block max-xl:text-center">
                                                کارشناس سئو
                                            </span>
                                        </div>
                                        <p class="text-public">
                                            لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده
                                            از طراحان
                                            گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که
                                            لازم است و
                                            برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود باشد.
                                            برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف.
                                        </p>
                                    </div>
                                    <div>
                                        <div class="mb-2">
                                            <div class="flex items-center mb-1.5">
                                                <div class="title-public title-public-medium lg:text-md text-base me-4">
                                                    طراحی محصول
                                                </div>
                                                <span class="text-sm text-dark font-medium">
                                                    85 درصد رضایت
                                                </span>
                                            </div>
                                            <div class="p-2 rounded-full bg-natural-alpha">
                                                <div class="bg-primary rounded-full h-1" style="width: 85%;">

                                                </div>
                                            </div>
                                        </div>
                                        <div class="mb-2">
                                            <div class="flex items-center mb-1.5">
                                                <div class="title-public title-public-medium lg:text-md text-base me-4">
                                                    توسعه کسب و کار
                                                </div>
                                                <span class="text-sm text-dark font-medium">
                                                    70 درصد رضایت
                                                </span>
                                            </div>
                                            <div class="p-2 rounded-full bg-natural-alpha">
                                                <div class="bg-primary rounded-full h-1" style="width: 70%;">

                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide>
                            <div
                                class="lg:p-4 p-2 border-dark-alpha/50 hover:bg-white hover:border-white hover:shadow-lighter-hover transition-all border-2 rounded-2xl overflow-hidden">
                                <div class="bg-white rounded-xl lg:p-8 p-5">
                                    <div class="xl:flex items-start lg:mb-8 mb-4">
                                        <div class="xl:me-8 w-fit max-xl:mx-auto shrink-0 max-xl:mb-2">
                                            <div
                                                class="block lg:w-[130px] w-[100px] lg:h-[130px] h-[100px] lg:border-8 border-6 border-light/40 rounded-full overflow-hidden lg:mb-6 mb-3">
                                                <img src="~/assets/img/picture-8.png" class="w-full h-full" alt="">
                                            </div>
                                            <div class="title-public title-public-medium">
                                                مریم خلیل پور
                                            </div>
                                            <span
                                                class="lg:text-2base text-sm font-medium text-dark block max-xl:text-center">
                                                کارشناس سئو
                                            </span>
                                        </div>
                                        <p class="text-public">
                                            لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده
                                            از طراحان
                                            گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که
                                            لازم است و
                                            برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود باشد.
                                            برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف.
                                        </p>
                                    </div>
                                    <div>
                                        <div class="mb-2">
                                            <div class="flex items-center mb-1.5">
                                                <div class="title-public title-public-medium lg:text-md text-base me-4">
                                                    طراحی محصول
                                                </div>
                                                <span class="text-sm text-dark font-medium">
                                                    85 درصد رضایت
                                                </span>
                                            </div>
                                            <div class="p-2 rounded-full bg-natural-alpha">
                                                <div class="bg-primary rounded-full h-1" style="width: 85%;">

                                                </div>
                                            </div>
                                        </div>
                                        <div class="mb-2">
                                            <div class="flex items-center mb-1.5">
                                                <div class="title-public title-public-medium lg:text-md text-base me-4">
                                                    توسعه کسب و کار
                                                </div>
                                                <span class="text-sm text-dark font-medium">
                                                    70 درصد رضایت
                                                </span>
                                            </div>
                                            <div class="p-2 rounded-full bg-natural-alpha">
                                                <div class="bg-primary rounded-full h-1" style="width: 70%;">

                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide>
                            <div
                                class="lg:p-4 p-2 border-dark-alpha/50 hover:bg-white hover:border-white hover:shadow-lighter-hover transition-all border-2 rounded-2xl overflow-hidden">
                                <div class="bg-white rounded-xl lg:p-8 p-5">
                                    <div class="xl:flex items-start lg:mb-8 mb-4">
                                        <div class="xl:me-8 w-fit max-xl:mx-auto shrink-0 max-xl:mb-2">
                                            <div
                                                class="block lg:w-[130px] w-[100px] lg:h-[130px] h-[100px] lg:border-8 border-6 border-light/40 rounded-full overflow-hidden lg:mb-6 mb-3">
                                                <img src="~/assets/img/picture-8.png" class="w-full h-full" alt="">
                                            </div>
                                            <div class="title-public title-public-medium">
                                                مریم خلیل پور
                                            </div>
                                            <span
                                                class="lg:text-2base text-sm font-medium text-dark block max-xl:text-center">
                                                کارشناس سئو
                                            </span>
                                        </div>
                                        <p class="text-public">
                                            لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده
                                            از طراحان
                                            گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که
                                            لازم است و
                                            برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود باشد.
                                            برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف.
                                        </p>
                                    </div>
                                    <div>
                                        <div class="mb-2">
                                            <div class="flex items-center mb-1.5">
                                                <div class="title-public title-public-medium lg:text-md text-base me-4">
                                                    طراحی محصول
                                                </div>
                                                <span class="text-sm text-dark font-medium">
                                                    85 درصد رضایت
                                                </span>
                                            </div>
                                            <div class="p-2 rounded-full bg-natural-alpha">
                                                <div class="bg-primary rounded-full h-1" style="width: 85%;">

                                                </div>
                                            </div>
                                        </div>
                                        <div class="mb-2">
                                            <div class="flex items-center mb-1.5">
                                                <div class="title-public title-public-medium lg:text-md text-base me-4">
                                                    توسعه کسب و کار
                                                </div>
                                                <span class="text-sm text-dark font-medium">
                                                    70 درصد رضایت
                                                </span>
                                            </div>
                                            <div class="p-2 rounded-full bg-natural-alpha">
                                                <div class="bg-primary rounded-full h-1" style="width: 70%;">

                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </SwiperSlide>
                    </Swiper>
                <!-- </div> -->
                <div class="swiper-paginations swiper-pagination-user-comments"></div>
            </div>
        </div>
        <!-- END-USER-COMMENTS -->
</template>