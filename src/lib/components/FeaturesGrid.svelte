<section class="py-12 bg-plain-dark">
  <div class="container-custom">
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      
      <!-- Card 1 -->
      <div class="bg-plain-dark-secondary rounded-2xl p-8 border border-gray-800 hover:border-gray-700 transition-colors group">
        <div class="h-40 mb-8 flex items-center justify-center relative">
            <!-- Icons Grid -->
            <div class="grid grid-cols-4 gap-3 opacity-60 group-hover:opacity-100 transition-opacity">
                {#each Array(8) as _}
                <div class="w-8 h-8 rounded bg-gray-800 border border-gray-700 flex items-center justify-center">
                  <div class="w-3 h-3 rounded bg-purple-500/30"></div>
                </div>
                {/each}
            </div>
        </div>
        <h3 class="text-xl font-bold text-white mb-3">Every research method</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Surveys, video interviews, prototype testing, card sorting, first click tests, five second tests, and more. All the methods you need in one platform.
        </p>
      </div>

      <!-- Card 2 -->
      <div class="bg-plain-dark-secondary rounded-2xl p-8 border border-gray-800 hover:border-gray-700 transition-colors group">
        <div class="h-40 mb-8 flex items-end justify-center gap-1 pb-4">
            <!-- Bar Chart -->
            <div class="w-3 bg-purple-900/40 h-12 rounded-t"></div>
            <div class="w-3 bg-purple-800/60 h-16 rounded-t"></div>
            <div class="w-3 bg-purple-700/80 h-10 rounded-t"></div>
            <div class="w-3 bg-purple-600 h-24 rounded-t"></div>
            <div class="w-3 bg-purple-500 h-20 rounded-t"></div>
            <div class="w-3 bg-purple-400 h-28 rounded-t shadow-[0_0_15px_rgba(168,85,247,0.5)]"></div>
            <div class="w-3 bg-purple-500 h-14 rounded-t"></div>
            <div class="w-3 bg-purple-600 h-18 rounded-t"></div>
            
            <!-- Tooltip-like badge -->
            <div class="absolute top-10 bg-white text-black text-[10px] font-bold px-2 py-1 rounded shadow-lg transform translate-x-4">
                3M participants
            </div>
        </div>
        <h3 class="text-xl font-bold text-white mb-3">Instant participants</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Access 3 million participants across 200+ targeting options. Get quality responses in hours, not weeks.
        </p>
      </div>

      <!-- Card 3 -->
      <div class="bg-plain-dark-secondary rounded-2xl p-8 border border-gray-800 hover:border-gray-700 transition-colors group">
        <div class="h-40 mb-8 flex flex-col items-center justify-center gap-3">
             <div class="flex gap-2">
                 <div class="px-3 py-1 bg-purple-600 text-white text-xs rounded font-medium">AI Insights</div>
                 <div class="px-3 py-1 bg-purple-600/20 text-purple-400 border border-purple-600/30 text-xs rounded font-medium">Study Builder</div>
             </div>
             <div class="flex gap-2">
                 <div class="px-3 py-1 bg-purple-600/20 text-purple-400 border border-purple-600/30 text-xs rounded font-medium">AI Interviewer</div>
                 <div class="px-3 py-1 bg-purple-600/20 text-purple-400 border border-purple-600/30 text-xs rounded font-medium">Coach AI</div>
             </div>
        </div>
        <h3 class="text-xl font-bold text-white mb-3">AI-powered insights</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Create studies with AI, conduct hundreds of simultaneous interviews, and get automated insights reports. Research at the speed of thought.
        </p>
      </div>

    </div>
  </div>
</section>
