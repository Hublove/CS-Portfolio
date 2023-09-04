<script>
    export let Title = ""
    export let Desc = ""
    export let Langs = ""

    Langs = Langs.split(" ");

</script>

<a
    class="flex flex-col justify-between block rounded-xl border border-gray-800 p-8 shadow-xl transition hover:border-white/10 hover:shadow-white/10"
    href="https://github.com/Hublove/PhotographyPortfolio"
    data-aos="zoom-out" 
    data-aos-once="true"
    data-aos-easing="ease-out-quart"
>
    <div class="">
        <h2 class="mt-4 mb-4 text-3xl font-bold text-white ">{Title}</h2>

        <p class="mt-1 text-sm text-gray-300">
            {Desc}
        </p>
    </div>
            
    <div class="flex mt-4 ">
        {#each Langs as Lang}
            <p class="rounded-lg py-2 px-2 border bg-white text-gray-900  w-max mr-3">{Lang}</p>
        {/each}
    </div>
</a>