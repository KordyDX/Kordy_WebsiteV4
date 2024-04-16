<script>
    import ToggleMode from "./toggleMode.svelte";
    import Separator from "$lib/components/ui/separator/separator.svelte";
</script>

<div
    class="rounded-3xl text-foreground flex flex-col bg-secondary"
>
    <div class="p-6 flex flex-col gap-4 place-items-center">
        <img class="rounded-full rotate-180" src="/bulb.png" alt="" />
        <h1 class="text-4xl"><b>Kristián Stefurak</b></h1>
        <h2 class="socBox text-xl bg-primary p-3 rounded-2xl">Webový developer</h2>
        <Separator class="bg-ring" />
        <div class="flex flex-col gap-4">
            <div class="flex place-items-center gap-3">
                <a
                    class="socBox p-4 rounded-xl"
                    target="_blank"
                    href="mailto:kristianstefurak@gmail.com"
                >
                    <img src="/email.svg" alt="" srcset="" />
                </a>
                <div>
                    <h2>Email</h2>
                    <a target="_blank" href="mailto:kristianstefurak@gmail.com"
                        >kristianstefurak@gmail.com</a
                    >
                </div>
            </div>
            <div class="flex place-items-center gap-3">
                <a
                    class="socBox p-4 rounded-xl"
                    target="_blank"
                    href="https://github.com/KordyDX/"
                >
                    <img src="/github.svg" alt="" srcset="" />
                </a>
                <div>
                    <h2>Github</h2>
                    <a target="_blank" href="https://github.com/KordyDX/"
                        >KordyDX</a
                    >
                </div>
            </div>
            <div class="flex place-items-center gap-3">
                <a
                    class="socBox p-4 rounded-xl"
                    target="_blank"
                    href="https://www.google.com/maps/place/D%C4%9B%C4%8D%C3%ADn+District/@50.8495579,14.0167064,10z/data=!3m1!4b1!4m6!3m5!1s0x47090ba3587da30f:0x300af0f6614aae0!8m2!3d50.908578!4d14.4753016!16zL20vMDlteDk4?entry=ttu"
                >
                    <img src="/marker.svg" alt="" srcset="" />
                </a>
                <div>
                    <h2>Bydliště</h2>
                    <a
                        target="_blank"
                        href="https://www.google.com/maps/place/D%C4%9B%C4%8D%C3%ADn+District/@50.8495579,14.0167064,10z/data=!3m1!4b1!4m6!3m5!1s0x47090ba3587da30f:0x300af0f6614aae0!8m2!3d50.908578!4d14.4753016!16zL20vMDlteDk4?entry=ttu"
                        >Okres Děčín</a
                    >
                </div>
            </div>
            <div class="flex flex-row gap-5 place-content-center place-items-center">
                <a target="_blank" href="https://www.instagram.com/kristian_kordy/"><img src="/instagram.svg" alt="" /></a>
                <a target="_blank" href="https://discordapp.com/users/399983880548909057"><img src="/discord.svg" alt="" /></a>
                <a target="_blank" href="https://twitter.com/KristianNeAsi"><img src="/x.svg" alt="" /></a>
                <ToggleMode/>

            </div>
        </div>
    </div>
</div>

<style lang="css">
    .socBox {
    }
</style>
