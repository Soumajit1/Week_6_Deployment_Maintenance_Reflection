remne
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Soumajit Chakraborty — Full-Stack Developer</title>
<meta name="description" content="Portfolio of Soumajit Chakraborty, Computer Science & Engineering student and aspiring full-stack developer.">
<link rel="preconnect" href=}
#menu.o{clip-path:circle(150% at calc(100% - 40px) 34px);visibility:visible}
#menu a{font:600 clamp(2.2rem,10vw,3.4rem) var(--d);letter-spacing:-.03em}
/* buttons */
.btn{display:inline-flex;align-items:center;gap:12px;padding:15px 26px;border-radius:999px;font:500 .95rem var(--d);border:1px solid var(--line);position:relative;overflow:hidden;cursor:pointer;background:none;color:var(--tx);transition:border-color .4s}
.btn::before{content:"";position:absolute;inset:0;background:var(--tx);transform:translateY(101%);transition:transform .5s cubic-bezier(.2,.8,.2,1)}
.btn>*{position:relative;transition:color .4s}
.btn:hover::before{transform:none}.btn:hover{border-color:var(--tx)}.btn:hover>*{color:#000}
.btn .ar{transition:transform .4s}.btn:hover .ar{transform:translateX(5px)}
.btn.p{background:var(--ac);border-color:var(--ac);color:#0b0715}.btn.p>*{color:#0b0715}
/* hero */
#home{min-height:100svh;display:flex;padding:0}
.hw{display:flex;flex-direction:column;justify-content:space-between;width:100%;padding-top:110px;padding-bottom:56px}
.kick{font:500 1rem var(--d);color:var(--mut);max-width:26ch}
.hname{font:800 clamp(2.6rem,9.4vw,9.6rem)/.86 var(--d);letter-spacing:-.05em;margin-top:30px}
.hname .ln{display:block;overflow:hidden;padding-bottom:.07em}
.hname .ch{display:inline-block;will-change:transform}
.role{font:500 clamp(1.05rem,1.8vw,1.5rem) var(--d);margin:28px 0 0}
.hero-row{display:flex;gap:30px;justify-content<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Soumajit Chakraborty — Full-Stack Developer</title>
<meta name="description" content="Portfolio of Soumajit Chakraborty, Computer Science & Engineering student and aspiring full-stack developer.">
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,400;12..96,600;12..96,800&family=Instrument+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{--bg:#08090b;--bg2:#101116;--line:rgba(255,255,255,.1);--tx:#ecedf0;--mut:#868b99;--ac:#a78bff;--d:'Bricolage Grotesque',system-ui,sans-serif;--b:'Instrument Sans',system-ui,sans-serif;--rail:76px}
*{box-sizing:border-box;margin:0}
body{background:var(--bg);color:var(--tx);font:400 17px/1.65 var(--b);overflow-x:hidden}
body::after{content:"";position:fixed;inset:0;pointer-events:none;z-index:95;opacity:.045;background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='140' height='140'%3E%3Cfilter id='n'%3E%3CfeTurbulence baseFrequency='.9'/%3E%3C/filter%3E%3Crect width='140' height='140' filter='url(%23n)'/%3E%3C/svg%3E")}
a{color:inherit;text-decoration:none}
:focus-visible{outline:2px solid var(--ac);outline-offset:4px;border-radius:4px}
#gl{position:fixed;inset:0;z-index:0}
.hero-ph{display:none;position:absolute;right:6%;top:12%;width:min(42vw,420px);border-radius:6px;opacity:.85}
main,footer{position:relative;z-index:2;padding-left:var(--rail)}
.wrap{max-width:1180px;margin:0 auto;padding:0 clamp(20px,5vw,56px)}
section{padding:clamp(90px,13vw,170px) 0;position:relative}
h2{font:600 clamp(2.4rem,6vw,5rem)/1 var(--d);letter-spacing:-.04em;max-width:15ch}
.lbl{font:500 .85rem var(--d);color:var(--ac);margin-bottom:26px}
.mut{color:var(--mut)}
/* rail */
.rail{position:fixed;left:0;top:0;bottom:0;width:var(--rail);z-index:80;display:flex;flex-direction:column;align-items:center;justify-content:space-between;padding:24px 0;border-right:1px solid var(--line);background:rgba(8,9,11,.4);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px)}
.logo{font:800 1.1rem var(--d);letter-spacing:-.04em}
.dots{display:flex;flex-direction:column;gap:4px}
.dots a{position:relative;width:44px;height:28px;display:grid;place-items:center}
.dots i{width:6px;height:6px;border-radius:50%;background:rgba(255,255,255,.25);transition:.4s}
.dots a.on i{background:var(--ac);transform:scale(1.7);box-shadow:0 0 12px var(--ac)}
.dots span{position:absolute;left:54px;white-space:nowrap;font:500 .78rem var(--d);padding:6px 12px;border-radius:6px;background:rgba(22,24,30,.95);border:1px solid var(--line);opacity:0;transform:translateX(-6px);transition:.3s;pointer-events:none}
.dots a:hover span,.dots a:focus-visible span{opacity:1;transform:none}
.rp{width:1px;height:70px;background:var(--line);position:relative;overflow:hidden}
#prog{position:absolute;inset:0;background:var(--ac);transform-origin:top;transform:scaleY(0)}
.top{display:none;position:fixed;top:0;left:0;right:0;z-index:80;padding:12px 18px;align-items:center;justify-content:space-between;transition:background .4s,backdrop-filter .4s}
.top.s{background:rgba(8,9,11,.65);backdrop-filter:blur(16px);-webkit-backdrop-filter:blur(16px);border-bottom:1px solid var(--line)}
#burger{width:44px;height:44px;border-radius:50%;background:none;border:1px solid var(--line);cursor:pointer;position:relative}
#burger i{position:absolute;left:13px;width:16px;height:1.5px;background:var(--tx);transition:transform .35s,top .35s}
#burger i:nth-child(1){top:17px}#burger i:nth-child(2){top:25px}
#burger[aria-expanded=true] i:nth-child(1){top:21px;transform:rotate(45deg)}
#burger[aria-expanded=true] i:nth-child(2){top:21px;transform:rotate(-45deg)}
#menu{position:fixed;inset:0;z-index:70;background:rgba(8,9,11,.97);display:flex;flex-direction:column;justify-content:center;padding:0 8vw;gap:4px;clip-path:circle(0 at calc(100% - 40px) 34px);transition:clip-path .7s cubic-bezier(.7,0,.2,1);visibility:hidden}
#menu.o{clip-path:circle(150% at calc(100% - 40px) 34px);visibility:visible}
#menu a{font:600 clamp(2.2rem,10vw,3.4rem) var(--d);letter-spacing:-.03em}
/* buttons */
.btn{display:inline-flex;align-items:center;gap:12px;padding:15px 26px;border-radius:999px;font:500 .95rem var(--d);border:1px solid var(--line);position:relative;overflow:hidden;cursor:pointer;background:none;color:var(--tx);transition:border-color .4s}
.btn::before{content:"";position:absolute;inset:0;background:var(--tx);transform:translateY(101%);transition:transform .5s cubic-bezier(.2,.8,.2,1)}
.btn>*{position:relative;transition:color .4s}
.btn:hover::before{transform:none}.btn:hover{border-color:var(--tx)}.btn:hover>*{color:#000}
.btn .ar{transition:transform .4s}.btn:hover .ar{transform:translateX(5px)}
.btn.p{background:var(--ac);border-color:var(--ac);color:#0b0715}.btn.p>*{color:#0b0715}
/* hero */
#home{min-height:100svh;display:flex;padding:0}
.hw{display:flex;flex-direction:column;justify-content:space-between;width:100%;padding-top:110px;padding-bottom:56px}
.kick{font:500 1rem var(--d);color:var(--mut);max-width:26ch}
.hname{font:800 clamp(2.6rem,9.4vw,9.6rem)/.86 var(--d);letter-spacing:-.05em;margin-top:30px}
.hname .ln{display:block;overflow:hidden;padding-bottom:.07em}
.hname .ch{display:inline-block;will-change:transform}
.role{font:500 clamp(1.05rem,1.8vw,1.5rem) var(--d);margin:28px 0 0}
.hero-row{display:flex;gap:30px;justify-content:space-between;align-items:flex-end;flex-wrap:wrap;margin-top:30px}
.intro{max-width:32ch}
.ctas{display:flex;gap:10px;flex-wrap:wrap}
.scroll{position:absolute;top:110px;right:clamp(20px,4vw,48px);font:500 .75rem var(--d);color:var(--mut);writing-mode:vertical-rl;display:flex;gap:12px;align-items:center}
.scroll::after{content:"";width:1px;height:54px;background:linear-gradient(var(--ac),transparent);animation:sl 2.2s infinite}
@keyframes sl{0%{transform:scaleY(0);transform-origin:top}50%{transform:scaleY(1);transform-origin:top}51%{transform-origin:bottom}100%{transform:scaleY(0);transform-origin:bottom}}
/* about */
.stmt{font:600 clamp(1.8rem,4.2vw,3.6rem)/1.15 var(--d);letter-spacing:-.035em;max-width:24ch}
.wd{opacity:.16;display:inline-block;margin-right:.26em}
.ab2{display:grid;grid-template-columns:minmax(220px,.7fr) 1fr;gap:clamp(30px,6vw,90px);margin-top:80px;align-items:center}
.pf{aspect-ratio:3/4;max-width:400px;border-radius:6px;overflow:hidden;position:relative;background:var(--bg2)}
.pf img{position:absolute;left:-6%;top:-6%;width:112%;height:112%;object-fit:cover;object-position:50% 20%}
.pf::after{content:"";position:absolute;inset:0;background:linear-gradient(180deg,transparent 60%,rgba(8,9,11,.8)),linear-gradient(140deg,rgba(167,139,255,.22),transparent 50%)}
.ab2 p{max-width:42ch;font-size:1.12rem}
.stats{display:grid;grid-template-columns:repeat(4,1fr);border-top:1px solid var(--line);margin-top:80px}
.stat{padding:26px 22px 8px 0;border-right:1px solid var(--line);padding-left:22px}.stat:first-child{padding-left:0}.stat:last-child{border:0}
.stat b{display:block;font:600 clamp(1.8rem,4vw,3.4rem)/1 var(--d);letter-spacing:-.04em}
.stat span{font-size:.85rem;color:var(--mut)}
/* projects index */
.row{border-top:1px solid var(--line)}.row:last-child{border-bottom:1px solid var(--line)}
.rh{display:grid;grid-template-columns:56px 1fr auto 36px;gap:12px;align-items:center;width:100%;text-align:left;background:none;border:0;color:var(--tx);padding:clamp(22px,3.4vw,40px) 0;cursor:pointer;font-family:var(--d)}
.rh .n{font-size:.9rem;color:var(--mut)}
.rh .t{font:600 clamp(2rem,6.2vw,5.6rem)/1 var(--d);letter-spacing:-.045em;transition:transform .5s cubic-bezier(.2,.8,.2,1),color .4s}
.rh .s{font-size:.85rem;color:var(--mut);text-align:right}
.rh .pl{font-size:1.6rem;transition:transform .5s,color .4s;text-align:center}
.row:hover .t,.row.o .t{transform:translateX(16px);color:var(--ac)}
.row.o .pl{transform:rotate(45deg);color:var(--ac)}
.rb{display:grid;grid-template-rows:0fr;transition:grid-template-rows .6s cubic-bezier(.2,.8,.2,1)}
.row.o .rb{grid-template-rows:1fr}
.rb>div{overflow:hidden}
.rbi{display:grid;grid-template-columns:56px 1.1fr 1fr;gap:12px 32px;padding:0 0 clamp(30px,4vw,50px)}
.rbi p{color:var(--mut);max-width:42ch;font-size:1.05rem}
.rbi ul{list-style:none;padding:0;display:grid;grid-template-columns:1fr 1fr;gap:6px 20px;font-size:.92rem;margin-bottom:20px}
.rbi li{padding-left:16px;position:relative}.rbi li::before{content:"";position:absolute;left:0;top:.75em;width:7px;height:1px;background:var(--ac)}
.tags{display:flex;gap:8px;flex-wrap:wrap;margin:18px 0 0}.tags span{font:500 .75rem var(--d);padding:5px 12px;border:1px solid var(--line);border-radius:999px;color:var(--mut)}
.pls{display:flex;gap:10px;flex-wrap:wrap}.pls .btn{padding:11px 20px;font-size:.85rem}
#pv{position:fixed;left:0;top:0;width:300px;aspect-ratio:4/3;border-radius:6px;overflow:hidden;border:1px solid var(--line);z-index:60;pointer-events:none;opacity:0;scale:.8;transition:opacity .35s,scale .45s cubic-bezier(.2,.8,.2,1);display:none;background:var(--bg2)}
#pv.on{opacity:1;scale:1}#pv svg{width:100%;height:100%;display:none}
/* skills */
.sr{display:grid;grid-template-columns:minmax(150px,.5fr) 1fr;gap:24px;align-items:center;padding:28px 0;border-top:1px solid var(--line);position:relative}
.sr:last-child{border-bottom:1px solid var(--line)}
.sr::after{content:"";position:absolute;left:0;bottom:-1px;height:1px;width:100%;background:var(--ac);transform:scaleX(0);transform-origin:left;transition:transform .7s cubic-bezier(.2,.8,.2,1)}
.sr:hover::after{transform:scaleX(1)}
.sr h3{font:600 clamp(1.5rem,3.4vw,2.8rem) var(--d);letter-spacing:-.035em;transition:color .4s}.sr:hover h3{color:var(--ac)}
.sr div{display:flex;gap:8px;flex-wrap:wrap}
.sr span{font:500 .95rem var(--d);padding:9px 16px;border:1px solid var(--line);border-radius:999px;transition:transform .45s cubic-bezier(.2,.8,.2,1),background .3s}
.sr:hover span{transform:translateY(-4px);background:rgba(167,139,255,.1)}
.sr:hover span:nth-child(2){transition-delay:.05s}.sr:hover span:nth-child(3){transition-delay:.1s}.sr:hover span:nth-child(4){transition-delay:.15s}
/* experience */
.tl{position:relative;margin-top:60px;padding-left:clamp(28px,6vw,80px)}
.tl::before{content:"";position:absolute;left:0;top:0;bottom:0;width:1px;background:var(--line)}
#tlp{position:absolute;left:0;top:0;width:1px;height:100%;background:var(--ac);transform-origin:top;transform:scaleY(0);box-shadow:0 0 12px var(--ac)}
.ex{position:relative;padding:0 0 clamp(46px,7vw,80px)}
.ex::before{content:"";position:absolute;left:calc(-1*clamp(28px,6vw,80px) - 4px);top:14px;width:9px;height:9px;border-radius:50%;background:var(--bg);border:1px solid var(--ac);transition:.4s}
.ex.on::before{background:var(--ac);box-shadow:0 0 16px var(--ac)}
.ex h3{font:600 clamp(1.7rem,3.6vw,3rem)/1.1 var(--d);letter-spacing:-.04em}.ex p{color:var(--mut);margin-top:6px}
/* achievements */
.ach{display:grid;grid-template-columns:repeat(3,1fr);margin-top:60px;border-top:1px solid var(--line)}
.ac{padding:34px 28px 10px 0;border-right:1px solid var(--line)}.ac+.ac{padding-left:28px}.ac:last-child{border:0}
.ac .big{font:800 clamp(2.6rem,6.4vw,6rem)/1 var(--d);letter-spacing:-.05em;color:var(--ac)}
.ac h3{font:600 1.3rem var(--d);margin:12px 0 6px}.ac p{color:var(--mut);font-size:.95rem}
.edu{display:flex;justify-content:space-between;gap:16px;flex-wrap:wrap;align-items:flex-end;padding:30px 0;border-top:1px solid var(--line);border-bottom:1px solid var(--line);margin-top:70px}
.edu h3{font:600 clamp(1.4rem,3vw,2.2rem) var(--d);letter-spacing:-.03em}.edu .yr{font:800 clamp(1.8rem,4.6vw,3.6rem) var(--d);color:var(--mut);letter-spacing:-.04em}
.soc{display:flex;gap:10px;flex-wrap:wrap;margin-top:50px}
.sl{display:flex;align-items:center;height:62px;border-radius:999px;border:1px solid var(--line);padding:0 20px;overflow:hidden;transition:max-width .6s cubic-bezier(.2,.8,.2,1),background .4s,border-color .4s;max-width:62px;white-space:nowrap;gap:14px;font:500 .95rem var(--d)}
.sl:hover,.sl:focus-visible{max-width:260px;background:rgba(167,139,255,.14);border-color:var(--ac)}
.sl i{font:800 .9rem var(--d);font-style:normal;width:22px;text-align:center;flex:none}
.sl em{font-style:normal;opacity:0;transform:translateX(-8px);transition:.4s .08s}.sl:hover em,.sl:focus-visible em{opacity:1;transform:none}
/* contact */
#contact{text-align:center;padding-bottom:clamp(110px,15vw,210px)}
#contact h2{font-size:clamp(2.8rem,10vw,9rem);max-width:10ch;margin:0 auto 28px;line-height:.9;text-shadow:0 0 40px rgba(8,9,11,.9)}
#contact p{max-width:38ch;margin:0 auto 40px;color:var(--tx)}
.cl{display:flex;justify-content:center;gap:10px;flex-wrap:wrap;margin-top:24px}
footer{border-top:1px solid var(--line);padding-top:28px;padding-bottom:28px;color:var(--mut);font-size:.88rem;background:rgba(8,9,11,.7)}
footer .wrap{display:flex;justify-content:space-between;gap:12px;flex-wrap:wrap}
/* cursor */
#cur,#cur2{position:fixed;left:0;top:0;pointer-events:none;z-index:120;border-radius:50%;display:none}
#cur{width:8px;height:8px;background:var(--tx);margin:-4px 0 0 -4px;mix-blend-mode:difference}
#cur2{width:38px;height:38px;margin:-19px 0 0 -19px;border:1px solid rgba(255,255,255,.45);place-items:center;font:700 .62rem var(--d);letter-spacing:.1em;transition:width .35s,height .35s,margin .35s,background .35s,border-color .35s,color .35s;color:transparent}
@media (hover:hover) and (pointer:fine){body.cc,body.cc a,body.cc button{cursor:none}#cur{display:block}#cur2{display:grid}#pv{display:block}}
#cur2.h{width:62px;height:62px;margin:-31px 0 0 -31px;border-color:var(--ac)}
#cur2.v{width:88px;height:88px;margin:-44px 0 0 -44px;background:var(--ac);border-color:var(--ac);color:#0b0715}
@media(max-width:900px){
:root{--rail:0px}.rail{display:none}.top{display:flex}
.ab2,.sr,.ach{grid-template-columns:1fr}.ab2{margin-top:50px}.stats{grid-template-columns:1fr 1fr}.stat:nth-child(2){border-right:0}.stat:nth-child(3){padding-left:0}
.stat{border-bottom:1px solid var(--line);padding-bottom:20px}
.ac,.ac+.ac{padding:26px 0;border-right:0;border-bottom:1px solid var(--line)}
.rh{grid-template-columns:34px 1fr 30px}.rh .s{display:none}
.rbi{grid-template-columns:1fr;padding-left:0}.rbi>:first-child{display:none}
.scroll{display:none}.hw{padding-top:100px}.hero-ph{display:none!important}
}
.rm *{animation:none!important;transition-duration:.01s!important}
@media(prefers-reduced-motion:reduce){*{animation:none!important}.wd{opacity:1}}
</style>
</head>
<body>
<div id="cur"></div><div id="cur2"></div><div id="pv"aria-hidden="true">
<svg viewBox="0 0 400 300"><rect width="400" height="300" fill="#12131a"/><g fill="none" stroke="#a78bff"><path d="M0 210Q100 150 200 190T400 130" stroke-opacity=".6"/><path d="M0 250Q100 200 200 230T400 180" stroke-opacity=".3"/></g><g fill="#a78bff"><circle cx="90" cy="168" r="6"/><circle cx="200" cy="190" r="6"/><circle cx="310" cy="146" r="6"/></g><rect x="40" y="40" width="160" height="70" rx="6" fill="#1b1d27"/><rect x="54" y="56" width="80" height="8" rx="4" fill="#fff" fill-opacity=".55"/><rect x="54" y="88" width="50" height="10" rx="3" fill="#a78bff"/></svg>
<svg viewBox="0 0 400 300"><rect width="400" height="300" fill="#12131a"/><g fill="#1b1d27" stroke="#fff" stroke-opacity=".14"><rect x="30" y="110" width="90" height="80" rx="6"/><rect x="155" y="110" width="90" height="80" rx="6"/><rect x="280" y="110" width="90" height="80" rx="6"/></g><path d="M120 150H155M245 150H280" stroke="#a78bff" stroke-width="2"/><g fill="#fff" fill-opacity=".5"><rect x="44" y="130" width="50" height="6" rx="3"/><rect x="169" y="130" width="50" height="6" rx="3"/><rect x="294" y="130" width="50" height="6" rx="3"/></g><g fill="#a78bff"><rect x="44" y="164" width="30" height="10" rx="3"/><rect x="169" y="164" width="30" height="10" rx="3"/><rect x="294" y="164" width="30" height="10" rx="3"/></g></svg>
<svg viewBox="0 0 400 300"><rect width="400" height="300" fill="#12131a"/><rect x="40" y="50" width="320" height="34" rx="17" fill="#1b1d27"/><g fill="#1b1d27"><rect x="40" y="110" width="320" height="42" rx="6"/><rect x="40" y="162" width="320" height="42" rx="6"/><rect x="40" y="214" width="320" height="42" rx="6"/></g><g fill="#a78bff"><rect x="54" y="124" width="14" height="14" rx="3"/><rect x="54" y="176" width="14" height="14" rx="3"/><rect x="54" y="228" width="14" height="14" rx="3"/></g><g fill="#fff" fill-opacity=".4"><rect x="80" y="127" width="110" height="6" rx="3"/><rect x="80" y="179" width="90" height="6" rx="3"/><rect x="80" y="231" width="130" height="6" rx="3"/></g></svg></div>
<canvas id="gl" aria-hidden="true"></canvas>

<aside class="rail" aria-label="Primary">
  <a class="logo" href="#home" aria-label="Home">SC</a>
  <nav class="dots" id="dots">
    <a href="#home"><i></i><span>Home</span></a><a href="#about"><i></i><span>About</span></a><a href="#projects"><i></i><span>Projects</span></a><a href="#experience"><i></i><span>Experience</span></a><a href="#skills"><i></i><span>Skills</span></a><a href="#achievements"><i></i><span>Achievements</span></a><a href="#contact"><i></i><span>Contact</span></a>
  </nav>
  <div class="rp"><i id="prog"></i></div>
</aside>
<header class="top" id="top"><a class="logo" href="#home">SC</a><button id="burger" aria-label="Menu" aria-expanded="false" aria-controls="menu"><i></i><i></i></button></header>
<div id="menu" aria-hidden="true"><a href="#home">Home</a><a href="#about">About</a><a href="#projects">Projects</a><a href="#experience">Experience</a><a href="#skills">Skills</a><a href="#achievements">Achievements</a><a href="#contact">Contact</a></div>

<main>
<section id="home"><div class="wrap hw">
  <p class="kick">Computer Science &amp; Engineering Student</p>
  <img class="hero-ph" id="fb" src="photo.jpg" alt="Portrait of Soumajit Chakraborty">
  <div>
    <h1 class="hname" aria-label="Soumajit Chakraborty"><span class="ln" aria-hidden="true">SOUMAJIT</span><span class="ln" aria-hidden="true">CHAKRABORTY</span></h1>
    <p class="role">Full-Stack Developer · Problem Solver · Technology Enthusiast</p>
    <div class="hero-row">
      <p class="mut intro" id="intro">Building practical digital experiences with code, creativity and modern technology.</p>
      <div class="ctas" id="ctas">
        <a class="btn p mag" href="#projects" data-c="h"><span>View Projects</span><span class="ar">→</span></a>
        <a class="btn mag" href="resume.pdf" download data-c="h"><span>Download Resume</span></a>
        <a class="btn mag" href="#contact" data-c="h"><span>Let's Connect</span></a>
      </div>
    </div>
  </div>
  <div class="scroll">Scroll</div>
</div></section>

<section id="about"><div class="wrap">
  <div class="lbl">About</div>
  <p class="stmt" id="stmt">I turn ideas into working software, from the database to the interface, and I keep learning the next tool.</p>
  <div class="ab2">
    <div class="pf" id="pf" data-cur="HELLO"><img src="photo.jpg" alt="Soumajit Chakraborty in a navy suit" width="900" height="1202" loading="lazy"></div>
    <div>
      <p>I'm a Computer Science &amp; Engineering student at <b>Asansol Engineering College</b>, interested in software development, modern web technologies and problem solving.</p>
      <p style="margin-top:16px" class="mut">I enjoy building practical applications and exploring new technologies.</p>
    </div>
  </div>
  <div class="stats">
    <div class="stat"><b>CSE</b><span>Computer Science &amp; Engineering</span></div>
    <div class="stat"><b><i class="cnt" data-n="110" style="font-style:normal">0</i>+</b><span>LeetCode problems</span></div>
    <div class="stat"><b><i class="cnt" data-n="46" style="font-style:normal">0</i>+</b><span>Salesforce badges</span></div>
    <div class="stat"><b>SIH 2026</b><span>Shortlisted</span></div>
  </div>
</div></section>

<section id="projects"><div class="wrap">
  <div class="lbl">Projects</div>
  <h2 data-split style="margin-bottom:70px">Built end to end.</h2>
  <div class="rows">
    <article class="row o"><button class="rh" aria-expanded="true" data-cur="OPEN"><span class="n">01</span><span class="t">AgriLink</span><span class="s">Node · Express · MySQL</span><span class="pl">+</span></button>
      <div class="rb"><div><div class="rbi"><span></span><div><p>AI-powered digital marketplace for farmer–buyer connectivity, price discovery and agricultural trade.</p><div class="tags"><span>HTML</span><span>CSS</span><span>JavaScript</span><span>Node.js</span><span>Express</span><span>MySQL</span></div></div>
      <div><ul><li>Farmer and buyer accounts</li><li>Produce listings</li><li>Offers and counter-offers</li><li>Transactions</li><li>Logistics</li><li>Reviews and trust</li><li>Dispute resolution</li><li>Multilingual support</li></ul><div class="pls"><a class="btn mag" href="#" data-c="h"><span>GitHub</span><span class="ar">↗</span></a><a class="btn p mag" href="#" data-c="h"><span>Live Demo</span><span class="ar">↗</span></a></div></div></div></div></div></article>
    <article class="row"><button class="rh" aria-expanded="false" data-cur="OPEN"><span class="n">02</span><span class="t">Unified Scholarship</span><span class="s">Students → Officers → Admins</span><span class="pl">+</span></button>
      <div class="rb"><div><div class="rbi"><span></span><div><p>A centralized scholarship platform connecting students, verifying officers and system administrators.</p><div class="tags"><span>Students</span><span>Verifying Officers</span><span>Administrators</span></div></div>
      <div><ul><li>Student registration</li><li>Eligibility checks</li><li>Application management</li><li>Document verification</li><li>Officer workflow</li><li>Application status</li><li>AI assistance</li><li>Admin management</li></ul><div class="pls"><a class="btn mag" href="#" data-c="h"><span>GitHub</span><span class="ar">↗</span></a><a class="btn p mag" href="#" data-c="h"><span>Live Demo</span><span class="ar">↗</span></a></div></div></div></div></div></article>
    <article class="row"><button class="rh" aria-expanded="false" data-cur="OPEN"><span class="n">03</span><span class="t">Online Job Portal</span><span class="s">Search · Filters · Employers</span><span class="pl">+</span></button>
      <div class="rb"><div><div class="rbi"><span></span><div><p>A modern job discovery and recruitment platform for candidates and employers.</p></div>
      <div><ul><li>Job listings</li><li>Search and filters</li><li>Candidate experience</li><li>Employer tools</li><li>Responsive UI</li></ul><div class="pls"><a class="btn mag" href="#" data-c="h"><span>GitHub</span><span class="ar">↗</span></a><a class="btn p mag" href="#" data-c="h"><span>Live Demo</span><span class="ar">↗</span></a></div></div></div></div></div></article>
  </div>
</div></section>

<section id="experience"><div class="wrap">
  <div class="lbl">Experience</div>
  <h2 data-split>Learning by building.</h2>
  <div class="tl" id="tl"><div id="tlp"></div>
    <div class="ex"><h3>AI for Sustainability</h3><p>Virtual internship · 1M1B</p></div>
    <div class="ex"><h3>Full Stack Web Development</h3><p>Virtual internship · RabTech Academy</p></div>
    <div class="ex"><h3>Yuva Intern</h3><p>Yuva Intern</p></div>
  </div>
</div></section>

<section id="skills"><div class="wrap">
  <div class="lbl">Skills</div>
  <h2 data-split style="margin-bottom:60px">Software development, layer by layer.</h2>
  <div class="sr"><h3>Frontend</h3><div><span>React</span><span>HTML</span><span>CSS</span><span>JavaScript</span></div></div>
  <div class="sr"><h3>Backend</h3><div><span>Node.js</span><span>Express</span><span>Java</span><span>Python</span></div></div>
  <div class="sr"><h3>Database</h3><div><span>MySQL</span><span>SQL</span><span>Firebase</span></div></div>
  <div class="sr"><h3>Cloud</h3><div><span>Google Cloud</span><span>Docker</span><span>Firebase</span></div></div>
  <div class="sr"><h3>Programming</h3><div><span>Python</span><span>C</span><span>Java</span><span>JavaScript</span><span>SQL</span></div></div>
  <div class="sr"><h3>Tools</h3><div><span>Git</span><span>GitHub</span><span>VS Code</span><span>Docker</span></div></div>
</div></section>

<section id="achievements"><div class="wrap">
  <div class="lbl">Achievements</div>
  <h2 data-split>Proof of practice.</h2>
  <div class="ach">
    <div class="ac"><div class="big">SIH 2026</div><h3>Smart India Hackathon</h3><p>Cleared the internal SIH hackathon and shortlisted for SIH 2026 from college.</p></div>
    <div class="ac"><div class="big"><i class="cnt" data-n="46" style="font-style:normal">0</i>+</div><h3>Salesforce badges</h3><p>11,000+ points · Agentblazer Champion</p></div>
    <div class="ac"><div class="big"><i class="cnt" data-n="110" style="font-style:normal">0</i>+</div><h3>LeetCode</h3><p>Problems solved</p></div>
  </div>
  <div class="edu"><div><p class="mut">Education</p><h3>Asansol Engineering College</h3><p class="mut">B.Tech — Computer Science &amp; Engineering</p></div><div class="yr">2024–2028</div></div>
  <div class="soc">
    <a class="sl" href="#" data-c="h"><i>GH</i><em>GitHub ↗</em></a><a class="sl" href="#" data-c="h"><i>in</i><em>LinkedIn ↗</em></a><a class="sl" href="#" data-c="h"><i>LC</i><em>LeetCode ↗</em></a><a class="sl" href="#" data-c="h"><i>X</i><em>X ↗</em></a><a class="sl" href="#" data-c="h"><i>SF</i><em>Trailhead ↗</em></a>
  </div>
</div></section>

<section id="contact"><div class="wrap">
  <h2 data-split>Let's Build Something Meaningful.</h2>
  <p>Have an idea, opportunity, or project in mind? Let's connect.</p>
  <a class="btn p mag" href="mailto:your-email@example.com" data-c="h" style="padding:22px 40px;font-size:1.1rem"><span>Say hello</span><span class="ar">→</span></a>
  <div class="cl"><a class="btn mag" href="mailto:your-email@example.com" data-c="h"><span>Email</span></a><a class="btn mag" href="#" data-c="h"><span>LinkedIn</span></a><a class="btn mag" href="#" data-c="h"><span>GitHub</span></a></div>
</div></section>
</main>
<footer><div class="wrap"><span>Soumajit Chakraborty © <span id="yr"></span></span><span>Designed &amp; Built with curiosity and code.</span></div></footer>

<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/ScrollTrigger.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@studio-freight/lenis@1.0.42/dist/lenis.min.js"></script>
<script>
(()=>{
const $=(s,r=document)=>r.querySelector(s),$$=(s,r=document)=>[...r.querySelectorAll(s)];
const RM=matchMedia('(prefers-reduced-motion:reduce)').matches,fine=matchMedia('(hover:hover) and (pointer:fine)').matches,mobile=innerWidth<900;
const sm=(a,b,x)=>{x=Math.min(1,Math.max(0,(x-a)/(b-a)));return x*x*(3-2*x)};
$('#yr').textContent=new Date().getFullYear();
if(RM)document.body.classList.add('rm');
$$('.hname .ln').forEach(l=>{l.innerHTML=[...l.textContent].map(c=>`<span class="ch">${c}</span>`).join('')});
const HAS=!!window.gsap;if(HAS)gsap.registerPlugin(ScrollTrigger);

/* smooth scroll */
let lenis=null;
if(!RM&&window.Lenis&&HAS){lenis=new Lenis({lerp:.09});lenis.on('scroll',ScrollTrigger.update);gsap.ticker.add(t=>lenis.raf(t*1000));gsap.ticker.lagSmoothing(0)}
const menu=$('#menu'),burger=$('#burger');
const closeMenu=()=>{menu.classList.remove('o');burger.setAttribute('aria-expanded','false');menu.setAttribute('aria-hidden','true');lenis&&lenis.start()};
burger.onclick=()=>{const o=!menu.classList.contains('o');menu.classList.toggle('o',o);burger.setAttribute('aria-expanded',o);menu.setAttribute('aria-hidden',!o);lenis&&(o?lenis.stop():lenis.start())};
addEventListener('keydown',e=>{if(e.key==='Escape')closeMenu()});
$$('a[href^="#"]').forEach(a=>{const h=a.getAttribute('href');if(h.length>1)a.addEventListener('click',e=>{e.preventDefault();closeMenu();const el=$(h);lenis?lenis.scrollTo(el,{offset:0}):el.scrollIntoView({behavior:RM?'auto':'smooth'})})});

/* active section + progress */
const secs=['home','about','projects','experience','skills','achievements','contact'],dots=$$('#dots a');
const io=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting)dots.forEach((d,i)=>d.classList.toggle('on',i===secs.indexOf(e.target.id)))}),{rootMargin:'-45% 0px -50% 0px'});
secs.forEach(s=>io.observe($('#'+s)));
const prog=$('#prog'),top=$('#top');
const onS=()=>{const m=document.documentElement.scrollHeight-innerHeight;prog.style.transform=`scaleY(${scrollY/m})`;top.classList.toggle('s',scrollY>30)};
addEventListener('scroll',onS,{passive:true});onS();

/* projects index */
const rows=$$('.row'),pv=$('#pv'),pvs=$$('#pv svg');
rows.forEach((r,i)=>{const h=$('.rh',r);
 h.onclick=()=>{const o=r.classList.contains('o');rows.forEach(x=>{x.classList.remove('o');$('.rh',x).setAttribute('aria-expanded','false')});if(!o){r.classList.add('o');h.setAttribute('aria-expanded','true')}setTimeout(()=>HAS&&ScrollTrigger.refresh(),700)};
 r.addEventListener('mouseenter',()=>{pvs.forEach((s,j)=>s.style.display=j===i?'block':'none');pv.classList.add('on')});
 r.addEventListener('mouseleave',()=>pv.classList.remove('on'))});

/* cursor, magnetic, preview follow */
if(fine&&!RM&&HAS){
 document.body.classList.add('cc');
 const c=$('#cur'),c2=$('#cur2');let mx=innerWidth/2,my=innerHeight/2,x=mx,y=my,px=mx,py=my;
 addEventListener('mousemove',e=>{mx=e.clientX;my=e.clientY;c.style.transform=`translate(${mx}px,${my}px)`});
 gsap.ticker.add(()=>{x+=(mx-x)*.16;y+=(my-y)*.16;c2.style.transform=`translate(${x}px,${y}px)`;px+=(mx-px)*.09;py+=(my-py)*.09;pv.style.transform=`translate(${px+40}px,${py-110}px) rotate(${(mx-px)*.04}deg)`});
 document.addEventListener('mouseover',e=>{const t=e.target.closest('[data-cur],[data-c],a,button');if(!t){c2.className='';c2.textContent='';return}
  if(t.dataset.cur){c2.className='v';c2.textContent=t.dataset.cur}else{c2.className='h';c2.textContent=''}});
 $$('.mag').forEach(b=>{b.addEventListener('mousemove',e=>{const r=b.getBoundingClientRect();gsap.to(b,{x:(e.clientX-r.left-r.width/2)*.25,y:(e.clientY-r.top-r.height/2)*.35,duration:.4,ease:'power3.out'})});b.addEventListener('mouseleave',()=>gsap.to(b,{x:0,y:0,duration:.7,ease:'elastic.out(1,.4)'}))});
}

/* counters */
$$('.cnt').forEach(el=>{const n=+el.dataset.n;if(RM||!HAS){el.textContent=n;return}const o={v:0};gsap.to(o,{v:n,duration:1.8,ease:'power2.out',onUpdate:()=>el.textContent=Math.round(o.v),scrollTrigger:{trigger:el,start:'top 92%',once:true}})});

/* 3D portrait: the photo is sampled into particles */
const U={uP:{value:RM?1:0},uSc:{value:0},uT:{value:0},uScale:{value:600},uMs:{value:new THREE.Vector2(99,99)}};
let ready=false;
function scene(img){
 const cv=$('#gl'),W=150,H=200,cc=document.createElement('canvas');cc.width=W;cc.height=H;const cx=cc.getContext('2d');cx.drawImage(img,0,0,W,H);
 let d;try{d=cx.getImageData(0,0,W,H).data}catch(e){return fail()}
 let r;try{r=new THREE.WebGLRenderer({canvas:cv,antialias:false,alpha:true})}catch(e){return fail()}
 r.setPixelRatio(Math.min(devicePixelRatio,mobile?1.5:2));r.setSize(innerWidth,innerHeight);
 const FOV=40,sc=new THREE.Scene(),cam=new THREE.PerspectiveCamera(FOV,innerWidth/innerHeight,.1,100);cam.position.z=9;
 const T=[],S=[],C=[],M=[];
 for(let j=0;j<H;j++)for(let i=0;i<W;i++){
  const k=(j*W+i)*4,R=d[k]/255,G=d[k+1]/255,B=d[k+2]/255,L=.299*R+.587*G+.114*B;
  const u=i/W,v=j/H,dx=(u-.5)/.5,dy=(v-.43)/.56,m=1-sm(.55,1,Math.hypot(dx,dy));if(m<.04)continue;
  T.push((u-.5)*4.5,(.5-v)*6,(1-L)*.55);
  S.push((Math.random()-.5)*20,(Math.random()-.5)*11,(Math.random()-.5)*8-1);
  C.push(R,G,B);M.push(L,Math.random(),m)}
 const g=new THREE.BufferGeometry();
 g.setAttribute('position',new THREE.Float32BufferAttribute(T,3));
 g.setAttribute('aT',new THREE.Float32BufferAttribute(T,3));g.setAttribute('aS',new THREE.Float32BufferAttribute(S,3));
 g.setAttribute('aC',new THREE.Float32BufferAttribute(C,3));g.setAttribute('aM',new THREE.Float32BufferAttribute(M,3));
 const mat=new THREE.ShaderMaterial({uniforms:U,transparent:true,depthWrite:false,
 vertexShader:`attribute vec3 aT;attribute vec3 aS;attribute vec3 aC;attribute vec3 aM;uniform float uP,uSc,uT,uScale;uniform vec2 uMs;varying vec3 vC;varying float vA;
 void main(){float r=aM.y;float e=smoothstep(0.,1.,clamp(uP*1.5-r*.5,0.,1.));
 vec3 s=aS+vec3(sin(uT*.2+r*20.)*.4,cos(uT*.17+r*30.)*.4,0.);
 vec3 p=mix(s,aT,e);p=mix(p,s*.85,uSc);
 vec2 d=p.xy-uMs;float f=exp(-dot(d,d)*1.6);p.xy+=normalize(d+1e-4)*f*.55*(1.-uSc);p.z+=f*.9*(1.-uSc)+sin(uT*1.2+r*6.283)*.02;
 vec4 mv=modelViewMatrix*vec4(p,1.);gl_Position=projectionMatrix*mv;
 gl_PointSize=(.022+(1.-aM.x)*.05)*uScale/-mv.z;
 vC=mix(aC*1.05,vec3(.65,.55,1.),.3);vA=mix(aM.z,.7,uSc)*(.45+.55*(1.-aM.x));}`,
 fragmentShader:`varying vec3 vC;varying float vA;void main(){float d=length(gl_PointCoord-.5);if(d>.5)discard;gl_FragColor=vec4(vC,smoothstep(.5,.2,d)*vA);}`});
 const pts=new THREE.Points(g,mat);pts.frustumCulled=false;sc.add(pts);
 const dx0=()=>innerWidth<900?0:2.5,sy=()=>innerWidth<900?1.1:0,ss=()=>innerWidth<900?.8:1;
 let nx=0,ny=0,sp=0,vis=true,clock=new THREE.Clock();
 const setScale=()=>U.uScale.value=r.domElement.height/(2*Math.tan(FOV*Math.PI/360));setScale();
 addEventListener('mousemove',e=>{nx=e.clientX/innerWidth*2-1;ny=-(e.clientY/innerHeight*2-1)},{passive:true});
 addEventListener('resize',()=>{r.setSize(innerWidth,innerHeight);cam.aspect=innerWidth/innerHeight;cam.updateProjectionMatrix();setScale()});
 document.addEventListener('visibilitychange',()=>vis=!document.hidden);
 const hh=9*Math.tan(FOV*Math.PI/360);
 (function loop(){requestAnimationFrame(loop);if(!vis)return;
  const mxs=document.documentElement.scrollHeight-innerHeight||1;sp+=(scrollY/mxs-sp)*.07;
  U.uT.value=clock.getElapsedTime()*(RM?0:1);
  U.uSc.value=sm(.03,.2,sp)*(1-sm(.86,.97,sp));
  const gx=dx0()*(1-sm(.84,.96,sp)),gs=ss();
  pts.position.set(gx,sy(),0);pts.scale.setScalar(gs);pts.rotation.y=nx*.12+sp*.6*(1-sm(.84,.96,sp));pts.rotation.x=-ny*.06;
  U.uMs.value.set((nx*hh*cam.aspect-gx)/gs,(ny*hh-sy())/gs);
  r.render(sc,cam)})();
 ready=true;
}
function fail(){const f=$('#fb');if(f&&innerWidth>900)f.style.display='block'}
const im=new Image();im.onload=()=>scene(im);im.onerror=fail;im.src='__SMALL__';
if(HAS&&!RM)gsap.to(U.uP,{value:1,duration:3.2,ease:'power2.inOut',delay:.3});

/* animations */
if(HAS&&!RM){
 const tl=gsap.timeline({delay:.2});
 tl.from('.logo,.dots,.rp,.top',{opacity:0,y:-14,stagger:.08,duration:.8,ease:'power3.out'})
   .from('.kick',{opacity:0,y:16,duration:.8},.2)
   .from('.hname .ch',{yPercent:110,filter:'blur(12px)',opacity:0,duration:1.1,ease:'expo.out',stagger:.035},.3)
   .from('.role,#intro',{y:20,opacity:0,stagger:.1,duration:.8,ease:'power3.out'},.9)
   .from('#ctas .btn',{y:20,opacity:0,stagger:.08,duration:.7,ease:'power3.out'},1.1);
 $$('[data-split]').forEach(h=>{h.innerHTML=h.textContent.split(' ').map(w=>`<span style="display:inline-block;overflow:hidden;vertical-align:top;padding-bottom:.1em"><span class="w" style="display:inline-block">${w}</span></span>`).join(' ');
  gsap.from($$('.w',h),{yPercent:110,duration:1,ease:'expo.out',stagger:.07,scrollTrigger:{trigger:h,start:'top 85%',once:true}})});
 const st=$('#stmt');st.innerHTML=st.textContent.split(' ').map(w=>`<span class="wd">${w}</span>`).join('');
 gsap.to('.wd',{opacity:1,stagger:.12,ease:'none',scrollTrigger:{trigger:st,start:'top 80%',end:'bottom 45%',scrub:true}});
 gsap.fromTo('#pf',{clipPath:'circle(16% at 50% 38%)'},{clipPath:'circle(80% at 50% 38%)',ease:'none',scrollTrigger:{trigger:'#pf',start:'top 90%',end:'top 30%',scrub:true}});
 gsap.fromTo('#pf img',{yPercent:-5},{yPercent:5,ease:'none',scrollTrigger:{trigger:'#pf',scrub:true}});
 gsap.from('.stat,.ac',{opacity:0,y:30,stagger:.1,duration:.8,scrollTrigger:{trigger:'.stats',start:'top 88%',once:true}});
 $$('.row').forEach(r=>gsap.from(r,{opacity:0,y:40,duration:.9,ease:'power3.out',scrollTrigger:{trigger:r,start:'top 90%',once:true}}));
 $$('.sr').forEach(r=>gsap.from(r,{opacity:0,y:30,duration:.8,ease:'power3.out',scrollTrigger:{trigger:r,start:'top 92%',once:true}}));
 gsap.to('#tlp',{scaleY:1,ease:'none',scrollTrigger:{trigger:'#tl',start:'top 60%',end:'bottom 60%',scrub:true}});
 $$('.ex').forEach(e=>ScrollTrigger.create({trigger:e,start:'top 62%',onEnter:()=>{e.classList.add('on');gsap.from(e.children,{y:24,opacity:0,stagger:.1,duration:.8,ease:'power3.out'})},onLeaveBack:()=>e.classList.remove('on')}));
}else{$$('.ex').forEach(e=>e.classList.add('on'));$('#tlp').style.transform='scaleY(1)'}
})();
</script>
</body>
</html>
.rb{display:grid;grid-template-rows:0fr;transition:grid-template-rows .6s cubic-bezier(.2,.8,.2,1)}
.row.
</body>
</html>
