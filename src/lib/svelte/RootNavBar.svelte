<script lang="ts">
  const urlTags = { target: "_blank", rel: "noopener noreferrer" };
  const home = "https://dezlymacauley.com";
  const youtube = "https://www.youtube.com/@dezlymacauley";
  const github = "https://github.com/dezlymacauley?tab=overview&from=2026-01-01&to=2026-12-31";
  const resume = "/resume/dezly_macauley_resume.pdf";
</script>


<style>
  @reference "$lib/css/global.css";

  .navbar-container {
    @apply flex justify-between;
    @apply items-center;
    @apply px-4 py-2;
  }

  .left-section-container {
    /* 

      TODO: Add logo later

    */

    @apply flex gap-2;
  }
  
  .right-section-container {
    @apply flex gap-4;
    @apply items-center;
  }

  .home-link {
    @apply text-gray-300 text-3xl font-semibold;
    @apply inline-block;
  }

  .right-section-link {
    @apply bg-gray-500 px-5 py-2 rounded-3xl;
    @apply inline-block;
    @apply text-gray-300 text-lg font-semibold;
  }

  .youtube-link {
    @apply bg-red-700;
    @apply shadow-lg shadow-red-700/75;
    @apply hover:shadow-xl hover:text-white hover:font-bold hover:bg-red-600;
    @apply transition duration-300;
  }

  .github-link {
    @apply bg-blue-700;
    @apply shadow-lg shadow-blue-700/75;
    @apply hover:shadow-xl hover:text-white hover:font-bold hover:bg-blue-600;
    @apply transition duration-300;
  }

  .resume-link {
    @apply bg-[#610079];
    @apply shadow-lg shadow-[#610079]/75;
    @apply hover:shadow-xl hover:text-white hover:font-bold hover:bg-[#9f00c6];
    @apply transition duration-300;
  }

</style>

<!---------------------------------------------------------------------------->

<nav class="navbar-container">

  <div class="left-section-container">
    <h1>
      <a class="home-link" href={home} {...urlTags}>Dezly Macauley</a>
    </h1>
  </div>

  <!-- Right Section -->
  <div class="right-section-container">

    <a
      href={youtube}
      class="right-section-link youtube-link"
      {...urlTags}
    >
      YouTube
    </a>

    <a
      href={github}
      class="right-section-link github-link"
      {...urlTags}
    >
      GitHub
    </a>

    <a
      href={resume}
      class="right-section-link resume-link"
      download
    >
      Download Resume
    </a>
  </div>
</nav>
