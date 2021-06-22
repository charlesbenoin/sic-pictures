<script>
    export let name;
    let time = 0;
    let duration;
    export let size = 1500;
    let scrollY = 0;

    $: {
        const totalScroll =
            document.documentElement.scrollHeight - window.innerHeight;
        time = duration * (scrollY / totalScroll);
        size = (scrollY / 1600) * 100;
    }
</script>

<svelte:window bind:scrollY />


<main>
    <div class="scroll-container" >
        <div class="video-container">
            <video style="height: {100 - size}%"
                   bind:currentTime="{time}"
                   bind:duration
                   preload="metadata"
                   muted
                   src="static/SIC LOGO FF.mp4"
                   type="video/mp4"></video>
        </div>
    </div>
    <section>
        <div class="bg-white">
            <div class="mx-auto py-12 max-w-7xl sm:px-6 lg:px-8 lg:py-8">
                <div class="space-y-12">
                    <ul class="space-y-12 sm:grid sm:grid-cols-2 sm:gap-x-6 sm:gap-y-12 sm:space-y-0 lg:grid-cols-3 lg:gap-x-8">
                        <li>
                            <a class="space-y-4" href="/projets">
                                <div class="aspect-w-3 aspect-h-2">
                                    <img class="object-cover shadow-lg rounded-lg" src="static/double_je.png" alt="">
                                </div>

                                <div class="space-y-2">
                                    <div class="text-lg leading-6 font-medium space-y-1">
                                        <a class="hover:underline">Projets</a>
                                    </div>
                                </div>
                            </a>
                        </li>
                        <li>
                            <a class="space-y-4" href="/partenaires">
                                <div class="aspect-w-3 aspect-h-2">
                                    <img class="object-cover shadow-lg rounded-lg" src="static/nice.png" alt="">
                                </div>

                                <div class="space-y-2">
                                    <div class="text-lg leading-6 font-medium space-y-1">
                                        <h3>Partenaires</h3>
                                    </div>
                                </div>
                            </a>
                        </li>
                        <li>
                            <a class="space-y-4" href="/contact">
                                <div class="aspect-w-3 aspect-h-2">
                                    <img class="object-cover shadow-lg rounded-lg" src="static/contact.png" alt="">
                                </div>

                                <div class="space-y-2">
                                    <div class="text-lg leading-6 font-medium space-y-1">
                                        <h3>Contact</h3>
                                    </div>
                                </div>
                            </a>
                        </li>

                        <!-- More people... -->
                    </ul>
                </div>
            </div>
        </div>
    </section>
</main>

<style>
    .scroll-container {
        height: 1200px;
    }

    .video-container {
        position: absolute;
        top: 0;
        left: 50%;
        overflow: hidden;
    }

    .video-container video {
        position: fixed;
        transform: translate(-50%);
        height: var(--size);

    }
</style>
