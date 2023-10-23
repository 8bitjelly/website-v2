<template>
    <div class="bg-[#A48DA1] py-4">
        <div class="w-full flex justify-center mb-8 mt-4">
            <nuxt-img class="h-16" src="/logo_white.png" />
        </div>

        <div class="flex flex-wrap justify-center gap-x-3 gap-y-2 mx-8 text-white">
            <NuxtLink to="#">{{ $t('menu.tech') }}</NuxtLink>
            <NuxtLink to="#">{{ $t('menu.blog') }}</NuxtLink>
            <NuxtLink to="#">{{ $t('menu.about') }}</NuxtLink>
            <NuxtLink to="#">{{ $t('menu.projects') }}</NuxtLink>
            <NuxtLink to="#">{{ $t('menu.policy') }}</NuxtLink>
        </div>

        <hr class="border-darker border-1 mx-8 my-4">
       
        <p class="text-darker text-center mb-4">© 2023 8BitJelly. MIT</p>

        <div class="flex justify-center gap-x-4">
            <NuxtLink to="#">
                <nuxt-img src="/svg/instagram-logo-duotone.svg" />
            </NuxtLink>
            <NuxtLink to="#">
                <nuxt-img src="/svg/facebook-logo-duotone.svg" />
            </NuxtLink>
            <NuxtLink to="#">
                <nuxt-img src="/svg/github-logo-duotone.svg" />
            </NuxtLink>
            <NuxtLink to="#">
                <nuxt-img src="/svg/discord-logo-duotone.svg" />
            </NuxtLink>
        </div>

    </div>
</template>