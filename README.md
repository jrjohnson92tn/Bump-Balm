<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Cyclebreaker Naturals — Breaking the Painkiller Cycle</title>
  <meta name="description" content="Cyclebreaker Naturals: Created by a father and veteran to offer safe, natural remedies for families. Bump Balm and more—healing without harm." />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#faf6f1;
      --text:#2b2b2b;
      --muted:#6a6a6a;
      --primary:#c97b2a;
      --primary-dark:#8c5620;
      --accent:#3c6e71;
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
          <div class="tag">Break the painkiller cycle • Plant-based • Family-first mission</div>
          <h1>Healing, Not Harming: One Father’s Mission</h1>
          <p class="sub">
            My name is J. I’m a father, an artist, and a veteran who’s lived the cost of relying on painkillers. When I served, my knees were wrecked—two 800mg ibuprofens before every 5-mile run just to keep up. I wasn’t trying to look weak; I just didn’t have another option. Those pills got me through the moment, but they took a toll in the long run.<br><br>
            Now, as a parent, I’m breaking that cycle. For my son, for myself, and for families everywhere—so no one has to choose between pain and risky relief.
          </p>
          <div class="cta">
            <a class="btn btn-primary" href="#donate">Support Our Mission</a>
            <a class="btn btn-outline" href="#subscribe">Get Early Access</a>
          </div>
          <div style="margin-top:16px">
            <span class="pill">No artificial additives</span>
            <span class="pill">People-first remedies</span>
            <span class="pill">Eco-friendly packaging</span>
          </div>
        </div>
        <div class="hero-card">
          <img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f?q=80&w=1200&auto=format&fit=crop" alt="Bump Balm jar and box mockup">
          <div style="display:flex; gap:12px; margin-top:12px">
            <div class="badge">Made for families</div>
            <div class="badge">Tested with herbalists</div>
          </div>
        </div>
      </div>
      <div class="container" style="margin-top:30px;">
        <h2 class="section-title">Our Mission & Vision</h2>
        <p>
          Cyclebreaker Naturals revives the spirit of the alchemist—turning nature into medicine that heals without harm. Our mission is to offer families safe, natural ways to find comfort and relief, without the risks of conventional painkillers.<br><br>
          <strong>Imagine a world where pain relief doesn’t come with a warning label. Where mothers can find comfort without fear. Where families choose remedies that heal, not harm.</strong><br>
          With your help, we can make that world real.
        </p>
      </div>
    </section>

    <!-- PRODUCTS -->
    <section id="products">
      <div class="container">
        <h2 class="section-title">The Product Family</h2>
        <p class="section-sub">Gentle, effective blends for everyday comfort—starting with Bump Balm.</p>
        <div class="grid products">
          <div class="card">
            <img src="https://images.unsplash.com/photo-1524592879378-00f07a629f5e?q=80&w=800&auto=format&fit=crop" alt="Bump Balm product">
            <h3>Bump Balm</h3>
            <div class="meta">Prenatal-safe comfort blend</div>
            <div class="ingredients-list">
              <span class="pill">Turmeric</span>
              <span class="pill">Ginger</span>
              <span class="pill">Cinnamon</span>
              <span class="pill">Raw honey</span>
            </div>
            <p class="note">Gentle by design. Culinary-level spices. No willow bark.</p>
          </div>
          <div class="card">
            <img src="https://images.unsplash.com/photo-1547514701-42782101795d?q=80&w=800&auto=format&fit=crop" alt="Pain? Willow It Away product">
            <h3>Pain? Willow It Away</h3>
            <div class="meta">General pain relief for everyday aches</div>
            <div class="ingredients-list">
              <span class="pill">White willow bark</span>
              <span class="pill">Turmeric</span>
              <span class="pill">Ginger</span>
              <span class="pill">Black pepper</span>
            </div>
            <p class="note">Not for pregnancy. For adults only. 1 tsp, up to 3x/day.</p>
          </div>
          <div class="card">
            <img src="https://images.unsplash.com/photo-1524592863891-8e98f9f1a30e?q=80&w=800&auto=format&fit=crop" alt="Turm It Down product">
            <h3>Turm It Down</h3>
            <div class="meta">Anti-inflammatory daily tonic</div>
            <div class="ingredients-list">
              <span class="pill">Turmeric</span>
              <span class="pill">Ginger</span>
              <span class="pill">Cinnamon</span>
              <span class="pill">Black pepper</span>
            </div>
            <p class="note">Stir into warm milk or water—your daily wellness ritual.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- STORY -->
    <section id="story">
      <div class="container story">
        <div>
          <h2 class="section-title">Why I Created Bump Balm</h2>
          <p>
            I’ve seen firsthand how easy it is to rely on painkillers just to get through the day. In the military, I pushed through pain with pills—but paid the price in the long run.<br><br>
            Now, as a father, I’m breaking that cycle for my son and for families everywhere. Cyclebreaker Naturals is about reviving the alchemist spirit—turning nature into medicine that heals without harm. Bump Balm is our first step: relief that nourishes, comforts, and protects.
          </p>
          <ul>
            <li>Created for expectant mothers, with their safety in mind</li>
            <li>Made with trusted, food-level ingredients</li>
            <li>Developed with herbalists and nutritionists</li>
          </ul>
          <div class="quote">“Medicine should comfort today and protect tomorrow.”</div>
          <div class="cta" style="margin-top:12px">
            <a class="btn btn-primary" href="#donate">Support the launch</a>
            <a class="btn btn-outline" href="#subscribe">Get early access</a>
          </div>
        </div>
        <div class="hero-card">
          <img src="https://images.unsplash.com/photo-1524593022611-49dc6c164db4?q=80&w=1200&auto=format&fit=crop" alt="Warm golden honey blend">
          <div class="badge">People-first • Small batch • Transparent</div>
        </div>
      </div>
    </section>

    <!-- INGREDIENTS + SAFETY -->
    <section>
      <div class="container">
        <h2 class="section-title">Ingredients & Safety</h2>
        <p class="section-sub">Simple, recognizable ingredients—designed for comfort and care.</p>
        <div class="grid" style="grid-template-columns:repeat(auto-fit,minmax(260px,1fr))">
          <div class="qa">
            <h3>What’s inside Bump Balm?</h3>
            <p>Raw honey, turmeric, ginger, cinnamon, and a tiny pinch of black pepper. Culinary-level amounts crafted for gentle support.</p>
          </div>
          <div class="qa">
            <h3>Pregnancy-safe approach</h3>
            <p>No willow bark or aspirin-like herbs. Bump Balm focuses on soothing spices traditionally used in food.</p>
          </div>
          <div class="qa">
            <h3>How to enjoy</h3>
            <p>Stir ½–1 tsp into warm milk or water for a golden comfort drink. Or take a small spoonful as needed.</p>
          </div>