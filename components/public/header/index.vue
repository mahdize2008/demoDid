<template>
    <!--START-HEADER-->
    <header>

    <PublicHeaderBanner/>

        <div class="lg:py-10 py-6 shadow-lighter-alpha">
            <div class="container flex max-lg:items-center">
                <a href="#" class="lg:me-auto lg:pe-8 me-auto pe-4 shrink-0">
                    <img src="~/assets/img/logo.png" class="lg:max-h-[62px] sm:max-h-[50px] max-h-[42px]" alt="">
                </a>
                <LazyPublicHeaderSearchbox/>
                
                <a href="tel:+02144304590"
                    class="flex items-center text-dark lg:text-base text-2base font-medium xl:me-10 lg:me-6 sm:me-4 me-2 shrink-0 max-sm:py-[9px] px-2 rounded max-sm:bg-primary-light-alpha">
                    <i class="icon-telephone text-primary sm:text-xl text-lg lg:me-4 sm:me-3"></i>
                    <span class="max-sm:hidden">
                        44304590 - 021
                    </span>
                </a>
                <a href="#" class="btn-public btn-public-light">
                    <i class="icon-headphones text-primary lg:text-xl text-lg lg:me-4 me-3"></i>
                    <span class="max-lg:hidden">دریافت</span> مشاوره
                </a>
            </div>
        </div>


        <div class="py-6">
            <div class="container flex lg:items-center">
                <PublicHeaderMenu/>
                <PublicHeaderSocialmedia/>
                
                
                
                <div class="flex items-center justify-center pe-3 me-3 cursor-pointer lg:hidden menu-button">
                    <i class="icon-layout1 text-dark text-xl"></i>
                </div>
                
                
                
                <LazyPublicHeaderMobilesearchbox/>

            </div>
        </div>


    </header>
    <!--END-HEADER-->
</template>