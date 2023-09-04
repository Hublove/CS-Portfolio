<script>
    export let lang = ""
    export let svg
</script>

<div class="hover:scale-105 ease-in duration-300">

    <div
        class="flex hover:invert justify-center rounded-xl p-4 shadow-sm bg-white border border-2 border-gray-900" 
        data-aos="zoom-out-left" 
        data-aos-once="true"
        data-aos-easing="ease-out-quart"
        data-aos-duration="1000"

        
    >
        <span class="inline-block rounded-lg bg-white m3">
            <img class="h-10 w-10" src="{svg}">
        </span>



        <h2 class="self-center mx-2 font-bold text-lg">{lang}</h2>
    </div>
</div>