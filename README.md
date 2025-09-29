# mgmt382-khaana-website

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Khaana — Management Team</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    /* --- Rustic Mexican vibe palette & typography (two font families) --- */
    :root{
      --terracotta:#B5522E;   /* warm clay */
      --sun:#E7A046;          /* agave flower */
      --sage:#3D6B63;         /* talavera green */
      --cream:#F7F3EF;        /* parchment */
      --ink:#2b2b2b;
    }
    html,body{margin:0;padding:0;background:var(--cream); color:var(--ink);}
    body{
      font-family: Arial, Helvetica, sans-serif; /* body font 1 */
      line-height:1.5;
    }
    header{
      background:
        linear-gradient(180deg, rgba(181,82,46,.85), rgba(181,82,46,.85)),
        url("https://images.unsplash.com/photo-1541542684-4a6495f76b07?q=80&w=1400&auto=format&fit=crop");
      background-size:cover; background-position:center;
      color:white; padding:44px 20px;
      border-bottom:8px solid var(--sun);
    }
    .brand{
      font-family: Georgia, 'Times New Roman', serif; /* heading font 2 */
      font-size: 2.2rem; letter-spacing:1px;
    }
    .tagline{
      font-size:1.05rem; opacity:.95; margin-top:6px;
    }
    main{max-width:980px;margin:24px auto;padding:0 16px;}
    .card{
      background:white; border:2px solid var(--terracotta);
      border-radius:16px; padding:18px 18px 14px;
      box-shadow:0 8px 18px rgba(0,0,0,.06);
      margin-bottom:18px;
    }
    h2{
      font-family: Georgia, 'Times New Roman', serif;
      color:var(--terracotta); font-size:1.6rem; margin:.2rem 0 0.8rem;
      border-left:10px solid var(--sage);
      padding-left:10px;
    }
    .lead {
      font-size:1.05rem;
    }
    .accent { color: var(--sage); font-weight: 700; }
    .note   { font-size:.95rem; background: #fff6ea; border-left:6px solid var(--sun); padding:10px 12px; border-radius:8px; }
    .team{
      display:grid; grid-template-columns: repeat(auto-fit, minmax(240px,1fr)); gap:14px;
    }
    .person{
      border:1px solid #e8d9cf; border-radius:14px; overflow:hidden; background:#fffdfa;
    }
    .person img{width:100%; height:180px; object-fit:cover;}
    .person .info{padding:12px 12px 14px;}
    .role{color:var(--sage); font-weight:700; font-size:1rem;}
    .name{font-weight:700; font-size:1.1rem; margin-bottom:6px;}
    .bio{font-size:.95rem;}
    ul, ol { margin: .4rem 0 .8rem 1.2rem;}
    li { margin: .15rem 0; }
    .links a{
      display:inline-block; margin-right:10px; margin-bottom:8px;
      text-decoration:none; border:2px solid var(--sage); color:var(--sage);
      padding:6px 10px; border-radius:10px; font-weight:700; font-size:.95rem;
    }
    .links a:hover{ background:var(--sage); color:white;}
    footer{
      margin:16px auto 38px; max-width:980px; padding:0 16px;
      font-size:.95rem; color:#4f4f4f;
    }
    .subtle{ color:#777; font-size:.9rem; }
    .underline{ text-decoration: underline; }
    /* at least two non-header font sizes are present via .lead (.95–1.05rem) and base */
    /* at least two font colors appear via var(--terracotta) and var(--sage) accents */
    .badge { background: var(--sun); color:#331c0d; padding:2px 8px; border-radius:999px; font-size:.85rem; font-weight:700; }
  </style>
</head>
<body>
  <header role="banner">
    <div class="brand">Khaana • Management Team</div>
    <div class="tagline"><em>Rustic Mexican kitchen</em> with a parallel <strong class="accent">food truck</strong> and live <u>Mariachi</u> <span class="badge">Thu–Sat after 7pm</span>.</div>
  </header>

  <main role="main">
    <!-- Intro / page purpose -->
    <section class="card">
      <h2>Who We Are</h2>
      <p class="lead">
        We steward Khaana’s vision across the <strong>restaurant</strong> and the <strong style="color:var(--terracotta)">food truck</strong>, keeping operations smooth, flavors bold, and the guest experience joyful when the <span class="underline">Mariachi</span> lights up the night.
        Below you’ll find short bios, leadership priorities, and recognitions.
      </p>
      <p class="note"><strong>Quick snapshot:</strong> Our core competencies include <em>dual-channel service</em> (dining room + truck), <em>events & catering</em>, and <em>live music programming</em> that drives evening covers and brand loyalty.</p>
    </section>

    <!-- Team grid -->
    <section class="card">
      <h2>Leadership</h2>
      <div class="team">
        <article class="person">
          <img src="https://images.unsplash.com/photo-1559339352-11d035aa65de?q=80&w=1200&auto=format&fit=crop" alt="Head chef plating tacos al pastor" />
          <div class="info">
            <div class="name">Sofía Martínez</div>
            <div class="role">Chef & Co-Founder</div>
            <p class="bio">Leads menu R&D and sourcing from local farms. Signature items include <em>tacos al pastor</em> and <em>charred elote bowls</em>. Partners with the truck team to ensure flavor parity across channels.</p>
          </div>
        </article>

        <article class="person">
          <img src="https://images.unsplash.com/photo-1514933651103-005eec06c04b?q=80&w=1200&auto=format&fit=crop" alt="Restaurant general manager in a rustic dining room" />
          <div class="info">
            <div class="name">Diego Alvarez</div>
            <div class="role">General Manager</div>
            <p class="bio">Owns FOH/BOH operations, hiring, training, and service design. Balances dining room turns with <strong>Mariachi</strong> showtimes to maximize guest flow and bar attach rate.</p>
          </div>
        </article>

        <article class="person">
          <img src="https://images.unsplash.com/photo-1490474418585-ba9bad8fd0ea?q=80&w=1200&auto=format&fit=crop" alt="Food truck manager at a busy street location" />
          <div class="info">
            <div class="name">Marisol Reyes</div>
            <div class="role">Food Truck & Events Lead</div>
            <p class="bio">Runs daily truck routing, pop-ups, and catering. Syncs menus with Chef Sofía and negotiates venue partnerships for Thu–Sat <span style="color:var(--sage); font-weight:700;">music nights</span>.</p>
          </div>
        </article>
      </div>
    </section>

    <!-- Ordered and unordered lists to meet requirements -->
    <section class="card">
      <h2>Quarterly Leadership Priorities</h2>
      <ol>
        <li>Standardize truck mise en place to <strong>sub-10-minute</strong> lunch rush ticket times.</li>
        <li>Launch seasonal <em>mole poblano</em> feature with paired beverage list.</li>
        <li>Integrate Mariachi set breaks with kitchen fire times to improve table turns.</li>
        <li>Roll out allergen icons on menus (dining + truck) and staff refresh training.</li>
        <li>Expand corporate catering with a “Street Tacos for 25–60” package.</li>
      </ol>
      <h2>Awards & Credentials</h2>
      <ul>
        <li><strong>City’s Best New Mexican Kitchen</strong> — Local Bites Weekly</li>
        <li>ServSafe® Manager Certified (all leadership)</li>
        <li>Farm-to-Restaurant partnership with <em>La Tierra</em> Cooperative</li>
      </ul>
    </section>

    <!-- Links: at least one external, plus an internal and a mailto -->
    <section class="card">
      <h2>Links & Downloads</h2>
      <p class="lead">Use these quick actions to learn more or take something with you:</p>
      <div class="links">
        <!-- External link -->
        <a href="https://en.wikipedia.org/wiki/Mexican_cuisine" target="_blank" rel="noopener">About Mexican Cuisine (external)</a>
        <!-- Internal site link (adjust this path to your team’s Products page URL if desired) -->
        <a href="products.html" target="_self">View Menu / Products</a>
        <!-- Contact me (mailto) -->
        <a href="mailto:your.name@university.edu?subject=Khaana%20Management%20Page">Contact me</a>
        <!-- Downloadable file: generated as a TXT blob so it always works -->
        <a href="#" id="download-bios">Download Team Bios (TXT)</a>
      </div>
      <p class="subtle">Tip: the “Download Team Bios” link generates a plain-text file in your browser so it’s always available without extra uploads.</p>
    </section>
  </main>

  <footer role="contentinfo">
    <p><strong>Hours note:</strong> Mariachi plays <u>Thursday–Saturday after 7:00 PM</u> in the dining room; the food truck mirrors the evening menu near Plaza Verde.</p>
    <p class="subtle">Last Modified: <span id="lastModified"></span></p>
  </footer>

  <script>
    // Auto "Last Modified" date (assignment requirement)
    document.getElementById('lastModified').textContent = document.lastModified;

    // Downloadable file generation so the page is fully self-contained
    (function(){
      const bios = [
        "Khaana — Management Team (TXT)",
        "--------------------------------",
        "Chef & Co-Founder: Sofia Martinez — Menu R&D, sourcing, flavor standards.",
        "General Manager: Diego Alvarez — FOH/BOH ops, hiring, guest experience.",
        "Food Truck & Events Lead: Marisol Reyes — routing, pop-ups, catering.",
        "",
        "Core Competencies:",
        "- Dual-channel: dining room + food truck",
        "- Live Mariachi: Thu–Sat after 7pm",
        "- Events & catering packages"
      ].join("\\n");
      const link = document.getElementById('download-bios');
      link.addEventListener('click', function(e){
        e.preventDefault();
        const blob = new Blob([bios], {type: "text/plain;charset=utf-8"});
        const url = URL.createObjectURL(blob);
        const a = document.createElement('a');
        a.href = url;
        a.download = "Khaana-Management-Bios.txt";
        document.body.appendChild(a);
        a.click();
        a.remove();
        setTimeout(()=>URL.revokeObjectURL(url), 1000);
      });
    })();
  </script>
</body>
</html>
