---
title: "Home"
---

<!-- Hero spans full width -->
<section class="home-hero">
  <h1>Powerhub Playground 🚀</h1>
  <p>
    A home for my experiments in <strong>machine learning</strong>, <strong>AI + LLMs</strong>, and
    <strong>financial systems</strong>. Small models, practical tools, and ideas I’m
    testing end-to-end.
  </p>
</section>

<!-- Sidebar + featured projects side by side -->
<div class="home-layout">

  <!-- Left sidebar profile card -->
  <aside class="home-sidebar">
    <div class="sidebar-card">
      <div class="sidebar-avatar">
        <!-- If you have an image in static/images/profile.jpg, use this -->
        <!-- <img src="/images/profile.jpg" alt="Harsh Malik" /> -->
        <span>HM</span>
      </div>
      <h2 class="sidebar-name">Harsh Malik</h2>
      <p class="sidebar-title">ML, Data & Finance</p>
      <p class="sidebar-blurb">
        Product Analyst – AI & Data at Citi. I build ML-powered tools and
        experiments at the intersection of models, workflow, and finance.
      </p>
      <div class="sidebar-links">
        <a href="../about/">About</a>
        <a href="../projects/">Projects</a>
        <a href="../get-in-touch/">Get in touch</a>
      </div>
      <div class="sidebar-social">
        <a href="https://github.com/godhunter98" target="_blank" rel="noopener noreferrer">
          GitHub
        </a>
        <a href="https://www.linkedin.com/in/harshmalik98/" target="_blank" rel="noopener noreferrer">
          LinkedIn
        </a>
      </div>
    </div>
  </aside>

  <!-- Main column: Featured Projects -->
  <div class="home-main">
    <section class="home-projects">
      <h2>Featured Projects 📌</h2>
      <div class="project-grid">
        <a class="project-card project-card--smol" href="projects/nano_transformers/">
          <div class="project-card-head">
            <span class="project-type">Transformers</span>
          </div>
          <div class="project-card-body">
            <h3>nano_transformers</h3>
            <p>From-scratch decoder-only transformer trained on Shakespeare, inspired by nanoGPT.</p>
            <div class="project-tags">Transformers · PyTorch · NLP</div>
          </div>
          <div class="project-card-footer">
            <span>Explore project</span>
          </div>
        </a>
        <a class="project-card project-card--smol" href="projects/finetuned_sql_llms/">
          <div class="project-card-head">
            <span class="project-type">Transformers</span>
          </div>
          <div class="project-card-body">
            <h3>Text-to-SQL LLMs</h3>
            <p>Fine-tuned models that turn English questions into SQL queries for analytics workflows.</p>
            <div class="project-tags">LLMs · SQL · Prompting</div>
          </div>
          <div class="project-card-footer">
            <span>Explore project</span>
          </div>
        </a>
        <a class="project-card project-card--smol" href="projects/portfolio_sql_cli_tool/">
          <div class="project-card-head">
            <span class="project-type">Tools</span>
          </div>
          <div class="project-card-body">
            <h3>Portfolio CLI Tracker</h3>
            <p>Command-line portfolio tracker using SQLite + Yahoo Finance to monitor holdings.</p>
            <div class="project-tags">Python · SQLite · Finance</div>
          </div>
          <div class="project-card-footer">
            <span>Explore project</span>
          </div>
        </a>
        <a class="project-card project-card--smol" href="projects/image_recognition_model/">
          <div class="project-card-head">
            <span class="project-type">Computer Vision</span>
          </div>
          <div class="project-card-body">
            <h3>Fashion CNN (98% Acc.)</h3>
            <p>Convolutional neural network on Fashion-MNIST with a small Streamlit demo app.</p>
            <div class="project-tags">Computer Vision · PyTorch</div>
          </div>
          <div class="project-card-footer">
            <span>Explore project</span>
          </div>
        </a>
      </div>
    </section>
  </div>

</div>