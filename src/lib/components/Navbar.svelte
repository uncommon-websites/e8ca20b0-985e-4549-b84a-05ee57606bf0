<script lang="ts">
  import { page } from '$app/stores';
</script>

<nav class="bg-black text-white py-4 px-6 flex items-center justify-between sticky top-0 z-50 border-b border-gray-900">
  <div class="flex items-center gap-8">
    <a href="/" class="flex items-center gap-2">
      <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="w-6 h-6">
        <path d="M12 2L13.2 9.92154L20.6603 7L14.4 12L20.6603 17L13.2 14.0785L12 22L10.8 14.0785L3.33975 17L9.6 12L3.33975 7L10.8 9.92154L12 2Z" fill="currentColor"/>
      </svg>
      <span class="text-2xl font-medium tracking-tight">Nordic Edge</span>
    </a>
    
    <div class="hidden md:flex items-center gap-6 text-[13px] font-medium text-gray-300">
      <a href="#services" class="hover:text-white transition-colors">Services</a>
      <a href="#how-it-works" class="hover:text-white transition-colors">How it works</a>
      <a href="#benefits" class="hover:text-white transition-colors">Benefits</a>
      <a href="#testimonials" class="hover:text-white transition-colors">Testimonials</a>
      <a href="#about" class="hover:text-white transition-colors">About</a>
    </div>
  </div>

  <div class="flex items-center gap-4">
    <a href="tel:+1234567890" class="text-gray-300 hover:text-white transition-colors hidden md:block text-[13px]">
      (604) 555-0123
    </a>
    <a href="#book" class="bg-primary-600 hover:bg-primary-700 text-white px-4 py-2 rounded-full text-[13px] font-medium transition-colors">
      Book Session
    </a>
  </div>
</nav>
