<script>
  // Hero component
</script>

<section class="relative w-full h-screen bg-[#3d2b1f] bg-cover bg-center overflow-hidden font-sans" style="background-image: url('https://images.unsplash.com/photo-1518644961665-ed172691aaa1?q=80&w=2500&auto=format&fit=crop');">
  <!-- Overlay -->
  <div class="absolute inset-0 bg-black/20"></div>

  <!-- Top Navigation -->
  <nav class="absolute top-0 right-0 p-8 flex items-center gap-4 z-20">
    <button class="px-5 py-2.5 text-white/90 hover:text-white font-medium text-sm transition-colors tracking-wide">Log in</button>
    <button class="px-6 py-2.5 bg-white text-gray-900 rounded-full font-medium text-sm hover:bg-gray-100 transition-colors shadow-sm tracking-wide">Sign up for free</button>
  </nav>

  <!-- Centered Timer -->
  <div class="absolute inset-0 flex items-center justify-center z-10 pointer-events-none">
    <div class="relative w-[500px] h-[500px] flex items-center justify-center">
      <!-- Circle SVG -->
      <svg class="absolute inset-0 w-full h-full -rotate-90" viewBox="0 0 100 100">
        <!-- Background circle (thin) -->
        <circle cx="50" cy="50" r="48" fill="none" stroke="white" stroke-width="0.5" stroke-opacity="0.4" />
        <!-- Dot at top (start) -->
        <circle cx="98" cy="50" r="1.5" fill="white" />
      </svg>
      
      <!-- Timer Text -->
      <span class="text-white text-[140px] font-light tracking-tight leading-none drop-shadow-sm select-none">25:00</span>
    </div>
  </div>

  <!-- Bottom Start Button -->
  <div class="absolute bottom-16 left-0 right-0 flex justify-center z-20">
    <button class="flex items-center gap-3 bg-white text-gray-900 px-10 py-3.5 rounded-full font-medium hover:bg-gray-100 transition-colors shadow-lg group">
      <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="currentColor" stroke="currentColor" stroke-width="0" class="text-gray-900 group-hover:scale-110 transition-transform">
        <polygon points="5 3 19 12 5 21 5 3"/>
      </svg>
      <span class="text-lg font-medium">Start</span>
    </button>
  </div>
</section>