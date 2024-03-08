<template>
    <!-- START-SIGN-IN -->
    <div class="pb-between-section bg-natural-alpha">
        <div class="container 2xl:px-28 xl:px-20 lg:px-16">
            <div class="flex max-xl:flex-wrap rounded-2xl overflow-hidden items-center">
                <div
                    class="xl:w-[212px] w-full xl:h-[212px] h-[150px] bg-gradient-danger flex items-center justify-center z-10 relative">
                    <i class="icon-mail text-white text-20xl"></i>
                </div>
                <form class="grow bg-dark xl:p-16 lg:p-12 p-5 flex flex-wrap justify-between xl:-m-3">
                    <div class="xl:grow max-xl:w-full xl:p-3 max-xl:mb-2">
                        <input type="text" class="input input-secondary" placeholder="نام و نام خانوادگی">
                    </div>
                    <div class="xl:grow max-xl:w-full xl:p-3 max-xl:mb-6 2xl:me-4 xl:me-2">
                        <input type="text" class="input input-secondary" placeholder="پست الکترونیک">
                    </div>
                    <div class="2xl:w-1/4 xl:w-fit max-xl:ms-auto xl:p-3">
                        <button type="submit"
                            class="btn-public btn-secondary bg-white hover:!text-dark text-dark lg:h-full xl:w-full">
                            عضو شوید
                            <i class="icon-left-arrow  xl:!ms-8 !ms-4 !text-dark"></i>
                        </button>
                    </div>
                </form>
            </div>
        </div>
    </div>
    <!-- END-SIGN-IN -->
</template>