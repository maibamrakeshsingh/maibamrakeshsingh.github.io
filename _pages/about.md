---
permalink: /
title: "BIOGRAPHY"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* =========================================
     1. STATIC LIGHT THEME VARIABLES (Locked)
     ========================================= */
  :root {
    --port-primary: #2c3e50;    /* Dark Academic Blue */
    --port-text: #3b3b3b;       /* Dark Gray for readability */
    --port-muted: #64748b;      /* Muted gray for subtitles */
    --port-bg: #fdfdfd;         /* Almost white for cards */
    --port-border: #eaeaea;     /* Light gray borders */
    --accent-color: #f0f7ff;    /* Soft blue for milestones */
  }

  /* =========================================
     2. GLOBAL HEADER FIXES (Matches Portfolio)
     ========================================= */
  .masthead, 
  .masthead__inner-wrap, 
  .masthead__menu, 
  .masthead__menu ul, 
  .greedy-nav {
    background-color: #ffffff !important;
    background: #ffffff !important;
  }
  
  .masthead {
    border-bottom: 1px solid var(--port-border) !important;
  }

  .masthead a, 
  .masthead__menu-item,
  .masthead__menu-item a,
  .greedy-nav a, 
  .greedy-nav .visible-links,
  .greedy-nav .visible-links li,
  .greedy-nav .visible-links a {
    background-color: transparent !important;
    background: transparent !important;
    color: var(--port-text) !important;
  }

  .masthead a:hover,
  .greedy-nav a:hover,
  .greedy-nav .visible-links a:hover,
  .greedy-nav .visible-links li.masthead__menu-item--current a,
  .greedy-nav .visible-links li.masthead__menu-item--current a:hover {
    background-color: transparent !important;
    background: transparent !important;
    color: var(--port-primary) !important;
  }

  h1.page__title, .page__title {
    color: var(--port-primary) !important;
    font-weight: 700 !important;
  }

  /* =========================================
     3. BIOGRAPHY LAYOUT STYLES
     ========================================= */
  /* Standardized Section Titles */
  .section-title {
    margin-top: 45px; 
    border-bottom: 1px solid var(--port-border); 
    padding-bottom: 8px; 
    text-transform: uppercase; 
    color: var(--port-primary) !important;
    font-size: 1.15em !important; 
    letter-spacing: 0.1em;
    font-weight: 700;
  }

  /* Standardized Text Style for Bio */
  .content-text {
    text-align: justify !important; 
    text-justify: inter-word !important;
    font-size: 0.95em; 
    line-height: 1.7; 
    margin-bottom: 20px; 
    color: var(--port-text);
  }

  /* Collaboration Alert */
  .collab-box {
    background-color: var(--accent-color);
    border-left: 4px solid var(--port-primary);
    padding: 14px 18px;
    font-size: 0.95em;
    color: var(--port-primary);
    font-weight: 500;
    margin: 30px 0;
    border-radius: 0 4px 4px 0;
    box-shadow: 0 1px 3px rgba(0,0,0,0.03);
    line-height: 1.6;
  }

  /* Research Interest Badges */
  .interest-pills {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 15px;
    margin-bottom: 30px;
  }
  
  .pill {
    background-color: var(--port-primary); 
    color: #ffffff; 
    font-size: 0.85em; 
    font-weight: 600;
    padding: 6px 14px;
    border-radius: 4px; 
    letter-spacing: 0.03em;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
  }

  /* News Timeline Styling */
  .news-scroll-container {
    max-height: 500px; 
    overflow-y: auto; 
    margin-top: 20px;
    padding-right: 15px;
  }
  
  .news-scroll-container::-webkit-scrollbar { width: 5px; }
  .news-scroll-container::-webkit-scrollbar-track { background: var(--port-bg); }
  .news-scroll-container::-webkit-scrollbar-thumb { background: #d1d5db; border-radius: 10px; }
  .news-scroll-container::-webkit-scrollbar-thumb:hover { background: #9ca3af; }

  .timeline-item {
    display: flex; 
    margin-bottom: 14px; 
    font-size: 0.9em; 
    line-height: 1.5;
    padding: 4px 0;
    align-items: baseline; 
  }
  
  .timeline-date {
    min-width: 95px; 
    font-weight: 700; 
    color: var(--port-muted); 
  }
  
  .timeline-content {
    flex: 1; 
    color: var(--port-text);
    word-wrap: break-word; /* Prevents text cutoff */
  }

  /* Highlighted Milestones */
  .timeline-item.milestone {
    background-color: var(--accent-color); 
    border-radius: 4px;
    padding: 8px 12px; /* Added horizontal padding to prevent cutoff */
    margin-left: -12px; /* Offsets the padding to align visually */
    margin-top: 2px;
    margin-bottom: 12px;
  }

  /* Mobile & Tablet Responsiveness */
  @media (max-width: 768px) {
    .timeline-item { 
      flex-direction: column; 
      margin-bottom: 18px;
    }
    .timeline-date { 
      margin-bottom: 4px; 
      font-size: 0.85em; 
      color: var(--port-primary);
    }
    .timeline-item.milestone { 
      margin-left: 0; 
      padding: 10px 12px;
    }
  }
</style>

```html
<div class="content-text">
  <strong>Maibam Rakesh</strong> is a Per-Doctoral Researcher in Mathematical Statistics at <strong>Bharathidasan University</strong>, working under the supervision of <strong>Dr. T. Jai Sankar</strong> in the <strong>Department of Statistics</strong>. His research integrates <strong>Statistical Learning</strong>, <strong>Stochastic Processes</strong>, and <strong>Agent-Based Modeling</strong> to investigate complex real-world systems and climate-related challenges. Currently, he is actively seeking Ph.D. opportunities to further advance research in applied mathematics, mathematical and applied statistics, with an emphasis on data-driven modeling and stochastic methodologies.
</div>

<div class="content-text">
  Multidisciplinary academic background includes an <strong>M.Sc. in Statistics</strong>, a <strong>B.Sc. in Mathematics</strong>, and a <strong>B.Sc. (Honours) in Physics</strong>. Ready for research collaborations, with contributions published in peer-reviewed venues indexed by <strong>IEEE Xplore</strong>, the <strong>ACM Digital Library</strong>, and <strong>Springer</strong>. Through his interdisciplinary training and research experience, he aims to develop innovative applied mathematical and statistical methodologies to address contemporary scientific and societal challenges.
</div>


<div class="collab-box" style="text-align: justify; text-justify: inter-word;">
  <i class="fas fa-lightbulb" style="color: #64748b; margin-right: 8px;"></i> I am actively seeking collaborative research opportunities to contribute - Mathematics, Mathematical and Applied Statistics, and Scientific Statistical Learning.
</div>

<h2 class="section-title">Research Interests</h2>
<div class="interest-pills">
  <span class="pill">Probability Theory & Stochastic Processes</span>
  <span class="pill">Stochastic & Information Geometry</span>
  <span class="pill">Spatial Statistics & Stochastic Fields</span>
  <span class="pill">Scientific Machine Learning (PINNs)</span>
  <span class="pill">Biostatistics & Epidemiological Modeling</span>
  <span class="pill">Statistical Inference & Learning Theory</span>
</div>

<h2 class="section-title">Recent News</h2>
<div class="news-scroll-container">
  
  <div class="timeline-item milestone">
    <div class="timeline-date">Mar 2026</div>
    <div class="timeline-content">Accepted a fully-funded Ph.D. offer in Environmental Data Science at the <strong>UES</strong>.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Apr 2024</div>
    <div class="timeline-content">Urban Heat Island forecasting paper published in the <strong>Journal of Environmental Informatics</strong>.</div>
  </div>

  <div class="timeline-item milestone">
    <div class="timeline-date">May 2026</div>
    <div class="timeline-content">Graduated with an <strong>M.Sc.</strong> in Statistics <strong>(CGPA: 9.31/10)</strong> from <strong>Bharathidasan University, Tiruchirappalli</strong>.</div>
  </div>

</div>
