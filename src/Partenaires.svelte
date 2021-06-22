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
                    <a href="/projets" class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">
                        Projets
                    </a>
                    <a href="/partenaires" class="border-transparent text-gray-900 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">
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
            Partenaires
        </h2>
    </div>
    <div class="bg-white">
        <div class="mx-auto py-12 px-4 max-w-6xl sm:px-6 lg:px-8 lg:py-24">
            <div class="space-y-12 ">
                <ul class="space-y-12 sm:grid sm:grid-cols-2 sm:gap-x-6 sm:gap-y-12 sm:space-y-0 lg:grid-cols-3 lg:gap-x-8">
                <div class="bg-white border sm:rounded-lg" style="height: 400px; padding-top: 30px">
                    <div class="justify-center" style="height: 150px; width:200px">
                        <img class="object-cover rounded-lg" src="static/nice.png" style="margin-left: 70px" alt="">
                    </div>
                    <div class="px-4 max-h-screen py-5 sm:px-6 justify-center">
                        <h2 class="text-lg leading-6 font-medium text-gray-900">
                            Ville de Nice
                        </h2>
                        <p class="mt-1  text-sm text-gray-500 justify-center">
                            La ville de Nice soutient particulièrement le projet qui revêt une certaine valeur patrimoniale, étant tournée dans le lieu historique qu’est le Théâtre National de Nice, un lieu voué à la destruction et qui aura su marquer le cœur des Niçois.
                        </p>
                        <br>
                    </div>
                </div>
                <div class="bg-white border sm:rounded-lg" style="height: 400px; padding-top: 30px">
                    <div class="justify-center" style="height: 100px; width:200px">
                        <img class="object-cover rounded-lg" src="static/tnn.jpg" style="margin-left: 70px" alt="">
                    </div>
                    <div class="px-4 max-h-screen py-5 sm:px-6 justify-center">
                        <h2 class="text-lg leading-6 font-medium text-gray-900">
                            Théâtre National de Nice
                        </h2>
                        <p class="mt-1  text-sm text-gray-500 justify-center">
                            Murielle Mayette-Holtz nous accueille dans le sein de son prestigieux théâtre, dont la beauté promet de faire de « Double Je » un film à l’esthétique marquée.
                        </p>
                        <br>
                    </div>
                </div>
                <div class="bg-white border sm:rounded-lg" style="height: 400px; padding-top: 30px">
                    <div class="justify-center" style="height: 100px; width:200px">
                        <img class="object-cover rounded-lg" src="static/visual_sequence.jpg" style="margin-left: 70px" alt="">
                    </div>
                    <div class="px-4 max-h-screen py-5 sm:px-6 justify-center">
                        <h2 class="text-lg leading-6 font-medium text-gray-900">
                            Visual Sequence
                        </h2>
                        <p class="mt-1  text-sm text-gray-500 justify-center">
                            Parmi les entreprises de location de matériels audiovisuels les plus implantées dans la région, Visual Sequence s’engage à fournir le matériel nécessaire à la production de notre film, nous accompagnant jusque dans sa réalisation : le steadycamer Nicolas Roux et son premier assistant caméra seront un atout de poids dans l’exécution du projet, tourné avec la ARRI Alexa Mini LF.
                        </p>
                        <br>
                    </div>
                </div>
                <div class="bg-white border sm:rounded-lg" style="height: 400px;">
                    <div class="justify-center" style="height: 100px; width:200px">
                        <img class="object-cover rounded-lg" src="static/ami.jpg" style="margin-left: 70px" alt="">
                    </div>
                    <div class="px-4 max-h-screen py-5 sm:px-6 justify-center" style="margin-top: 50px">
                        <h2 class="text-lg leading-6 font-medium text-gray-900">
                            AMI Paris
                        </h2>
                        <p class="mt-1  text-sm text-gray-500 justify-center">
                            Entreprise de prêt-à-porter particulièrement en vogue, AMI fait à nos côtés ses premiers pas dans le cinéma. Alexandre Mattiussi est pour la première fois de sa carrière styliste de cinéma.
                        </p>
                        <br>
                    </div>
                </div>
                <div class="bg-white border sm:rounded-lg" style="height: 400px; padding-top: 30px">
                    <div class="justify-center" style="height: 100px; width:200px">
                        <img class="object-cover rounded-lg" src="static/silverway.png" style="margin-left: 70px" alt="">
                    </div>
                    <div class="px-4 max-h-screen py-5 sm:px-6 justify-center">
                        <h2 class="text-lg leading-6 font-medium text-gray-900">
                            SILVERWAY
                        </h2>
                        <p class="mt-1  text-sm text-gray-500 justify-center">
                            Le laboratoire numérique réputé nous fait l’honneur de prendre en charge la post-production, nous garantissant un montage, mixage et étalonnage à la hauteur de nos ambitions.
                        </p>
                    </div>
                </div>
                <div class="bg-white border sm:rounded-lg" style="height: 400px; padding-top: 30px">
                    <div class="justify-center" style="height: 100px; width:200px">
                        <img class="object-cover rounded-lg" src="static/region_sud.png" style="margin-left: 70px" alt="">
                    </div>
                    <div class="px-4 max-h-screen py-5 sm:px-6 justify-center">
                        <h2 class="text-lg leading-6 font-medium text-gray-900">
                            Région SUD
                        </h2>
                        <p class="mt-1  text-sm text-gray-500 justify-center">
                            Première aide étatique sur nos projets, la Région nous permet de réaliser des films à la hauteur de nos ambitions.
                        </p>
                    </div>
                </div>
                <div class="bg-white border sm:rounded-lg" style="height: 400px; padding-top: 30px">
                    <div class="justify-center" style="height: 100px; width:200px">
                        <img class="object-cover rounded-lg" src="static/proarti.png" style="margin-left: 70px" alt="">
                    </div>
                    <div class="px-4 max-h-screen py-5 sm:px-6 justify-center">
                        <h2 class="text-lg leading-6 font-medium text-gray-900">
                            Proarti
                        </h2>
                        <p class="mt-1  text-sm text-gray-500 justify-center">
                            Un fond de dotations culturelles très implanté qui permet à notre entreprise d’avoir recours au mode de financement alternatif très efficace qu’est le mécénat culturel, via la défiscalisation qu’elle offre à nos partenaires.
                        </p>
                    </div>
                </div>
                <div class="bg-white border sm:rounded-lg" style="height: 400px; padding-top: 120px">
                    <div class="justify-center" style="height: 100px; width:200px">
                        <img class="object-cover rounded-lg" src="static/albane.png" style="margin-left: 70px" alt="">
                    </div>
                    <div class="px-4 max-h-screen py-5 sm:px-6 justify-center">
                        <h2 class="text-lg leading-6 font-medium text-gray-900">
                            Albane Communication
                        </h2>
                    </div>
                </div>
                <div class="bg-white border sm:rounded-lg" style="height: 400px; padding-top: 50px">
                    <div class="justify-center" style="height: 100px; width:200px">
                        <img class="object-cover rounded-lg" src="static/panorama.jpg" style="margin-left: 70px" alt="">
                    </div>
                    <div class="px-4 max-h-screen py-5 sm:px-6 justify-center">
                        <h2 class="text-lg leading-6 font-medium text-gray-900" style="padding-top: 120px">
                            Mome
                        </h2>
                    </div>
                </div>
                <div class="bg-white border sm:rounded-lg" style="height: 400px; padding-top: 120px">
                    <div class="justify-center" style="height: 100px; width:200px">
                        <img class="object-cover rounded-lg" src="static/cnc.png" style="margin-left: 70px" alt="">
                    </div>
                    <div class="px-4 max-h-screen py-5 sm:px-6 justify-center">
                        <h2 class="text-lg leading-6 font-medium text-gray-900">
                            CNC
                        </h2>
                    </div>
                </div>
                <div class="bg-white border sm:rounded-lg" style="height: 400px; padding-top: 120px">
                    <div class="justify-center" style="height: 100px; width:200px">
                        <img class="object-cover rounded-lg" src="static/esra.png" style="margin-left: 70px" alt="">
                    </div>
                    <div class="px-4 max-h-screen py-5 sm:px-6 justify-center">
                        <h2 class="text-lg leading-6 font-medium text-gray-900">
                            Esra
                        </h2>
                    </div>
                </div>
                <div class="bg-white border sm:rounded-lg" style="height: 400px; padding-top: 120px">
                    <div class="justify-center" style="height: 100px; width:200px">
                        <img class="object-cover rounded-lg" src="static/cinequanon.png" style="margin-left: 70px" alt="">
                    </div>
                    <div class="px-4 max-h-screen py-5 sm:px-6 justify-center">
                        <h2 class="text-lg leading-6 font-medium text-gray-900">
                            Cine Qua Non
                        </h2>
                    </div>
                </div>
            </ul>
        </div>
    </div>
    </div>
</main>
</body>