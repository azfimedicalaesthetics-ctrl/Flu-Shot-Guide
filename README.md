# Flu-Shot-Guide
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Flu Shot: The 60-Second Guide</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,700&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
:root{--ink:#14213d;--muted:#4b5563;--line:#d9d4c7;--bg:#faf7f0;--band:#f1ece0;--accent:#0f766e;--accent-dark:#0b5a54;--alert:#b91c1c}
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:'Inter',sans-serif;background:var(--bg);color:var(--ink);line-height:1.5;-webkit-font-smoothing:antialiased}
.wrap{max-width:560px;margin:0 auto}
h1,h2,.serif{font-family:'Fraunces',Georgia,serif;text-wrap:balance}
.label{font-size:11px;text-transform:uppercase;letter-spacing:.14em;font-weight:600;color:var(--muted)}
section{padding:32px 20px;border-bottom:1px solid var(--line)}
section.band{background:var(--band)}
h1{font-size:40px;line-height:1.05;letter-spacing:-.02em;margin:10px 0 14px}
h2{font-size:25px;line-height:1.15;letter-spacing:-.01em;margin:8px 0 16px}
p.lead{font-size:16px;color:var(--muted);max-width:46ch;text-wrap:pretty}
.stats{display:grid;grid-template-columns:repeat(3,1fr);margin-top:24px;border-top:1px solid var(--ink);border-bottom:1px solid var(--line)}
.stats div{padding:14px 10px 14px 0}
.stats div+div{padding-left:12px;border-left:1px solid var(--line)}
.stats b{display:block;font-family:'Fraunces',serif;font-size:30px;color:var(--accent-dark);font-variant-numeric:tabular-nums lining-nums}
.stats span{font-size:12px;color:var(--muted);line-height:1.3;display:block}
.seg{display:flex;flex-wrap:wrap;border:1px solid var(--ink);margin-bottom:16px}
.seg button{flex:1 1 33%;padding:11px 6px;font:600 13px 'Inter';background:transparent;color:var(--ink);border:0;border-right:1px solid var(--ink);border-bottom:1px solid var(--ink);cursor:pointer;transition:background .15s}
.seg button:hover{background:#e6e0d0}
.seg button.on{background:var(--ink);color:#fff}
button:focus-visible,a:focus-visible,summary:focus-visible{outline:3px solid var(--accent);outline-offset:2px}
.panel{border-left:4px solid var(--accent);padding:4px 0 4px 16px}
.panel h3{font-family:'Fraunces',serif;font-size:20px;margin-bottom:6px}
.panel p{font-size:15px;color:var(--muted)}
.panel .doses{margin-top:10px;font-weight:600;font-size:14px;color:var(--accent-dark)}
.flip{width:100%;text-align:left;display:block;border:1px solid var(--ink);background:var(--bg);padding:16px;margin-bottom:10px;cursor:pointer;font-family:inherit;color:var(--ink);transition:background .15s}
.flip:hover{background:#fff}
.flip .q{font-family:'Fraunces',serif;font-size:18px;font-weight:700;display:flex;justify-content:space-between;gap:12px}
.flip .a{display:none;margin-top:10px;padding-top:10px;border-top:1px solid var(--line);font-size:15px;color:var(--muted)}
.flip .a b{color:var(--accent-dark)}
.flip.open{background:#fff}
.flip.open .a{display:block}
.flip .tog{transition:transform .2s;flex:none}
.flip.open .tog{transform:rotate(45deg)}
.tl svg{width:100%;height:auto;display:block}
.cap{font-size:12px;color:var(--muted);margin-top:8px}
.two{display:grid;grid-template-columns:1fr;gap:0}
.col{padding:14px 0;border-top:1px solid var(--line)}
.col h3{font-size:12px;text-transform:uppercase;letter-spacing:.14em;margin-bottom:6px}
.col.ok h3{color:var(--accent-dark)}
.col.bad{border-left:4px solid var(--alert);padding-left:14px}
.col.bad h3{color:var(--alert)}
.col li{margin:4px 0 4px 18px;font-size:15px;color:var(--muted)}
.chk{display:flex;gap:12px;align-items:flex-start;padding:13px 0;border-bottom:1px solid var(--line);cursor:pointer;font-size:15px}
.chk input{margin-top:3px;width:20px;height:20px;accent-color:var(--accent);flex:none}
.chk.done{color:var(--accent-dark)}
.note{margin-top:14px;font-size:14px;font-weight:600;color:var(--accent-dark);min-height:22px}
.cta{padding:36px 20px 28px;background:var(--ink);color:#e8ecf4}
.cta h2{color:#fff}
.cta p{font-size:15px;color:#c3cadb;margin-bottom:20px;max-width:44ch}
.btn{display:block;text-align:center;background:#fff;color:var(--ink);font-weight:700;text-decoration:none;padding:16px;border:2px solid #fff;transition:background .15s,color .15s}
.btn:hover{background:var(--accent);border-color:var(--accent);color:#fff}
.small{font-size:12px;color:#9aa4bd;margin-top:18px;text-wrap:pretty}
@media(prefers-reduced-motion:reduce){*{transition:none!important}}
</style>
</head>
<body>
<main class="wrap">

<section>
  <div class="label">Patient guide · Flu season Oct–May</div>
  <h1>One shot. Two weeks. A much safer winter.</h1>
  <p class="lead">Tap around — it takes about a minute. Everything here comes from the CDC's Vaccine Information Statement for the flu shot.</p>
  <div class="stats">
    <div><b>6 mo+</b><span>Everyone this age is advised to get it yearly</span></div>
    <div><b>1</b><span>Dose for most people each season</span></div>
    <div><b>~2 wk</b><span>For protection to build after the shot</span></div>
  </div>
</section>

<section class="band">
  <div class="label">Step 1</div>
  <h2>Why does this matter for <em>me</em>?</h2>
  <div class="seg" id="seg" role="tablist" aria-label="Choose who you are"></div>
  <div class="panel" id="panel" aria-live="polite"></div>
</section>

<section>
  <div class="label">Step 2</div>
  <h2>Things you may have heard</h2>
  <div id="myths"></div>
</section>

<section class="band">
  <div class="label">Step 3</div>
  <h2>How the timing works</h2>
  <div class="tl">
    <svg viewBox="0 0 520 190" role="img" aria-label="Timeline: get vaccinated, protection builds over about 2 weeks, flu season runs October to May">
      <line x1="20" y1="95" x2="500" y2="95" stroke="#14213d" stroke-width="2"/>
      <rect x="20" y="85" width="150" height="20" fill="#0f766e"/>
      <text x="95" y="100" text-anchor="middle" font-family="Inter" font-size="11" font-weight="700" fill="#fff" letter-spacing="1">~2 WEEKS</text>
      <circle cx="20" cy="95" r="9" fill="#14213d"/>
      <circle cx="170" cy="95" r="9" fill="#fff" stroke="#0f766e" stroke-width="3"/>
      <text x="20" y="62" font-family="Fraunces" font-size="16" font-weight="700" fill="#14213d">Get the shot</text>
      <text x="20" y="45" font-family="Inter" font-size="10" fill="#4b5563" letter-spacing="1.4">DAY 0</text>
      <text x="170" y="62" font-family="Fraunces" font-size="16" font-weight="700" fill="#14213d">Protected</text>
      <text x="170" y="45" font-family="Inter" font-size="10" fill="#4b5563" letter-spacing="1.4">DAY ~14</text>
      <rect x="20" y="132" width="480" height="26" fill="none" stroke="#14213d" stroke-width="1"/>
      <rect x="20" y="132" width="480" height="26" fill="#14213d" opacity=".08"/>
      <text x="260" y="149" text-anchor="middle" font-family="Inter" font-size="11" font-weight="600" fill="#14213d" letter-spacing="1.4">FLU SEASON: USUALLY OCTOBER TO MAY</text>
      <text x="20" y="180" font-family="Inter" font-size="10" fill="#4b5563">So earlier in the season is better than waiting for it to peak.</text>
    </svg>
    <p class="cap">Fig. 1 — Protection is not instant. Source: CDC Flu VIS (1/31/2025).</p>
  </div>
</section>

<section>
  <div class="label">Step 4</div>
  <h2>What to expect afterward</h2>
  <div class="two">
    <div class="col ok">
      <h3>Common and usually mild</h3>
      <ul><li>Soreness, redness or swelling where the shot went in</li><li>Fever</li><li>Muscle aches</li><li>Headache</li></ul>
    </div>
    <div class="col bad">
      <h3>Call 9-1-1 right away</h3>
      <ul><li>Hives</li><li>Swelling of the face or throat</li><li>Difficulty breathing</li><li>Fast heartbeat</li><li>Dizziness or weakness</li></ul>
    </div>
  </div>
  <p class="cap">Severe allergic reactions are very rare. Some people also faint after any medical procedure; tell your provider if you feel dizzy or notice vision changes or ringing in the ears.</p>
</section>

<section class="band">
  <div class="label">Step 5</div>
  <h2>Before you go: tell your provider if…</h2>
  <label class="chk"><input type="checkbox"> <span>I have had an allergic reaction after a previous flu shot, or have any severe, life-threatening allergy</span></label>
  <label class="chk"><input type="checkbox"> <span>I have ever had Guillain-Barré Syndrome (GBS)</span></label>
  <label class="chk"><input type="checkbox"> <span>My child has ever had a seizure</span></label>
  <label class="chk"><input type="checkbox"> <span>I am moderately or severely ill today (a minor cold is usually fine)</span></label>
  <div class="note" id="note">Tick anything that applies — then mention it at your visit.</div>
</section>

<section class="cta">
  <div class="label" style="color:#9aa4bd">Want the full details?</div>
  <h2>Read the official CDC statement</h2>
  <p>The complete Vaccine Information Statement covers risks, safety, and where to report or learn more.</p>
  <a class="btn" href="https://www.cdc.gov/vaccines/hcp/current-vis/downloads/flu.pdf" target="_blank" rel="noopener">Open the CDC Flu Vaccine Information Statement (PDF)</a>
  <p class="small">General education only, not personal medical advice. Ask your doctor, nurse or pharmacist what is right for you.</p>
</section>

</main>

<script>
var groups=[
{k:"Adult",h:"Flu can knock you out for days, and it spreads.",p:"Flu brings fever and chills, sore throat, muscle aches, fatigue, cough, headache and a runny or stuffy nose. Anyone can get it, so a yearly shot is advised for everyone 6 months and older.",d:"1 dose each flu season"},
{k:"Pregnant",h:"Pregnancy raises your risk of flu complications.",p:"Pregnant women are among those at greatest risk of complications. Inactivated flu vaccine can be given at any time during pregnancy, for anyone who is or will be pregnant during flu season.",d:"1 dose, any trimester"},
{k:"65+",h:"Your risk of serious complications is higher.",p:"People 65 and older are at greatest risk of complications such as pneumonia, bronchitis, sinus infections and ear infections.",d:"1 dose each flu season"},
{k:"Child",h:"Young children are at higher risk too.",p:"Infants and young children are at greatest risk of flu complications. Vomiting and diarrhea are more common in children than adults. Kids 6 months through 8 years may need 2 doses in a single season.",d:"1 or 2 doses, ask your provider"},
{k:"Health condition",h:"Flu can make your existing condition worse.",p:"If you have heart disease, cancer, diabetes, or a weakened immune system, flu can worsen your condition and raise your risk of complications.",d:"1 dose each flu season"}
];
var seg=document.getElementById('seg'),panel=document.getElementById('panel');
function show(i){
  [].forEach.call(seg.children,function(b,j){b.classList.toggle('on',i===j);b.setAttribute('aria-selected',i===j)});
  var g=groups[i];
  panel.innerHTML='<h3>'+g.h+'</h3><p>'+g.p+'</p><div class="doses">'+g.d+'</div>';
}
groups.forEach(function(g,i){
  var b=document.createElement('button');b.textContent=g.k;b.setAttribute('role','tab');
  b.onclick=function(){show(i)};seg.appendChild(b);
});
show(0);

var myths=[
{q:"\"The flu shot gives you the flu.\"",a:"<b>No.</b> Influenza vaccine does not cause flu. You may feel sore or achy for a day or so; that is your body responding."},
{q:"\"The strains change, so it won't work.\"",a:"<b>It still helps.</b> Flu viruses keep changing, so a new vaccine is made every year. Even when it is not an exact match, it may still provide some protection."},
{q:"\"I have a cold, so I should skip it.\"",a:"<b>Usually not needed.</b> People with minor illnesses like a cold may be vaccinated. If you are moderately or severely ill, it is usually best to wait until you recover."},
{q:"\"I'm due for other vaccines too.\"",a:"<b>No problem.</b> Flu vaccine may be given at the same time as other vaccines."},
{q:"\"Flu is just a bad cold.\"",a:"<b>It can be much more.</b> In an average year, thousands of people in the US die from flu and many more are hospitalized. The vaccine prevents millions of illnesses and doctor visits each year."}
];
var m=document.getElementById('myths');
myths.forEach(function(x){
  var b=document.createElement('button');b.className='flip';b.setAttribute('aria-expanded','false');
  b.innerHTML='<div class="q"><span>'+x.q+'</span><svg class="tog" width="20" height="20" viewBox="0 0 20 20"><path d="M10 3v14M3 10h14" stroke="#0f766e" stroke-width="2.5"/></svg></div><div class="a">'+x.a+'</div>';
  b.onclick=function(){var o=b.classList.toggle('open');b.setAttribute('aria-expanded',o)};
  m.appendChild(b);
});

var boxes=document.querySelectorAll('.chk input'),note=document.getElementById('note');
[].forEach.call(boxes,function(c){
  c.onchange=function(){
    c.parentNode.classList.toggle('done',c.checked);
    var n=[].filter.call(boxes,function(x){return x.checked}).length;
    note.textContent=n?"Good to know. Mention "+(n>1?"these "+n+" items":"this")+" when you get vaccinated.":"Tick anything that applies \u2014 then mention it at your visit.";
  };
});
</script>
</body>
</html>
