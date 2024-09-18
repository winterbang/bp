<template>
    <div>
        <div class="h-96 bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500">
        
        </div>

        <section class="container mx-auto py-10">
            <div class="flex justify-between items-center">
                <span class="text-3xl font-bold">我们的服务</span>
            </div>
            <div class="grid grid-cols-4 gap-4 mt-10">
                <div v-for="i in 4" :key="i" class="h-32 bg-white rounded-lg border border-slate-50 shadow-lg my-5">
                </div>
            </div>
        </section>
        <section class="container mx-auto py-10">
            <div class="flex justify-between items-center">
                <span class="text-3xl font-bold">客户案例</span>
                <span>查看更多案例>></span>
            </div>

            <div class="grid grid-cols-4 gap-4 mt-10">
                <div v-for="i in 4" :key="i" class="h-32 bg-white rounded-lg border border-slate-50 shadow-lg my-5">

                </div>
            </div>
        </section>
    </div>

  </template>