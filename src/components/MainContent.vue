<script>
    export default {
        name: 'MainContent'
    }
</script>

<template>
    <main class="main-content flex flex-col items-center">
        <div class="line-container-top flex flex-col justify-center items-center mt-[8em] mb-[4em]">
            <div class="vertical-line w-[0.038em] h-16 bg-[#D1D1DF] flex justify-center items-center"></div>
            <div class="circle-line flex justify-center items-center w-[3em] h-[3em] border-[#D1D1DF] border rounded-full slate-600 text-preset-5"> 01</div>
        </div>
        <div class="img-container flex justify-between flex-wrap gap-[2em] mb-[4em]">
            <img class="w-64 h-64 rounded-lg" src="../assets/image-woman-in-videocall.jpg" alt="">
            <img class="w-64 h-64 rounded-lg" src="../assets/image-women-videochatting.jpg" alt="">
            <img class="w-64 h-64 rounded-lg" src="../assets/image-men-in-meeting.jpg" alt="">
            <img class="w-64 h-64 rounded-lg" src="../assets/image-man-texting.jpg" alt="">
        </div>
        <div class="main-text-container">
            <h3 class="text-preset-3 cyan-600 mb-[1em]">Built for modern use</h3>
            <h2 class="text-preset-2 slate-900 mb-[1em]">Smarter meetings, all<br> in one place</h2>
            <p class="text-preset-4 slate-600 max-w-[26em]">Send messages, share files, show your screen, and record your meetings — 
                all in one workspace. Control who can join with invite-only team access, data encryption, and data export.
            </p>
        </div>
        <div class="line-container-bottom flex flex-col justify-center items-center mt-[3.5em] relative top-[25px] z-40">
            <div class="vertical-line w-[0.038em] h-16 bg-[#D1D1DF] flex justify-center items-center"></div>
            <div class="circle-line bg-white flex justify-center items-center w-[3em] h-[3em] border-[#D1D1DF] border rounded-full slate-600 text-preset-5"> 02</div>
        </div>
    </main>
</template>