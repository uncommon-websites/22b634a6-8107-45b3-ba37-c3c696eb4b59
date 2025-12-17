<script>
  const logos = [
    { name: "Soldo", font: "font-sans font-bold" },
    { name: "Vodafone", font: "font-sans font-bold text-red-600" },
    { name: "FEVO", font: "font-sans font-black tracking-tight" },
    { name: "Glean", font: "font-sans font-bold" },
    { name: "Trade Me", font: "font-sans font-bold text-green-600" },
    { name: "Figma", font: "font-sans font-bold" },
    { name: "Notion", font: "font-sans font-bold" },
    { name: "Slack", font: "font-sans font-bold" },
    { name: "Stripe", font: "font-sans font-bold text-purple-600" },
    { name: "Shopify", font: "font-sans font-bold text-green-700" },
    { name: "Atlassian", font: "font-sans font-bold text-blue-600" },
    { name: "Zendesk", font: "font-sans font-bold" },
  ];
</script>

<section class="py-16 border-b border-gray-100">
  <div class="container-custom text-center">
    <p class="text-[10px] font-bold tracking-[0.2em] text-gray-400 uppercase mb-10">
      Trusted by product teams at leading companies
    </p>
    
    <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-x-8 gap-y-12 items-center justify-items-center opacity-60 grayscale hover:grayscale-0 transition-all duration-500">
      {#each logos as logo}
        <div class="text-xl md:text-2xl text-gray-800 flex items-center justify-center w-full">
           <!-- Placeholder for actual SVG logos -->
           <span class="{logo.font}">{logo.name}</span>
        </div>
      {/each}
    </div>
  </div>
</section>
