<template>
    <ul class="flex items-center me-auto max-lg:hidden">
        <li class="me-8 last:me-0">
            <RouterLink to="/" class="text-dark hover:text-primary transition-all text-base font-semibold py-1">
                خانه
            </RouterLink>
        </li>
        <li class="me-8 last:me-0">
            <RouterLink to="/about-us" class="text-dark hover:text-primary transition-all text-base font-semibold py-1">
                درباره ما
            </RouterLink>
        </li>
        <li class="me-8 last:me-0">
            <RouterLink to="/services-archive" class="text-dark hover:text-primary transition-all text-base font-semibold py-1 flex items-center">
                خدمات
                <i class="icon-down text-xs font-bold ms-4"></i>
            </RouterLink>
        </li>
        <li class="me-8 last:me-0">
            <a href="#" class="text-dark hover:text-primary transition-all text-base font-semibold py-1">
                پرسش های متداول
            </a>
        </li>
        <li class="me-8 last:me-0">
            <RouterLink to="/blog-archive" class="text-dark hover:text-primary transition-all text-base font-semibold py-1">
                وبلاگ
            </RouterLink>
        </li>
        <li class="me-8 last:me-0">
            <RouterLink to="/contact-us" class="text-dark hover:text-primary transition-all text-base font-semibold py-1">
                تماس با ما
            </RouterLink>
        </li>
    </ul>
</template>