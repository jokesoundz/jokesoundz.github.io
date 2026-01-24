<style>
/* ------------------------------ */
/* HERO SECTION                   */
/* ------------------------------ */

.hero {
  text-align: center;
  margin: 3rem auto 2rem;
  max-width: 800px;
  padding: 0 1rem;
}

.hero h1 {
  font-size: 2.0rem;
  margin-bottom: 1rem;
  font-weight: 700;
}

.hero p {
  font-size: 1.1rem;
  line-height: 1.6;
}

/* ------------------------------ */
/* TWO-COLUMN LAYOUT              */
/* ------------------------------ */

.portfolio-columns {
  display: flex;
  flex-direction: column; /* Mobile default */
  gap: 2rem;
  margin-top: 2rem;
}

/* Column base styles */
.projects-column,
.tech-column {
  flex: 1;
}

/* Desktop layout */
@media (min-width: 900px) {
  .portfolio-columns {
    flex-direction: row; /* Side-by-side */
    align-items: flex-start;
  }

  /* Desktop order: Tech left, Projects right */
  .tech-column {
    order: 1;
  }
  .projects-column {
    order: 2;
  }
}

/* Mobile layout: Projects first, Tech second */
@media (max-width: 899px) {
  .projects-column {
    order: 1;
  }
  .tech-column {
    order: 2;
  }
}

/* Project item spacing */
.project-item {
  margin-bottom: 1.2rem;
  line-height: 1.5;
}

/* Project links */
.project-item a {
  font-weight: bold;
  text-decoration: none;
  color: inherit;
}

.project-item a:hover {
  text-decoration: underline;
}

/* Optional: tighten headings */
.portfolio-columns h2 {
  margin-bottom: 0.8rem;
}

.portfolio-columns h3 {
  margin-top: 1rem;
  margin-bottom: 0.3rem;
}

</style>

<!-- ------------------------------ -->
<!-- HERO SECTION                   -->
<!-- ------------------------------ -->

<section class="hero">
  <h1>VR, Games, Software Developer & Creative Coder</h1>
  <p>
    Welcome to my portfolio.  I build interactive systems across VR, audio, web, and data.<br>
    My work focuses on modular systems, universal design, clear user experience, and playful experimentation.
  </p>
</section>

<!-- ------------------------------ -->
<!-- TWO-COLUMN SECTION             -->
<!-- ------------------------------ -->

<div class="portfolio-columns">
  <!-- RIGHT COLUMN: PROJECTS -->
  <div class="projects-column">
    <h2>Featured Projects</h2>
    <div class="project-item">
      <a href="projects/vr-interaction-prototype.md">👁️ VR Interaction Prototype</a><br>
      A modular VR interaction system exploring accessible design, gaze‑based interaction, and responsive visual/audio cues.
    </div>
    <div class="project-item">
      <a href="projects/ufo-data-explorer.md">🛸 UFO Data Explorer</a><br>
      A Jupyter notebook investigation into UFO sighting data, from licence checks to dead ends to insights about the limits of open datasets.
    </div>
    <div class="project-item">
      <a href="projects/dj-mixing-app.md">🎛️ DJ Mixing App</a><br>
      A modular JUCE-based DJ mixer with an OOP-designed cue button that mimics two-handed deck control through a hover-and-release gesture.
      </div>
    <div class="project-item">
      <a href="projects/brat-snaps-webcam-widget.md">🎭 Brat Snaps Webcam Widget</a><br>
      A browser‑based creative webcam filter using p5.js and ML‑based face detection for playful, stylised effects.
    </div>
  </div>

  <!-- LEFT COLUMN: TECH STACK -->
  <div class="tech-column">
    <h2>Core Tech Stack</h2>
    <h3>Languages</h3>
    <p>C# • C++ • Python • JavaScript • SQL • HTML • CSS</p>
    <h3>Frameworks & Libraries</h3>
    <p>Unity Engine • XR Interaction Toolkit • OpenXR • JUCE • p5.js • Node.js • NumPy • pandas • geopandas • Matplotlib • seaborn • folium • scipy</p>
    <h3>Tools & Envinroments</h3>
    <p>Unity Editor • Visual Studio • VS Code • Git • GitHub • Jupyter Notebooks</p>
    <h3>Systems & Domains</h3>
    <p>VR Interaction Systems • Real-time UI • Creative Coding • Audio Programming • Data Analysis & Visualisation • Image Processing • ML-based object detection • Game Mechanics • Object-Oriented Programming • Version Control</p>
  </div>
</div>

<!-- ------------------------------ -->
<!-- FOOTER IMAGE                   -->
<!-- ------------------------------ -->

<figure style="margin: 20px auto; text-align: center;">
  <img src="/assets/images/joe-and-mr-ping.png"
       alt="ASCII art of Joe and his cat"
       style="max-width: 100%; height: auto;">
  
  <figcaption style="font-size: 0.9em; color: #666; texxt-align: right; max-width: 100%">
    Joe &amp; Mr Ping<br>
    ASCII art generated via
    <a href="https://www.asciiart.eu/webcam-to-ascii-art"
       target="_blank"
       rel="noopener noreferrer">
       asciiart.eu
    </a>
  </figcaption>
</figure>

