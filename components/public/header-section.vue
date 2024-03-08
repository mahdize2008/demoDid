<template>
    <div class="header-section text-center" :class="link ? '!text-right me-auto pe-4' : ''">
        <h2 class="header-title-public" :class="lightMode ? 'header-title-public-white' : ''">
            {{ title }}
        </h2>
        <h4 class="header-subtitle-public" :class="lightMode ? 'header-subtitle-public-white' : ''">
            {{ subtitle }}
        </h4>
    </div>
    <a v-if="link" href="#" class="header-section-link max-sm:relative max-sm:z-10">
        {{ link }}
        <i class="icon-left-arrow"></i>
    </a>
</template>

<script setup>
let { title, subtitle, link, lightMode } = defineProps(['title', 'subtitle', 'link', 'lightMode'])
</script>