---
layout: default
title: Colby Snyder
---

<section class="hero">
  <div class="hero-copy">
    <p class="eyebrow">Chemical Engineering + Physics (VIPER), University of Pennsylvania</p>
    <h1>Engineering clean-energy systems from first-principles to deployment.</h1>
    <p>{{ site.description }}</p>
    <div class="cta-row" id="contact">
      <a class="button primary" href="mailto:{{ site.email }}">Email</a>
      <a class="button" href="{{ site.linkedin_url }}" target="_blank" rel="noopener">LinkedIn</a>
      <a class="button" href="{{ site.github_url }}" target="_blank" rel="noopener">GitHub</a>
    </div>
  </div>
  <img class="hero-photo" src="{{ site.logo | relative_url }}" alt="Portrait of Colby Snyder">
</section>

<section id="projects" class="section">
  <div class="section-head">
    <h2>Featured Projects</h2>
  </div>

  <article class="project-card">
    <img src="{{ '/assets/SPARC.jpg' | relative_url }}" alt="Fusion research at CFS">
    <div>
      <h3>Functional Materials Research at Commonwealth Fusion Systems</h3>
      <p>I developed repeatable cryogenic specimen preparation and custom fixtures for high-temperature superconducting tape stacks, then executed mechanical and thermal-expansion testing to reduce uncertainty for structural magnet models in a first-of-a-kind fusion system.</p>
    </div>
  </article>

  <article class="project-card">
    <img src="{{ '/assets/4680.jpg' | relative_url }}" alt="Tesla battery development">
    <div>
      <h3>Lithium-Ion Cell Development at Tesla</h3>
      <p>I led low-temperature charging studies that combined electrochemical diagnostics, microscopy, and COMSOL/Python modeling to evaluate AC heating waveforms and derisk lithium plating. The resulting cold-weather charging features now run across millions of packs.</p>
    </div>
  </article>

  <article class="project-card">
    <img src="{{ '/assets/outdoor_roof_photo.png' | relative_url }}" alt="Thermal coating test stand">
    <div>
      <h3>Thermal Coating Test Stand</h3>
      <p>I designed and built an outdoor irradiation test stand for cool-roof materials, automated data acquisition, and increased throughput by 6x for neighborhood-scale urban heat mitigation research.</p>
      <p><a href="{{ '/assets/documents/Portfolio_ThermalTestStand-3.pdf' | relative_url }}" target="_blank" rel="noopener">Project report</a> | <a href="{{ '/assets/documents/Cool Roofs Design V1.pdf' | relative_url }}" target="_blank" rel="noopener">Early prototype</a></p>
    </div>
  </article>

  <article class="project-card">
    <img src="{{ '/assets/reactor_design.png' | relative_url }}" alt="Carbon capture reactor design">
    <div>
      <h3>Carbon Upcycled CO2 Capture Reactor</h3>
      <p>I designed a self-sustaining reactor concept that converts captured CO2 into carbon nanofibers while using reaction byproducts to power thermocatalysis. Our team presented the concept as a DOE EnergyTech University Prize national semifinalist.</p>
      <p><a href="{{ '/assets/documents/Carbon Upcycled Pitch.pdf' | relative_url }}" target="_blank" rel="noopener">Pitch deck</a></p>
    </div>
  </article>
</section>

<section id="research" class="section">
  <div class="section-head">
    <h2>Research + Publications</h2>
  </div>

  <article class="project-card">
    <img src="{{ '/assets/electrolyte_abstract.png' | relative_url }}" alt="Sodium battery electrolyte research">
    <div>
      <h3>Sodium Battery Electrolytes</h3>
      <p>I led polymer electrolyte development using boron nitride and NaFSI-based systems, quantified structure-property relationships, and published peer-reviewed results on ionic transport mechanisms.</p>
      <p><a href="https://pubs.acs.org/doi/10.1021/acs.jpcc.3c06455" target="_blank" rel="noopener">Paper 1</a> | <a href="https://pubs.acs.org/doi/full/10.1021/acs.chemmater.4c01192" target="_blank" rel="noopener">Paper 2</a> | <a href="{{ '/assets/documents/APS Electrolyte Poster Final.pdf' | relative_url }}" target="_blank" rel="noopener">Poster</a> | <a href="{{ '/assets/documents/VIPR 121 Final Presentation.pdf' | relative_url }}" target="_blank" rel="noopener">Slides</a></p>
    </div>
  </article>

  <article class="project-card">
    <img src="{{ '/assets/GA.jpeg' | relative_url }}" alt="General Atomics internship">
    <div>
      <h3>Ceramic Composite Process Development at General Atomics</h3>
      <p>During my 2024 internship, I worked on manufacturing improvements for silicon carbide composites and delivered an 80% reduction in process energy intensity for high-temperature reactor and turbine applications.</p>
    </div>
  </article>

  <article class="project-card">
    <img src="{{ '/assets/Ansys.jpg' | relative_url }}" alt="Fusion CFD modeling">
    <div>
      <h3>Fusion Energy Modeling with ANSYS</h3>
      <p>At Princeton Plasma Physics Laboratory, I model heat extraction using Ansys Fluent CFD to evaluate fluidized-bed heat exchanger performance and compare thermodynamic cycle efficiency for future fusion plants.</p>
    </div>
  </article>
</section>
