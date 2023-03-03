<script>
    const Lock = () => {
        const toggle = document.getElementById('socials')
        const arrow = document.getElementById('arrow')
        toggle.classList.toggle('hidden')
        arrow.classList.toggle('rotate-180')
        arrow.classList.toggle('pr-0')
        arrow.classList.toggle('pr-[13px]')
    }

</script>

<div class="flex border-[2px] rounded-[20px] border-[#D9D9D9]">
    <!-- svelte-ignore a11y-click-events-have-key-events -->
    <img id="arrow" on:click={Lock} class="cursor-pointer p-[10px] pl-[13px] pr-0" src="/arrow.svg" alt="arrow">
    <div id="socials" class="socials flex justify-center items-center gap-[13px] px-[13px] border-l-[2px] border-r-[2px] border-[#D9D9D9] hidden">
        <a href="/" class="rounded-full">
            <img src="/whatsappLink.svg" alt="whatsapp">
        </a>
        <a href="/" class="rounded-full">
            <img src="/vkLink.svg" alt="">
        </a>
        <a href="/" class="rounded-full">
            <img src="/telegramLink.svg" alt="">
        </a>
    </div>
    <!-- svelte-ignore a11y-click-events-have-key-events -->
    <img on:click={Lock} class="earth-btn cursor-pointer p-[10px] pl-[13px]" src="/earth.svg" alt="earth">
</div>


<style>
</style>
