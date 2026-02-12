<script>
  const year = new Date().getFullYear();
</script>

<style>
  footer {
    @reference "$lib/css/global.css";

    @apply mt-6;
    @apply p-6;
    @apply text-center text-[#6F7680] font-semibold;
    @apply border-t-2 border-[#222];
  }

  .tagline {
    @apply text-sm font-normal mt-2;
  }

  .links {
    @apply mt-4 flex justify-center gap-6 text-sm;
  }

  .links a {
    @apply hover:text-white transition-colors duration-200;
  }
</style>

<footer>
  <p>© {year} Dezly Macauley. All rights reserved.</p>


  <div class="links">
    <a href="https://github.com/dezlymacauley" target="_blank" rel="noopener noreferrer">
      GitHub
    </a>
    <a href="https://www.youtube.com/@dezlymacauley" target="_blank" rel="noopener noreferrer">
      YouTube
    </a>
  </div>
</footer>
