
import type { PublicFooterCommunication } from '#build/components';

import type { PublicFooterLinks } from '#build/components';

import type { PublicFooterContext } from '#build/components';
<template>
    <!--START-FOOTER-->
    <footer>

        <div class="py-between-section bg-dark">
            <div class="container 2xl:px-28 xl:px-20 lg:px-16">
                <div class="flex max-lg:flex-wrap items-start xl:-m-14 lg:-m-10">
                    <PublicFooterContext/>
                    <PublicFooterLinks/>
                    <PublicFooterCommunication/>
                </div>
            </div>
        </div>

    </footer>
    <!--END-FOOTER-->
</template>