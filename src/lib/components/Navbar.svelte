<script>
  import { onMount } from 'svelte';
  
  let isScrolled = false;

  onMount(() => {
    const handleScroll = () => {
      isScrolled = window.scrollY > 10;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<nav class="fixed top-0 left-0 right-0 z-50 transition-all duration-300 {isScrolled ? 'bg-white/90 backdrop-blur-md border-b border-gray-100 py-3' : 'bg-transparent py-5'}">
  <div class="container-custom flex items-center justify-between">
    <div class="flex items-center gap-8">
      <a href="/" class="flex items-center gap-2 text-xl font-bold tracking-tight text-gray-900">
        <!-- Logo Icon -->
        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-plain-green">
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M12.2566 21.954C17.929 21.954 22.5274 17.484 22.5274 11.9699C22.5274 6.45586 17.929 1.98584 12.2566 1.98584C6.58422 1.98584 1.98584 6.45586 1.98584 11.9699C1.98584 17.484 6.58422 21.954 12.2566 21.954ZM15.4608 6.63684C15.6167 6.09831 15.0791 5.77985 14.5881 6.1199L7.73395 10.8665C7.20146 11.2352 7.28522 11.9699 7.85977 11.9699H9.66465V11.9563H13.1823L10.3161 12.9394L9.05251 17.303C8.89655 17.8415 9.43412 18.16 9.92517 17.8199L16.7793 13.0734C17.3118 12.7046 17.228 11.9699 16.6535 11.9699H13.9165L15.4608 6.63684Z"
            fill="currentColor"
          />
        </svg>
        Ballpark
      </a>
      
      <div class="hidden md:flex items-center gap-6 text-sm font-medium text-gray-600">
        <a href="#" class="hover:text-gray-900 transition-colors">Platform <span class="text-xs ml-0.5">▼</span></a>
        <a href="#" class="hover:text-gray-900 transition-colors">Participants</a>
        <a href="#" class="hover:text-gray-900 transition-colors">Resources <span class="text-xs ml-0.5">▼</span></a>
        <a href="#" class="hover:text-gray-900 transition-colors">Pricing</a>
        <a href="#" class="hover:text-gray-900 transition-colors">Trust Center</a>
      </div>
    </div>

    <div class="flex items-center gap-3">
      <a href="#" class="px-3 py-1.5 text-xs font-semibold border border-gray-200 rounded text-gray-700 hover:border-gray-400 transition-colors uppercase tracking-wide">
        Sign In
      </a>
      <a href="#" class="px-3 py-1.5 text-xs font-semibold bg-plain-green text-white rounded hover:opacity-90 transition-opacity uppercase tracking-wide">
        Start Free Trial
      </a>
    </div>
  </div>
</nav>
