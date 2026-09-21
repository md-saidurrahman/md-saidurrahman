<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Md Saidur Rahman — Education Graduate</title>
<meta name="description" content="Portfolio of Md Saidur Rahman, B.Ed. (Special Education) graduate of the University of Dhaka.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Archivo:wght@500;600;700&family=Literata:opsz,wght@7..72,400;7..72,500;7..72,600&display=swap" rel="stylesheet">
<style>
:root{
  box-sizing:border-box;
  padding-top:env(safe-area-inset-top,0px);
  padding-bottom:env(safe-area-inset-bottom,0px);

  --paper:#EBEFF6;
  --surface:#FFFFFF;
  --ink:#131A2C;
  --muted:#5C6780;
  --rule:#C6D0E2;
  --rule-soft:#DCE3EF;
  --accent:#1E3A8F;
  --accent-ink:#1E3A8F;
  --mark:#F2B12C;
  --mark-soft:#FBE7B8;

  --hdr:58px;
  --gutter:9.5rem;
  --pad:clamp(1.15rem,4vw,3rem);

  --sans:'Archivo','Helvetica Neue',Helvetica,Arial,sans-serif;
  --serif:'Literata',Georgia,'Times New Roman',Times,serif;

  color-scheme:light;
}
@media (prefers-color-scheme:dark){
  :root:not([data-theme="light"]){
    --paper:#0D1220;
    --surface:#141B2C;
    --ink:#E8EDF9;
    --muted:#98A3BD;
    --rule:#2A3550;
    --rule-soft:#1E2740;
    --accent:#9DB4FF;
    --accent-ink:#9DB4FF;
    --mark:#F2B12C;
    --mark-soft:#3A2F12;
    color-scheme:dark;
  }
}
:root[data-theme="dark"]{
  --paper:#0D1220;
  --surface:#141B2C;
  --ink:#E8EDF9;
  --muted:#98A3BD;
  --rule:#2A3550;
  --rule-soft:#1E2740;
  --accent:#9DB4FF;
  --accent-ink:#9DB4FF;
  --mark:#F2B12C;
  --mark-soft:#3A2F12;
  color-scheme:dark;
}

*,*::before,*::after{box-sizing:inherit}
html{height:100%;scroll-behavior:smooth;scroll-padding-top:calc(env(safe-area-inset-top,0px) + var(--hdr) + 1.5rem)}
body{
  margin:0;min-height:100%;
  background:var(--paper);color:var(--ink);
  font-family:var(--serif);font-size:1.0625rem;line-height:1.72;
  -webkit-font-smoothing:antialiased;
}
img{max-width:100%}
a{color:var(--accent-ink)}
:focus-visible{outline:3px solid var(--mark);outline-offset:3px;border-radius:2px}

/* ---------- header ---------- */
.hdr{
  position:sticky;top:env(safe-area-inset-top,0px);z-index:40;
  background:color-mix(in srgb,var(--paper) 88%,transparent);
  backdrop-filter:blur(10px);-webkit-backdrop-filter:blur(10px);
  border-bottom:1px solid var(--rule);
}
.hdr-in{
  max-width:78rem;margin:0 auto;height:var(--hdr);
  padding:0 var(--pad);
  display:flex;align-items:center;gap:1rem;
}
.sig{
  font-family:var(--sans);font-weight:700;font-size:.95rem;letter-spacing:-.01em;
  text-decoration:none;color:var(--ink);white-space:nowrap;
}
.sig span{color:var(--muted);font-weight:500}
.nav{margin-left:auto;display:flex;align-items:center;gap:.15rem}
.nav a{
  font-family:var(--sans);font-size:.85rem;font-weight:500;
  text-decoration:none;color:var(--muted);
  padding:.45rem .6rem;border-radius:3px;
}
.nav a:hover{color:var(--ink)}
.nav a[aria-current="true"]{color:var(--ink);box-shadow:inset 0 -2px 0 var(--mark)}
.tools{display:flex;align-items:center;gap:.4rem;margin-left:.6rem}
.btn-icon{
  font-family:var(--sans);font-size:.8rem;font-weight:600;
  background:transparent;color:var(--muted);
  border:1px solid var(--rule);border-radius:3px;
  padding:.4rem .6rem;cursor:pointer;line-height:1;
}
.btn-icon:hover{color:var(--ink);border-color:var(--ink)}
.menu-btn{display:none}
.prog{height:2px;background:var(--mark);width:0%;transition:width .08s linear}

