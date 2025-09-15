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
      text-align:center;
      padding:48px 20px;
    }
    .avatar{
      width:150px; height:150px; border-radius:50%;
      background:#fff; border:2px solid rgba(99,102,241,.25);
      box-shadow: var(--shadow);
      object-fit:cover;
      margin-bottom:16px;
    }
    .hero h1{ margin:0; font-size:clamp(26px,3vw,32px); }
    .hero p{ margin:8px 0 0; color:var(--muted); font-size:16px; }

    /* Nav */
    .nav{ display:flex; flex-wrap:wrap; gap:10px; justify-content:center; margin-top:18px; }
    .nav a{
      text-decoration:none; color:var(--link); font-weight:600; font-size:14px;
      background:#fff; border:1px solid rgba(2,6,23,.06);
      padding:8px 14px; border-radius:999px; box-shadow:var(--shadow);
      transition: transform .15s ease, box-shadow .2s ease, color .15s ease, border-color .15s ease;
    }
    .nav a:hover{
      transform: translateY(-1px);
      box-shadow: 0 12px 28px rgba(2,6,23,.08), 0 3px 10px rgba(2,6,23,.06);
      color:var(--link-hover);
      border-color: rgba(99,102,241,.25);
    }

    /* Container */
    .container{ max-width:820px; margin:32px auto; padding:0 20px; text-align:center; }

    /* Card */
    .card{
      background:var(--card);
      border:1px solid rgba(2,6,23,.06);
      border-radius:var(--radius);
      padding:24px;
      box-shadow:var(--shadow);
      margin-bottom:24px;
    }
    .card h2{ margin-top:0; font-size:22px; }

    .contact{ margin:8px 0; font-size:15px; line-height:1.6; }
    .contact a{ color:var(--link); text-decoration:none; }
    .contact a:hover{ color:var(--link-hover); }

    .chips{ display:flex; flex-wrap:wrap; gap:10px; justify-content:center; margin-top:14px; }
    .chip{
      background:var(--chip);
      border:1px solid rgba(99,102,241,.25);
      color:#374151; font-weight:600; font-size:13px;
      padding:6px 12px; border-radius:999px;
    }

    footer{height:24px;}
  </style>
</head>
<body>
  <!-- Hero -->
  <header class="hero">
    <img src="picture.jpeg" alt="Portrait of Yunan (Anny) Zhu" class="avatar">
    <h1>Yunan (Anny) Zhu</h1>
    <p>I am an Assistant Research Fellow at the Center for Meteorological Impact and Risk Research, Chinese Academy of Meteorological Sciences (CAMS). My work sits at the intersection of spatial economics, urban policy, and environmental risk, studying how place-based programs and climate shocks shape housing markets and neighborhood resilience.</p>
    <nav class="nav">
      <a href="index.html" aria-current="page">About</a>
      <a href="Yunan_Zhu_CV_new.pdf" target="_blank" rel="noopener">CV</a>
      <a href="education.html">Education</a>
      <a href="project.html">Projects</a>
      <a href="hobby.html">Hobbies</a>
    </nav>
  </header>

  <!-- Content -->
  <main class="container">
    <!-- Contact -->
    <section class="card">
      <h2>Contact</h2>
      <div class="contact">
        <div>Center for Meteorological Impact and Risk Research</div>
        <div>Chinese Academy of Meteorological Sciences</div>
        <div>Beijing, China 100081</div>
        <div><a href="mailto:zhuyunan@cma.gov.cn">zhuyunan@cma.gov.cn</a></div>
      </div>
    </section>

    <!-- Research Interests -->
    <section class="card">
      <h2>Research Interests</h2>
      <div class="chips">
        <span class="chip">Regional/Urban Economics</span>
        <span class="chip">Causal Inference (DID / CSDID)</span>
        <span class="chip">GIS & Remote Sensing</span>
        <span class="chip">Program Evaluation</span>
      </div>
    </section>
  </main>

  <footer></footer>
</body>
</html>

