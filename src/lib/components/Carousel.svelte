<script lang="ts">
  const images = [
    {
      src: "/generated/image-cozy-interior-of-a-wooden-sauna-with-war-1765481378672-4.webp",
      title: "Premium Sauna Experience"
    },
    {
      src: "/generated/image-person-relaxing-in-a-cold-plunge-tub-out-1765481371301-1.webp",
      title: "Invigorating Cold Plunge"
    },
    {
      src: "/generated/image-mobile-cold-plunge-unit-with-ice-and-ste-1765481388480-8.webp",
      title: "Professional Equipment"
    }
  ];
</script>

<section class="bg-white pb-24 overflow-hidden">
  <div class="flex gap-4 overflow-x-auto px-6 pb-8 snap-x">
    {#each images as img}
      <div class="min-w-[80vw] md:min-w-[60vw] lg:min-w-[45vw] h-[400px] snap-center first:pl-0">
        <img src={img.src} alt={img.title} class="w-full h-full object-cover rounded-lg" />
      </div>
    {/each}
  </div>
  
  <div class="text-center mt-4">
    <p class="text-gray-500 text-sm mb-4">Contrast therapy <span class="text-gray-400">Sauna + Cold Plunge</span></p>
    <div class="flex justify-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-primary-600"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
    </div>
  </div>
</section>