@media (max-width:860px){
  .nav{
    position:absolute;top:100%;left:0;right:0;
    flex-direction:column;align-items:stretch;gap:0;
    background:var(--surface);border-bottom:1px solid var(--rule);
    padding:.4rem var(--pad) .8rem;display:none;
  }
  .nav.open{display:flex}
  .nav a{padding:.6rem 0;border-bottom:1px solid var(--rule-soft);font-size:.95rem}
  .nav a[aria-current="true"]{box-shadow:inset 3px 0 0 var(--mark);padding-left:.6rem}
  .menu-btn{display:block;margin-left:auto}
  .tools{margin-left:.2rem}
}

/* ---------- layout ---------- */
.wrap{max-width:78rem;margin:0 auto;padding:0 var(--pad)}
.row{
  display:grid;grid-template-columns:var(--gutter) minmax(0,1fr);
  border-top:1px solid var(--rule);
}
.row:first-of-type{border-top:0}
.gut{
  border-right:1px solid var(--rule);
  padding:2.6rem 1.25rem 2.6rem 0;
}
.gut h2{
  position:sticky;top:calc(env(safe-area-inset-top,0px) + var(--hdr) + 1.6rem);
  margin:0;font-family:var(--sans);font-weight:600;font-size:.95rem;
  letter-spacing:-.005em;color:var(--ink);
}
.gut h2 small{display:block;font-weight:500;color:var(--muted);font-size:.78rem;margin-top:.2rem}
.body{padding:2.6rem 0 3.2rem clamp(1.25rem,3vw,2.75rem);min-width:0}
@media (max-width:820px){
  .row{grid-template-columns:1fr}
  .gut{border-right:0;padding:2rem 0 0}
  .gut h2{position:static}
  .body{padding:1rem 0 2.6rem}
}

/* ---------- hero ---------- */
.hero{padding:clamp(3rem,9vw,6rem) 0 clamp(2.5rem,6vw,4rem)}
.hero .name{
  font-family:var(--sans);font-weight:700;
  font-size:clamp(2.9rem,10.5vw,6.6rem);
  line-height:.92;letter-spacing:-.035em;margin:0;
  max-width:14ch;
}
.hero .name em{font-style:normal;display:block}
.role{
  font-family:var(--sans);font-weight:500;font-size:clamp(1rem,2.2vw,1.2rem);
  color:var(--muted);margin:1.4rem 0 0;line-height:1.5;max-width:40ch;
}
.objective{max-width:60ch;margin:1.6rem 0 0;font-size:1.1rem}
.cta{display:flex;flex-wrap:wrap;gap:.6rem;margin-top:2rem}
.btn{
  font-family:var(--sans);font-size:.9rem;font-weight:600;
  text-decoration:none;cursor:pointer;line-height:1;
  padding:.8rem 1.1rem;border-radius:3px;border:1px solid var(--ink);
  background:var(--ink);color:var(--paper);
}
.btn:hover{background:transparent;color:var(--ink)}
.btn.ghost{background:transparent;color:var(--ink);border-color:var(--rule)}
.btn.ghost:hover{border-color:var(--ink);background:var(--surface)}

/* ---------- record table ---------- */
.record{border-top:1px solid var(--rule-soft)}
.record div{
  display:grid;grid-template-columns:11rem minmax(0,1fr);
  gap:1rem;padding:.85rem 0;border-bottom:1px solid var(--rule-soft);
}
.record dt{font-family:var(--sans);font-size:.82rem;font-weight:500;color:var(--muted);margin:0;padding-top:.18rem}
.record dd{margin:0;font-weight:500}
@media (max-width:560px){
  .record div{grid-template-columns:1fr;gap:.1rem;padding:.7rem 0}
}

