<!---------------------------------------------------------------------------->
<style>
  @reference "$lib/global.css";

  main {
    @apply min-h-screen;
    @apply bg-gray-950;
  }

  a {
    @apply inline-block;
    @apply px-5 py-2;
    @apply text-gray-300 text-lg font-semibold;
    @apply cursor-pointer;
  }

  .dezlymacauley-dot-com-link {
    @apply text-4xl hover:text-white;
    @apply px-2;
    @apply pt-2 pb-4;
  }

  .youtube-link {
    @apply bg-red-700;
    @apply rounded-3xl;
    @apply shadow-lg shadow-red-700/75;
    @apply hover:shadow-xl hover:text-white hover:font-bold hover:bg-red-600;
  }

  .github-link {
    @apply bg-blue-700;
    @apply rounded-3xl;
    @apply shadow-lg shadow-blue-700/75;
    @apply hover:shadow-xl hover:text-white hover:font-bold hover:bg-blue-600;
  }

  .resume-link {
    @apply bg-[#610079];
    @apply rounded-3xl;
    @apply shadow-lg shadow-[#610079]/75;
    @apply hover:shadow-xl hover:text-white hover:font-bold hover:bg-[#9f00c6];
  }
</style>
<!---------------------------------------------------------------------------->
<main>
  <h1>
    <a
      class="dezlymacauley-dot-com-link"
      href="https://dezlymacauley.com"
      target="_blank"
      rel="noopener noreferrer"
    >Dezly Macauley</a>
  </h1>

  <a
    href="https://www.youtube.com/@dezlymacauley"
    class="youtube-link"
    target="_blank"
    rel="noopener noreferrer"
  >
    YouTube
  </a>

  <a
    href="https://github.com/dezlymacauley?tab=overview&from=2026-01-01&to=2026-12-31"
    class="github-link"
    target="_blank"
    rel="noopener noreferrer"
  >
    GitHub
  </a>

  <a
    href="/resume/dezly_macauley_resume.pdf"
    class="resume-link"
    download
  >
    Download Resume
  </a>
</main>
