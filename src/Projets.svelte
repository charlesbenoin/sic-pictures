<script>
    import { onMount } from "svelte";

    onMount(() => {
        window.scrollTo(0, 0);
    });
</script>

<body>
<nav class="bg-white shadow">
    <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8">
        <div class="relative flex justify-between h-16">
            <div class="flex-1 flex items-center justify-center sm:items-stretch sm:justify-center">
                <div class="hidden sm:ml-6 sm:flex sm:space-x-8">
                    <!-- Current: "border-indigo-500 text-gray-900", Default: "border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700" -->
                    <a href="/" class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">
                        Accueil
                    </a>
                    <a href="/projets" class="border-transparent text-gray-900 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">
                        Projets
                    </a>
                    <a href="/partenaires" class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">
                        Partenaires
                    </a>
                    <a href="/contact" class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">
                        Contact
                    </a>
                </div>
            </div>
        </div>
    </div>
</nav>
<main class="py-10">
    <div class="relative">
        <h2 class="text-center text-3xl leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">
            Projets
        </h2>
    </div>
    <div class="mt-8 max-w-3xl mx-auto gap-6 sm:px-6 lg:max-w-xl ">
        <div class="space-y-6 lg:col-start-1 lg:col-span-2 justify-center">
    <section aria-labelledby="applicant-information-title">
            <div class="bg-white border sm:rounded-lg ">
                <div class="px-4 py-5 sm:px-6 justify-center">
                    <h2 id="applicant-information-title" class="text-lg leading-6 font-medium text-gray-900">
                        Avant-Garde
                    </h2>
                    <p class="mt-1  text-sm text-gray-500 justify-center">
                        Frontière franco-allemande.
                        Felix Linneman, un galeriste berlinois, se  rend en France pour une exposition. Il transporte avec lui la sculpture phare  de sa collection. Face à l’objet, le douanier français hésite : s’agit-il vraiment  d’une œuvre d’art ?
                    </p>
                    <br>
                    <h5>
                        <a href="https://vimeo.com/manage/videos/529048214/a14cc08b55" target="_blank">Voir la bande annonce</a>
                    </h5>
                </div>
                    <div class="justify-center" style="height: 300px; width:400px">
                        <img class="object-cover shadow-lg rounded-lg" src="static/avant_garde.png" style="margin-left: 65px" alt="">
                    </div>
            </div>
            <div class="bg-white border sm:rounded-lg ">
                <div class="px-4 py-5 sm:px-6 justify-center">
                    <h2 class="text-lg leading-6 font-medium text-gray-900">
                        Le dernier bain
                    </h2>
                    <p class="mt-1  text-sm text-gray-500 justify-center">
                        Dans une chambre d'enfant, un étrange adulte s'amuse avec ses peluches. Mais que cache véritablement ces discussions ?
                    </p>
                    <br>
                    <h5>
                        <a href="https://vimeo.com/manage/videos/527436149" target="_blank">Voir la bande annonce</a>
                    </h5>
                </div>
                    <div class="justify-center" style="height: 600px; width:400px">
                        <img class="object-cover shadow-lg rounded-lg" src="static/dernier_bain.jpg" style="margin-left: 65px" alt="">
                    </div>
            </div>
            <div class="bg-white border sm:rounded-lg ">
                <div class="px-4 py-5 sm:px-6 justify-center">
                    <h2 class="text-lg leading-6 font-medium text-gray-900">
                        Double Je
                    </h2>
                    <p class="mt-1  text-sm text-gray-500 justify-center">
                        Liam, un acteur candide, arrive dans une troupe de théâtre avec une admiration folle pour Eléa, l’actrice avec qui il partage l'affiche. Mais les deux acteurs se confrontent très vite à la violence psychologique et physique d'un metteur en scène prêt à tout pour faire une œuvre d'art authentique.
                    </p>
                    <br>
                    <h5>
                        <a href="https://vimeo.com/361297228" target="_blank">Voir la bande annonce</a>
                    </h5>
                </div>
                    <div class="justify-center" style="height: 300px; width:400px">
                        <img class="object-cover shadow-lg rounded-lg" src="static/double_je.png" style="margin-left: 65px" alt="">
                    </div>
            </div>
        </section>
        </div>
    </div>
</main>
</body>


<style>
    .wrap {
        max-width: 600px;
        margin: 0 auto;
    }
    .vp {
        margin-bottom: 10px;
    }
</style>