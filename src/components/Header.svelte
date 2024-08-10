<script>
    import SectionWrapper from "./SectionWrapper.svelte";
    import { openModal } from "../store";
</script>

<header class="flex flex-col relative z-20">
    <div
        class="max-w-[1400px] mx-auto w-full flex items-center justify-between p-4 py-6"
    >
        <a href="/">
            <h1 class="font-semibold text-blue-400">
                Lid<span class="text-indigo-800">Tek</span>
            </h1>
        </a>
        <button
            on:click={() => ($openModal = true)}
            class="md:hidden grid place-items-center"
        >
            <i class="fa-solid fa-bars"></i>
        </button>
        <nav class="hidden md:flex items-center gap-4 lg:gap-6">
            <a
                href="https://github.com/LidTek"
                class="duration-200 hover:text-blue-600 cursor-pointer"
            >
                <i class="fa-brands fa-github pr-2" />
                Github
            </a>
            <a
                href="/goal"
                class="duration-200 hover:text-blue-600 cursor-pointer"
                >Our Goal</a
            >
            <button class="specialBtn">
                <a href="https://discord.gg/fmYnZss29N">Join Our Discord!</a>
            </button>
        </nav>
    </div>
</header>
