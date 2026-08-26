<!DOCTYPE html>

<html dir="ltr" lang="en">
<head>
<meta charset="utf-8"/>
<meta content="width=device-width,initial-scale=1" name="viewport"/>
<meta content="Amir Mehdi Parviz — AI Engineer portfolio" name="description"/>
<title>Amir Mehdi Parviz — Eclipse Ring</title>
<link href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='14' fill='%230a1117'/%3E%3Ccircle cx='32' cy='32' r='16' fill='none' stroke='%236fd9cf' stroke-width='3'/%3E%3Ccircle cx='32' cy='16' r='4' fill='%23e9ad56'/%3E%3C/svg%3E" rel="icon" type="image/svg+xml"/>
<meta content="website" property="og:type"/>
<meta content="Amir Mehdi Parviz — AI Engineer" property="og:title"/>
<meta content="AI/ML engineering, full-stack development, and Persian NLP/OCR systems." property="og:description"/>
<meta content="summary" name="twitter:card"/>
<meta content="Amir Mehdi Parviz — AI Engineer" name="twitter:title"/>
<meta content="AI/ML engineering, full-stack development, and Persian NLP/OCR systems." name="twitter:description"/>
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500&amp;family=Inter:wght@400;500;600&amp;family=Space+Grotesk:wght@500;600;700&amp;family=Vazirmatn:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css"/>
<style>
:root{
  --bg:#0a1117;--panel:#0d151c;--panel-2:#111b23;--panel-3:#15232e;
  --line:#202f3a;--line-strong:#314551;--text:#eff4f6;--muted:#9cadb6;--faint:#617581;
  --accent:#6fd9cf;--warm:#e9ad56;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{position:relative;margin:0;background:var(--bg);color:var(--text);font:15px/1.7 Inter,sans-serif;overflow-x:hidden}
a{color:inherit;text-decoration:none}
button{font:inherit;cursor:pointer}
.wrap{width:min(1200px,calc(100% - 64px));margin:auto}
.mono{font-family:'IBM Plex Mono',monospace}

nav{position:sticky;top:0;z-index:40;background:rgba(10,17,23,.88);backdrop-filter:blur(16px);border-bottom:1px solid var(--line)}
nav .wrap{min-height:66px;display:flex;align-items:center;gap:24px;justify-content:space-between}
.brand{font:600 14px 'Space Grotesk';letter-spacing:.06em;white-space:nowrap}
.navlinks{display:flex;align-items:center;gap:22px;flex:1;overflow-x:auto;scrollbar-width:none;color:var(--muted);font-size:12.5px;white-space:nowrap}
.navlinks::-webkit-scrollbar{display:none}
.navlinks a{display:inline-block;padding:8px 0;transition:.2s}
.navlinks a:hover{color:var(--accent)}
.nav-actions{display:flex;align-items:center;gap:9px;flex-shrink:0}
.lang-toggle{border:1px solid var(--line-strong);background:var(--panel);color:var(--text);border-radius:7px;min-width:40px;min-height:36px;padding:0 10px;font:500 11px 'IBM Plex Mono';transition:.2s}
.lang-toggle:hover{border-color:var(--accent);color:var(--accent)}
.nav-email{font:500 11px 'IBM Plex Mono';color:var(--muted)}
.nav-email:hover{color:var(--accent)}

main{padding:40px 0 0;position:relative;z-index:2}
footer{position:relative;z-index:2}
.surface{margin-bottom:88px}
.hero.surface{margin-bottom:56px}

.hero-grid{display:grid;grid-template-columns:1fr 1.25fr;gap:32px;align-items:stretch}
.hero-copy{display:flex;flex-direction:column;justify-content:center;padding:12px 0}
.kicker{color:var(--accent);font:500 11px 'IBM Plex Mono';letter-spacing:.12em;text-transform:uppercase}
.identity-name{font:700 clamp(40px,5.2vw,64px)/1.05 'Space Grotesk';letter-spacing:-.04em;margin:14px 0 8px}
.identity-role{font:500 13px 'IBM Plex Mono';color:var(--warm);margin-bottom:14px}
.identity-meta{display:flex;gap:8px 14px;flex-wrap:wrap;color:var(--muted);font:11px 'IBM Plex Mono';margin-bottom:18px}
.profile-links{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:28px}
.profile-link{display:inline-flex;align-items:center;min-height:38px;border:1px solid var(--line-strong);border-radius:7px;padding:0 12px;color:var(--muted);font:10.5px 'IBM Plex Mono';transition:.2s}
.profile-link:hover{color:var(--accent);border-color:var(--accent);background:rgba(111,217,207,.05)}
h1{font:600 clamp(28px,3.4vw,42px)/1.15 'Space Grotesk';letter-spacing:-.03em;margin:0 0 14px;max-width:560px}
.lead{font-size:15px;color:var(--muted);max-width:560px;margin:0}
.actions{display:flex;gap:10px;flex-wrap:wrap;margin-top:26px}
.btn{display:inline-flex;align-items:center;min-height:44px;padding:0 18px;border:1px solid var(--line-strong);border-radius:7px;font-weight:500;transition:.2s}
.btn:hover{border-color:var(--accent)}
.btn.primary{background:var(--text);color:var(--bg);border-color:var(--text)}

.scanner{border:1px solid var(--line-strong);border-radius:12px;background:var(--panel);overflow:hidden}
.scanner-head,.preview-status{min-height:45px;display:flex;align-items:center;gap:10px;padding:0 15px;color:var(--faint);font:10.5px 'IBM Plex Mono'}
.scanner-head{border-bottom:1px solid var(--line)}
.preview-status{border-top:1px solid var(--line)}
.preview-status span:nth-child(2){flex:1;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.preview-stage{aspect-ratio:16/10;position:relative;overflow:hidden;background:#05090d;display:grid;place-items:center}
.preview-media{position:absolute;inset:0;width:100%;height:100%;object-fit:contain;opacity:0;transform:scale(1.01);transition:.7s ease;background:#05090d}
.preview-media.visible{opacity:1;transform:scale(1)}
.placeholder{text-align:center;color:var(--faint);font:11px 'IBM Plex Mono';padding:30px;max-width:420px}
.placeholder strong{display:block;color:var(--muted);margin-bottom:6px}
.rail{margin-inline-start:auto;display:flex;gap:5px}
.rail-dot{width:18px;height:3px;border:0;background:#334552;padding:0;cursor:pointer}
.rail-dot.active{background:var(--accent)}
.preview-caption{position:absolute;z-index:4;inset-inline:14px;bottom:14px;padding:14px 15px;border:1px solid rgba(255,255,255,.14);background:rgba(5,9,13,.86);backdrop-filter:blur(12px);display:flex;align-items:flex-end;justify-content:space-between;gap:18px;border-radius:8px;opacity:0;transform:translateY(5px);transition:.35s;pointer-events:none}
.preview-caption.show{opacity:1;transform:none}
.preview-caption .pc-copy{min-width:0}
.preview-caption .pc-label{color:var(--accent);font:10px 'IBM Plex Mono';letter-spacing:.1em}
.preview-caption b{display:block;font:600 15px 'Space Grotesk';margin-top:3px}
.preview-caption p{margin:5px 0 0;color:var(--muted);font-size:11.5px;line-height:1.5;max-width:420px}
.preview-caption a{pointer-events:auto;color:var(--text);font:10.5px 'IBM Plex Mono';white-space:nowrap;flex-shrink:0}

.proof-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin-bottom:88px}
.metric{background:var(--panel);border-radius:11px;padding:18px 20px;box-shadow:inset 0 1px 0 rgba(255,255,255,.025)}
.metric b{display:block;font:600 19px 'Space Grotesk';margin-bottom:3px}
.metric span{color:var(--muted);font-size:12px}

main>.surface:not(.hero){display:grid;grid-template-columns:210px minmax(0,1fr);column-gap:48px}
main>.surface:not(.hero)>.section-head{grid-column:1;align-self:start;position:sticky;top:90px}
main>.surface:not(.hero)>:not(.section-head){grid-column:2}
.section-head .num{color:var(--faint);font:11px 'IBM Plex Mono'}
.section-head>div:first-child::after{content:"";display:block;width:30px;height:2px;background:var(--accent);margin-top:14px;opacity:.8;border-radius:2px}
h2{font:600 27px 'Space Grotesk';margin:10px 0 0;letter-spacing:-.02em;line-height:1.2}
.section-head p{color:var(--muted);margin:14px 0 0;font-size:11.5px;line-height:1.65;max-width:200px}

.focus-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:0 24px;border-top:1px solid rgba(152,168,181,.13)}
.focus-item{padding:20px 0;border-bottom:1px solid rgba(152,168,181,.09);transition:.2s}
.focus-item:hover{background:rgba(255,255,255,.012)}
.focus-no{color:var(--accent);font:10px 'IBM Plex Mono';letter-spacing:.1em}
.focus-item h3{font:600 16px 'Space Grotesk';margin:10px 0 8px}
.focus-item p{margin:0;color:var(--muted);font-size:12.5px;line-height:1.65}

.skills-compact{border-top:1px solid rgba(152,168,181,.13)}
.skill-row{display:grid;grid-template-columns:140px 1fr;gap:20px;align-items:start;padding:18px 0;border-bottom:1px solid rgba(152,168,181,.1)}
.skill-cat{font:500 11px 'IBM Plex Mono';color:var(--accent);letter-spacing:.06em;text-transform:uppercase;padding-top:5px}
.skill-tags{display:flex;flex-wrap:wrap;gap:8px}
.skill-tags span{background:rgba(17,29,39,.74);color:var(--muted);border:1px solid rgba(152,168,181,.10);border-radius:999px;padding:6px 10px;font-size:11.5px}

.project-grid{border-top:1px solid rgba(152,168,181,.14)}
.project-row{display:grid;grid-template-columns:40px minmax(0,1fr) 250px;gap:18px;padding:26px 0;border-bottom:1px solid rgba(152,168,181,.1);scroll-margin-top:96px;transition:.2s}
.project-row:hover{background:rgba(255,255,255,.01)}
.proj-no{color:var(--faint);font:11px 'IBM Plex Mono';padding-top:4px}
.project-label{display:block;color:var(--accent);font:500 10px 'IBM Plex Mono';letter-spacing:.1em;margin-bottom:8px}
.project-row-main h3{font:600 19px 'Space Grotesk';margin:0 0 8px}
.project-row-main p{margin:0;color:var(--muted);font-size:13px;line-height:1.7}
.project-row-side{display:flex;flex-direction:column;gap:9px;justify-content:center}
.project-row-side div{display:grid;grid-template-columns:78px 1fr;gap:8px}
.project-row-side span{color:var(--faint);font:9px 'IBM Plex Mono';letter-spacing:.07em}
.project-row-side b{font:500 10.8px 'IBM Plex Mono';color:var(--text);line-height:1.5}
.project-row details{grid-column:2/-1;margin-top:8px;border-top:1px solid rgba(152,168,181,.08)}
.project-row details summary{padding:10px 0;color:var(--accent);font:500 9.5px 'IBM Plex Mono';letter-spacing:.05em;cursor:pointer;list-style:none;display:flex;align-items:center;gap:8px}
.project-row details summary::-webkit-details-marker{display:none}
.project-row details summary::after{content:"+";color:var(--faint);font-size:14px}
.project-row details[open] summary::after{content:"\2212"}
.overview-body{padding:0 0 14px}
.overview-note{font-size:11px;color:var(--faint);margin:0 0 12px}
.public-diagram{display:flex;align-items:center;gap:6px;flex-wrap:wrap}
.diagram-node{padding:7px 10px;background:var(--panel-3);border-radius:6px;color:var(--text);font:500 10px 'IBM Plex Mono'}
.diagram-arrow{color:var(--faint);font:12px 'IBM Plex Mono'}

.privacy-note{margin-top:22px;border-inline-start:2px solid rgba(111,217,207,.5);padding:10px 14px;color:var(--faint);font-size:12px;display:flex;gap:9px;align-items:flex-start;background:rgba(111,217,207,.03)}
.privacy-note strong{color:var(--muted);font-weight:500}

.build-card{border-top:1px solid rgba(152,168,181,.13);display:grid;grid-template-columns:40px minmax(0,1fr) auto;gap:16px;align-items:start;padding:22px 0}
.build-card h3{font:600 19px 'Space Grotesk';margin:0 0 6px}
.build-card p{margin:0;color:var(--muted);font-size:13.5px}
.build-status{color:var(--warm);font:10px 'IBM Plex Mono';letter-spacing:.07em;border:1px solid var(--line-strong);padding:7px 9px;border-radius:6px;white-space:nowrap;background:rgba(232,170,77,.08)}

.jobs{border-top:1px solid rgba(152,168,181,.13)}
.job-card{display:grid;grid-template-columns:160px 1fr;column-gap:26px;padding:24px 0;border-bottom:1px solid rgba(152,168,181,.1)}
.job-card time{display:block;color:var(--faint);font:10.5px 'IBM Plex Mono';grid-column:1}
.job-card .org{color:var(--accent);font-size:12.5px;margin-top:6px;grid-column:1}
.job-card h3{font:600 18px 'Space Grotesk';margin:0;grid-column:2;grid-row:1/span 2}
.job-card p{margin:6px 0 0;color:var(--muted);font-size:13.5px;grid-column:2}
.job-tags{display:flex;gap:6px;flex-wrap:wrap;margin-top:14px;grid-column:2}
.job-tags span{background:rgba(255,255,255,.03);border-radius:5px;padding:5px 8px;color:var(--faint);font:9.5px 'IBM Plex Mono'}

.writing-list{border-top:1px solid rgba(152,168,181,.13)}
.writing-item{display:grid;grid-template-columns:36px 1fr auto;align-items:center;gap:14px;padding:20px 0;border-bottom:1px solid rgba(152,168,181,.09);transition:.2s}
.writing-item:hover{background:rgba(255,255,255,.012)}
.writing-item h3{margin:0;font:600 15px 'Space Grotesk'}
.writing-item p{margin:4px 0 0;color:var(--muted);font-size:12px}
.writing-item .arrow{color:var(--accent);font:10px 'IBM Plex Mono';white-space:nowrap}

.about-grid{display:grid;grid-template-columns:1.3fr .8fr;gap:24px}
.about-card p{margin:0;color:var(--muted)}
.edu .label{color:var(--faint);font:10px 'IBM Plex Mono';letter-spacing:.08em;margin-bottom:8px}
.edu b{display:block;font:600 15px 'Space Grotesk';margin-bottom:5px}
.edu span{color:var(--muted);font-size:12.5px}

.contact-band{position:relative;z-index:2;border-top:1px solid var(--line);padding:72px 0}
.contact-band-inner{max-width:640px;text-align:center;margin:auto}
.contact-band .num{display:block;color:var(--faint);font-size:11px;margin-bottom:14px}
.contact-band h2{font-size:clamp(24px,3.4vw,34px)}
.contact-band p{color:var(--muted);margin:16px 0 0;font-size:14px;line-height:1.7}
.contact-actions{display:flex;gap:12px;justify-content:center;flex-wrap:wrap;margin-top:30px}
.btn.big{min-height:50px;padding:0 26px;font-size:14px;border-radius:9px}
footer{border-top:1px solid var(--line);padding:40px 0 56px;color:var(--muted)}
.footer-row{display:flex;justify-content:space-between;gap:20px;flex-wrap:wrap;align-items:center}
.footer-email{color:var(--muted);font-size:11px}
.footer-email:hover{color:var(--accent)}

.reveal{opacity:0;transform:translateY(10px);transition:.5s}
.reveal.in{opacity:1;transform:none}

html[dir="rtl"] body{font-family:'Vazirmatn',sans-serif;line-height:1.85}
html[dir="rtl"] .mono,html[dir="rtl"] .kicker,html[dir="rtl"] .identity-role,html[dir="rtl"] .identity-meta,html[dir="rtl"] .profile-link,html[dir="rtl"] .nav-email,html[dir="rtl"] .lang-toggle,html[dir="rtl"] .scanner-head,html[dir="rtl"] .preview-status,html[dir="rtl"] .project-label,html[dir="rtl"] .proj-no,html[dir="rtl"] .section-head .num,html[dir="rtl"] .project-row-side span,html[dir="rtl"] .project-row-side b,html[dir="rtl"] .build-status,html[dir="rtl"] .job-card time,html[dir="rtl"] .job-tags span,html[dir="rtl"] .writing-item .arrow,html[dir="rtl"] .skill-cat,html[dir="rtl"] .diagram-node,html[dir="rtl"] .project-row details summary{font-family:'Vazirmatn',sans-serif}
html[dir="rtl"] .identity-name,html[dir="rtl"] h1,html[dir="rtl"] h2,html[dir="rtl"] .focus-item h3,html[dir="rtl"] .project-row-main h3,html[dir="rtl"] .build-card h3,html[dir="rtl"] .job-card h3,html[dir="rtl"] .writing-item h3,html[dir="rtl"] .edu b,html[dir="rtl"] .preview-caption b{font-family:'Vazirmatn',sans-serif;letter-spacing:0;line-height:1.5}
html[dir="rtl"] .diagram-arrow{transform:scaleX(-1)}

@media(max-width:1024px){
  .wrap{width:min(1200px,calc(100% - 40px))}
  main>.surface:not(.hero){grid-template-columns:170px minmax(0,1fr);column-gap:28px}
  .hero-grid{gap:24px}
  .about-grid{grid-template-columns:1fr}
}

@media(max-width:820px){
  .hero-grid{grid-template-columns:1fr}
  .scanner{order:-1}
  main>.surface:not(.hero){grid-template-columns:92px minmax(0,1fr);column-gap:16px}
  main>.surface:not(.hero)>.section-head{top:80px}
  .section-head p{display:none}
  .focus-grid{grid-template-columns:1fr 1fr}
  .job-card{grid-template-columns:1fr;row-gap:6px}
  .job-card time,.job-card .org,.job-card h3,.job-card p,.job-tags{grid-column:1}
  .job-card h3{grid-row:auto}
  .project-row{grid-template-columns:32px 1fr}
  .project-row-side{grid-column:2;display:grid;grid-template-columns:1fr 1fr;gap:8px 14px;margin-top:10px}
  .project-row-side div{display:block}
  .project-row-side span{display:block;margin-bottom:2px}
  .project-row details{grid-column:2}
  .writing-item p{display:-webkit-box;-webkit-line-clamp:1;-webkit-box-orient:vertical;overflow:hidden}
}

@media(max-width:768px){
  nav .wrap{min-height:auto;padding:10px 0 8px;display:grid;grid-template-columns:1fr auto;gap:8px 12px}
  .brand{font-size:12px}
  .nav-actions{justify-self:end}
  .nav-email{display:none}
  .navlinks{grid-column:1/-1;order:3;padding:6px 0 0;font-size:11px;gap:16px}
  main{padding-top:26px}
  .wrap{width:min(1200px,calc(100% - 28px))}
  .surface{margin-bottom:56px}
  .hero.surface{margin-bottom:32px}
  .proof-grid{grid-template-columns:1fr 1fr;gap:8px;margin-bottom:56px}
  .identity-name{font-size:clamp(38px,12vw,52px)}
  h1{font-size:clamp(26px,7.5vw,32px);max-width:none}
  .lead{max-width:none}
  .profile-links{display:grid;grid-template-columns:1fr 1fr;gap:7px}
  .profile-link{justify-content:center}
  .actions{display:grid;grid-template-columns:1fr}
  h2{font-size:clamp(22px,6.5vw,26px)}
  .focus-item h3{font-size:14.5px}
  .job-card,.build-card,.project-row{padding:20px 0}
  .contact-band{padding:52px 0}
  .contact-actions{display:grid;grid-template-columns:1fr}
}

@media(max-width:480px){
  .wrap{width:min(1200px,calc(100% - 22px))}
  .proof-grid{grid-template-columns:1fr}
  .focus-grid{grid-template-columns:1fr}
  .project-row-side{grid-template-columns:1fr}
  .footer-row{flex-direction:column;align-items:flex-start}
}

@media(prefers-reduced-motion:reduce){*{scroll-behavior:auto!important;transition:none!important;animation:none!important}}

#starField{position:fixed;inset:0;width:100%;height:100%;pointer-events:none;z-index:0;opacity:.6}
#scrollOrbit{position:absolute;inset:0;width:100%;height:100%;pointer-events:none;z-index:0;overflow:visible}
.orbit-base,.orbit-glow,.orbit-core{fill:none;vector-effect:non-scaling-stroke;stroke-linecap:round;stroke-linejoin:round}
.orbit-base{stroke:rgba(232,170,77,.1);stroke-width:1.35}
.orbit-glow{stroke:rgba(232,170,77,.24);stroke-width:8;stroke-dasharray:92 1000;filter:blur(5px);opacity:.7;will-change:stroke-dashoffset}
.orbit-core{stroke:rgba(255,211,132,.9);stroke-width:2;stroke-dasharray:92 1000;filter:drop-shadow(0 0 5px rgba(232,170,77,.4));will-change:stroke-dashoffset}

.sun-end-zone{position:relative;z-index:1;height:520px;margin-top:20px;overflow:hidden}
.terminal-sun{position:absolute;left:50%;bottom:40px;width:min(480px,74vw);height:480px;transform:translateX(-50%);pointer-events:none;opacity:.7}
.sun-haze{position:absolute;left:50%;bottom:-1.7%;width:83%;height:27%;transform:translateX(-50%);border-radius:50%;background:radial-gradient(ellipse at 50% 100%,rgba(111,217,207,.05),transparent 70%);filter:blur(9px)}
.sun-body{position:absolute;left:50%;bottom:13.75%;width:62.5%;height:62.5%;transform:translateX(-50%);border-radius:50%;background:radial-gradient(circle,rgba(10,17,23,.96) 0 62%,rgba(232,170,77,.18) 63% 65%,rgba(10,17,23,.9) 66% 100%);border:1px solid rgba(232,170,77,.16);box-shadow:0 -8px 40px rgba(232,170,77,.06)}

.sun-tech-orbits{position:absolute;inset:0;pointer-events:none;transform-origin:50% 55%}
.orbit-track{position:absolute;inset:0;animation:orbit-spin 42s linear infinite;transform-origin:50% 55%}
.orbit-track.inner{animation-duration:30s;animation-direction:reverse}
.orbit-item{position:absolute;left:50%;top:55%;transform:translate(-50%,-50%) rotate(var(--angle)) translateY(calc(var(--radius) * -1))}
.orbit-badge-wrap{transform:rotate(calc(-1 * var(--angle)))}
.orbit-badge{display:flex;align-items:center;gap:8px;padding:7px 11px;border-radius:999px;border:1px solid rgba(232,170,77,.15);background:rgba(10,17,23,.75);color:var(--text);font:500 10px 'IBM Plex Mono';box-shadow:0 10px 22px rgba(0,0,0,.16);backdrop-filter:blur(8px);white-space:nowrap;animation:orbit-counter-spin 42s linear infinite}
.orbit-track.inner .orbit-badge{animation:orbit-counter-spin-rev 30s linear infinite}
.orbit-badge i{font-size:14px;color:rgba(255,214,141,.9)}
.orbit-badge span{opacity:.88}
@keyframes orbit-spin{to{transform:rotate(360deg)}}
@keyframes orbit-counter-spin{to{transform:rotate(-360deg)}}
@keyframes orbit-counter-spin-rev{to{transform:rotate(360deg)}}

@media(max-width:768px){
  #starField{opacity:.4}
  .orbit-base{stroke-width:1}
  .orbit-glow{stroke-width:6;opacity:.55}
  .orbit-core{stroke-width:1.6}
  .sun-end-zone{height:340px;margin-top:10px}
  .terminal-sun{width:88vw;height:320px;bottom:20px}
  .sun-tech-orbits{transform:scale(.72)}
}
@media(max-width:480px){
  .orbit-badge span{display:none}
  .orbit-badge{padding:7px;border-radius:999px}
  .sun-tech-orbits{transform:scale(.55)}
}
@media(prefers-reduced-motion:reduce){.orbit-track,.orbit-badge{animation:none}}

</style>
</head>
<body>
<canvas aria-hidden="true" id="starField"></canvas>
<svg aria-hidden="true" id="scrollOrbit" preserveaspectratio="none" viewbox="0 0 1000 1000">
<path class="orbit-base" d="M 965 16 C 900 130 858 230 790 332 C 710 451 640 548 602 648 C 565 744 535 825 500 875 C 462 910 440 930 438 950 C 436 975 458 992 500 995 C 548 998 578 978 579 950 C 580 920 548 900 500 900 C 452 900 420 922 420 952 C 420 982 452 1000 500 1000 C 548 1000 580 980 580 950" pathlength="1000"></path>
<path class="orbit-glow" d="M 965 16 C 900 130 858 230 790 332 C 710 451 640 548 602 648 C 565 744 535 825 500 875 C 462 910 440 930 438 950 C 436 975 458 992 500 995 C 548 998 578 978 579 950 C 580 920 548 900 500 900 C 452 900 420 922 420 952 C 420 982 452 1000 500 1000 C 548 1000 580 980 580 950" id="orbitGlow" pathlength="1000"></path>
<path class="orbit-core" d="M 965 16 C 900 130 858 230 790 332 C 710 451 640 548 602 648 C 565 744 535 825 500 875 C 462 910 440 930 438 950 C 436 975 458 992 500 995 C 548 998 578 978 579 950 C 580 920 548 900 500 900 C 452 900 420 922 420 952 C 420 982 452 1000 500 1000 C 548 1000 580 980 580 950" id="orbitCore" pathlength="1000"></path>
</svg>
<nav>
<div class="wrap">
<div class="brand">A.M.PARVIZ</div>
<div class="navlinks">
<a data-i18n="nav.focus" href="#focus">Focus</a>
<a data-i18n="nav.skills" href="#skills">Skills</a>
<a data-i18n="nav.projects" href="#projects">Systems</a>
<a data-i18n="nav.building" href="#building">Building</a>
<a data-i18n="nav.experience" href="#experience">Experience</a>
<a data-i18n="nav.writing" href="#writing">Writing</a>
<a data-i18n="nav.about" href="#about">About</a>
</div>
<div class="nav-actions">
<a class="nav-email" data-i18n="nav.email" href="https://mail.google.com/mail/?view=cm&amp;fs=1&amp;to=a.m.parviz02@gmail.com" rel="noopener" target="_blank">EMAIL ↗</a>
<button aria-label="Switch language" class="lang-toggle" id="langToggle" type="button">FA</button>
</div>
</div>
</nav>
<main class="wrap">
<section class="hero surface reveal">
<div class="hero-grid">
<div class="hero-copy">
<div class="kicker" data-i18n="hero.kicker">Applied AI Engineer</div>
<div class="identity-name">Amir Mehdi<br/>Parviz</div>
<div class="identity-role" data-i18n="hero.role">LLM Systems · Document AI · AI Backend</div>
<div class="identity-meta">
<span data-i18n="hero.location">Iran</span>
<span data-i18n="hero.years">3+ years in AI engineering</span>
<span data-i18n="hero.engagement">Part-time / Project-based</span>
</div>
<div class="profile-links">
<a class="profile-link" data-i18n="profile.email" href="https://mail.google.com/mail/?view=cm&amp;fs=1&amp;to=a.m.parviz02@gmail.com" rel="noopener" target="_blank">EMAIL ↗</a>
<a class="profile-link" href="https://github.com/GIGAParviz" rel="noopener" target="_blank">GITHUB ↗</a>
<a class="profile-link" href="https://www.linkedin.com/in/amir-mehdi-parviz/" rel="noopener" target="_blank">LINKEDIN ↗</a>
<a class="profile-link" href="https://huggingface.co/GIGAParviz" rel="noopener" target="_blank">HUGGING FACE ↗</a>
</div>
<h1 data-i18n="hero.title">I build AI systems that survive contact with production.</h1>
<p class="lead" data-i18n="hero.lead">I work across AI models, evaluation, serving and backend integration — turning experiments into usable, maintainable systems.</p>
<div class="actions">
<a class="btn primary" data-i18n="hero.work" href="#projects">Selected work</a>
</div>
</div>
<div class="scanner">
<div class="scanner-head"><span data-i18n="preview.label">PROJECT MEDIA</span><div class="rail" id="mediaRail"></div></div>
<div class="preview-stage" id="previewStage">
<div class="placeholder" id="previewPlaceholder"><strong data-i18n="preview.emptyTitle">Project previews</strong><span data-i18n="preview.emptyText">Images and videos from examples/ appear here automatically.</span></div>
<div class="preview-caption" id="previewCaption"><div class="pc-copy"><span class="pc-label" data-i18n="preview.system">SELECTED SYSTEM</span><b id="previewProject">Selected system</b><p id="previewDescription"></p></div><a data-i18n="preview.view" href="#projects" id="previewProjectLink">VIEW PROJECT →</a></div>
</div>
<div class="preview-status"><span data-i18n="preview.path">examples/</span><span id="previewName">waiting for media…</span><span id="previewCount">0/0</span></div>
</div>
</div>
</section>
<div class="proof-grid reveal">
<div class="metric"><b>3+</b><span data-i18n="proof.years">Years in AI engineering</span></div>
<div class="metric"><b>7</b><span data-i18n="proof.systems">Selected systems</span></div>
<div class="metric"><b data-i18n="proof.self">Self-hosted</b><span data-i18n="proof.deploy">Deployment experience</span></div>
<div class="metric"><b data-i18n="proof.end">End-to-end</b><span data-i18n="proof.scope">Model to backend integration</span></div>
</div>
<section class="surface reveal" id="focus">
<div class="section-head"><div><div class="num" data-i18n="focus.num">01 / ENGINEERING FOCUS</div><h2 data-i18n="focus.title">What I work on</h2></div><p data-i18n="focus.sub">A compact view of the engineering areas I repeatedly work across.</p></div>
<div class="focus-grid">
<div class="focus-item"><div class="focus-no">01</div><h3 data-i18n="focus.llm.title">LLM / VLM Systems</h3><p data-i18n="focus.llm.text">Applied language and vision-language systems built around real application workflows.</p></div>
<div class="focus-item"><div class="focus-no">02</div><h3 data-i18n="focus.doc.title">Document AI</h3><p data-i18n="focus.doc.text">Persian OCR, document understanding and structured information extraction.</p></div>
<div class="focus-item"><div class="focus-no">03</div><h3 data-i18n="focus.serve.title">Model Serving</h3><p data-i18n="focus.serve.text">Local and self-hosted inference, APIs, performance and deployment-oriented workflows.</p></div>
<div class="focus-item"><div class="focus-no">04</div><h3 data-i18n="focus.backend.title">AI Backend</h3><p data-i18n="focus.backend.text">FastAPI services, databases, validation, orchestration and application integration.</p></div>
</div>
</section>
<section class="surface reveal skills-section" id="skills">
<div class="section-head"><div><div class="num" data-i18n="skills.num">02 / SKILLS &amp; STACK</div><h2 data-i18n="skills.title">Tools I use to build</h2></div><p data-i18n="skills.sub">A practical stack across AI models, backend systems, serving and evaluation.</p></div>
<div class="skills-compact">
<div class="skill-row"><span class="skill-cat" data-i18n="skills.ai">AI / ML</span><div class="skill-tags"><span>PyTorch</span><span>Transformers</span><span>PEFT / LoRA</span><span>LangChain</span><span>MCP</span><span>scikit-learn</span></div></div>
<div class="skill-row"><span class="skill-cat" data-i18n="skills.backend">Backend</span><div class="skill-tags"><span>Python</span><span>FastAPI</span><span>PostgreSQL</span><span>SQLAlchemy</span><span>Redis</span><span>Celery</span><span>JWT</span></div></div>
<div class="skill-row"><span class="skill-cat" data-i18n="skills.doc">Document AI / CV</span><div class="skill-tags"><span>OCR</span><span>OpenCV</span><span>YOLO</span><span>VLMs</span><span>Structured Extraction</span></div></div>
<div class="skill-row"><span class="skill-cat" data-i18n="skills.infra">Serving / Infra</span><div class="skill-tags"><span>vLLM</span><span>Docker</span><span>Linux</span><span>CUDA</span><span>Quantization</span><span>REST APIs</span></div></div>
</div>
</section>
<section class="surface reveal" id="projects">
<div class="section-head"><div><div class="num" data-i18n="projects.num">02 / SELECTED SYSTEMS</div><h2 data-i18n="projects.title">Selected systems</h2></div><p data-i18n="projects.sub">Public summaries only. Internal architecture, datasets, prompts, business rules and implementation details are intentionally omitted.</p></div>


<div class="project-grid"><article class="project-row" id="project-ocr">
<span class="proj-no">01</span>
<div class="project-row-main"><span class="project-label" data-i18n="project.featured">FEATURED SYSTEM</span><h3 data-i18n="p1.title"></h3><p data-i18n="p1.desc"></p></div>
<div class="project-row-side"><div><span data-i18n="meta.focus">FOCUS</span><b data-i18n="p1.focus"></b></div><div><span data-i18n="meta.engineering">ENGINEERING</span><b data-i18n="p1.eng"></b></div><div><span data-i18n="meta.stack">STACK</span><b data-i18n="p1.stack"></b></div></div>
<details><summary data-en="VIEW PUBLIC OVERVIEW" data-fa="نمایش نمای کلی عمومی">VIEW PUBLIC OVERVIEW</summary><div class="overview-body"><p class="overview-note" data-en="High-level public view — internal architecture, data, prompts and business logic are intentionally omitted." data-fa="این فقط نمای عمومی سیستم است؛ معماری داخلی، داده‌ها، پرامپت‌ها و منطق کسب‌وکار عمداً منتشر نشده‌اند.">High-level public view — internal architecture, data, prompts and business logic are intentionally omitted.</p><div class="public-diagram"><span class="diagram-node" data-en="Document Input" data-fa="ورودی سند">Document Input</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="AI Processing" data-fa="پردازش هوشمند">AI Processing</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="Validation" data-fa="اعتبارسنجی">Validation</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="Application Output" data-fa="خروجی کاربردی">Application Output</span></div></div></details>
</article><article class="project-row" id="project-ocr-training">
<span class="proj-no">02</span>
<div class="project-row-main"><span class="project-label" data-i18n="project.system">SYSTEM</span><h3 data-i18n="p2.title"></h3><p data-i18n="p2.desc"></p></div>
<div class="project-row-side"><div><span data-i18n="meta.focus">FOCUS</span><b data-i18n="p2.focus"></b></div><div><span data-i18n="meta.engineering">ENGINEERING</span><b data-i18n="p2.eng"></b></div><div><span data-i18n="meta.stack">STACK</span><b data-i18n="p2.stack"></b></div></div>
<details><summary data-en="VIEW PUBLIC OVERVIEW" data-fa="نمایش نمای کلی عمومی">VIEW PUBLIC OVERVIEW</summary><div class="overview-body"><p class="overview-note" data-en="High-level public view — internal architecture, data, prompts and business logic are intentionally omitted." data-fa="این فقط نمای عمومی سیستم است؛ معماری داخلی، داده‌ها، پرامپت‌ها و منطق کسب‌وکار عمداً منتشر نشده‌اند.">High-level public view — internal architecture, data, prompts and business logic are intentionally omitted.</p><div class="public-diagram"><span class="diagram-node" data-en="Prepared Data" data-fa="داده آماده‌شده">Prepared Data</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="Model Adaptation" data-fa="بهبود مدل">Model Adaptation</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="Evaluation" data-fa="ارزیابی">Evaluation</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="Candidate Model" data-fa="مدل منتخب">Candidate Model</span></div></div></details>
</article><article class="project-row" id="project-survey">
<span class="proj-no">03</span>
<div class="project-row-main"><span class="project-label" data-i18n="project.system">SYSTEM</span><h3 data-i18n="p3.title"></h3><p data-i18n="p3.desc"></p></div>
<div class="project-row-side"><div><span data-i18n="meta.focus">FOCUS</span><b data-i18n="p3.focus"></b></div><div><span data-i18n="meta.engineering">ENGINEERING</span><b data-i18n="p3.eng"></b></div><div><span data-i18n="meta.stack">STACK</span><b data-i18n="p3.stack"></b></div></div>
<details><summary data-en="VIEW PUBLIC OVERVIEW" data-fa="نمایش نمای کلی عمومی">VIEW PUBLIC OVERVIEW</summary><div class="overview-body"><p class="overview-note" data-en="High-level public view — internal architecture, data, prompts and business logic are intentionally omitted." data-fa="این فقط نمای عمومی سیستم است؛ معماری داخلی، داده‌ها، پرامپت‌ها و منطق کسب‌وکار عمداً منتشر نشده‌اند.">High-level public view — internal architecture, data, prompts and business logic are intentionally omitted.</p><div class="public-diagram"><span class="diagram-node" data-en="User Workflow" data-fa="جریان کاربر">User Workflow</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="AI Assistance" data-fa="کمک هوش مصنوعی">AI Assistance</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="Structured Data" data-fa="داده ساختاریافته">Structured Data</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="Application Flow" data-fa="جریان نرم‌افزار">Application Flow</span></div></div></details>
</article><article class="project-row" id="project-speech">
<span class="proj-no">04</span>
<div class="project-row-main"><span class="project-label" data-i18n="project.system">SYSTEM</span><h3 data-i18n="p4.title"></h3><p data-i18n="p4.desc"></p></div>
<div class="project-row-side"><div><span data-i18n="meta.focus">FOCUS</span><b data-i18n="p4.focus"></b></div><div><span data-i18n="meta.engineering">ENGINEERING</span><b data-i18n="p4.eng"></b></div><div><span data-i18n="meta.stack">STACK</span><b data-i18n="p4.stack"></b></div></div>
<details><summary data-en="VIEW PUBLIC OVERVIEW" data-fa="نمایش نمای کلی عمومی">VIEW PUBLIC OVERVIEW</summary><div class="overview-body"><p class="overview-note" data-en="High-level public view — internal architecture, data, prompts and business logic are intentionally omitted." data-fa="این فقط نمای عمومی سیستم است؛ معماری داخلی، داده‌ها، پرامپت‌ها و منطق کسب‌وکار عمداً منتشر نشده‌اند.">High-level public view — internal architecture, data, prompts and business logic are intentionally omitted.</p><div class="public-diagram"><span class="diagram-node" data-en="Voice Interface" data-fa="رابط صوتی">Voice Interface</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="AI Processing" data-fa="پردازش هوشمند">AI Processing</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="Response Layer" data-fa="لایه پاسخ">Response Layer</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="User Output" data-fa="خروجی کاربر">User Output</span></div></div></details>
</article><article class="project-row" id="project-dabir">
<span class="proj-no">05</span>
<div class="project-row-main"><span class="project-label" data-i18n="project.system">SYSTEM</span><h3 data-i18n="p5.title"></h3><p data-i18n="p5.desc"></p></div>
<div class="project-row-side"><div><span data-i18n="meta.focus">FOCUS</span><b data-i18n="p5.focus"></b></div><div><span data-i18n="meta.engineering">ENGINEERING</span><b data-i18n="p5.eng"></b></div><div><span data-i18n="meta.stack">STACK</span><b data-i18n="p5.stack"></b></div></div>
<details><summary data-en="VIEW PUBLIC OVERVIEW" data-fa="نمایش نمای کلی عمومی">VIEW PUBLIC OVERVIEW</summary><div class="overview-body"><p class="overview-note" data-en="High-level public view — internal architecture, data, prompts and business logic are intentionally omitted." data-fa="این فقط نمای عمومی سیستم است؛ معماری داخلی، داده‌ها، پرامپت‌ها و منطق کسب‌وکار عمداً منتشر نشده‌اند.">High-level public view — internal architecture, data, prompts and business logic are intentionally omitted.</p><div class="public-diagram"><span class="diagram-node" data-en="Document Input" data-fa="ورودی سند">Document Input</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="AI Workflow" data-fa="گردش کار هوشمند">AI Workflow</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="Validation" data-fa="اعتبارسنجی">Validation</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="Controlled Output" data-fa="خروجی کنترل‌شده">Controlled Output</span></div></div></details>
</article><article class="project-row" id="project-ecg">
<span class="proj-no">06</span>
<div class="project-row-main"><span class="project-label" data-i18n="project.system">SYSTEM</span><h3 data-i18n="p6.title"></h3><p data-i18n="p6.desc"></p></div>
<div class="project-row-side"><div><span data-i18n="meta.focus">FOCUS</span><b data-i18n="p6.focus"></b></div><div><span data-i18n="meta.engineering">ENGINEERING</span><b data-i18n="p6.eng"></b></div><div><span data-i18n="meta.stack">STACK</span><b data-i18n="p6.stack"></b></div></div>
<details><summary data-en="VIEW PUBLIC OVERVIEW" data-fa="نمایش نمای کلی عمومی">VIEW PUBLIC OVERVIEW</summary><div class="overview-body"><p class="overview-note" data-en="High-level public view — internal architecture, data, prompts and business logic are intentionally omitted." data-fa="این فقط نمای عمومی سیستم است؛ معماری داخلی، داده‌ها، پرامپت‌ها و منطق کسب‌وکار عمداً منتشر نشده‌اند.">High-level public view — internal architecture, data, prompts and business logic are intentionally omitted.</p><div class="public-diagram"><span class="diagram-node" data-en="Input" data-fa="ورودی">Input</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="ML Analysis" data-fa="تحلیل یادگیری ماشین">ML Analysis</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="Review" data-fa="بازبینی">Review</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="Structured Output" data-fa="خروجی ساختاریافته">Structured Output</span></div></div></details>
</article><article class="project-row" id="project-engineering">
<span class="proj-no">07</span>
<div class="project-row-main"><span class="project-label" data-i18n="project.engineering">SYSTEM</span><h3 data-i18n="p7.title"></h3><p data-i18n="p7.desc"></p></div>
<div class="project-row-side"><div><span data-i18n="meta.focus">FOCUS</span><b data-i18n="p7.focus"></b></div><div><span data-i18n="meta.engineering">ENGINEERING</span><b data-i18n="p7.eng"></b></div><div><span data-i18n="meta.stack">STACK</span><b data-i18n="p7.stack"></b></div></div>
<details><summary data-en="VIEW PUBLIC OVERVIEW" data-fa="نمایش نمای کلی عمومی">VIEW PUBLIC OVERVIEW</summary><div class="overview-body"><p class="overview-note" data-en="High-level public view — internal architecture, data, prompts and business logic are intentionally omitted." data-fa="این فقط نمای عمومی سیستم است؛ معماری داخلی، داده‌ها، پرامپت‌ها و منطق کسب‌وکار عمداً منتشر نشده‌اند.">High-level public view — internal architecture, data, prompts and business logic are intentionally omitted.</p><div class="public-diagram"><span class="diagram-node" data-en="Application" data-fa="اپلیکیشن">Application</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="Service Layer" data-fa="لایه سرویس">Service Layer</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="AI / Backend Logic" data-fa="منطق AI / بک‌اند">AI / Backend Logic</span><span aria-hidden="true" class="diagram-arrow">→</span><span class="diagram-node" data-en="Deployment" data-fa="استقرار">Deployment</span></div></div></details>
</article></div><div class="privacy-note"><span>◈</span><span><strong data-i18n="projects.privateTitle">Portfolio disclosure policy:</strong> <span data-i18n="projects.privateText">project descriptions are intentionally high-level; sensitive technical and business details are not published.</span></span></div></section>
<section class="surface reveal" id="building">
<div class="section-head"><div><div class="num" data-i18n="building.num">04 / CURRENTLY BUILDING</div><h2 data-i18n="building.title">Work in progress</h2></div><p data-i18n="building.sub">A public-level snapshot of what I am exploring now.</p></div>
<div class="build-card"><div class="proj-no">01</div><div><h3 data-i18n="building.project">Multi-model Project Planning System</h3><p data-i18n="building.desc">An experimental AI system for comparing model-generated implementation approaches before a project moves into execution.</p></div><div class="build-status" data-i18n="building.status">IN DEVELOPMENT</div></div>
</section>
<section class="surface reveal" id="experience">
<div class="section-head"><div><div class="num" data-i18n="experience.num">05 / EXPERIENCE</div><h2 data-i18n="experience.title">Production context</h2></div><p data-i18n="experience.sub">Roles and engineering domains, kept concise.</p></div>
<div class="jobs">
<div class="job-card"><time>2026 — Present</time><h3 data-i18n="job1.title">AI Engineer · Part-time / Project-based</h3><div class="org">Vira RNDlab · Iran</div><p data-i18n="job1.desc">Project-based AI engineering across document AI, LLM/VLM applications, model serving, evaluation and backend integration.</p><div class="job-tags"><span>Document AI</span><span>Model Serving</span><span>Evaluation</span><span>FastAPI</span></div></div>
<div class="job-card"><time>2020 — 2025</time><h3 data-i18n="job2.title">AI Developer &amp; Data Analyst</h3><div class="org">Caitech · Iran</div><p data-i18n="job2.desc">AI product work across NLP, computer vision, document processing, data analysis and application integration.</p><div class="job-tags"><span>LLM / NLP</span><span>Computer Vision</span><span>Data Analysis</span><span>APIs</span></div></div>
</div>
</section>
<section class="surface reveal" id="writing">
<div class="section-head"><div><div class="num" data-i18n="writing.num">05 / WRITING &amp; NOTES</div><h2 data-i18n="writing.title">Engineering ideas I write about</h2></div><p data-i18n="writing.sub">Public notes around AI engineering, reliability and deployment.</p></div>
<div class="writing-list">
<a class="writing-item" href="https://www.linkedin.com/in/amir-mehdi-parviz/" rel="noopener" target="_blank"><span class="proj-no">01</span><h3 data-i18n="w1.title">Reliable AI Systems</h3><p data-i18n="w1.desc">Why production reliability requires more than model quality.</p><span class="arrow">LINKEDIN ↗</span></a>
<a class="writing-item" href="https://www.linkedin.com/in/amir-mehdi-parviz/" rel="noopener" target="_blank"><span class="proj-no">02</span><h3 data-i18n="w2.title">vLLM vs Ollama in Local Model Serving</h3><p data-i18n="w2.desc">Practical observations around local serving and production-oriented inference.</p><span class="arrow">LINKEDIN ↗</span></a>
<a class="writing-item" href="https://www.linkedin.com/in/amir-mehdi-parviz/" rel="noopener" target="_blank"><span class="proj-no">03</span><h3 data-i18n="w3.title">Persian OCR Engineering Notes</h3><p data-i18n="w3.desc">Lessons from building and evaluating Persian OCR systems.</p><span class="arrow">LINKEDIN ↗</span></a>
</div>
</section>
<section class="surface reveal" id="about">
<div class="section-head"><div><div class="num" data-i18n="about.num">07 / ABOUT</div><h2 data-i18n="about.title">AI engineering with a systems mindset</h2></div></div>
<div class="about-grid"><div class="about-card"><p data-i18n="about.text">I work across the boundary between AI models and software systems: evaluation, serving, APIs, backend integration and the engineering required to move from a prototype toward a usable product.</p></div><div class="about-card edu"><div class="label" data-i18n="about.edu">EDUCATION</div><b data-i18n="about.uni">Kermanshah University of Technology</b><span data-i18n="about.degree">Bachelor of Chemical Engineering · 2022 — 2026 · Iran</span></div></div>
</section>
</main>
<section class="contact-band" id="contact">
<div class="wrap contact-band-inner">
<span class="num mono" data-i18n="contact.num">08 / CONTACT</span>
<h2 data-i18n="contact.title">Building an AI system that needs to move beyond the demo?</h2>
<p data-i18n="contact.text">I am interested in AI engineering work around LLM/VLM systems, Document AI, model serving and backend integration.</p>
<div class="contact-actions">
<a class="btn primary big" data-i18n="contact.email" href="https://mail.google.com/mail/?view=cm&amp;fs=1&amp;to=a.m.parviz02@gmail.com" rel="noopener" target="_blank">Email me</a>
<a class="btn big" href="https://www.linkedin.com/in/amir-mehdi-parviz/" rel="noopener" target="_blank">LinkedIn ↗</a>
</div>
</div>
</section>
<footer><div class="wrap footer-row"><div><b style="color:var(--text)">Amir Mehdi Parviz</b><br/><span data-i18n="footer.role">AI Engineer · Iran</span></div><a class="mono footer-email" href="https://mail.google.com/mail/?view=cm&amp;fs=1&amp;to=a.m.parviz02@gmail.com" rel="noopener" target="_blank">a.m.parviz02@gmail.com ↗</a></div></footer>
<div class="sun-end-zone" aria-hidden="true">
  <div class="terminal-sun">
  <div class="sun-haze"></div><div class="sun-body"></div>
  <div class="sun-tech-orbits">
    <div class="orbit-track outer">
      <div class="orbit-item" style="--angle:0deg;--radius:225px"><div class="orbit-badge-wrap"><div class="orbit-badge"><i class="devicon-python-plain"></i><span>Python</span></div></div></div>
      <div class="orbit-item" style="--angle:55deg;--radius:225px"><div class="orbit-badge-wrap"><div class="orbit-badge"><i class="devicon-fastapi-plain"></i><span>FastAPI</span></div></div></div>
      <div class="orbit-item" style="--angle:110deg;--radius:225px"><div class="orbit-badge-wrap"><div class="orbit-badge"><i class="devicon-pytorch-original"></i><span>PyTorch</span></div></div></div>
      <div class="orbit-item" style="--angle:165deg;--radius:225px"><div class="orbit-badge-wrap"><div class="orbit-badge"><i class="devicon-opencv-plain"></i><span>OpenCV</span></div></div></div>
      <div class="orbit-item" style="--angle:220deg;--radius:225px"><div class="orbit-badge-wrap"><div class="orbit-badge"><i class="devicon-postgresql-plain"></i><span>PostgreSQL</span></div></div></div>
      <div class="orbit-item" style="--angle:280deg;--radius:225px"><div class="orbit-badge-wrap"><div class="orbit-badge"><i class="devicon-docker-plain"></i><span>Docker</span></div></div></div>
      <div class="orbit-item" style="--angle:332deg;--radius:225px"><div class="orbit-badge-wrap"><div class="orbit-badge"><i class="devicon-linux-plain"></i><span>Linux</span></div></div></div>
    </div>
    <div class="orbit-track inner">
      <div class="orbit-item" style="--angle:30deg;--radius:172px"><div class="orbit-badge-wrap"><div class="orbit-badge"><i class="devicon-git-plain"></i><span>Git</span></div></div></div>
      <div class="orbit-item" style="--angle:120deg;--radius:172px"><div class="orbit-badge-wrap"><div class="orbit-badge"><i class="devicon-redis-plain"></i><span>Redis</span></div></div></div>
      <div class="orbit-item" style="--angle:210deg;--radius:172px"><div class="orbit-badge-wrap"><div class="orbit-badge"><i class="devicon-sqlalchemy-plain"></i><span>SQLAlchemy</span></div></div></div>
      <div class="orbit-item" style="--angle:300deg;--radius:172px"><div class="orbit-badge-wrap"><div class="orbit-badge"><i class="devicon-vscode-plain"></i><span>AI Tools</span></div></div></div>
    </div>
  </div>
  </div>
</div>
<script>
const I18N={
  en:{
    'nav.focus':'Focus','nav.skills':'Skills','nav.projects':'Systems','nav.building':'Building','nav.experience':'Experience','nav.writing':'Writing','nav.about':'About','nav.email':'EMAIL ↗',
    'hero.kicker':'Applied AI Engineer','hero.role':'LLM Systems · Document AI · AI Backend','hero.location':'Iran','hero.years':'3+ years in AI engineering','hero.engagement':'Part-time / Project-based','profile.email':'EMAIL ↗','hero.title':'I build AI systems that survive contact with production.','hero.lead':'I work across AI models, evaluation, serving and backend integration — turning experiments into usable, maintainable systems.','hero.work':'Selected work','hero.contact':'Get in touch',
    'preview.label':'PROJECT MEDIA','preview.emptyTitle':'Project previews','preview.emptyText':'Selected project media is loaded directly for faster previews.','preview.system':'SELECTED SYSTEM','preview.view':'VIEW PROJECT →','preview.path':'examples/','preview.wait':'waiting for media…','preview.add':'Add media to examples/','preview.github':'On GitHub Pages, keep the repository public so the page can discover images and videos automatically.','preview.selected':'Selected system',
    'proof.years':'Years in AI engineering','proof.systems':'Selected systems','proof.self':'Self-hosted','proof.deploy':'Deployment experience','proof.end':'End-to-end','proof.scope':'Model to backend integration',
    'focus.num':'01 / ENGINEERING FOCUS','focus.title':'What I work on','focus.sub':'A compact view of the engineering areas I repeatedly work across.','focus.llm.title':'LLM / VLM Systems','focus.llm.text':'Applied language and vision-language systems built around real application workflows.','focus.doc.title':'Document AI','focus.doc.text':'Persian OCR, document understanding and structured information extraction.','focus.serve.title':'Model Serving','focus.serve.text':'Local and self-hosted inference, APIs, performance and deployment-oriented workflows.','focus.backend.title':'AI Backend','focus.backend.text':'FastAPI services, databases, validation, orchestration and application integration.',
    'skills.num':'02 / SKILLS & STACK','skills.title':'Tools I use to build','skills.sub':'A practical stack across AI models, backend systems, serving and evaluation.','skills.ai':'AI / ML','skills.backend':'Backend','skills.doc':'Document AI / CV','skills.infra':'Serving / Infra','skills.eval':'Evaluation','skills.eng':'Engineering','projects.num':'03 / SELECTED SYSTEMS','projects.title':'Selected systems','projects.sub':'Public summaries only. Internal architecture, datasets, prompts, business rules and implementation details are intentionally omitted.','project.featured':'FEATURED SYSTEM','project.system':'SYSTEM','project.engineering':'ENGINEERING PROJECTS','meta.focus':'FOCUS','meta.engineering':'ENGINEERING','meta.stack':'STACK','projects.privateTitle':'Portfolio disclosure policy:','projects.privateText':'project descriptions are intentionally high-level; sensitive technical and business details are not published.',
    'p1.title':'Persian OCR & Document Intelligence Platform','p1.desc':'Persian document intelligence system focused on dependable text extraction and structured outputs for real-world workflows.','p1.focus':'Document AI','p1.eng':'Reliability + integration','p1.stack':'Python · FastAPI · OpenCV · GPU Inference',
    'p2.title':'Persian OCR Model Development & Evaluation','p2.desc':'Model adaptation and evaluation work for Persian OCR using curated data and repeatable validation workflows.','p2.focus':'OCR quality','p2.eng':'Training + evaluation','p2.stack':'PyTorch · Transformers · PEFT',
    'p3.title':'AI-assisted Survey & Feedback System','p3.desc':'Application-oriented survey system with AI-assisted processing and structured response workflows.','p3.focus':'AI applications','p3.eng':'Workflow integration','p3.stack':'Python · Application AI',
    'p4.title':'Speech-enabled AI Response System','p4.desc':'Voice-based AI interaction system combining speech interfaces with language-model processing.','p4.focus':'Voice AI','p4.eng':'AI orchestration','p4.stack':'Python · Speech · LLM',
    'p5.title':'AI Document Workflow / DABIRKHANEH','p5.desc':'Persian document-workflow application using AI-assisted processing within a controlled software workflow.','p5.focus':'Document workflows','p5.eng':'Backend + AI integration','p5.stack':'FastAPI · PostgreSQL · APIs',
    'p6.title':'ECG Analysis & Classification Pipeline','p6.desc':'Computer-vision and machine-learning pipeline for ECG analysis with reviewable structured outputs.','p6.focus':'Computer vision','p6.eng':'Detection + classification','p6.stack':'OpenCV · ML · Python',
    'p7.title':'Additional Engineering Projects','p7.desc':'Backend, product and AI-integration work spanning application services and deployment-oriented engineering.','p7.focus':'Product engineering','p7.eng':'Backend + delivery','p7.stack':'Docker · C#/.NET · APIs',
    'building.num':'04 / CURRENTLY BUILDING','building.title':'Work in progress','building.sub':'A public-level snapshot of what I am exploring now.','building.project':'Multi-model Project Planning System','building.desc':'An experimental AI system for comparing model-generated implementation approaches before a project moves into execution.','building.status':'IN DEVELOPMENT',
    'experience.num':'05 / EXPERIENCE','experience.title':'Production context','experience.sub':'Roles and engineering domains, kept concise.','job1.title':'AI Engineer · Part-time / Project-based','job1.desc':'Project-based AI engineering across document AI, LLM/VLM applications, model serving, evaluation and backend integration.','job2.title':'AI Developer & Data Analyst','job2.desc':'AI product work across NLP, computer vision, document processing, data analysis and application integration.',
    'writing.num':'06 / WRITING & NOTES','writing.title':'Engineering ideas I write about','writing.sub':'Public notes around AI engineering, reliability and deployment.','w1.title':'Reliable AI Systems','w1.desc':'Why production reliability requires more than model quality.','w2.title':'vLLM vs Ollama in Local Model Serving','w2.desc':'Practical observations around local serving and production-oriented inference.','w3.title':'Persian OCR Engineering Notes','w3.desc':'Lessons from building and evaluating Persian OCR systems.',
    'about.num':'07 / ABOUT','about.title':'AI engineering with a systems mindset','about.text':'I work across the boundary between AI models and software systems: evaluation, serving, APIs, backend integration and the engineering required to move from a prototype toward a usable product.','about.edu':'EDUCATION','about.uni':'Kermanshah University of Technology','about.degree':'Bachelor of Chemical Engineering · 2022 — 2026 · Iran',
    'contact.num':'08 / CONTACT','contact.title':'Building an AI system that needs to move beyond the demo?','contact.text':'I am interested in AI engineering work around LLM/VLM systems, Document AI, model serving and backend integration.','contact.email':'Email me','footer.role':'AI Engineer · Iran'
  },
  fa:{
    'nav.focus':'تمرکز تخصصی','nav.projects':'پروژه‌ها','nav.building':'در حال ساخت','nav.experience':'تجربه','nav.writing':'نوشته‌ها','nav.about':'درباره من','nav.email':'ایمیل ↗',
    'hero.kicker':'مهندس هوش مصنوعی کاربردی','hero.role':'سیستم‌های LLM · هوش اسناد · بک‌اند هوش مصنوعی','hero.location':'ایران','hero.years':'بیش از ۳ سال تجربه در مهندسی هوش مصنوعی','hero.engagement':'پاره‌وقت / پروژه‌ای','profile.email':'ایمیل ↗','hero.title':'سیستم‌های هوش مصنوعی را برای استفاده واقعی و فراتر از دمو می‌سازم.','hero.lead':'در مرز بین مدل‌های هوش مصنوعی، ارزیابی، سروینگ و بک‌اند کار می‌کنم تا آزمایش‌ها به سیستم‌های قابل‌استفاده و قابل‌نگهداری تبدیل شوند.','hero.work':'مشاهده پروژه‌ها','hero.contact':'ارتباط با من',
    'preview.label':'پیش‌نمایش پروژه‌ها','preview.emptyTitle':'پیش‌نمایش پروژه‌ها','preview.emptyText':'رسانه‌های منتخب پروژه‌ها به‌صورت مستقیم بارگذاری می‌شوند تا پیش‌نمایش سریع‌تر باشد.','preview.system':'پروژه منتخب','preview.view':'مشاهده پروژه ←','preview.path':'examples/','preview.wait':'در انتظار فایل…','preview.add':'فایل‌های پروژه را داخل examples/ قرار دهید','preview.github':'در GitHub Pages مخزن را Public نگه دارید تا تصاویر و ویدئوها به‌صورت خودکار شناسایی شوند.','preview.selected':'پروژه منتخب',
    'proof.years':'سال تجربه در مهندسی AI','proof.systems':'سیستم منتخب','proof.self':'Self-hosted','proof.deploy':'تجربه استقرار مدل','proof.end':'End-to-end','proof.scope':'از مدل تا یکپارچه‌سازی بک‌اند',
    'focus.num':'۰۱ / تمرکز تخصصی','focus.title':'حوزه‌هایی که روی آن‌ها کار می‌کنم','focus.sub':'نمایی کوتاه از حوزه‌های مهندسی که به‌طور مداوم در پروژه‌ها با آن‌ها درگیر هستم.','focus.llm.title':'سیستم‌های LLM / VLM','focus.llm.text':'سیستم‌های زبانی و چندوجهی برای سناریوهای واقعی نرم‌افزاری.','focus.doc.title':'هوش اسناد','focus.doc.text':'OCR فارسی، درک سند و استخراج ساختاریافته اطلاعات.','focus.serve.title':'سروینگ مدل','focus.serve.text':'اجرای محلی و Self-hosted، APIها، کارایی و فرایندهای استقرار.','focus.backend.title':'بک‌اند هوش مصنوعی','focus.backend.text':'سرویس‌های FastAPI، دیتابیس، اعتبارسنجی، orchestration و یکپارچه‌سازی با نرم‌افزار.',
    'skills.num':'۰۲ / مهارت‌ها و ابزارها','skills.title':'ابزارهایی که با آن‌ها می‌سازم','skills.sub':'پشته فنی کاربردی برای مدل‌های AI، بک‌اند، سروینگ و ارزیابی.','skills.ai':'هوش مصنوعی / یادگیری ماشین','skills.backend':'بک‌اند','skills.doc':'هوش اسناد / بینایی ماشین','skills.infra':'سروینگ / زیرساخت','skills.eval':'ارزیابی','skills.eng':'مهندسی نرم‌افزار','projects.num':'۰۳ / پروژه‌های منتخب','projects.title':'سیستم‌های منتخب','projects.sub':'توضیحات این بخش فقط در سطح عمومی هستند. معماری داخلی، دیتاست‌ها، پرامپت‌ها، قوانین کسب‌وکار و جزئیات پیاده‌سازی عمداً منتشر نشده‌اند.','project.featured':'پروژه منتخب','project.system':'سیستم','project.engineering':'پروژه‌های مهندسی','meta.focus':'تمرکز','meta.engineering':'مهندسی','meta.stack':'فناوری‌ها','projects.privateTitle':'سیاست انتشار نمونه‌کار:','projects.privateText':'توضیحات پروژه‌ها عمداً در سطح کلی نگه داشته شده‌اند و جزئیات فنی یا تجاری حساس منتشر نمی‌شوند.',
    'p1.title':'پلتفرم OCR فارسی و هوش اسناد','p1.desc':'سیستم هوش اسناد فارسی با تمرکز بر استخراج قابل‌اعتماد متن و خروجی‌های ساختاریافته برای جریان‌های کاری واقعی.','p1.focus':'هوش اسناد','p1.eng':'قابلیت اطمینان + یکپارچه‌سازی','p1.stack':'Python · FastAPI · OpenCV · GPU Inference',
    'p2.title':'توسعه و ارزیابی مدل OCR فارسی','p2.desc':'کار روی بهبود و ارزیابی OCR فارسی با داده‌های آماده‌سازی‌شده و فرایندهای اعتبارسنجی قابل‌تکرار.','p2.focus':'کیفیت OCR','p2.eng':'آموزش + ارزیابی','p2.stack':'PyTorch · Transformers · PEFT',
    'p3.title':'سامانه هوشمند نظرسنجی و بازخورد','p3.desc':'سامانه نظرسنجی نرم‌افزارمحور با پردازش مبتنی بر هوش مصنوعی و جریان ساختاریافته پاسخ‌ها.','p3.focus':'اپلیکیشن‌های AI','p3.eng':'یکپارچه‌سازی جریان کار','p3.stack':'Python · Application AI',
    'p4.title':'سامانه پاسخ‌گویی صوتی هوشمند','p4.desc':'سیستم تعامل صوتی مبتنی بر هوش مصنوعی که رابط‌های گفتاری را با پردازش مدل زبانی ترکیب می‌کند.','p4.focus':'هوش مصنوعی صوتی','p4.eng':'Orchestration هوش مصنوعی','p4.stack':'Python · Speech · LLM',
    'p5.title':'گردش کار اسناد هوشمند / دبیرخانه','p5.desc':'اپلیکیشن گردش کار اسناد فارسی با پردازش هوشمند در یک جریان نرم‌افزاری کنترل‌شده.','p5.focus':'گردش کار اسناد','p5.eng':'بک‌اند + یکپارچه‌سازی AI','p5.stack':'FastAPI · PostgreSQL · APIs',
    'p6.title':'پایپ‌لاین تحلیل و طبقه‌بندی ECG','p6.desc':'پایپ‌لاین بینایی ماشین و یادگیری ماشین برای تحلیل ECG با خروجی‌های ساختاریافته و قابل بررسی.','p6.focus':'بینایی ماشین','p6.eng':'تشخیص + طبقه‌بندی','p6.stack':'OpenCV · ML · Python',
    'p7.title':'سایر پروژه‌های مهندسی','p7.desc':'کارهای بک‌اند، محصول و یکپارچه‌سازی هوش مصنوعی در سرویس‌های نرم‌افزاری و مهندسی استقرار.','p7.focus':'مهندسی محصول','p7.eng':'بک‌اند + تحویل نرم‌افزار','p7.stack':'Docker · C#/.NET · APIs',
    'building.num':'۰۴ / در حال ساخت','building.title':'در حال توسعه','building.sub':'نمایی عمومی و کوتاه از چیزی که اکنون در حال بررسی و ساخت آن هستم.','building.project':'سامانه برنامه‌ریزی پروژه با چند مدل','building.desc':'یک سیستم آزمایشی هوش مصنوعی برای مقایسه رویکردهای پیشنهادی مدل‌ها پیش از ورود پروژه به مرحله اجرا.','building.status':'در حال توسعه',
    'experience.num':'۰۵ / تجربه','experience.title':'تجربه در پروژه‌های واقعی','experience.sub':'نقش‌ها و حوزه‌های مهندسی، به‌صورت خلاصه.','job1.title':'مهندس هوش مصنوعی · پاره‌وقت / پروژه‌ای','job1.desc':'مهندسی پروژه‌ای هوش مصنوعی در حوزه هوش اسناد، LLM/VLM، سروینگ مدل، ارزیابی و یکپارچه‌سازی بک‌اند.','job2.title':'توسعه‌دهنده هوش مصنوعی و تحلیلگر داده','job2.desc':'توسعه محصولات هوش مصنوعی در NLP، بینایی ماشین، پردازش اسناد، تحلیل داده و یکپارچه‌سازی نرم‌افزار.',
    'writing.num':'۰۵ / نوشته‌ها','writing.title':'موضوعاتی که درباره مهندسی AI می‌نویسم','writing.sub':'یادداشت‌های عمومی درباره مهندسی هوش مصنوعی، قابلیت اطمینان و استقرار.','w1.title':'سیستم‌های هوش مصنوعی قابل‌اعتماد','w1.desc':'چرا برای محصول واقعی، کیفیت مدل به‌تنهایی کافی نیست.','w2.title':'vLLM در برابر Ollama برای سروینگ محلی','w2.desc':'مشاهدات عملی درباره سروینگ محلی و inference با نگاه production.','w3.title':'یادداشت‌های مهندسی OCR فارسی','w3.desc':'درس‌هایی از ساخت و ارزیابی سیستم‌های OCR فارسی.',
    'about.num':'۰۷ / درباره من','about.title':'مهندسی هوش مصنوعی با نگاه سیستمی','about.text':'در مرز بین مدل‌های هوش مصنوعی و سیستم‌های نرم‌افزاری کار می‌کنم: ارزیابی، سروینگ، APIها، یکپارچه‌سازی بک‌اند و مهندسی لازم برای عبور از نمونه اولیه به محصول قابل‌استفاده.','about.edu':'تحصیلات','about.uni':'دانشگاه صنعتی کرمانشاه','about.degree':'کارشناسی مهندسی شیمی · ۲۰۲۲ — ۲۰۲۶ · ایران',
    'contact.num':'۰۸ / ارتباط','contact.title':'سیستم هوش مصنوعی شما باید از مرحله دمو عبور کند؟','contact.text':'به پروژه‌های مهندسی AI در حوزه LLM/VLM، هوش اسناد، سروینگ مدل و یکپارچه‌سازی بک‌اند علاقه‌مندم.','contact.email':'ارسال ایمیل','footer.role':'مهندس هوش مصنوعی · ایران'
  }
};
let currentLang='en';
function t(key){return I18N[currentLang]?.[key]??I18N.en[key]??key}
function applyLanguage(lang){
  currentLang=lang==='fa'?'fa':'en';
  try{localStorage.setItem('portfolioLang',currentLang)}catch(e){}
  document.documentElement.lang=currentLang;
  document.documentElement.dir=currentLang==='fa'?'rtl':'ltr';
  document.querySelectorAll('[data-i18n]').forEach(el=>{const key=el.dataset.i18n;if(I18N[currentLang][key]!=null)el.textContent=I18N[currentLang][key]});
  document.querySelectorAll('[data-en][data-fa]').forEach(el=>{el.textContent=currentLang==='fa'?el.dataset.fa:el.dataset.en});
  const toggle=document.getElementById('langToggle');
  toggle.textContent=currentLang==='fa'?'EN':'FA';
  toggle.setAttribute('aria-label',currentLang==='fa'?'Switch to English':'تغییر زبان به فارسی');
  document.title=currentLang==='fa'?'امیرمهدی پرویز — مهندس هوش مصنوعی':'Amir Mehdi Parviz — AI Engineer';
  if(items.length && items[idx]) renderPreviewCopy(items[idx]);
  if(pname && !items.length) pname.textContent=t('preview.wait');
}
document.getElementById('langToggle').addEventListener('click',()=>applyLanguage(currentLang==='en'?'fa':'en'));

const DURATION=5200;

// Explicit media manifest: no directory listing and no GitHub API request.
// Relative URLs are served directly by GitHub Pages/CDN when deployed from this repo.
const MEDIA_MANIFEST=[
  {
    name:'Speed-and-Distance-Estimator.mp4',
    src:'examples/Speed-and-Distance-Estimator.mp4',
    kind:'video',
    href:'#project-engineering',
    titleEn:'Vehicle Speed & Distance Estimator',
    titleFa:'تخمین سرعت و فاصله خودروها',
    descEn:'Vehicle detection with speed and relative-distance estimation.',
    descFa:'پروژه تشخیص خودروها و تخمین سرعت و فاصله نسبی آن‌ها.'
  },
  {
    name:'exmaple_ide.png',
    src:'examples/exmaple_ide.png',
    kind:'image',
    href:'#project-engineering',
    titleEn:'AI-Assisted IDE',
    titleFa:'IDE هوشمند',
    descEn:'A custom IDE that can use local AI models such as Ollama to assist with coding.',
    descFa:'یک IDE شخصی‌سازی‌شده که برای کمک در کدنویسی می‌تواند از مدل‌های محلی مانند Ollama استفاده کند.'
  },
  {
    name:'traffic.mp4',
    src:'examples/traffic.mp4',
    kind:'video',
    href:'#project-engineering',
    titleEn:'Traffic Flow Tracking',
    titleFa:'پایش جریان ترافیک',
    descEn:'Detects vehicles at a four-way intersection, defines entry and exit zones, and records each vehicle’s movement through the junction.',
    descFa:'سامانه‌ای برای تشخیص خودروها در چهارراه، تعریف ورودی و خروجی برای هر مسیر و ثبت حرکت هر خودرو در تقاطع.'
  },
  {
    name:'ocr_demo.mp4',
    src:'examples/ocr_demo.mp4',
    kind:'video',
    href:'#project-ocr',
    titleEn:'Persian OCR System',
    titleFa:'سامانه OCR فارسی',
    descEn:'A public demo of my Persian OCR and Document AI project.',
    descFa:'دمویی عمومی از پروژه OCR فارسی و Document AI خودم.'
  }
].map(item=>({...item,src:new URL(item.src,location.href).href}));

let items=MEDIA_MANIFEST,idx=0,timer=null,current=null,showSeq=0;
const preparedMedia=new Map();
const stage=document.getElementById('previewStage');
const pname=document.getElementById('previewName');
const pcount=document.getElementById('previewCount');
const placeholder=document.getElementById('previewPlaceholder');
const rail=document.getElementById('mediaRail');
const previewCaption=document.getElementById('previewCaption');
const previewProject=document.getElementById('previewProject');
const previewDescription=document.getElementById('previewDescription');
const previewProjectLink=document.getElementById('previewProjectLink');

function renderPreviewCopy(item){
  if(!item)return;
  previewProject.textContent=currentLang==='fa'?item.titleFa:item.titleEn;
  previewDescription.textContent=currentLang==='fa'?item.descFa:item.descEn;
  previewProjectLink.href=item.href||'#projects';
}

function createMedia(item){
  const isVideo=item.kind==='video';
  const el=document.createElement(isVideo?'video':'img');
  el.className='preview-media';
  if(isVideo){
    el.muted=true;
    el.autoplay=true;
    el.loop=true;
    el.playsInline=true;
    el.preload='metadata';
  }else{
    el.alt=currentLang==='fa'?item.titleFa:item.titleEn;
    el.decoding='async';
    el.loading='eager';
  }
  el.src=item.src;
  return el;
}

function prepareMedia(i){
  i=(i+items.length)%items.length;
  if(preparedMedia.has(i))return preparedMedia.get(i);
  const item=items[i],el=createMedia(item);
  const promise=new Promise(resolve=>{
    if(item.kind==='video'){
      if(el.readyState>=2)return resolve(el);
      const done=()=>{cleanup();resolve(el)};
      const cleanup=()=>{el.removeEventListener('loadeddata',done);el.removeEventListener('canplay',done)};
      el.addEventListener('loadeddata',done,{once:true});
      el.addEventListener('canplay',done,{once:true});
      // Do not block the slideshow indefinitely on a slow connection.
      setTimeout(()=>{cleanup();resolve(el)},2600);
      el.load();
    }else{
      if(el.complete)return resolve(el);
      const done=()=>resolve(el);
      el.addEventListener('load',done,{once:true});
      el.addEventListener('error',done,{once:true});
    }
  });
  preparedMedia.set(i,promise);
  return promise;
}

function warmNext(i){
  // Only one item ahead is proactively loaded, avoiding an initial download of every video.
  const next=(i+1)%items.length;
  prepareMedia(next).catch(()=>{});
}

function setRail(){
  if(!rail)return;
  rail.innerHTML='';
  items.forEach((it,i)=>{
    const b=document.createElement('button');
    b.type='button';
    b.className='rail-dot';
    b.title=currentLang==='fa'?it.titleFa:it.titleEn;
    b.setAttribute('aria-label',(currentLang==='fa'?'نمایش ':'Show ')+(currentLang==='fa'?it.titleFa:it.titleEn));
    if(i===idx)b.classList.add('active');
    b.addEventListener('click',()=>show(i));
    rail.appendChild(b);
  });
}

async function show(i){
  if(!items.length)return;
  const seq=++showSeq;
  idx=(i+items.length)%items.length;
  const it=items[idx];
  const next=await prepareMedia(idx);
  if(seq!==showSeq)return;

  if(next.parentNode!==stage)stage.appendChild(next);
  next.classList.remove('visible');
  requestAnimationFrame(()=>requestAnimationFrame(()=>next.classList.add('visible')));

  const prev=current;
  current=next;
  pname.textContent=it.name;
  pcount.textContent=`${idx+1}/${items.length}`;
  renderPreviewCopy(it);
  previewCaption.classList.add('show');

  if(next.tagName==='VIDEO')next.play().catch(()=>{});
  if(prev&&prev!==next){
    prev.classList.remove('visible');
    if(prev.tagName==='VIDEO')prev.pause();
    setTimeout(()=>{if(prev!==current&&prev.parentNode===stage)prev.remove()},750);
  }

  setRail();
  warmNext(idx);
  clearTimeout(timer);
  timer=setTimeout(()=>show(idx+1),DURATION);
}

placeholder.hidden=true;
show(0);
const rev=document.querySelectorAll('.reveal');if('IntersectionObserver'in window){const io=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting){e.target.classList.add('in');io.unobserve(e.target)}}),{threshold:.1});rev.forEach(e=>io.observe(e))}else rev.forEach(e=>e.classList.add('in'));
let initialLang='en';try{initialLang=localStorage.getItem('portfolioLang')||'en'}catch(e){}applyLanguage(initialLang);


