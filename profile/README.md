<style>
  /* container */
  .three-pillars {
      display:block;
  }

  /* columns */
  .three-pillars > * {
      padding:1rem;
  }

  /* tablet breakpoint */
  @media (min-width:768px) {
      .three-pillars {
          display: grid;
          grid-auto-rows: 1fr;
          grid-template-columns: 1fr 1fr 1fr;
      }
  }
</style>

<div align="center">
  <a href="https://github.com/dolbyio-samples"><img src="./assets/github-banner.jpg"/></a>
</div>

<div id="social" align="center">
  <a href="https://www.linkedin.com/company/dolbyio" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="@dolbyio on LinkedIn"/></a>
  &nbsp; &nbsp; &nbsp;
  <a href="https://www.youtube.com/@DolbyIO" target="_blank"><img src="https://img.shields.io/badge/YouTube-red?style=flat-square&logo=youtube&logoColor=white" alt="@dolbyio on YouTube"/></a>
  &nbsp; &nbsp; &nbsp;
  <a href="https://twitter.com/DolbyIO" target="_blank"><img src="https://img.shields.io/badge/Twitter-blue?style=flat-square&logo=twitter&logoColor=white" alt="@dolbyio on Twitter"/></a>
  &nbsp; &nbsp; &nbsp;
</div>

<div id="blurb">
  <h2>Build true-to-life experiences with the Dolby.io developer platform</h2>
</div>

<div class="three-pillars">
  <div class="column">
    <h3>Streaming APIs</h3>
    <p>Deliver instant, real-time streaming experiences with less than half a second of latency.</p>
  </div>
  <div class="column">
      <h3>Communications APIs</h3>
      <p>Add Dolby-quality voice, video, and spatial chat to your applications.</p>
  </div>
  <div class="column">
      <h3>Media APIs</h3>
      <p>Streamline file-based media workflows with automated voice and music post-processing.</p>
  </div>
</div>
