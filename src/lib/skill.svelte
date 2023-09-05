<script>
    export let lang = ""
    export let svg
</script>

<div class="hover:scale-105 ease-in duration-300">

    <div
        class="h-full flex hover:invert  items-center justify-center rounded-xl sm:p-4 px-4 py-2 shadow-sm bg-white border border-2 border-gray-900" 
        data-aos="zoom-out-left" 
        data-aos-once="true"
        data-aos-easing="ease-out-quart"
        data-aos-duration="1000"

        
    >
        <span class="inline-block rounded-lg bg-white ">
            <img class="sm:h-10 sm:w-10 h-9 w-9" src="{svg}">
        </span>



        <h2 class="self-center mx-2 font-bold text-md sm:text-lg">{lang}</h2>
    </div>
</div>