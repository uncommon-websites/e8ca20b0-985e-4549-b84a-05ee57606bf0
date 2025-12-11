<script lang="ts">
  export let text = "Book Now";
  export let href = "#book";
</script>

<div class="bg-primary-950 text-white text-[11px] font-medium py-3 px-4 flex justify-between items-center tracking-wide">
  <div class="flex-1 text-center">
    <span class="opacity-90">Vancouver's only mobile sauna & cold plunge service • Book your session today</span>
  </div>
  <a {href} class="bg-primary-600 hover:bg-primary-700 text-white px-3 py-1.5 rounded text-[10px] font-bold uppercase tracking-wider ml-4 transition-colors">
    {text}
  </a>
</div>
