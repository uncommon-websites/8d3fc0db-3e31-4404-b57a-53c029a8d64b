<script lang="ts">
  const steps = [
    {
      num: "01",
      title: "Discovery call",
      desc: "Share your wealth management goals and learn how Atlas can serve your unique needs with AI-powered workflows.",
      img: "/generated/image-professional-financial-advisor-meeting-w-1770162388160-1.webp"
    },
    {
      num: "02",
      title: "Portfolio analysis",
      desc: "Our team conducts a comprehensive review of your current holdings, tax situation, and alternative investment opportunities.",
      img: "/generated/image-professional-team-analyzing-investment-p-1770162395275-4.webp"
    },
    {
      num: "03",
      title: "AI onboarding",
      desc: "We configure your AI agents to automate workflows, optimize tax strategies, and monitor your portfolio 24/7.",
      img: "/generated/image-modern-wealth-management-office-with-sle-1770162385550-0.webp"
    },
    {
      num: "04",
      title: "Ongoing management",
      desc: "Your dedicated advisor team and AI agents work together to grow and protect your wealth with institutional-grade strategies.",
      img: "/generated/image-sophisticated-trading-floor-or-wealth-ma-1770162391059-2.webp"
    }
  ];
</script>

<section class="bg-white py-24 px-6">
  <div class="max-w-[1200px] mx-auto">
    <h2 class="text-[40px] leading-tight font-light text-gray-900 mb-16 max-w-[600px]">
      Get started with Atlas in four simple steps. Begin managing your wealth in weeks.
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-16">
      {#each steps as step}
        <div class="flex flex-col">
          <div class="bg-black text-white text-xs font-bold w-8 h-8 flex items-center justify-center rounded mb-6">
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
        <h3 class="text-2xl font-light mb-2">Want the details?</h3>
        <p class="text-gray-500 text-sm">Learn more about our AI-powered wealth management platform.</p>
      </div>
      <div class="flex gap-4">
        <button class="px-6 py-3 bg-white border border-gray-200 hover:bg-gray-50 rounded-lg text-sm font-medium transition-colors">
          How it works
        </button>
        <button class="px-6 py-3 bg-[oklch(0.577_0.245_27.325)] hover:bg-[oklch(0.505_0.213_27.518)] text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
          Download prospectus
        </button>
      </div>
    </div>
  </div>
</section>
