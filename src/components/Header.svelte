<script>
  import SectionWrapper from "./SectionWrapper.svelte";
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
    <button class="md:hidden grid-place">
      <i class="fa-solid fa-bars"></i>
    </button>
    <nav class="hidden md:flex items-center gap-4 lg:gap-6">
      <a href="" class="duration-200 hover:text-blue-600 cursor-pointer"
        >The Project</a
      >
      <a href="" class="duration-200 hover:text-blue-600 cursor-pointer"
        >Our Goal</a
      >
      <button class="specialBtn">
        <a href="https://discord.gg/fmYnZss29N">Join Our Discord!</a>
      </button>
    </nav>
  </div>
</header>
