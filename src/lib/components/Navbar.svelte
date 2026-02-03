<script lang="ts">
  import { page } from '$app/stores';
</script>

<nav class="bg-black text-white py-4 px-6 flex items-center justify-between sticky top-0 z-50 border-b border-gray-900">
  <div class="flex items-center gap-8">
    <a href="/" class="text-2xl font-medium tracking-tight">Atlas</a>
    
    <div class="hidden md:flex items-center gap-6 text-[13px] font-medium text-gray-300">
      <a href="#" class="hover:text-white transition-colors">Workflows</a>
      <a href="#" class="hover:text-white transition-colors">AI Agents</a>
      <a href="#" class="hover:text-white transition-colors">How it works</a>
      <a href="#" class="hover:text-white transition-colors">Investments</a>
      <a href="#" class="hover:text-white transition-colors">Advisors</a>
    </div>
  </div>

  <div class="flex items-center gap-4">
    <button class="text-gray-300 hover:text-white transition-colors">
      <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.3-4.3"/></svg>
    </button>
    <a href="#" class="bg-[oklch(0.577_0.245_27.325)] hover:bg-[oklch(0.505_0.213_27.518)] text-white px-4 py-2 rounded-full text-[13px] font-medium transition-colors">
      Open Account
    </a>
  </div>
</nav>
