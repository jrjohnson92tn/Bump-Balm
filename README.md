# Bump-Balm<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Bump Balm — Safe, Natural Relief for Moms-to-Be (and Beyond)</title>
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
          <!-- Replace src with your mockup image URL -->
          <img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f?q=80&w=1200&auto=format&fit=crop" alt="Bump Balm jar and box mockup">
          <div style="display:flex; gap:12px; margin-top:12px">
            <div class="badge">Crafted for comfort</div>
            <div class="badge">Tested with herbalists</div>
          </div>
        </div>
      </div>
    </section>

    <!-- PRODUCTS -->
    <section id="products">
      <div class="container">
        <h2 class="section-title">The product family</h2>
        <p class="section-sub">Start with Bump Balm, then expand to gentle, effective blends for everyday relief.</p>

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
            <p class="note">Culinary-level spices. No willow bark. Gentle by design.</p>
          </div>

          <div class="card">
            <img src="https://images.unsplash.com/photo-1547514701-42782101795d?q=80&w=800&auto=format&fit=crop" alt="Pain? Willow It Away product">
            <h3>Pain? Willow It Away</h3>
            <div class="meta">General pain relief</div>
            <div class="ingredients-list">
              <span class="pill">White willow bark</span>
              <span class="pill">Turmeric</span>
              <span class="pill">Ginger</span>
              <span class="pill">Black pepper</span>
            </div>
            <p class="note">Not for pregnancy. Suggested use: 1 tsp, up to 3x/day.</p>
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
            <p class="note">Stir into warm milk or water; daily wellness ritual.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- STORY -->
    <section id="story">
      <div class="container story">
        <div>
          <h2 class="section-title">The story behind the remedy</h2>
          <p>I’ve lived the cost of painkillers. In the military, my knees were in rough shape. During basic training, I’d take two 800mg ibuprofens before our 5-mile runs just to keep up. I wasn’t trying to look weak or give a bad performance—but it hurt me in the long run.</p>
          <p>Now, as a father, I’m breaking that cycle. <strong>Cyclebreaker Naturals</strong> exists to revive the alchemist spirit—turning nature into medicine that heals without harm. Bump Balm is our first step: relief that feels like nourishment.</p>
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
        <h2 class="section-title">Ingredients & safety</h2>
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
          <div class="qa">
            <h3>Transparency</h3>
            <p>We collaborate with herbalists and keep dosing guidance clear. People-first, always.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- TESTIMONIALS -->
    <section>
      <div class="container">
        <h2 class="section-title">What early testers say</h2>
        <p class="section-sub">Real comfort, real simplicity.</p>
        <div class="grid" style="grid-template-columns:repeat(auto-fit,minmax(260px,1fr))">
          <div class="card"><p>“Warm, gentle relief. It’s my nightly ritual.” — A.</p></div>
          <div class="card"><p>“I feel good about what’s inside. No guesswork.” — M.</p></div>
          <div class="card"><p>“Helps me unwind without worrying.” — K.</p></div>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section id="faq">
      <div class="container">
        <h2 class="section-title">FAQ</h2>
        <div class="grid faq">
          <div class="qa">
            <h3>Is this a medicine?</h3>
            <p>No. It’s a natural wellness blend made with food-level ingredients. We avoid medical claims and focus on comfort.</p>
          </div>
          <div class="qa">
            <h3>Is Bump Balm safe for pregnancy?</h3>
            <p>It’s crafted without aspirin-like herbs and uses culinary-level spices. Always check with your clinician for personalized guidance.</p>
          </div>
          <div class="qa">
            <h3>When can I buy?</h3>
            <p>We’re launching small batches after our GoFundMe campaign. Join the list below for early access.</p>
          </div>
          <div class="qa">
            <h3>What about stronger relief?</h3>
            <p>Our general blend “Pain? Willow It Away” is designed for non-pregnant adults. Bump Balm remains gentle by design.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- SUBSCRIBE + DONATE -->
    <section id="subscribe">
      <div class="container">
        <h2 class="section-title">Join the early access list</h2>
        <p class="section-sub">Get launch updates, first dibs on small batches, and behind-the-scenes progress.</p>
        <form class="subscribe" onsubmit="subscribe(event)">
          <input type="email" id="email" placeholder="Your email address" required />
          <button class="btn btn-primary" type="submit">Notify me</button>
        </form>
        <p class="note" id="msg"></p>
      </div>
    </section>

    <section id="donate">
      <div class="container">
        <h2 class="section-title">Support the launch</h2>
        <p class="section-sub">Help us fund testing, small-batch production, and eco-friendly packaging.</p>
        <a class="btn btn-primary" href="https://www.gofundme.com/f/your-bump-balm-campaign" target="_blank" rel="noopener">Donate on GoFundMe</a>
        <p class="note" style="margin-top:10px">Your support makes people-first remedies possible.</p>
      </div>
    </section>
  </main>

  <footer class="foot">
    <div class="container" style="display:grid; grid-template-columns:1.2fr .8fr; gap:20px">
      <div>
        <div class="brand" style="margin-bottom:8px">
          <div class="logo" aria-hidden="true"></div>
          <div>Cyclebreaker Naturals</div>
        </div>
        <p>Reviving the alchemist spirit—natural remedies that heal without harm.</p>
        <p class="note">© <span id="year"></span> Cyclebreaker Naturals. All rights reserved.</p>
      </div>
      <div>
        <p><strong>Contact</strong></p>
        <p class="note">Email: hello@cyclebreakernaturals.com</p>
        <p class="note">Based in Nashville, TN</p>
      </div>
    </div>
  </footer>

  <script>
    function subscribe(e){
      e.preventDefault();
      const email = document.getElementById('email').value.trim();
      const msg = document.getElementById('msg');
      if(!email){ msg.textContent = "Please enter a valid email."; return; }
      // Placeholder: send to your backend or service (e.g., Mailchimp, ConvertKit)
      msg.textContent = "Thanks! You’re on the list.";
      document.getElementById('email').value = "";
    }
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
