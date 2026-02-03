<script lang="ts">
  export let text = "View Strategy";
  export let href = "#";
</script>

<div class="bg-black text-white text-[11px] font-medium py-3 px-4 flex justify-between items-center tracking-wide">
  <div class="flex-1 text-center">
    <span class="opacity-90">Institutional-grade wealth management for the next generation of wealth</span>
  </div>
  <a {href} class="bg-[oklch(0.577_0.245_27.325)] hover:bg-[oklch(0.505_0.213_27.518)] text-white px-3 py-1.5 rounded text-[10px] font-bold uppercase tracking-wider ml-4 transition-colors">
    {text}
  </a>
</div>
