<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Bump Balm — Safe, Natural Relief for Moms-to-Be</title>
  <meta name="description" content="Bump Balm: a gentle, plant-based relief blend for expectant mothers. Join the movement for safer, natural remedies." />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#faf6f1;
      --text:#2b2b2b;
      --muted:#6a6a6a;
      --primary:#c97b2a;      /* golden amber */
      --primary-dark:#8c5620;
      --accent:#3c6e71;       /* calming teal */
      --card:#fffaf3;
      --border:#e8dfd3;
      --shadow:0 10px 30px rgba(0,0,0,0.08);
    }
    *{box-sizing:border-box}
    body{
      margin:0; font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial,sans-serif;
      color:var(--text); background:var(--bg); line-height:1.6;
    }
    img{max-width:100%; display:block}
    a{color:var(--accent); text-decoration:none}
    .container{max-width:1100px; margin:0 auto; padding:0 20px}
    header{position:sticky; top:0; z-index:50; background:rgba(250,246,241,0.9); backdrop-filter:saturate(180%) blur(12px); border-bottom:1px solid var(--border)}
    .nav{display:flex; align-items:center; justify-content:space-between; padding:14px 0}
    .brand{display:flex; align-items:center; gap:10px; font-weight:700}
    .logo{
      width:36px; height:36px; border-radius:8px; background:linear-gradient(135deg,#f5c36a,#c97b2a);
      box-shadow:var(--shadow);
    }
    .nav a{font-weight:600; margin-left:18px}
    .btn{
      display:inline-block; padding:12px 18px; border-radius:10px; font-weight:700; transition:.2s all;
    }
    .btn-primary{background:var(--primary); color:#fff}
    .btn-primary:hover{background:var(--primary-dark); transform:translateY(-1px)}
    .btn-outline{border:2px solid var(--primary); color:var(--primary)}
    .btn-outline:hover{background:var(--primary); color:#fff}
    .hero{
      position:relative; overflow:hidden;
      background:radial-gradient(1200px 500px at 20% 10%, #fff4e2, transparent), radial-gradient(1000px 400px at 80% 30%, #eaf4f4, transparent);
    }
    .hero-inner{display:grid; grid-template-columns:1.1fr .9fr; gap:30px; padding:60px 0}
    .hero h1{
      font-family:"Playfair Display", serif; font-size:44px; line-height:1.15; margin:0 0 14px
    }
    .tag{display:inline-block; background:#fff; border:1px solid var(--border); border-radius:999px; padding:6px 12px; font-size:14px; color:var(--muted); margin-bottom:16px}
    .sub{font-size:18px; color:var(--muted); margin-bottom:22px}
    .cta{display:flex; gap:12px; flex-wrap:wrap}
    .hero-card{
      background:var(--card); border:1px solid var(--border); border-radius:18px; padding:20px; box-shadow:var(--shadow)
    }
    .hero-card img{border-radius:12px}
    .pill{display:inline-block; background:#fff; border:1px solid var(--border); border-radius:999px; padding:6px 10px; font-size:13px; color:var(--muted); margin-right:8px}
    section{padding:50px 0}
    .section-title{font-family:"Playfair Display", serif; font-size:32px; margin-bottom:10px}
    .section-sub{color:var(--muted); margin-bottom:24px}
    .grid{display:grid; gap:20px}
    .products{grid-template-columns:repeat(auto-fit,minmax(260px,1fr))}
    .card{
      background:#fff; border:1px solid var(--border); border-radius:16px; padding:18px; box-shadow:var(--shadow)
    }
    .card h3{margin:10px 0 6px}
    .meta{color:var(--muted); font-size:14px}
    .ingredients-list{display:flex; flex-wrap:wrap; gap:8px; margin-top:10px}
    .ingredients-list .pill{background:#fffdf7}
    .story{display:grid; grid-template-columns:1fr 1fr; gap:26px}
    .story .quote{background:#fff; border-left:4px solid var(--primary); padding:14px 16px; color:var(--muted); border-radius:10px}
    .badge{display:inline-flex; align-items:center; gap:8px; background:#fff; border:1px solid var(--border); border-radius:999px; padding:8px 12px; font-size:14px; color:var(--muted)}
    .faq{grid-template-columns:1fr 1fr}
    .qa{background:#fff; border:1px solid var(--border); border-radius:14px; padding:16px}
    .foot{
      background:#1f1f1f; color:#ddd; padding:40px 0; margin-top:20px
    }
    .foot a{color:#fff}
    .subscribe{display:flex; gap:10px; flex-wrap:wrap; margin-top:12px}
    input[type=email]{
      padding:12px 14px; border:1px solid var(--border); border-radius:10px; min-width:260px
    }
    .note{font-size:13px; color:var(--muted)}
    @media (max-width:900px){
      .hero-inner{grid-template-columns:1fr}
      .story{grid-template-columns:1fr}
      .faq{grid-template-columns:1fr}
    }
  </style>
</head>
<body>

  <header>
    <div class="container nav">
      <div class="brand">
        <div class="logo" aria-hidden="true"></div>
        <div>Cyclebreaker Naturals</div>
      </div>
      <nav>
        <a href="#products">Products</a>
        <a href="#story">Story</a>
        <a href="#faq">FAQ</a>
        <a class="btn btn-primary" href="#donate">Donate</a>
      </nav>
    </div>
  </header>

  <main>
    <!-- HERO -->
    <section class="hero">
      <div class="container hero-inner">
        <div>
          <div class="tag">Prenatal-safe relief • Plant-based • Small batch</div>
          <h1>Bump Balm: safe, natural relief for moms-to-be (and beyond)</h1>
          <p class="sub">A gentle golden blend of turmeric, ginger, cinnamon, and raw honey—crafted to soothe, nourish, and protect.</p>
          <div class="cta">
            <a class="btn btn-primary" href="#donate">Support on GoFundMe</a>
            <a class="btn btn-outline" href="#subscribe">Join the early access list</a>
          </div>
          <div style="margin-top:16px">
            <span class="pill">No artificial additives</span>
            <span class="pill">People-first mission</span>
            <span class="pill">Eco-friendly packaging</span>
          </div>
        </div>
        <div class="hero-card">
          <!-- Updated hero image -->
          <img src="https://copilot.microsoft.com/th/id/BCO.9d923664-a35e-4f57-babb-038056d4e7a3.png" 
               alt="Bump Balm product and packaging">
          <div style="display:flex; gap:12px; margin-top:12px">
            <div class="badge">Crafted for comfort</div>
            <