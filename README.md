<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>My Autobiography — [Your Name]</title>
  <meta name="description" content="Autobiography of [Your Name] — timeline, highlights, photos, contact." />

  <!-- Basic styling: change colors below to personalize -->
  <style>
    :root{
      --bg: #ffffff;
      --text: #111827;
      --muted: #6b7280;
      --accent: #0ea5a2;
      --card: #f8fafc;
      --max-width: 900px;
      --radius: 12px;
      --gap: 1.125rem;
    }
    [data-theme="dark"]{
      --bg: #0b1220;
      --text: #e6eef6;
      --muted: #93a3b8;
      --accent: #2dd4bf;
      --card: #071029;
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background:linear-gradient(180deg, var(--bg), var(--card));
      color:var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.45;
      padding:2rem;
      display:flex;
      justify-content:center;
      align-items:flex-start;
    }

    .container{
      width:100%;
      max-width:var(--max-width);
      background:transparent;
      display:grid;
      gap:var(--gap);
    }

    header{
      display:flex;
      gap:1rem;
      align-items:center;
      justify-content:space-between;
    }
    .brand{
      display:flex;
      gap:0.875rem;
      align-items:center;
    }
    .avatar{
      width:72px;height:72px;border-radius:14px;
      background:linear-gradient(135deg,var(--accent),#8b5cf6);
      display:flex;align-items:center;justify-content:center;
      color:#fff;font-weight:700;font-size:20px;
      box-shadow:0 6px 20px rgba(2,6,23,0.12);
    }
    h1{margin:0;font-size:1.35rem;letter-spacing: -0.2px}
    p.lead{margin:.25rem 0 0;color:var(--muted);font-size:0.95rem}

    nav.controls{display:flex;gap:.5rem;align-items:center}
    button.icon{
      background:transparent;border:1px solid rgba(0,0,0,0.06);
      padding:.5rem .6rem;border-radius:10px;cursor:pointer;
      color:var(--text);font-weight:600;
    }
    [data-theme="dark"] button.icon{border:1px solid rgba(255,255,255,0.06)}

    main{display:grid;gap:var(--gap)}
    .card{
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      padding:1.25rem;border-radius:var(--radius);
      box-shadow:0 6px 18px rgba(2,6,23,0.06);
      backdrop-filter: blur(4px);
    }

    .summary{display:flex;gap:1rem;flex-wrap:wrap;align-items:center}
    .summary .bio{
      flex:1;
      min-width:220px;
    }
    .meta{display:flex;gap:.75rem;flex-wrap:wrap;margin-top:.5rem}
    .meta small{color:var(--muted);background:transparent;padding:.35rem .6rem;border-radius:8px;border:1px dashed rgba(0,0,0,0.04)}

    /* Timeline */
    .timeline{display:grid;gap:.75rem;margin-top:.5rem}
    .event{display:flex;gap:1rem;align-items:flex-start}
    .event .dot{width:12px;height:12px;border-radius:50%;background:var(--accent);margin-top:6px}
    .event h3{margin:0;font-size:1rem}
    .event time{display:block;color:var(--muted);font-size:.9rem;margin-top:.15rem}

    /* Skills grid */
    .skills{display:flex;gap:.5rem;flex-wrap:wrap;margin-top:.5rem}
    .skill{background:linear-gradient(90deg, rgba(255,255,255,0.02), rgba(0,0,0,0.01));padding:.45rem .65rem;border-radius:8px;font-weight:600;color:var(--muted);font-size:.9rem}

    /* Gallery */
    .gallery{display:grid;grid-template-columns:repeat(3,1fr);gap:.6rem;margin-top:.6rem}
    .gallery img{width:100%;height:110px;object-fit:cover;border-radius:8px}

    /* Contact */
    .contact form{display:grid;gap:.6rem}
    .contact input,.contact textarea{padding:.6rem;border-radius:8px;border:1px solid rgba(0,0,0,0.06);background:transparent;color:var(--text);min-height:40px}
    .contact button{padding:.6rem .9rem;border-radius:10px;border:0;background:var(--accent);color:white;font-weight:700;cursor:pointer}

    footer{color:var(--muted);font-size:.9rem;text-align:center;padding-top:1rem}

    /* Responsive */
    @media (max-width:720px){
      .gallery{grid-template-columns:repeat(2,1fr)}
      body{padding:1rem}
    }

    /* Print-friendly */
    @media print{
      body{background:white;color:black;padding:0}
      .container{max-width:100%;padding:0}
      button.icon, nav.controls, footer{display:none}
      .avatar{display:none}
      .card{box-shadow:none}
    }
  </style>
</head>
<body data-theme="light">
  <div class="container" role="main">

    <!-- Header -->
    <header>
      <div class="brand" aria-hidden="false">
        <div class="avatar" aria-hidden="true">ES</div>
        <div>
          <h1 id="name">Christine Toring</h1>
          <p class="lead" id="subtitle">Computer Technology student</p>
        </div>
      </div>


    <!-- Intro / Summary -->
    <main>
      <section class="card summary" aria-labelledby="about-heading">
        <div class="bio" >
          <h2 id="about-heading">My Autobiography</h2>
          <p id="about-text">
           Hi — I am Christine F. Toring, I am 18 years old, first year college student of Lapu-lapu City College. I live with my parents and i have 4 siblings,  My Papa is a Construction Welder, My Mama is a Housewife, Our older Brother has a family, and i have 2 nephew already. My ate is currently working in Barangay Babag as a Secretary of Barangay Captain, and my two sister are still studying, My older sister is a third year college and my younger sister is a grade 10 student.</br>
           </br>

    

          </p>Ever since I started my studies, I have always aimed to do my best despite the challenges i will face, Coming from a family with limited financial resources. I know how hard it is to sustain educational expenses, buy learning materials, and support my daily needs. As a student, I will make sure to maintain good grades and be a responsible who values education as a key to a better future.

          </p>

        </br>

          <div class="meta" aria-hidden="true">
            <small>📍 Philippines</small>
            <small>📝 Computer Technology</small>
            <small>🎓 Lapu-Lapu City College</small>
          </div>



          <br/>

      <!-- Skills -->
      <section class="card" aria-labelledby="skills-heading">
        <h1 id="skills-heading">Education Account</h1>
        <div class="skills" role="list" aria-label="Skills">
             <div class="skills" role="list" aria-label="Skills">toring.christine@llcc.edu.ph</div>
        </div>
      </section>

    </br>


          <!-- Skills -->
      <section class="card" aria-labelledby="skills-heading">
        <h1 id="skills-heading">Hobbies</h1>
        <div class="skills" role="list" aria-label="Skills">
             <div class="skills" role="list" aria-label="Skills">Dancing, Listening Music, Watching random Vids</div>
        </div>
      </section>
 
    </br>

  <!-- Skills -->
      <section class="card" aria-labelledby="skills-heading">
        <h1 id="skills-heading">Mobile Number</h1>
        <div class="skills" role="list" aria-label="Skills">
             <div class="skills" role="list" aria-label="Skills">0945-550-3512</div>
        </div>
      </section>
 


     
  
  </script>
</body>
</html>
