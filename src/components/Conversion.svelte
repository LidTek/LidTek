<script>
  import CtAs from "./CTAs.svelte";
</script>

<section
  class="py-14 md:py-20 flex flex-col gap-8 bg-[rgb(150,150,200)] text-white text-center items-center justify-center"
>
  <h4 class="text-xl sm:text-2xl md:text-3xl poppins">
    <span class="poppins font-bold">Curious</span> about our team?
  </h4>
  <p class="poppins text-base sm:text-lg md:text-xl">
    ✦ It's really easy to reach us! ✦
  </p>
  <CtAs dark={true} />
</section>
