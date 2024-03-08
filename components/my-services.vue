<template>
    <!-- START-SERVICES-2 -->
    <div
        class="relative pt-between-section after:bg-natural-alpha after:bottom-0 after:start-0 after:w-full lg:after:h-[248px] after:h-[190px] after:absolute">
        <div class="container 2xl:px-28 xl:px-20 lg:px-16 flex flex-wrap items-center">
            <PublicHeaderSection title="برخی از خدمات گروه ما" subtitle="با حضور برترین کارشناسان"
                link="مشاهده همه خدمات" />
            <!-- <div class="swiper swiper-container"> -->
            <Swiper :slides-per-view="3" class="w-full swiper-services3 max-lg:overflow-visible">
                <SwiperSlide class="max-lg:w-[270px]">
                    <div class="h-[220px]">
                        <img src="~/assets/img/picture-3.png" class="w-full h-full" alt="">
                    </div>
                    <div class="lg:p-9 p-4 bg-white lg:h-[248px] h-[190px]">
                        <h3 class="title-public line-clamp-1">
                            کمپین دیجیتال مارکتینگ
                        </h3>
                        <p class="text-public text-public-small lg:mb-4 mb-3 line-clamp-4">
                            لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان
                            گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است.
                        </p>
                        <a href="#" class="btn-link">
                            جزئیات
                            <i class="icon-left-arrow"></i>
                        </a>
                    </div>
                </SwiperSlide>
                <SwiperSlide class="max-lg:w-[270px]">
                    <div class="h-[220px]">
                        <img src="~/assets/img/picture-4.png" class="w-full h-full" alt="">
                    </div>
                    <div class="lg:p-9 p-4 bg-white lg:h-[248px] h-[190px]">
                        <h3 class="title-public line-clamp-1">
                            طراحی برند بوک
                        </h3>
                        <p class="text-public text-public-small lg:mb-4 mb-3 line-clamp-4">
                            لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان
                            گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است.
                        </p>
                        <a href="#" class="btn-link">
                            جزئیات
                            <i class="icon-left-arrow"></i>
                        </a>
                    </div>
                </SwiperSlide>
                <SwiperSlide class="max-lg:w-[270px]">
                    <div class="h-[220px]">
                        <img src="~/assets/img/picture-5.png" class="w-full h-full" alt="">
                    </div>
                    <div class="lg:p-9 p-4 bg-white lg:h-[248px] h-[190px]">
                        <h3 class="title-public line-clamp-1">
                            سئو و بهینه سازی
                        </h3>
                        <p class="text-public text-public-small lg:mb-4 mb-3 line-clamp-4">
                            لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان
                            گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است.
                        </p>
                        <a href="#" class="btn-link">
                            جزئیات
                            <i class="icon-left-arrow"></i>
                        </a>
                    </div>
                </SwiperSlide>
            </Swiper>
            <!-- </div> -->
        </div>
    </div>
    <!-- END-SERVICES-2 -->
</template>