<script lang="ts">
  const resume: string = "dezly_macauley_resume.pdf";
  const github: string = "https://github.com/dezlymacauley";
  const target: string = "_blank";
  const rel: string = "noreferrer";
</script>

<!---------------------------------------------------------------------------->

<h1>Dezly Macauley</h1>

<h2>Docker</h2>

<div>
  <a href={github} {target} {rel}>GitHub</a>
  <a href={resume} {target}>Resume</a>
</div>

<!---------------------------------------------------------------------------->

<style>
  div {
    display: flex;
    flex-direction: column;
    gap: 12px;
    
    margin-top: 10px;
  }
</style>
