<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>THE BEST PACK OF THE MOMENT</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg1: #2a0f0f;
      --bg2: #190808;
      --accent1: #ff3b3b;
      --accent2: #b60000;
      --glass: rgba(255,255,255,0.06);
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family: 'Poppins', system-ui, -apple-system, Arial, sans-serif;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}
    body{
      background: radial-gradient(1200px 600px at 10% 10%, rgba(123,97,255,0.12), transparent 8%),
                  radial-gradient(1000px 500px at 90% 90%, rgba(255,122,89,0.08), transparent 10%),
                  linear-gradient(180deg,var(--bg1),var(--bg2));
      display:flex;align-items:center;justify-content:center;padding:40px;
    }

    /* Subtle moving noise / shimmer */
    .scene{
      width:min(980px,96%);
      max-width:1100px;
      padding:48px;
      border-radius:28px;
      background: linear-gradient(180deg, rgba(255,255,255,0.03), rgba(255,255,255,0.02));
      box-shadow: 0 10px 30px rgba(2,6,23,0.6), inset 0 1px 0 rgba(255,255,255,0.02);
      position:relative;overflow:hidden;backdrop-filter: blur(6px);
      display:flex;gap:32px;align-items:center;justify-content:space-between;
    }

    /* Decorative diagonal shine */
    .scene::after{
      content:"";position:absolute;inset:-40% -30% auto -30%;height:200%;
      background:linear-gradient(120deg, transparent 20%, rgba(255,255,255,0.03) 40%, rgba(255,255,255,0.06) 50%, transparent 60%);
      transform:translateX(-20%);
      animation: sweep 7s linear infinite;
      pointer-events:none;
    }
    @keyframes sweep{to{transform:translateX(120%)}}

    .copy{
      color: #e6eef8;flex:1;min-width:0;
    }
    h1{
      margin:0 0 16px 0;font-weight:800;font-size:clamp(28px,6vw,56px);line-height:1.02;
      background:linear-gradient(90deg,var(--accent1), var(--accent2));
      -webkit-background-clip:text;background-clip:text;color:transparent;
      text-shadow: 0 6px 30px rgba(123,97,255,0.12);
      letter-spacing: -0.02em;
    }
    p.lead{
      margin:0 0 24px 0;color:rgba(230,238,248,0.85);font-weight:300;font-size:clamp(14px,2.2vw,18px);
    }

    .cta{
      display:flex;gap:14px;align-items:center;flex-wrap:wrap;
    }
    .btn{
      display:inline-flex;align-items:center;gap:12px;padding:14px 20px;border-radius:14px;font-weight:700;text-decoration:none;
      background:linear-gradient(90deg,var(--accent1),var(--accent2));color:#081029;box-shadow: 0 12px 30px rgba(123,97,255,0.14), 0 6px 12px rgba(0,0,0,0.35);
      transform:translateZ(0);transition:transform .22s cubic-bezier(.2,.9,.3,1), box-shadow .22s;
    }
    .btn:hover{transform:translateY(-6px);box-shadow:0 22px 50px rgba(123,97,255,0.2)}
    .btn:active{transform:translateY(-2px)}

    .btn svg{width:18px;height:18px;display:block}

    .subtle{
      color:rgba(230,238,248,0.7);font-size:13px;padding:8px 12px;border-radius:12px;background:var(--glass);backdrop-filter: blur(3px);
      border:1px solid rgba(255,255,255,0.02)
    }

    /* Right card artwork */
    .art{
      width:320px;max-width:36%;min-width:220px;border-radius:20px;padding:18px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      display:flex;flex-direction:column;align-items:center;gap:12px;justify-content:center;border:1px solid rgba(255,255,255,0.02);
    }
    .pack-visual{
      width:120px;height:120px;border-radius:18px;background:linear-gradient(135deg,var(--accent2),var(--accent1));
      display:grid;place-items:center;font-weight:800;color:white;font-size:20px;box-shadow:0 8px 30px rgba(123,97,255,0.18);
    }
    .pack-tag{font-size:13px;color:rgba(230,238,248,0.9);font-weight:600}

    @media (max-width:820px){
      .scene{flex-direction:column;align-items:center;padding:28px}
      .art{width:100%;max-width:unset}
      .pack-visual{width:96px;height:96px}
    }
  </style>
</head>
<body>
  <main class="scene" role="main">
    <section class="copy">
      <h1>THE BEST PACK OF THE MOMENT</h1>
      <p class="lead">Curated and updated content: the pack that is going viral right now, with items selected for those who want top speed and quality. Press the button below and check it out on the channel — just click, open, and enjoy.</p>

      <div class="cta">
        <a class="btn" href="https://t.me/Hotvibespacks" target="_blank" rel="noopener noreferrer" aria-label="Acessar o pack no Telegram">
          <!-- Telegram paper-plane icon -->
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" aria-hidden="true">
            <path d="M22 2L2 11.5l4.5 1.5L10 21l1.5-5 6.5 4L22 2z" fill="white" opacity="0.95"/>
          </svg>
          ACCESS
        </a>

        <div class="subtle">Secure link — opens in Telegram</div>
      </div>
    </section>

    <aside class="art" aria-hidden="true">
      <div class="pack-visual">PACK</div>
      <div class="pack-tag">Hot Vibes • Updated</div>
      <div style="font-size:13px;color:rgba(230,238,248,0.7);text-align:center;max-width:220px">Tap the button to open the channel and download the latest content. Compatible with desktop and mobile.</div>
    </aside>
  </main>
</body>
</html>
