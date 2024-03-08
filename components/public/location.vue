<template>
    <!-- START-LOCATION -->
    <div class="lg:py-6 py-4 bg-natural-alpha">
        <div class="container flex items-center">
            <RouterLink to="/" class="lg:me-6 me-4">
                <i class="icon-home text-natural-beta lg:text-2xl text-lg"></i>
            </RouterLink>
            <ul class="flex items-center text-dark text-md lg:-mx-4 -mx-2.5">
                <li>
                    <RouterLink to="/"
                        class="py-1 lg:px-4 px-2.5 text-dark hover:text-primary font-semibold lg:text-2base text-sm">
                        صفحات
                    </RouterLink>
                </li>
                .
                <li>
                    <RouterLink :to="link"
                        class="py-1 lg:px-4 px-2.5 text-dark hover:text-primary font-semibold lg:text-2base text-sm">
                        {{ name }}
                    </RouterLink>
                </li>
            </ul>
        </div>
    </div>
    <!-- END-LOCATION -->
</template>

<script setup>
let {name,link} = defineProps(['name','link']);
</script>