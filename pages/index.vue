<style>
.header {
    position: absolute;
    margin-top: 9%;
    margin-left: 16%;
}
.description {
    position: absolute;
    margin-top: 16%;
    margin-left: 16%;
}
.white-side {
    border-top-right-radius: 50%;
}
.black-side {
    border-bottom-left-radius: 50%;
}
</style>
<template>
    <div class='w-screen h-screen flex background'>
        <div class='h-full w-3/5 bg-black overflow-visible'>
            <div class='h-full w-full bg-white white-side overflow-visible'>
                <h1 class='text-white mix-blend-difference text-8xl header'>seleneace</h1>
                <h1 class='text-white mix-blend-difference text-5xl description'>Providing the infrastructure for space exploration</h1>
            </div>
        </div>
        <div class='h-full w-2/5 bg-white'>
            <div class='h-full w-full bg-black black-side'></div>
        </div>
    </div>


</template>