/* ---------- entries ---------- */
.entry{padding:1.5rem 0;border-bottom:1px solid var(--rule-soft)}
.entry:first-child{padding-top:0}
.entry:last-child{border-bottom:0;padding-bottom:0}
.entry h3{
  font-family:var(--sans);font-weight:600;font-size:1.22rem;
  letter-spacing:-.015em;margin:0 0 .25rem;line-height:1.3;
}
.org{margin:0;color:var(--ink)}
.when{
  font-family:var(--sans);font-size:.82rem;color:var(--muted);
  margin:.5rem 0 0;display:block;
}
.facts{list-style:none;margin:.9rem 0 0;padding:0;display:flex;flex-wrap:wrap;gap:.4rem .5rem}
.facts li{
  font-family:var(--sans);font-size:.8rem;font-weight:500;
  border:1px solid var(--rule);border-radius:3px;padding:.3rem .55rem;color:var(--muted);
}
.facts li b{color:var(--ink);font-weight:600}
.facts li.mark{background:var(--mark-soft);border-color:var(--mark);color:var(--ink)}

.filters{display:flex;flex-wrap:wrap;gap:.4rem;margin:0 0 1.6rem}
.filters button{
  font-family:var(--sans);font-size:.82rem;font-weight:500;
  background:transparent;color:var(--muted);cursor:pointer;
  border:1px solid var(--rule);border-radius:3px;padding:.42rem .75rem;
}
.filters button:hover{color:var(--ink);border-color:var(--ink)}
.filters button[aria-pressed="true"]{background:var(--ink);border-color:var(--ink);color:var(--paper)}
.count{font-family:var(--sans);font-size:.8rem;color:var(--muted);margin:0 0 1.4rem}
.entry[hidden]{display:none}

/* ---------- skills ---------- */
.skills{margin:0}
.skills > div{
  display:grid;grid-template-columns:11rem minmax(0,1fr);gap:1rem;
  padding:1.1rem 0;border-bottom:1px solid var(--rule-soft);
}
.skills > div:last-child{border-bottom:0}
.skills dt{font-family:var(--sans);font-size:.85rem;font-weight:600;margin:0;padding-top:.25rem}
.skills dd{margin:0;display:flex;flex-wrap:wrap;gap:.4rem .5rem}
.chip{
  font-family:var(--sans);font-size:.85rem;font-weight:500;
  border:1px solid var(--rule);border-radius:3px;padding:.35rem .6rem;
  background:var(--surface);
}
.chip small{color:var(--muted);font-weight:400}
@media (max-width:560px){
  .skills > div{grid-template-columns:1fr;gap:.6rem}
}

/* ---------- contact ---------- */
.contact-list{list-style:none;margin:0;padding:0}
.contact-list li{
  display:flex;flex-wrap:wrap;align-items:center;gap:.75rem;
  padding:.95rem 0;border-bottom:1px solid var(--rule-soft);
}
.contact-list .label{font-family:var(--sans);font-size:.8rem;color:var(--muted);width:5.5rem;flex:none}
.contact-list a,.contact-list span.val{font-weight:500;color:var(--ink);text-decoration:none;word-break:break-word}
.contact-list a:hover{box-shadow:inset 0 -2px 0 var(--mark)}
.copy{
  margin-left:auto;font-family:var(--sans);font-size:.75rem;font-weight:600;
  background:transparent;border:1px solid var(--rule);border-radius:3px;
  padding:.3rem .5rem;color:var(--muted);cursor:pointer;
}
.copy:hover{color:var(--ink);border-color:var(--ink)}

.foot{
  border-top:1px solid var(--rule);
  padding:1.6rem 0 2.4rem;
  font-family:var(--sans);font-size:.8rem;color:var(--muted);
  display:flex;flex-wrap:wrap;gap:.6rem 1.5rem;align-items:center;
}
.foot a{color:var(--muted)}

#toast{
  position:fixed;left:50%;transform:translateX(-50%);
  bottom:calc(env(safe-area-inset-bottom,0px) + 1.5rem);
  background:var(--ink);color:var(--paper);
  font-family:var(--sans);font-size:.85rem;font-weight:500;
  padding:.6rem .9rem;border-radius:3px;z-index:60;
  opacity:0;pointer-events:none;transition:opacity .18s ease;
}
#toast.show{opacity:1}

/* one orchestrated entrance, hero only */
.lift{opacity:0;transform:translateY(12px);animation:lift .7s cubic-bezier(.2,.7,.3,1) forwards}
.lift:nth-child(2){animation-delay:.08s}
.lift:nth-child(3){animation-delay:.16s}
.lift:nth-child(4){animation-delay:.24s}
@keyframes lift{to{opacity:1;transform:none}}
@media (prefers-reduced-motion:reduce){
  html{scroll-behavior:auto}
  .lift{animation:none;opacity:1;transform:none}
  *{transition-duration:.001ms !important}
}

