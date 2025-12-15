<script>
  const logos = [
    { name: "Entrepreneur First", font: "font-sans font-bold tracking-tight" },
    { name: "Antler", font: "font-sans font-bold" },
    { name: "Y Combinator", font: "font-mono font-bold tracking-wide" },
    { name: "Seedcamp", font: "font-sans font-bold" },
    { name: "Forward Partners", font: "font-sans font-medium" },
    { name: "Notion Capital", font: "font-sans font-bold" },
    { name: "Balderton", font: "font-serif font-bold italic" },
    { name: "Index Ventures", font: "font-sans font-light tracking-wider" },
    { name: "Passion Capital", font: "font-sans font-bold" },
    { name: "LocalGlobe", font: "font-sans font-bold tracking-tight" },
    { name: "Backed VC", font: "font-sans font-black" },
    { name: "Connect Ventures", font: "font-sans font-medium" },
  ];
</script>

<section class="py-16 border-b border-gray-100">
  <div class="container-custom text-center">
    <p class="text-[10px] font-bold tracking-[0.2em] text-gray-400 uppercase mb-10">
      Trusted by portfolio companies from leading VCs
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
