<template>
<!-- START-COMMENTS -->
<div class="pb-between-section bg-natural-alpha">
            <div class="container 2xl:px-28 xl:px-20 lg:px-16">
                
                <PublicHeaderSection title="نظرات برخی از مشتریان" subtitle="به مجموعه ما اعتماد کرده اند"/>
                
                <!-- <div class="swiper swiper-container swiper-comments"> -->
                    <Swiper :slides-per-view="3" :pagination="{el:'.swiper-pagination-comments',clickable:'true'}" :modules="[SwiperPagination]" :space-between="30" class="max-lg:overflow-visible">
                        <SwiperSlide class="max-lg:w-[270px]">
                            <div
                                class="bg-white group rounded-xl xl:p-8 lg:p-5 p-4 hover:shadow-lighter-hover transition-all">
                                <div class="flex items-center mb-7">
                                    <div
                                        class="lg:w-24 w-20 lg:h-24 h-20 rounded-full lg:border-10 border-6 me-4 border-natural-alpha group-hover:border-primary-light transition-all overflow-hidden">
                                        <img src="~/assets/img/picture-6.png" class="w-full h-full" alt="">
                                    </div>
                                    <div>
                                        <h4 class="text-base font-extrabold text-dark mb-0.5">
                                            رحیم قاسمی نژاد
                                        </h4>
                                        <span class="text-sm text-natural-beta">
                                            10 بهمن ماه 1402
                                        </span>
                                    </div>
                                </div>
                                <p class="text-public">
                                    لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از
                                    طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که
                                    لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود
                                    ابزارهای کاربردی می باشد.
                                </p>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[270px]">
                            <div
                                class="bg-white group rounded-xl xl:p-8 lg:p-5 p-4 hover:shadow-lighter-hover transition-all">
                                <div class="flex items-center mb-7">
                                    <div
                                        class="lg:w-24 w-20 lg:h-24 h-20 rounded-full lg:border-10 border-6 me-4 border-natural-alpha group-hover:border-primary-light transition-all overflow-hidden">
                                        <img src="~/assets/img/picture-7.png" class="w-full h-full" alt="">
                                    </div>
                                    <div>
                                        <h4 class="text-base font-extrabold text-dark mb-0.5">
                                            رقیه رحیمی
                                        </h4>
                                        <span class="text-sm text-natural-beta">
                                            10 بهمن ماه 1402
                                        </span>
                                    </div>
                                </div>
                                <p class="text-public">
                                    لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از
                                    طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که
                                    لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود
                                    ابزارهای کاربردی می باشد.
                                </p>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[270px]">
                            <div
                                class="bg-white group rounded-xl xl:p-8 lg:p-5 p-4 hover:shadow-lighter-hover transition-all">
                                <div class="flex items-center mb-7">
                                    <div
                                        class="lg:w-24 w-20 lg:h-24 h-20 rounded-full lg:border-10 border-6 me-4 border-natural-alpha group-hover:border-primary-light transition-all overflow-hidden">
                                        <img src="~/assets/img/picture-8.png" class="w-full h-full" alt="">
                                    </div>
                                    <div>
                                        <h4 class="text-base font-extrabold text-dark mb-0.5">
                                            شهروز رحیمیان راد
                                        </h4>
                                        <span class="text-sm text-natural-beta">
                                            10 بهمن ماه 1402
                                        </span>
                                    </div>
                                </div>
                                <p class="text-public">
                                    لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از
                                    طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که
                                    لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود
                                    ابزارهای کاربردی می باشد.
                                </p>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[270px]">
                            <div
                                class="bg-white group rounded-xl xl:p-8 lg:p-5 p-4 hover:shadow-lighter-hover transition-all">
                                <div class="flex items-center mb-7">
                                    <div
                                        class="lg:w-24 w-20 lg:h-24 h-20 rounded-full lg:border-10 border-6 me-4 border-natural-alpha group-hover:border-primary-light transition-all overflow-hidden">
                                        <img src="~/assets/img/picture-9.png" class="w-full h-full" alt="">
                                    </div>
                                    <div>
                                        <h4 class="text-base font-extrabold text-dark mb-0.5">
                                            رحیم قاسمی نژاد
                                        </h4>
                                        <span class="text-sm text-natural-beta">
                                            10 بهمن ماه 1402
                                        </span>
                                    </div>
                                </div>
                                <p class="text-public">
                                    لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از
                                    طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که
                                    لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود
                                    ابزارهای کاربردی می باشد.
                                </p>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[270px]">
                            <div
                                class="bg-white group rounded-xl xl:p-8 lg:p-5 p-4 hover:shadow-lighter-hover transition-all">
                                <div class="flex items-center mb-7">
                                    <div
                                        class="lg:w-24 w-20 lg:h-24 h-20 rounded-full lg:border-10 border-6 me-4 border-natural-alpha group-hover:border-primary-light transition-all overflow-hidden">
                                        <img src="~/assets/img/picture-6.png" class="w-full h-full" alt="">
                                    </div>
                                    <div>
                                        <h4 class="text-base font-extrabold text-dark mb-0.5">
                                            رحیم قاسمی نژاد
                                        </h4>
                                        <span class="text-sm text-natural-beta">
                                            10 بهمن ماه 1402
                                        </span>
                                    </div>
                                </div>
                                <p class="text-public">
                                    لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از
                                    طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که
                                    لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود
                                    ابزارهای کاربردی می باشد.
                                </p>
                            </div>
                        </SwiperSlide>
                        <SwiperSlide class="max-lg:w-[270px]">
                            <div
                                class="bg-white group rounded-xl xl:p-8 lg:p-5 p-4 hover:shadow-lighter-hover transition-all">
                                <div class="flex items-center mb-7">
                                    <div
                                        class="lg:w-24 w-20 lg:h-24 h-20 rounded-full lg:border-10 border-6 me-4 border-natural-alpha group-hover:border-primary-light transition-all overflow-hidden">
                                        <img src="~/assets/img/picture-6.png" class="w-full h-full" alt="">
                                    </div>
                                    <div>
                                        <h4 class="text-base font-extrabold text-dark mb-0.5">
                                            رحیم قاسمی نژاد
                                        </h4>
                                        <span class="text-sm text-natural-beta">
                                            10 بهمن ماه 1402
                                        </span>
                                    </div>
                                </div>
                                <p class="text-public">
                                    لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از
                                    طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که
                                    لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود
                                    ابزارهای کاربردی می باشد.
                                </p>
                            </div>
                        </SwiperSlide>
                    </Swiper>
                <!-- </div> -->
                <div class="swiper-paginations swiper-pagination-comments"></div>
            </div>
        </div>
        <!-- END-COMMENTS -->
</template>