@media print{
  .hdr,.cta,.filters,.copy,#toast,.foot{display:none !important}
  :root{--paper:#fff;--ink:#000;--muted:#333;--rule:#999;--rule-soft:#ccc;--surface:#fff}
  body{font-size:11pt}
  .entry[hidden]{display:block !important}
  .row{grid-template-columns:8rem 1fr}
}
</style>
</head>
<body>

<header class="hdr">
  <div class="hdr-in">
    <a class="sig" href="#top">Md Saidur Rahman <span>/ B.Ed.</span></a>
    <nav class="nav" id="nav" aria-label="Sections">
      <a href="#profile">Profile</a>
      <a href="#education">Education</a>
      <a href="#experience">Experience</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>
    <div class="tools">
      <button class="btn-icon menu-btn" id="menuBtn" aria-expanded="false" aria-controls="nav">Menu</button>
      <button class="btn-icon" id="themeBtn" aria-label="Switch to dark theme">Dark</button>
    </div>
  </div>
  <div class="prog" id="prog"></div>
</header>

<main id="top">
  <div class="wrap">

    <section class="hero">
      <h1 class="name lift">Md Saidur<em>Rahman</em></h1>
      <p class="role lift">Education graduate, University of Dhaka — specialised in special education, now teaching with an edtech team in Dhaka.</p>
      <div class="cta lift">
        <a class="btn" href="mailto:saidur.rahman.shoishob@gmail.com">Email me</a>
        <button class="btn ghost" id="printBtn">Save as PDF</button>
      </div>
    </section>

    <section class="row" id="profile">
      <div class="gut"><h2>Profile<small>Who I am</small></h2></div>
      <div class="body">
        <p class="objective">I want to contribute to education with the academic knowledge and skills I have built, addressing both contemporary and traditional problems in the field by generating research, knowledge and ideas. My next step is higher study abroad, to widen that knowledge and sharpen my research expertise.</p>
        <dl class="record">
          <div><dt>Degree</dt><dd>B.Ed. in Special Education, University of Dhaka, 2025</dd></div>
          <div><dt>Current role</dt><dd>Instructor, Mojaru Educational Technology Limited</dd></div>
          <div><dt>Research</dt><dd>Data enumerator on a UNICEF-funded study of teacher professional development</dd></div>
          <div><dt>Based in</dt><dd>Mirpur, Dhaka</dd></div>
          <div><dt>Languages</dt><dd>Bangla and English</dd></div>
          <div><dt>Looking for</dt><dd>Graduate study and research work in education</dd></div>
        </dl>
      </div>
    </section>

    <section class="row" id="education">
      <div class="gut"><h2>Education<small>2018 to 2025</small></h2></div>
      <div class="body">

        <article class="entry">
          <h3>Bachelor of Education (B.Ed.)</h3>
          <p class="org">University of Dhaka</p>
          <span class="when">1 January 2022 – 27 August 2025</span>
          <ul class="facts">
            <li>Specialisation <b>Special Education</b></li>
          </ul>
        </article>

        <article class="entry">
          <h3>Higher Secondary Certificate</h3>
          <p class="org">Shaheed Police Smriti College</p>
          <span class="when">2020</span>
          <ul class="facts">
            <li>Science group</li>
            <li class="mark">GPA <b>5.00</b></li>
          </ul>
        </article>

        <article class="entry">
          <h3>Secondary School Certificate</h3>
          <p class="org">Gonobhaban Govt. High School</p>
          <span class="when">2018</span>
          <ul class="facts">
            <li>Science group</li>
            <li class="mark">GPA <b>5.00</b></li>
          </ul>
        </article>

      </div>
    </section>

    <section class="row" id="experience">
      <div class="gut"><h2>Experience<small>Teaching, research, internship</small></h2></div>
      <div class="body">
        <div class="filters" role="group" aria-label="Filter experience by type">
          <button data-filter="all" aria-pressed="true">All</button>
          <button data-filter="teaching" aria-pressed="false">Teaching</button>
          <button data-filter="research" aria-pressed="false">Research</button>
          <button data-filter="internship" aria-pressed="false">Internship</button>
        </div>
        <p class="count" id="count" aria-live="polite">Showing all 3 roles</p>

        <article class="entry" data-type="teaching">
          <h3>Instructor</h3>
          <p class="org">Mojaru Educational Technology Limited</p>
          <span class="when">18 February 2025 – present</span>
          <ul class="facts"><li>Teaching</li></ul>
        </article>

        <article class="entry" data-type="research">
          <h3>Data Enumerator</h3>
          <p class="org">Effectiveness study on the Continuous Professional Development (CPD) programme and training — funded by UNICEF, supervised by the Directorate of Primary Education</p>
          <span class="when">9 – 19 November 2025</span>
          <ul class="facts"><li>Research</li><li>Field data collection</li></ul>
        </article>

        <article class="entry" data-type="internship">
          <h3>Intern Teacher</h3>
          <p class="org">Dhaka Govt. Badhir High School</p>
          <span class="when">3 November 2024 – 27 February 2025</span>
          <ul class="facts"><li>Internship</li><li>Special education setting</li></ul>
        </article>

      </div>
    </section>

    <section class="row" id="skills">
      <div class="gut"><h2>Skills<small>Tools and strengths</small></h2></div>
      <div class="body">
        <dl class="skills">
          <div>
            <dt>Research</dt>
            <dd>
              <span class="chip">SPSS <small>educational data analysis</small></span>
              <span class="chip">Survey data collection</span>
            </dd>
          </div>
          <div>
            <dt>Teaching tools</dt>
            <dd>
              <span class="chip">Google Classroom</span>
              <span class="chip">Zoom</span>
              <span class="chip">LMS platforms</span>
            </dd>
          </div>
          <div>
            <dt>Documents</dt>
            <dd>
              <span class="chip">Word</span>
              <span class="chip">Excel</span>
              <span class="chip">PowerPoint</span>
              <span class="chip">Google Docs, Sheets, Slides and Forms</span>
            </dd>
          </div>
          <div>
            <dt>Design and media</dt>
            <dd>
              <span class="chip">Canva <small>presentations and marketing</small></span>
              <span class="chip">Facebook</span>
              <span class="chip">Instagram</span>
              <span class="chip">TikTok</span>
            </dd>
          </div>
          <div>
            <dt>Working with people</dt>
            <dd>
              <span class="chip">Communication</span>
              <span class="chip">Organisation</span>
              <span class="chip">Teamwork</span>
            </dd>
          </div>
          <div>
            <dt>Beyond the classroom</dt>
            <dd>
              <span class="chip">Debate</span>
              <span class="chip">Public speaking</span>
            </dd>
          </div>
          <div>
            <dt>Languages</dt>
            <dd>
              <span class="chip">Bangla</span>
              <span class="chip">English</span>
            </dd>
          </div>
        </dl>
      </div>
    </section>

    <section class="row" id="contact">
      <div class="gut"><h2>Contact<small>Get in touch</small></h2></div>
      <div class="body">
        <ul class="contact-list">
          <li>
            <span class="label">Email</span>
            <a href="mailto:saidur.rahman.shoishob@gmail.com">saidur.rahman.shoishob@gmail.com</a>
            <button class="copy" data-copy="saidur.rahman.shoishob@gmail.com">Copy</button>
          </li>
          <li>
            <span class="label">Phone</span>
            <a href="tel:+8801631076583">01631076583</a>
            <button class="copy" data-copy="01631076583">Copy</button>
          </li>
          <li>
            <span class="label">Address</span>
            <span class="val">91/B, Middle Pirerbagh, Mirpur, Dhaka-1216</span>
          </li>
        </ul>
      </div>
    </section>

    <footer class="foot">
      <span>Md Saidur Rahman</span>
      <span>Dhaka, Bangladesh</span>
      <span id="year"></span>
    </footer>

  </div>
</main>

<div id="toast" role="status" aria-live="polite"></div>

<script>
(function(){
  "use strict";

  /* theme */
  var root=document.documentElement,themeBtn=document.getElementById("themeBtn");
  function systemDark(){return window.matchMedia&&window.matchMedia("(prefers-color-scheme: dark)").matches;}
  function current(){return root.getAttribute("data-theme")||(systemDark()?"dark":"light");}
  function paint(){
    var d=current()==="dark";
    themeBtn.textContent=d?"Light":"Dark";
    themeBtn.setAttribute("aria-label","Switch to "+(d?"light":"dark")+" theme");
  }
  try{var saved=localStorage.getItem("srp-theme");if(saved==="dark"||saved==="light")root.setAttribute("data-theme",saved);}catch(e){}
  paint();
  themeBtn.addEventListener("click",function(){
    var next=current()==="dark"?"light":"dark";
    root.setAttribute("data-theme",next);
    try{localStorage.setItem("srp-theme",next);}catch(e){}
    paint();
  });

  /* mobile menu */
  var nav=document.getElementById("nav"),menuBtn=document.getElementById("menuBtn");
  menuBtn.addEventListener("click",function(){
    var open=nav.classList.toggle("open");
    menuBtn.setAttribute("aria-expanded",String(open));
    menuBtn.textContent=open?"Close":"Menu";
  });
  nav.addEventListener("click",function(e){
    if(e.target.tagName==="A"&&nav.classList.contains("open")){
      nav.classList.remove("open");menuBtn.setAttribute("aria-expanded","false");menuBtn.textContent="Menu";
    }
  });

  /* scroll progress + active section */
  var prog=document.getElementById("prog");
  var links=Array.prototype.slice.call(nav.querySelectorAll("a"));
  var sections=links.map(function(a){return document.querySelector(a.getAttribute("href"));}).filter(Boolean);
  var ticking=false;
  function update(){
    var h=document.documentElement;
    var max=h.scrollHeight-h.clientHeight;
    prog.style.width=(max>0?(h.scrollTop/max)*100:0)+"%";
    var line=h.clientHeight*0.32,active=null;
    sections.forEach(function(s){if(s.getBoundingClientRect().top<=line)active=s;});
    links.forEach(function(a){
      if(active&&a.getAttribute("href")==="#"+active.id)a.setAttribute("aria-current","true");
      else a.removeAttribute("aria-current");
    });
    ticking=false;
  }
  window.addEventListener("scroll",function(){if(!ticking){ticking=true;requestAnimationFrame(update);}},{passive:true});
  window.addEventListener("resize",update);update();

  /* experience filter */
  var entries=Array.prototype.slice.call(document.querySelectorAll("#experience .entry"));
  var buttons=Array.prototype.slice.call(document.querySelectorAll(".filters button"));
  var count=document.getElementById("count");
  buttons.forEach(function(btn){
    btn.addEventListener("click",function(){
      var f=btn.getAttribute("data-filter");
      buttons.forEach(function(b){b.setAttribute("aria-pressed",String(b===btn));});
      var shown=0;
      entries.forEach(function(en){
        var show=(f==="all"||en.getAttribute("data-type")===f);
        en.hidden=!show;if(show)shown++;
      });
      count.textContent=f==="all"
        ? "Showing all "+shown+" roles"
        : "Showing "+shown+" "+(shown===1?"role":"roles")+" in "+btn.textContent.toLowerCase();
      update();
    });
  });

  /* copy to clipboard */
  var toast=document.getElementById("toast"),toastTimer;
  function say(msg){
    toast.textContent=msg;toast.classList.add("show");
    clearTimeout(toastTimer);toastTimer=setTimeout(function(){toast.classList.remove("show");},1800);
  }
  document.addEventListener("click",function(e){
    var b=e.target.closest?e.target.closest(".copy"):null;
    if(!b)return;
    var text=b.getAttribute("data-copy");
    function fallback(){
      var t=document.createElement("textarea");
      t.value=text;t.setAttribute("readonly","");t.style.position="fixed";t.style.opacity="0";
      document.body.appendChild(t);t.select();
      var ok=false;try{ok=document.execCommand("copy");}catch(err){ok=false;}
      document.body.removeChild(t);
      say(ok?"Copied":"Select and copy: "+text);
    }
    if(navigator.clipboard&&navigator.clipboard.writeText){
      navigator.clipboard.writeText(text).then(function(){say("Copied");},fallback);
    }else fallback();
  });

  /* print */
  document.getElementById("printBtn").addEventListener("click",function(){window.print();});

  document.getElementById("year").textContent="Updated "+new Date().getFullYear();
})();
</script>
</body>
</html>

