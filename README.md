<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>3d Prints fy – 3D-Druck nach deinem Wunsch</title>
<meta name="description" content="3D-Druck nach Maß: Deko, Halter, Ersatzteile und Geschenke. Schick mir deine Idee.">
<style>
:root{
  --bg:#FFFFFF; --alt:#F5F5F7; --card:#FFFFFF; --ink:#1D1D1F; --muted:#6E6E73; --link:#0066CC; --line:#D2D2D7; --nav:rgba(255,255,255,.8);
  --t1:#E9E5FB; --t2:#FDE7DE; --t3:#DCEFF2; --t4:#F8E2EE;
  box-sizing:border-box; padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme:dark){
  :root:not([data-theme="light"]){--bg:#000;--alt:#161617;--card:#1D1D1F;--ink:#F5F5F7;--muted:#A1A1A6;--link:#2997FF;--line:#424245;--nav:rgba(22,22,23,.8);--t1:#2A2766;--t2:#4A2B35;--t3:#1F4048;--t4:#4A2A47;color-scheme:dark}
}
:root[data-theme="dark"]{--bg:#000;--alt:#161617;--card:#1D1D1F;--ink:#F5F5F7;--muted:#A1A1A6;--link:#2997FF;--line:#424245;--nav:rgba(22,22,23,.8);--t1:#2A2766;--t2:#4A2B35;--t3:#1F4048;--t4:#4A2A47;color-scheme:dark}
html{scroll-padding-top:calc(env(safe-area-inset-top,0px) + 56px);scroll-behavior:smooth}
*,*::before,*::after{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font-family:-apple-system,BlinkMacSystemFont,"SF Pro Text","Segoe UI",Roboto,Helvetica,Arial,sans-serif;font-size:1.0625rem;line-height:1.5;-webkit-font-smoothing:antialiased}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);background:var(--nav);backdrop-filter:blur(20px);-webkit-backdrop-filter:blur(20px);z-index:10}
a{color:var(--link);text-decoration:none}
a:hover{text-decoration:underline}
:focus-visible{outline:3px solid var(--link);outline-offset:3px;border-radius:4px}
.nav{position:sticky;top:env(safe-area-inset-top,0px);z-index:11;background:var(--nav);backdrop-filter:saturate(180%) blur(20px);-webkit-backdrop-filter:saturate(180%) blur(20px);border-bottom:1px solid var(--line)}
.nav div{max-width:1000px;margin:0 auto;height:52px;padding:0 1.25rem;display:flex;align-items:center;justify-content:space-between;font-size:.9rem}
.nav b{font-weight:600;font-size:1rem;color:var(--ink)}
.nav nav a{margin-left:1.5rem;color:var(--ink);opacity:.8}
.wrap{max-width:1000px;margin:0 auto;padding:0 1.25rem}
.hero{text-align:center;padding:4.5rem 0 2rem}
.eyebrow{font-size:1.2rem;font-weight:600;color:var(--muted);margin:0 0 .5rem}
h1{font-size:clamp(2.7rem,9vw,5.6rem);line-height:1.04;letter-spacing:-.035em;font-weight:700;margin:0 auto 1rem;max-width:11em}
.lead{font-size:clamp(1.15rem,2.5vw,1.55rem);line-height:1.35;color:var(--muted);max-width:30em;margin:0 auto 1.5rem}
.links a{font-size:1.2rem;margin:0 .9rem;display:inline-block}
.links a::after{content:" ›"}
.hero svg{display:block;width:min(300px,70%);margin:2.5rem auto 0}
.grow{transform-box:fill-box;transform-origin:50% 100%;animation:print 3.4s steps(44) both}
@keyframes print{from{transform:scaleY(0)}to{transform:scaleY(1)}}
@media (prefers-reduced-motion:reduce){.grow{animation:none}html{scroll-behavior:auto}}
.band{background:var(--alt);padding:5rem 0}
.band.plain{background:var(--bg)}
h2{font-size:clamp(2rem,5vw,3.3rem);letter-spacing:-.03em;line-height:1.08;font-weight:700;margin:0 0 .5rem;text-align:center}
.sub{color:var(--muted);text-align:center;max-width:32em;margin:0 auto 3rem;font-size:1.2rem;line-height:1.4}
.tiles{display:grid;grid-template-columns:repeat(2,1fr);gap:1rem}
.tile{background:var(--card);border-radius:28px;padding:2.25rem 1.5rem 0;text-align:center;overflow:hidden;display:flex;flex-direction:column;align-items:center;min-height:430px}
.tile h3{font-size:1.9rem;letter-spacing:-.02em;margin:0 0 .25rem;font-weight:700}
.tile p{margin:0 0 .6rem;color:var(--muted);max-width:20em}
.tile .l{font-size:1.1rem}
.tile .l::after{content:" ›"}
.art{margin-top:auto;width:100%;display:flex;justify-content:center}
.art svg{height:210px;width:auto;display:block}
.steps{display:grid;grid-template-columns:repeat(3,1fr);gap:2rem;text-align:center}
.steps i{display:block;font-style:normal;font-size:4rem;font-weight:700;letter-spacing:-.04em;color:var(--link);line-height:1}
.steps h3{margin:.5rem 0 .25rem;font-size:1.35rem}
.steps p{margin:0;color:var(--muted)}
.good{display:grid;grid-template-columns:1fr 1fr;gap:1rem}
.box{background:var(--card);border-radius:28px;padding:2rem}
.box h3{margin:0 0 .75rem;font-size:1.4rem}
.box ul{margin:0;padding-left:1.15rem;color:var(--muted)}
.box li{margin:.35rem 0}
.cta{text-align:center}
.pill{display:inline-block;background:var(--link);color:#fff;padding:.85rem 1.7rem;border-radius:980px;font-size:1.15rem;margin-top:1rem}
.pill:hover{text-decoration:none;opacity:.9}
.form,.out{max-width:560px;margin:0 auto;text-align:left}
.form label{display:block;font-size:.95rem;font-weight:600;margin:0 0 1rem}
.form input,.form select,.form textarea,.out textarea{display:block;width:100%;margin-top:.35rem;padding:.8rem 1rem;font:inherit;font-size:1rem;font-weight:400;color:var(--ink);background:var(--card);border:1px solid var(--line);border-radius:14px}
.form textarea{resize:vertical}
button.pill{border:0;cursor:pointer;font:inherit;font-size:1.15rem}
.form .pill,.out .pill{display:block;margin:1rem auto 0}
.hint{color:var(--muted);font-size:.9rem;margin:.75rem 0 0;text-align:center}
.out{margin-top:2rem}
.out p{color:var(--muted)}
.legal{padding:3rem 0 1rem;font-size:.95rem;color:var(--muted);border-top:1px solid var(--line)}
.legal h2{font-size:1.5rem;text-align:left;letter-spacing:-.02em;color:var(--ink)}
.legal h3{font-size:1.05rem;margin:1.25rem 0 .25rem;color:var(--ink)}
.legal p{margin:.3rem 0;max-width:46em}
.todo{background:#FFE98A;color:#3B3000;padding:0 .3em;border-radius:4px}
footer{padding:1.5rem 0 3rem;font-size:.85rem;color:var(--muted);border-top:1px solid var(--line)}
footer a{margin-left:1rem}
@media (max-width:760px){
  .tiles,.good,.steps{grid-template-columns:1fr}
  .tile{min-height:380px}
  .nav nav a:not(:last-child){display:none}
  .hero{padding-top:3rem}
}
</style>
</head>
<body>

<svg width="0" height="0" style="position:absolute" aria-hidden="true">
  <defs>
    <path id="vase" d="M45 10H75C75 40 105 60 105 100C105 135 85 150 60 150C35 150 15 135 15 100C15 60 45 40 45 10Z"/>
    <path id="cup" d="M20 40H100V138Q100 150 88 150H32Q20 150 20 138Z"/>
    <linearGradient id="g1" x1="0" y1="0" x2="0" y2="1"><stop offset="0" stop-color="#8FD6C2"/><stop offset="1" stop-color="#5B3FD6"/></linearGradient>
    <linearGradient id="g2" x1="0" y1="0" x2="0" y2="1"><stop offset="0" stop-color="#FFC27A"/><stop offset="1" stop-color="#E5546B"/></linearGradient>
    <linearGradient id="g3" x1="0" y1="0" x2="0" y2="1"><stop offset="0" stop-color="#7FE0D0"/><stop offset="1" stop-color="#2F6FBF"/></linearGradient>
    <linearGradient id="g4" x1="0" y1="0" x2="0" y2="1"><stop offset="0" stop-color="#F7A8D0"/><stop offset="1" stop-color="#7B4FD6"/></linearGradient>
    <pattern id="layers" width="120" height="3" patternUnits="userSpaceOnUse"><rect y="2" width="120" height="1" fill="#000" opacity=".14"/></pattern>
  </defs>
</svg>

<header class="nav"><div>
  <b>3d Prints fy</b>
  <nav><a href="#angebot">Angebot</a><a href="#ablauf">Ablauf</a><a href="#anfrage">Anfrage</a></nav>
</div></header>

<main>
  <section class="hero wrap">
    <p class="eyebrow">3D-Druck nach Maß</p>
    <h1>Deine Idee. Schicht für Schicht.</h1>
    <p class="lead">Deko, Halter, Ersatzteile, Geschenke. Wenn es sich drucken lässt, drucke ich es für dich.</p>
    <p class="links"><a href="#anfrage">Anfrage senden</a><a href="#angebot">Angebot ansehen</a></p>
    <svg viewBox="0 0 120 160" role="img" aria-label="Ein gedrucktes Objekt mit sichtbaren Schichtlinien">
      <defs><clipPath id="reveal"><rect class="grow" x="0" y="0" width="120" height="160"/></clipPath></defs>
      <g clip-path="url(#reveal)"><use href="#vase" fill="url(#g1)"/><use href="#vase" fill="url(#layers)"/></g>
    </svg>
  </section>

  <section class="band" id="angebot">
    <div class="wrap">
      <h2>Was ich drucke.</h2>
      <p class="sub">Von der einzelnen Vase bis zum Ersatzteil. Preise gibt es auf Anfrage, passend zu Größe und Aufwand.</p>
      <div class="tiles">
        <article class="tile" style="background:linear-gradient(var(--card) 55%,var(--t1))">
          <h3>Deko und Vasen</h3><p>Mehrfarbig, mit Verlauf oder einfarbig.</p>
          <a class="l" href="#anfrage" data-kat="Deko und Vasen">Anfragen</a>
          <div class="art"><svg viewBox="0 0 120 160" aria-hidden="true"><use href="#vase" fill="url(#g1)"/><use href="#vase" fill="url(#layers)"/></svg></div>
        </article>
        <article class="tile" style="background:linear-gradient(var(--card) 55%,var(--t2))">
          <h3>Halter und Organizer</h3><p>Für Schreibtisch, Werkstatt und Küche.</p>
          <a class="l" href="#anfrage" data-kat="Halter und Organizer">Anfragen</a>
          <div class="art"><svg viewBox="0 0 120 160" aria-hidden="true"><use href="#cup" fill="url(#g2)"/><use href="#cup" fill="url(#layers)"/></svg></div>
        </article>
        <article class="tile" style="background:linear-gradient(var(--card) 55%,var(--t3))">
          <h3>Ersatzteile</h3><p>Klammern, Knöpfe, Abdeckungen und mehr, nach deinem Maß.</p>
          <a class="l" href="#anfrage" data-kat="Ersatzteil">Anfragen</a>
          <div class="art"><svg viewBox="0 0 120 160" aria-hidden="true">
            <g id="gear"><circle cx="60" cy="90" r="46" fill="none" stroke="url(#g3)" stroke-width="14" stroke-dasharray="11 9"/><circle cx="60" cy="90" r="38" fill="url(#g3)"/></g>
            <use href="#gear" style="fill:url(#layers)"/><circle cx="60" cy="90" r="14" style="fill:var(--card)"/>
          </svg></div>
        </article>
        <article class="tile" style="background:linear-gradient(var(--card) 55%,var(--t4))">
          <h3>Geschenke</h3><p>Namensschilder, Türschilder und persönliche Unikate.</p>
          <a class="l" href="#anfrage" data-kat="Geschenk">Anfragen</a>
          <div class="art"><svg viewBox="0 0 120 160" aria-hidden="true">
            <rect x="6" y="60" width="108" height="70" rx="16" fill="url(#g4)"/><rect x="6" y="60" width="108" height="70" rx="16" fill="url(#layers)"/>
            <text x="60" y="104" text-anchor="middle" font-size="22" font-weight="700" fill="#fff" font-family="-apple-system,Segoe UI,Roboto,sans-serif">Dein Name</text>
          </svg></div>
        </article>
      </div>
    </div>
  </section>

  <section class="band plain" id="ablauf">
    <div class="wrap">
      <h2>So einfach geht’s.</h2>
      <p class="sub">Drei Schritte von der Idee zum fertigen Teil.</p>
      <div class="steps">
        <div><i>1</i><h3>Idee schicken</h3><p>Schreib mir, was du brauchst, mit Maßen, Farbe und gern einem Foto.</p></div>
        <div><i>2</i><h3>Angebot erhalten</h3><p>Du bekommst einen Preis und eine Lieferzeit. Erst danach wird gedruckt.</p></div>
        <div><i>3</i><h3>Druck und Versand</h3><p>Dein Teil wird gedruckt, geprüft und verschickt.</p></div>
      </div>
    </div>
  </section>

  <section class="band">
    <div class="wrap">
      <h2>Gut zu wissen.</h2>
      <p class="sub">Damit am Ende alles passt und alles seine Ordnung hat.</p>
      <div class="good">
        <div class="box"><h3>Das drucke ich gern</h3><ul>
          <li>Eigene Entwürfe und Designs mit passender Lizenz</li>
          <li>Deine eigenen Dateien, wenn du die Rechte daran hast</li>
          <li>Deko, Halter, Ersatzteile und Geschenke</li>
        </ul></div>
        <div class="box"><h3>Das drucke ich nicht</h3><ul>
          <li>Geschützte Figuren und Marken, z. B. aus Filmen oder Spielen</li>
          <li>Waffen und gefährliche Gegenstände</li>
          <li>Teile für Lebensmittel, Medizin oder sicherheitskritische Zwecke</li>
        </ul></div>
      </div>
      <p class="sub" style="margin:2rem auto 0;font-size:1rem">Material ist meist PLA: nicht wasserdicht und nicht hitzebeständig. Für Frischblumen bitte ein Glas einsetzen.</p>
    </div>
  </section>

  <section class="band plain cta" id="anfrage">
    <div class="wrap">
      <h2>Was soll ich für dich drucken?</h2>
      <p class="sub" style="margin-bottom:1rem">Schreib mir kurz deine Idee. Ich melde mich in der Regel innerhalb eines Tages.</p>
      <form id="anfrage-form" class="form">
<label>Dein Name<input name="name" required autocomplete="name"></label>
<label>Deine E-Mail<input name="mail" type="email" required autocomplete="email"></label>
<label>Was soll gedruckt werden?<select name="kat" id="kat"><option>Deko und Vasen</option><option>Halter und Organizer</option><option>Ersatzteil</option><option>Geschenk</option><option>Etwas anderes</option></select></label>
<label>Menge<input name="menge" inputmode="numeric" placeholder="z. B. 1"></label>
<label>Beschreibung<textarea name="text" rows="5" required placeholder="Maße, Farbe, Wunschtext, Verwendung …"></textarea></label>
<button class="pill" type="submit">Anfrage vorbereiten</button>
<p class="hint">Dein E-Mail-Programm öffnet sich mit fertigem Text. Du musst nur noch auf Senden klicken.</p>
</form>
<div id="out" class="out" hidden><p>Falls sich nichts geöffnet hat, kopiere den Text und sende ihn an <b>leonlaserich06@gmail.com</b>:</p><textarea id="txt" rows="9" readonly></textarea><button id="copy" class="pill" type="button">Text kopieren</button></div>
    </div>
  </section>
</main>

<div class="wrap">
  <section class="legal" id="impressum">
    <h2>Impressum</h2>
    <p>Angaben gemäß § 5 DDG</p>
    <p><span class="todo">Vor- und Nachname</span><br><span class="todo">Straße und Hausnummer</span><br><span class="todo">PLZ und Ort</span></p>
    <p>E-Mail: leonlaserich06@gmail.com</p>
    <p><span class="todo">Falls vorhanden: Umsatzsteuer-ID, oder bei Kleinunternehmerregelung: Hinweis nach § 19 UStG</span></p>
  </section>

  <section class="legal" id="datenschutz" style="border-top:0;padding-top:1rem">
    <h2>Datenschutz</h2>
    <h3>Verantwortlicher</h3>
    <p>Verantwortlich ist die im Impressum genannte Person.</p>
    <h3>Hosting</h3>
    <p>Diese Seite wird bei GitHub Pages gehostet (GitHub Inc., USA). Beim Aufruf verarbeitet der Anbieter technisch notwendige Daten wie deine IP-Adresse. Grundlage ist Art. 6 Abs. 1 lit. f DSGVO (sicherer und effizienter Betrieb der Seite).</p>
    <h3>Kontaktaufnahme</h3>
    <p>Das Anfrageformular sendet selbst keine Daten an einen Server: Es bereitet nur eine E-Mail vor, die du in deinem E-Mail-Programm abschickst. Wenn du mir per E-Mail schreibst, verarbeite ich deine Angaben nur, um deine Anfrage zu beantworten (Art. 6 Abs. 1 lit. b oder f DSGVO). Ich lösche sie, sobald sie nicht mehr nötig sind und keine Aufbewahrungspflichten bestehen.</p>
    <h3>Cookies, Tracking und Schriften</h3>
    <p>Diese Seite setzt keine Cookies, nutzt keine Analyse- oder Tracking-Dienste und lädt keine externen Schriften.</p>
    <h3>Deine Rechte</h3>
    <p>Du hast das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung der Verarbeitung und Widerspruch. Außerdem kannst du dich bei einer Datenschutzaufsichtsbehörde beschweren.</p>
  </section>

  <footer>© 2026 3d Prints fy<a href="#impressum">Impressum</a><a href="#datenschutz">Datenschutz</a></footer>
</div>

<script>
(function(){
 var sel=document.getElementById('kat');
 document.querySelectorAll('[data-kat]').forEach(function(a){a.addEventListener('click',function(){sel.value=a.getAttribute('data-kat');});});
 var f=document.getElementById('anfrage-form'),out=document.getElementById('out'),txt=document.getElementById('txt'),cp=document.getElementById('copy'),NL=String.fromCharCode(10);
 f.addEventListener('submit',function(e){
  e.preventDefault();
  var d=new FormData(f);
  var subject='Anfrage: '+d.get('kat');
  var body='Hallo,'+NL+NL+'ich habe eine Anfrage.'+NL+NL+'Name: '+d.get('name')+NL+'E-Mail: '+d.get('mail')+NL+'Was: '+d.get('kat')+NL+'Menge: '+(d.get('menge')||'-')+NL+NL+'Beschreibung:'+NL+d.get('text')+NL+NL+'Viele Grüße'+NL+d.get('name');
  txt.value='An: leonlaserich06@gmail.com'+NL+'Betreff: '+subject+NL+NL+body;
  out.hidden=false;
  window.location.href='mailto:leonlaserich06@gmail.com?subject='+encodeURIComponent(subject)+'&body='+encodeURIComponent(body);
 });
 cp.addEventListener('click',function(){txt.select();try{navigator.clipboard.writeText(txt.value);}catch(err){document.execCommand('copy');}cp.textContent='Kopiert ✓';});
})();
</script>
</body>
</html>
