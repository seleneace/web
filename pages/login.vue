<style>
.background {
    background-color: rgb(229, 229, 247, 0.3);
}
.earth {
    height: 200%;
    width: 100%;
    border-radius: 50%;
    background-color: #000000;
    position: fixed;
    margin-left: 65%;
    margin-top: -5%;
}
.moon {
    height: 44%;
    width: 22%;
    border-radius: 50%;
    background-color: #000000;
    position: absolute;
    margin-left: 15%;
    margin-top: 5%;
}
</style>
<template>
    <div class='earth'></div>
    <div class='moon'></div>
    <div class='w-screen h-screen flex items-center justify-center background flex-col gap-y-4'>
        <h1 class='text-black text-5xl'>seleneace</h1>
        <div class='bg-white shadow-lg h-96 w-96 rounded-lg flex content-start items-center flex-col gap-y-6'>
            <div class='mt-12'>
                <label for="first_name" class="block mb-2 text-sm font-medium text-gray-900">Username</label>
                <input type="text" id="username" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5" required>
            </div>
            <div>
                <label for="first_name" class="block mb-2 text-sm font-medium text-gray-900">Password</label>
                <input type="password" id="password" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5" required>
            </div>
            <div>
                <button type="button" class="text-gray-900 bg-white border border-gray-300 focus:outline-none hover:bg-gray-100 focus:ring-4 focus:ring-gray-200 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2">Login</button>
            </div>
        </div>
    </div>
</template>