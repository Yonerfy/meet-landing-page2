<script>
     export default {
        name: 'Footer'
    }
</script>

<template>
    <footer class="relative bg-[url(./assets/image-footer.jpg)] bg-no-repeat bg-cover">
        <div class="absolute inset-0 bg-[#4D96A9] opacity-90 z-0"></div>
        <div class="footer-container md:px-[5em] px-[2em] py-[7em] z-10 relative flex justify-between">
            <div class="col-title mb-[1.5em] flex-1/3">
                <h4 class="text-preset-2 text-white text-center md:text-left">Experience more together</h4>
            </div>
            <div class="col-par mb-[1.5em] flex-1/3">
                <p class="text-white text-preset-4 md:w-[25em] w-[20em] md:text-left text-center xl:px-8">Stay connected with reliable HD meetings and unlimited one-on-one and group video sessions.</p>
            </div>
            <div class="col-button flex-1/3">
                <button class="btn px-6 py-3 bg-[#855FB1] rounded-full text-preset-5 text-white">Download <span class="text-[#8FE3F9]">v1.3</span></button>
            </div>
        </div>
    </footer>
</template>