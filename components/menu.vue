<template>
    <div class="h-16 py-4 ">
        <div class="flex justify-center items-center gap-x-4">
            <NuxtLink to="#" class="text-lg font-semibold">{{ $t('menu.tech') }}</NuxtLink>
            <NuxtLink to="#" class="text-lg font-semibold">{{ $t('menu.blog') }}</NuxtLink>
            <nuxt-img class="h-16" loading="lazy" src="/logo_black.svg" alt="8BitJelly"/>
            <NuxtLink to="#" class="text-lg font-semibold">{{ $t('menu.about') }}</NuxtLink>
            <NuxtLink to="#" class="text-lg font-semibold">{{ $t('menu.projects') }}</NuxtLink>
        </div>
    </div>
</template>