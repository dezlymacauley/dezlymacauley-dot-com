<style>
  @reference "$lib/css/global.css";

  .navbar-container {
    /* @apply border-4 border-green-400; */
    @apply flex justify-between;
    @apply items-center;
    @apply px-4 py-2;
  }

  .left-section-container {
    @apply border-4 border-pink-400;
  }
  
  .right-section-container {

  }

  .dezlymacauley-dot-com-link {
    @apply text-gray-300 text-4xl font-semibold;
    @apply inline-block;
    @apply cursor-pointer;
  }

  .right-section-link {
    /* @apply px-4; */
    /* @apply inline-block; */
    /* @apply px-5 py-2; */
    /* @apply text-gray-300 text-lg font-semibold; */
    /* @apply cursor-pointer; */
  }

  .youtube-link {
    /* @apply bg-red-700; */
    /* @apply rounded-3xl; */
    /* @apply shadow-lg shadow-red-700/75; */
    /* @apply hover:shadow-xl hover:text-white hover:font-bold hover:bg-red-600; */
  }

  .github-link {
    /* @apply bg-blue-700; */
    /* @apply rounded-3xl; */
    /* @apply shadow-lg shadow-blue-700/75; */
    /* @apply hover:shadow-xl hover:text-white hover:font-bold hover:bg-blue-600; */
  }

  .resume-link {
    /* @apply bg-[#610079]; */
    /* @apply rounded-3xl; */
    /* @apply shadow-lg shadow-[#610079]/75; */
    /* @apply hover:shadow-xl hover:text-white hover:font-bold hover:bg-[#9f00c6]; */
  }

</style>

<!---------------------------------------------------------------------------->

<nav class="navbar-container">

  <div class="left-section-container">

    <h1>
      <a
        class="dezlymacauley-dot-com-link"
        href="https://dezlymacauley.com"
        target="_blank"
        rel="noopener noreferrer"
      >Dezly Macauley</a>
    </h1>

  </div>

  <!-- Right Section -->
  <div class="right-section-link border-4 border-orange-400 flex">
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
      class="right-section-link github-link"
      target="_blank"
      rel="noopener noreferrer"
    >
      GitHub
    </a>

    <a
      href="/resume/dezly_macauley_resume.pdf"
      class="right-section-link resume-link"
      download
    >
      Download Resume
    </a>
  </div>
</nav>
