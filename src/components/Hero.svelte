<script>
  import CtAs from "./CTAs.svelte";
  import Header from "./Header.svelte";
  import SectionWrapper from "./SectionWrapper.svelte";
</script>

<SectionWrapper>
  <div
    class="flex flex-col gap-10 flex-1 items-center justify-center pb-10 md:pb-14"
  >
    <h2
      class="text-5xl sm:text-6xl md:text-7xl lg:text-8xl max-w-[1200px] mx-auto w-full text-center font-semibold text-blue-400"
    >
      Lid<span class="text-indigo-800">Tek</span>
    </h2>
    <p
      class="text-xl sm:text-2xl md:text-3xl text-center max-w-[1000px] mx-auto w-full"
    >
      We are curious about learning new things,
    </p>
    <CtAs></CtAs>
    <h3
      class="text-2xl sm:text-3xl md:text-4xl max-w-[1200px] mx-auto w-full text-center font-semibold text-blue-700"
    >
      Our First Project!
    </h3>
    <p
      class="text-xl sm:text-2xl md:text-3xl text-center max-w-[1000px] mx-auto w-full"
    >
      a fun multiplayer drawing game using Golang, Svelte, and WebRTC!
    </p>
    <button class="specialBtnDark">
      <a
        href="https://drawniverse.gamu.group"
        class="text-base sm:text-lg md:text-xl">Drawniverse&copy;</a
      >
    </button>
  </div>
</SectionWrapper>
