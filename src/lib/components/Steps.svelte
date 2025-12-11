<script lang="ts">
  const steps = [
    {
      num: "01",
      title: "Book online",
      desc: "Choose your preferred date, time, and session type. Select from our range of packages to fit your schedule and needs.",
      img: "/generated/image-busy-professional-at-home-looking-stress-1765481393195-10.webp"
    },
    {
      num: "02",
      title: "We arrive",
      desc: "Our professional team arrives at your location with all equipment. We handle complete setup and ensure everything is perfect.",
      img: "/generated/image-professional-team-setting-up-mobile-saun-1765481373698-2.webp"
    },
    {
      num: "03",
      title: "Experience",
      desc: "Enjoy your personalized contrast therapy session. Alternate between sauna heat and cold plunge for peak performance recovery.",
      img: "/generated/image-person-relaxing-in-a-cold-plunge-tub-out-1765481371301-1.webp"
    },
    {
      num: "04",
      title: "We clean up",
      desc: "Relax and enjoy the afterglow. Our team handles all breakdown and cleanup. You're left feeling rejuvenated and ready.",
      img: "/generated/image-athletic-person-emerging-from-sauna-look-1765481376359-3.webp"
    }
  ];
</script>

<section class="bg-white py-24 px-6" id="how-it-works">
  <div class="max-w-[1200px] mx-auto">
    <h2 class="text-[40px] leading-tight font-light text-gray-900 mb-16 max-w-[600px]">
      Get Nordic Edge in four simple steps. As easy as booking a spa appointment.
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-16">
      {#each steps as step}
        <div class="flex flex-col">
          <div class="bg-primary-600 text-white text-xs font-bold w-8 h-8 flex items-center justify-center rounded mb-6">
            {step.num}
          </div>
          <h3 class="text-xl font-normal mb-2">{step.title}</h3>
          <p class="text-gray-500 text-sm leading-relaxed mb-6 min-h-[80px]">{step.desc}</p>
          <div class="rounded-xl overflow-hidden h-[200px] bg-gray-100">
            <img src={step.img} alt={step.title} class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-500" />
          </div>
        </div>
      {/each}
    </div>

    <div class="bg-[#f9f9f7] rounded-2xl p-12 flex flex-col md:flex-row items-center justify-between gap-8">
      <div>
        <h3 class="text-2xl font-light mb-2">Ready to experience it?</h3>
        <p class="text-gray-500 text-sm">Book your first session and embrace your inner Viking.</p>
      </div>
      <div class="flex gap-4">
        <button class="px-6 py-3 bg-white border border-gray-200 hover:bg-gray-50 rounded-lg text-sm font-medium transition-colors">
          View pricing
        </button>
        <button class="px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg>
          Book session
        </button>
      </div>
    </div>
  </div>
</section>