// Ambient stars: very faint and static so they remain texture, not decoration.
const starField=document.getElementById('starField');
const starCtx=starField?.getContext('2d');
let starPoints=[];
function seedStars(){
  if(!starField||!starCtx)return;
  const dpr=Math.min(window.devicePixelRatio||1,2);
  const w=window.innerWidth,h=window.innerHeight;
  starField.width=Math.floor(w*dpr);starField.height=Math.floor(h*dpr);
  starField.style.width=w+'px';starField.style.height=h+'px';
  starCtx.setTransform(dpr,0,0,dpr,0,0);
  const count=Math.max(58,Math.min(145,Math.floor((w*h)/9200)));
  // Stable pseudo-random layout on resize: no distracting twinkle animation.
  let seed=72831;
  const rand=()=>{seed=(seed*1664525+1013904223)>>>0;return seed/4294967296};
  starPoints=Array.from({length:count},()=>({
    x:rand()*w,y:rand()*h,r:.35+rand()*.9,a:.06+rand()*.14
  }));
  starCtx.clearRect(0,0,w,h);
  starPoints.forEach(st=>{
    starCtx.beginPath();starCtx.arc(st.x,st.y,st.r,0,Math.PI*2);
    starCtx.fillStyle=`rgba(237,243,247,${st.a})`;starCtx.fill();
  });
}
seedStars();
let starResizeTimer;
window.addEventListener('resize',()=>{clearTimeout(starResizeTimer);starResizeTimer=setTimeout(seedStars,120)},{passive:true});

// Scroll-following orbital highlight. The path uses gentle, vertically monotonic curves
// so the bright segment stays aligned with the reader as the page scrolls.
const orbitGlow=document.getElementById('orbitGlow');
const orbitCore=document.getElementById('orbitCore');
let orbitTicking=false;
function updateOrbit(){
  orbitTicking=false;
  if(!orbitGlow||!orbitCore)return;
  const root=document.documentElement;
  const max=Math.max(1,root.scrollHeight-window.innerHeight);
  const progress=Math.min(1,Math.max(0,window.scrollY/max));
  // pathLength=1000 and dash length=115. A non-repeating gap keeps one bright
  // segment on the path; moving it by 908 units takes it from start to finish.
  const offset=-(progress*908);
  orbitGlow.style.strokeDashoffset=String(offset);
  orbitCore.style.strokeDashoffset=String(offset);
}
function requestOrbitUpdate(){
  if(orbitTicking)return;
  orbitTicking=true;
  requestAnimationFrame(updateOrbit);
}
updateOrbit();
window.addEventListener('scroll',requestOrbitUpdate,{passive:true});
window.addEventListener('resize',requestOrbitUpdate,{passive:true});

</script>
</body>
</html>
