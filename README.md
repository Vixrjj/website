
<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>3d Prints fy – Vasen und Deko aus dem 3D-Drucker</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,400;12..96,600;12..96,800&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#F1F2F7; --surface:#FFFFFF; --ink:#1E2340; --muted:#5B6180; --line:#D9DCE8;
  --accent:#5B3FD6; --accent-ink:#FFFFFF; --tile1:#E4E0FA; --tile2:#FBE3DA; --tile3:#D9EEF0; --tile4:#F6DDEB;
  box-sizing:border-box; padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme:dark){
  :root:not([data-theme="light"]){
    --bg:#141731; --surface:#1D2142; --ink:#EEF0FA; --muted:#A5AACB; --line:#2E3360;
    --accent:#9D88FF; --accent-ink:#141731; --tile1:#2A2766; --tile2:#4A2B35; --tile3:#1F4048; --tile4:#4A2A47; color-scheme:dark;
  }
}
:root[data-theme="dark"]{
  --bg:#141731; --surface:#1D2142; --ink:#EEF0FA; --muted:#A5AACB; --line:#2E3360;
  --accent:#9D88FF; --accent-ink:#141731; --tile1:#2A2766; --tile2:#4A2B35; --tile3:#1F4048; --tile4:#4A2A47; color-scheme:dark;
}
html{scroll-padding-top:env(safe-area-inset-top,0px);scroll-behavior:smooth}
*,*::before,*::after{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font-family:"Bricolage Grotesque",system-ui,-apple-system,"Segoe UI",sans-serif;font-size:1.0625rem;line-height:1.6}
a{color:inherit}
:focus-visible{outline:3px solid var(--accent);outline-offset:3px}
.wrap{max-width:1080px;margin:0 auto;padding:0 1.25rem}
header.top{display:flex;justify-content:space-between;align-items:center;padding:1.25rem 0}
.logo{font-weight:800;font-size:1.25rem;letter-spacing:-.02em;text-decoration:none}
nav a{margin-left:1.25rem;text-decoration:none;color:var(--muted)}
nav a:hover{color:var(--ink)}
.hero{display:grid;grid-template-columns:1.1fr .9fr;gap:2rem;align-items:center;padding:2rem 0 4rem}
h1{font-size:clamp(2.4rem,6vw,4.4rem);line-height:1.02;letter-spacing:-.035em;font-weight:800;margin:0 0 1.25rem;max-width:12em}
.lead{color:var(--muted);max-width:34em;margin:0 0 2rem}
.btns{display:flex;flex-wrap:wrap;gap:.75rem}
.btn{display:inline-block;padding:.8rem 1.4rem;border-radius:999px;font-weight:600;text-decoration:none;border:2px solid var(--accent)}
.btn.primary{background:var(--accent);color:var(--accent-ink)}
.btn.ghost{color:var(--ink);border-color:var(--line)}
.btn:hover{border-color:var(--ink)}
.hero svg{width:100%;max-width:380px;justify-self:center;display:block}
.grow{transform-box:fill-box;transform-origin:50% 100%;animation:print 3.2s steps(42) both}
@keyframes print{from{transform:scaleY(0)}to{transform:scaleY(1)}}
@media (prefers-reduced-motion:reduce){.grow{animation:none}html{scroll-behavior:auto}}
section{padding:3.5rem 0;border-top:1px solid var(--line)}
h2{font-size:clamp(1.7rem,3.5vw,2.4rem);letter-spacing:-.025em;line-height:1.1;margin:0 0 .5rem}
.sub{color:var(--muted);margin:0 0 2rem;max-width:36em}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(215px,1fr));gap:1.25rem}
.item .tile{border-radius:1.5rem 1.5rem .5rem .5rem;padding:1.5rem 1rem 1rem;display:flex;justify-content:center}
.item svg{height:190px;width:auto}
.item h3{margin:.9rem 0 .15rem;font-size:1.2rem}
.item p{margin:0 0 .6rem;color:var(--muted);font-size:.98rem}
.row{display:flex;justify-content:space-between;align-items:center;gap:.5rem}
.price{font-weight:600}
.item a.ask{font-weight:600;color:var(--accent)}
.facts{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:2rem}
.facts h3{margin:0 0 .35rem;font-size:1.15rem}
.facts p{margin:0;color:var(--muted)}
.contact{background:var(--surface);border-radius:1.5rem;padding:2rem;max-width:640px}
.contact p{margin:0 0 1.25rem}
footer{padding:2rem 0 3rem;color:var(--muted);font-size:.95rem;border-top:1px solid var(--line)}
@media (max-width:760px){
  .hero{grid-template-columns:1fr;padding-top:0}
  .hero svg{max-width:260px;order:-1}
  nav a:first-child{display:none}
}
</style>
</head>
<body>

