<script>
export default {
    name: 'Hero'
}
</script>


<template>
    <div class="logo flex justify-center my-[7em]">
        <img src="../assets/logo.svg" alt="page logo">
    </div>

    <div class="w-[1440px] mx-auto flex justify-between mt-[4em]">
        <div class="img-left">
            <img src="../assets/image-hero-left.png" alt="">
        </div>
        <div class="hero-text mx-[2em]">
            <h1 class="text-preset-1 mb-[0.5em] slate-900">Group Chat<br/>for Everyone</h1>
            <p class="text-preset-4 slate-600 max-w-[26em] mb-[2em]">Meet makes it easy to connect with others face-to-face virtually and collaborate across any device.</p>
            <div class="btn-container flex gap-[1em] justify-center">
                <button class="btn px-6 py-3 bg-[#4D96A9] rounded-full text-preset-5 text-white">Download <span class="text-[#8FE3F9]">v1.3</span></button>
                <button class="btn btn px-6 py-3 bg-[#855FB1] rounded-full text-preset-5 text-white">What is it?</button>
            </div>
        </div>
        <div class="img-right">
            <img src="../assets/image-hero-right.png" alt="">
        </div>
    </div>

</template>

