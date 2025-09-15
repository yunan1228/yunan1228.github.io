<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Yunan (Anny) Zhu — About</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#f7f8fb;
      --card:#ffffff;
      --ink:#1f2937;
      --muted:#64748b;
      --link:#2563eb;
      --link-hover:#1e40af;
      --ring:rgba(99,102,241,.25);
      --shadow: 0 10px 25px rgba(2,6,23,.06), 0 2px 8px rgba(2,6,23,.04);
      --radius:16px;
      --chip:#eef2ff;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      font-family:'Poppins', system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      margin:0; padding:0; color:var(--ink);
      background:
        radial-gradient(1200px 600px at 10% -10%, rgba(99,102,241,.08), transparent 60%),
        radial-gradient(900px 500px at 110% 10%, rgba(14,165,233,.08), transparent 60%),
        var(--bg);
    }

    /* Header */
    .hero{
      background: linear-gradient(135deg, rgba(14,165,233,.18), rgba(99,102,241,.18));
      border-bottom:1px solid rgba(99,102,241,.15);
    }
    .hero-inner{
      max-width:1024px; margin:0 auto; padding:40px 20px 30px;
      display:flex; align-items:center; gap:16px;
    }
    .avatar{
      width:64px; height:64px; border-radius:50%;
      background:#fff; border:1px solid rgba(99,102,241,.2);
      box-shadow: var(--shadow);
      object-fit:cover; flex:0 0 64px;
    }
    .hero h1{ margin:0; font-size:clamp(24px,3vw,30px); letter-spacing:.2px; }
    .hero p{ margin:.25rem 0 0; color:var(--muted); font-size:15px; }

    /* Nav */
    .nav{ display:flex; flex-wrap:wrap; gap:10px; margin-top:14px; }
    .nav a{
      text-decoration:none; color:var(--link); font-weight:600; font-size:14px;
      background:#fff; border:1px solid rgba(2,6,23,.06);
      padding:8px 12px; border-radius:999px; box-shadow:var(--shadow);
      transition: transform .15s ease, box-shadow .2s ease, color .15s ease, border-color .15s ease;
    }
    .nav a:hover{
      transform: translateY(-1px);
      box-shadow: 0 12px 28px rgba(2,6,23,.08), 0 3px 10px rgba(2,6,23,.06);
      color:var(--link-hover);
      border-color: rgba(99,102,241,.25);
    }

    /* Container & cards */
    .container{ max-width:1024px; margin:24px auto 64px; padding:0 20px; }
    .about-grid{ display:grid; grid-template-columns:1fr; gap:18px; }
    @media (min-width: 900px){ .about-grid{ grid-template-columns: 1.2fr .8fr; } }

    .card{
      background:var(--card);
      border:1px solid rgba(2,6,23,.06);
      border-radius:var(--radius);
      padding:22px;
      box-shadow:var(--shadow);
      transition: transform .18s ease, box-shadow .2s ease, border-color .2s ease;
      position:relative; overflow:hidden;
    }
    .card:hover{
      transform: translateY(-2px);
      box-shadow: 0 16px 36px rgba(2,6,23,.10), 0 6px 18px rgba(2,6,23,.06);
      border-color: rgba(99,102,241,.22);
    }
    .card h2{ margin:.25rem 0 10px; font-size:clamp(20px,2.5vw,24px); }
    .muted{ color:var(--muted); }

    /* Chips */
    .chips{ display:flex; flex-wrap:wrap; gap:8px; margin:10px 0 4px; }
    .chip{
      background:var(--chip);
      border:1px solid rgba(99,102,241,.25);
      color:#374151; font-weight:600; font-size:12px;
      padding:6px 10px; border-radius:999px;
    }

    /* Actions (no Download CV) */
    .actions{ margin-top:12px; display:flex; gap:10px; flex-wrap:wrap; }
    .btn{
      display:inline-flex; align-items:center; gap:8px;
      text-decoration:none; font-weight:700; font-size:14px;
      color:#0f172a; background:#f8fafc;
      border:1px solid rgba(2,6,23,.08);
      padding:9px 12px; border-radius:12px;
      transition: transform .15s ease, box-shadow .2s ease, border-color .2s ease, background .2s ease;
    }
    .btn:hover{
      transform: translateY(-1px);
      background:#ffffff;
      border-color: var(--ring);
      box-shadow: 0 10px 24px rgba(99,102,241,.12);
    }

    /* Contact */
    .contact{ display:grid; gap:8px; font-size:15px; }
    .contact a{ color:var(--link); text-decoration:none; }
    .contact a:hover{ color:var(--link-hover); }

    footer{height:24px;}
  </style>
</head>
<body>
  <!-- Header -->
  <header class="hero">
    <div class="hero-inner">
      <img src="picture.jpeg" alt="Portrait of Yunan (Anny) Zhu" class="avatar">
      <div>
        <h1>Yunan (Anny) Zhu</h1>
        <p>Assistant Research Fellow · Center for Meteorological Impact and Risk Research, Chinese Academy of Meteorological Sciences</p>
        <nav class="nav" aria-label="Primary">
          <a href="index.html" aria-current="page">About</a>
          <a href="Yunan_Zhu_CV_new.pdf" target="_blank" rel="noopener">CV</a>
          <a href="education.html">Education</a>
          <a href="project.html">Projects</a>
          <a href="hobby.html">Hobbies</a>
        </nav>
      </div>
    </div>
  </header>

  <!-- Content -->
  <main class="container">
    <div class="about-grid">
      <!-- Intro -->
      <section class="card">
        <h2>About Me</h2>
        <p>
          I am an <strong>Assistant Research Fellow</strong> at the <em>Center for Meteorological Impact and Risk Research</em>, 
          Chinese Academy of Meteorological Sciences (CAMS). My work sits at the intersection of 
          <strong>spatial economics</strong>, <strong>urban policy</strong>, and <strong>environmental risk</strong>, 
          studying how place-based programs and climate shocks shape housing markets and neighborhood resilience.
        </p>
        <div class="chips">
          <span class="chip">Spatial/Urban Economics</span>
          <span class="chip">Causal Inference (DID / CSDID)</span>
          <span class="chip">GIS & Remote Sensing</span>
          <span class="chip">Risk & Resilience</span>
        </div>
        <p>
          I combine modern causal methods with spatial data to evaluate land bank programs, foreclosure dynamics, and climate-information services.
          I’m especially interested in evidence that translates into actionable policy for resilient, equitable communities.
        </p>
        <div class="actions">
          <a class="btn" href="project.html">View Projects</a>
          <a class="btn" href="education.html">Education</a>
        </div>
      </section>

      <!-- Contact -->
      <aside class="card">
        <h2>Contact</h2>
        <div class="contact">
          <div>Center for Meteorological Impact and Risk Research</div>
          <div>Chinese Academy of Meteorological Sciences</div>
          <div>Beijing, China 100081</div>
          <div><a href="mailto:zhuyunan@cma.gov.cn">zhuyunan@cma.gov.cn</a></div>
        </div>
        <hr style="border:none;border-top:1px solid rgba(2,6,23,.08);margin:16px 0;">
        <div class="contact muted">
          <div>Areas: Spatial/Urban/Environmental Economics · Risk & Resilience</div>
        </div>
      </aside>
    </div>
  </main>

  <footer></footer>
</body>
</html>