<svg width="0" height="0" style="position:absolute" aria-hidden="true">
  <defs>
    <path id="s1" d="M45 10H75C75 40 105 60 105 100C105 135 85 150 60 150C35 150 15 135 15 100C15 60 45 40 45 10Z"/>
    <path id="s2" d="M38 10H82C82 50 70 60 70 80C70 100 90 120 90 150H30C30 120 50 100 50 80C50 60 38 50 38 10Z"/>
    <path id="s3" d="M10 40H110C110 110 85 150 60 150C35 150 10 110 10 40Z"/>
    <path id="s4" d="M40 10H80C95 40 70 55 85 85C100 115 90 140 80 150H40C30 140 20 115 35 85C50 55 25 40 40 10Z"/>
    <linearGradient id="g1" x1="0" y1="0" x2="0" y2="1"><stop offset="0" stop-color="#8FD6C2"/><stop offset="1" stop-color="#5B3FD6"/></linearGradient>
    <linearGradient id="g2" x1="0" y1="0" x2="0" y2="1"><stop offset="0" stop-color="#FFC27A"/><stop offset="1" stop-color="#E5546B"/></linearGradient>
    <linearGradient id="g3" x1="0" y1="0" x2="0" y2="1"><stop offset="0" stop-color="#7FE0D0"/><stop offset="1" stop-color="#2F6FBF"/></linearGradient>
    <linearGradient id="g4" x1="0" y1="0" x2="0" y2="1"><stop offset="0" stop-color="#F7A8D0"/><stop offset="1" stop-color="#7B4FD6"/></linearGradient>
    <pattern id="layers" width="120" height="3" patternUnits="userSpaceOnUse"><rect y="2" width="120" height="1" fill="#000" opacity=".14"/></pattern>
  </defs>
</svg>

