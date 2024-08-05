<script>
  import CtAs from "./CTAs.svelte";
  import Header from "./Header.svelte";
  import SectionWrapper from "./SectionWrapper.svelte";
</script>

<SectionWrapper>
  <Header></Header>
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
      Still in development... but we have a discord server!! You can join our
      server. By joining you will also help us build our community.
    </p>
    <CtAs></CtAs>
  </div>
</SectionWrapper>
