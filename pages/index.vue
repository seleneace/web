<style>
.header {
    margin-top: 15%;
    margin-left: 15%;
    color: #6171ffff;
}
.description {
    margin-top: 2%;
    margin-left: 15%;
}
.btn-login {
    display: inline-block;
    margin-top: 1%;
    margin-left: 1%;
    width: 8%;
}
.white-side {
    border-top-right-radius: 50%;
}
.black-side {
    border-bottom-left-radius: 50%;
}
.pattern {
    background-color: #000000;
    opacity: 1;
    background-image:  radial-gradient(#ffffff 1.8px, transparent 1.8px), radial-gradient(#ffffff 1.8px, #000000 1.8px);
    background-size: 72px 72px;
    background-position: 0 0,36px 36px;
}
</style>
<template>
    <!-- Page 1 -->
    <div class='w-screen h-screen flex'>
        <div class='h-full w-3/5 pattern overflow-visible'>
            <div class='h-full w-full bg-white white-side overflow-visible'>
                <button type="button" class="btn-login text-gray-900 bg-white border border-gray-300 focus:outline-none hover:bg-gray-100 focus:ring-4 focus:ring-gray-200 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2">Login</button>
                <h1 class='text-8xl header'>seleneace</h1>
                <h1 class='text-black text-5xl description'>Providing the infrastructure for space exploration</h1>
            </div>
        </div>
        <div class='h-full w-2/5 bg-white'>
            <div class='h-full w-full black-side pattern'/>
        </div>
    </div>
</template>