<div class="wrap">
  <header class="top">
    <a class="logo" href="#top">3d Prints fy</a>
    <nav><a href="#sortiment">Sortiment</a><a href="#fertigung">Fertigung</a><a href="#anfrage">Anfrage</a></nav>
  </header>

  <main id="top">
    <div class="hero">
      <div>
        <h1>Vasen und Deko, Schicht für Schicht gedruckt.</h1>
        <p class="lead">Einzelstücke aus dem 3D-Drucker. Jede Vase entsteht in mehreren Stunden aus hunderten dünnen Schichten, in Farben und Verläufen, die du im Laden nicht findest.</p>
        <div class="btns">
          <a class="btn primary" href="#sortiment">Vasen ansehen</a>
          <a class="btn ghost" href="#anfrage">Wunschstück anfragen</a>
        </div>
      </div>
      <svg viewBox="0 0 120 160" role="img" aria-label="Eine gedruckte Vase mit sichtbaren Schichtlinien">
        <defs><clipPath id="reveal"><rect class="grow" x="0" y="0" width="120" height="160"/></clipPath></defs>
        <g clip-path="url(#reveal)">
          <use href="#s1" fill="url(#g1)"/>
          <use href="#s1" fill="url(#layers)"/>
        </g>
      </svg>
    </div>

    <section id="sortiment">
      <h2>Das Sortiment</h2>
      <p class="sub">Eine Auswahl aus der aktuellen Kollektion. Farben und Größen lassen sich anpassen.</p>
      <div class="grid">
        <article class="item">
          <div class="tile" style="background:var(--tile1)"><svg viewBox="0 0 120 160" aria-hidden="true"><use href="#s1" fill="url(#g1)"/><use href="#s1" fill="url(#layers)"/></svg></div>
          <h3>Tropfen</h3>
          <p>Rundlich mit schmalem Hals, ca. 18 cm hoch, Silk-PLA im Farbverlauf.</p>
          <div class="row"><span class="price">ab 24 €</span><a class="ask" href="mailto:leonlaserich06@gmail.com?subject=Anfrage%20Vase%20Tropfen">Anfragen</a></div>
        </article>
        <article class="item">
          <div class="tile" style="background:var(--tile2)"><svg viewBox="0 0 120 160" aria-hidden="true"><use href="#s2" fill="url(#g2)"/><use href="#s2" fill="url(#layers)"/></svg></div>
          <h3>Taille</h3>
          <p>Schlank mit Einschnürung, ca. 22 cm hoch, ideal für lange Zweige.</p>
          <div class="row"><span class="price">ab 28 €</span><a class="ask" href="mailto:leonlaserich06@gmail.com?subject=Anfrage%20Vase%20Taille">Anfragen</a></div>
        </article>
        <article class="item">
          <div class="tile" style="background:var(--tile3)"><svg viewBox="0 0 120 160" aria-hidden="true"><use href="#s3" fill="url(#g3)"/><use href="#s3" fill="url(#layers)"/></svg></div>
          <h3>Schale</h3>
          <p>Flach und weit, ca. 12 cm hoch, für Trockenblumen oder als Schmuckschale.</p>
          <div class="row"><span class="price">ab 19 €</span><a class="ask" href="mailto:leonlaserich06@gmail.com?subject=Anfrage%20Schale">Anfragen</a></div>
        </article>
        <article class="item">
          <div class="tile" style="background:var(--tile4)"><svg viewBox="0 0 120 160" aria-hidden="true"><use href="#s4" fill="url(#g4)"/><use href="#s4" fill="url(#layers)"/></svg></div>
          <h3>Welle</h3>
          <p>Geschwungene Silhouette, ca. 20 cm hoch, jedes Stück leicht anders.</p>
          <div class="row"><span class="price">ab 26 €</span><a class="ask" href="mailto:leonlaserich06@gmail.com?subject=Anfrage%20Vase%20Welle">Anfragen</a></div>
        </article>
      </div>
    </section>

    <section id="fertigung">
      <h2>So entsteht eine Vase</h2>
      <p class="sub">Alles wird auf einem Bambu Lab H2C gedruckt und von Hand kontrolliert.</p>
      <div class="facts">
        <div><h3>Mehrfarbig gedruckt</h3><p>Farbverläufe und Muster entstehen direkt im Druck, ohne nachträgliches Lackieren.</p></div>
        <div><h3>Für Trockenblumen</h3><p>Die Vasen sind nicht wasserdicht. Für Frischblumen einfach ein Glas oder Reagenzglas einsetzen.</p></div>
        <div><h3>Dein Wunsch zählt</h3><p>Farbe, Höhe oder ein Name auf dem Fuß: Schreib mir, was du dir vorstellst.</p></div>
      </div>
    </section>

    <section id="anfrage">
      <h2>Anfrage senden</h2>
      <div class="contact">
        <p>Schreib mir kurz, welche Vase du möchtest und in welchen Farben. Du bekommst in der Regel innerhalb eines Tages eine Antwort mit Preis und Lieferzeit.</p>
        <a class="btn primary" href="mailto:leonlaserich06@gmail.com?subject=Anfrage%203d%20Prints%20fy">E-Mail schreiben</a>
      </div>
    </section>
  </main>

  <footer>
    <p>© 2026 3d Prints fy. Impressum und Datenschutzerklärung folgen hier.</p>
  </footer>
</div>

</body>
</html>
