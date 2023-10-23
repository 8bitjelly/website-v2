<template>
    <div class="w-screen overflow-x-hidden">

        <Landing />

        <div class="mt-24">
            <div class="px-4 flex flex-col gap-y-2 mb-8">
                <p class="z-10 text-primary font-bold">- {{ $t('page.home.projects.sub') }}</p>
                <h1 class="z-10 text-darker text-4xl font-bold leading-tight">{{ $t('page.home.projects.title') }}</h1>
                <p class="z-10 text-darker/80 text-md font-light">{{ $t('page.home.projects.desc') }}</p>
            </div>
            <div class="slider w-full flex justify-center">
                <div>
                    <div class="bg-gray-400 w-64 h-64 rounded-xl mb-4"></div>
                    <p class="text-xl text-primary font-bold">Gierka 1</p>
                    <p class="text-darker">Lorem ipsum dolor</p>
                </div>
                
            </div>
        </div>

        <div class="mt-24 flex justify-center">
            <Tech />
        </div>

        <div class="mt-24">
            <div class="px-4 flex flex-col gap-y-2 mb-8">
                <p class="z-10 text-primary font-bold">- {{ $t('page.home.about.sub') }}</p>
                <h1 class="z-10 text-darker text-4xl font-bold leading-tight">{{ $t('page.home.about.title') }}</h1>
                <p class="z-10 text-darker/80 text-md font-light">{{ $t('page.home.about.desc') }}</p>
            </div>
            


        </div>
    </div>
</template>