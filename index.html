<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>APEX · Wealth Intelligence Platform</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;0,900;1,400;1,700&family=DM+Sans:ital,opsz,wght@0,9..40,200;0,9..40,300;0,9..40,400;0,9..40,500;1,9..40,300&family=DM+Mono:wght@300;400;500&display=swap" rel="stylesheet">

<style>
:root {
  --bg:        #080c10;
  --surface:   #0d1117;
  --card:      #111820;
  --border:    rgba(255,255,255,.07);
  --accent:    #00e5a0;
  --accent2:   #0af;
  --gold:      #e8c96d;
  --red:       #ff4d6a;
  --text:      #f0f4f8;
  --muted:     rgba(240,244,248,.45);
  --font-disp: 'Playfair Display', serif;
  --font-body: 'DM Sans', sans-serif;
  --font-mono: 'DM Mono', monospace;
}

*, *::before, *::after { margin:0; padding:0; box-sizing:border-box; }
html { scroll-behavior:smooth; font-size:16px; }

body {
  background: var(--bg);
  color: var(--text);
  font-family: var(--font-body);
  font-weight: 300;
  overflow-x: hidden;
  cursor: none;
}

/* ── CUSTOM CURSOR ── */
#cursor { position:fixed; z-index:9999; pointer-events:none; mix-blend-mode:exclusion; }
#cursor .dot  { width:8px; height:8px; background:#fff; border-radius:50%; position:absolute; transform:translate(-50%,-50%); transition:transform .1s; }
#cursor .ring { width:40px; height:40px; border:1px solid rgba(255,255,255,.5); border-radius:50%; position:absolute; transform:translate(-50%,-50%); transition:all .18s cubic-bezier(.25,.46,.45,.94); }
body:hover #cursor .ring { opacity:1; }

/* ── GRAIN OVERLAY ── */
body::after {
  content:''; position:fixed; inset:0; z-index:300; pointer-events:none;
  opacity:.028; mix-blend-mode:overlay;
  background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='200' height='200'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");
}

/* ── NAVBAR ── */
nav {
  position: fixed; top:0; left:0; right:0; z-index:200;
  display: flex; align-items:center; justify-content:space-between;
  padding: 22px 56px;
  background: linear-gradient(to bottom, rgba(8,12,16,.95), transparent);
  backdrop-filter: blur(0px);
  transition: backdrop-filter .4s, background .4s;
}
nav.scrolled { backdrop-filter:blur(20px); background:rgba(8,12,16,.88); }
.nav-logo { font-family:var(--font-disp); font-size:22px; font-weight:900; letter-spacing:.06em; color:var(--text); }
.nav-logo span { color:var(--accent); }
.nav-links { display:flex; gap:38px; list-style:none; }
.nav-links a { font-size:13px; letter-spacing:.08em; text-transform:uppercase; color:var(--muted); text-decoration:none; transition:color .3s; }
.nav-links a:hover { color:var(--text); }
.nav-cta { font-size:13px; font-weight:500; letter-spacing:.06em; padding:11px 26px; background:var(--accent); color:#000; border-radius:2px; text-decoration:none; transition:all .3s; }
.nav-cta:hover { background:#fff; transform:translateY(-1px); box-shadow:0 8px 30px rgba(0,229,160,.25); }

/* ── HERO ── */
#hero {
  min-height: 100vh;
  display: grid;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  gap: 0;
  padding: 130px 56px 80px;
  position: relative;
  overflow: hidden;
}

.hero-bg-grid {
  position:absolute; inset:0; z-index:0;
  background-image:
    linear-gradient(rgba(0,229,160,.04) 1px, transparent 1px),
    linear-gradient(90deg, rgba(0,229,160,.04) 1px, transparent 1px);
  background-size: 60px 60px;
  mask-image: radial-gradient(ellipse 80% 80% at 50% 50%, black, transparent);
  animation: gridShift 20s linear infinite;
}
@keyframes gridShift { to { background-position: 60px 60px; } }

.hero-glow {
  position:absolute; width:700px; height:700px; border-radius:50%;
  background: radial-gradient(circle, rgba(0,229,160,.12) 0%, transparent 70%);
  top: -100px; right: -100px; pointer-events:none; z-index:0;
  animation: pulse 6s ease-in-out infinite;
}
.hero-glow2 {
  position:absolute; width:500px; height:500px; border-radius:50%;
  background: radial-gradient(circle, rgba(0,170,255,.08) 0%, transparent 70%);
  bottom: -50px; left: 20%; pointer-events:none; z-index:0;
  animation: pulse 8s ease-in-out infinite reverse;
}
@keyframes pulse { 0%,100%{transform:scale(1);opacity:.8;} 50%{transform:scale(1.1);opacity:1;} }

.hero-left { position:relative; z-index:1; }
.hero-eyebrow {
  display: inline-flex; align-items:center; gap:10px;
  font-family:var(--font-mono); font-size:11px; letter-spacing:.2em; text-transform:uppercase;
  color:var(--accent); margin-bottom:28px;
}
.hero-eyebrow::before { content:''; width:32px; height:1px; background:var(--accent); }

.hero-title {
  font-family: var(--font-disp);
  font-size: clamp(48px,5.5vw,84px);
  font-weight: 900;
  line-height: .96;
  letter-spacing: -.02em;
  margin-bottom: 28px;
}
.hero-title em { font-style:italic; color:var(--accent); display:block; }
.hero-title .outline {
  -webkit-text-stroke: 1px rgba(240,244,248,.35);
  color: transparent;
}

.hero-desc { font-size:17px; line-height:1.75; color:var(--muted); max-width:440px; margin-bottom:44px; font-weight:300; }

.hero-actions { display:flex; align-items:center; gap:22px; flex-wrap:wrap; }
.btn-primary {
  display:inline-flex; align-items:center; gap:10px;
  background:var(--accent); color:#000; font-weight:500; font-size:14px;
  letter-spacing:.06em; padding:16px 34px; border-radius:2px;
  text-decoration:none; transition:all .35s; position:relative; overflow:hidden;
}
.btn-primary::after { content:''; position:absolute; inset:0; background:#fff; opacity:0; transition:opacity .3s; }
.btn-primary:hover::after { opacity:.15; }
.btn-primary:hover { transform:translateY(-2px); box-shadow:0 12px 40px rgba(0,229,160,.3); }
.btn-primary svg { width:16px; height:16px; }
.btn-ghost {
  font-size:13px; letter-spacing:.08em; text-transform:uppercase; color:var(--muted);
  text-decoration:none; display:inline-flex; align-items:center; gap:8px; transition:color .3s;
}
.btn-ghost:hover { color:var(--text); }
.btn-ghost span { display:inline-block; transition:transform .3s; }
.btn-ghost:hover span { transform:translateX(4px); }

.hero-stats {
  display:flex; gap:44px; margin-top:60px; padding-top:40px;
  border-top:1px solid var(--border);
}
.stat-item { }
.stat-num {
  font-family:var(--font-disp); font-size:34px; font-weight:700;
  background: linear-gradient(135deg, var(--text), var(--accent));
  -webkit-background-clip:text; -webkit-text-fill-color:transparent;
}
.stat-label { font-size:11px; letter-spacing:.12em; text-transform:uppercase; color:var(--muted); margin-top:4px; }

/* ── APP MOCKUP ── */
.hero-right { position:relative; z-index:1; display:flex; justify-content:center; }

.app-frame {
  width: min(400px, 42vw);
  background: var(--card);
  border: 1px solid var(--border);
  border-radius: 24px;
  overflow: hidden;
  box-shadow: 0 60px 120px rgba(0,0,0,.8), 0 0 0 1px rgba(255,255,255,.05), inset 0 1px 0 rgba(255,255,255,.08);
  animation: floatApp 7s ease-in-out infinite;
  position: relative;
}
@keyframes floatApp { 0%,100%{transform:translateY(0) rotateX(2deg) rotateY(-4deg);} 50%{transform:translateY(-14px) rotateX(2deg) rotateY(-4deg);} }

.app-notch {
  height: 32px; background:var(--surface); display:flex; align-items:center;
  justify-content:center; gap:6px;
}
.app-notch::before { content:''; width:60px; height:6px; background:rgba(255,255,255,.12); border-radius:10px; }

.app-header {
  padding: 20px 22px 16px;
  background: linear-gradient(135deg, #0d1420, #111e2a);
  border-bottom: 1px solid var(--border);
}
.app-greeting { font-size:12px; color:var(--muted); letter-spacing:.06em; }
.app-name { font-family:var(--font-disp); font-size:18px; font-weight:700; margin-top:2px; }
.app-balance-wrap { margin-top:14px; }
.app-balance-label { font-size:10px; letter-spacing:.15em; text-transform:uppercase; color:var(--muted); }
.app-balance {
  font-family:var(--font-mono); font-size:32px; font-weight:500; color:var(--text);
  letter-spacing:-.02em; margin-top:4px;
  display:flex; align-items:baseline; gap:6px;
}
.app-balance .currency { font-size:18px; color:var(--accent); }
.app-pnl {
  display:inline-flex; align-items:center; gap:5px;
  background:rgba(0,229,160,.12); color:var(--accent); border-radius:20px;
  font-size:12px; font-weight:500; padding:4px 10px; margin-top:8px;
}
.app-pnl.neg { background:rgba(255,77,106,.12); color:var(--red); }

.app-tabs {
  display:flex; padding:0 22px;
  background: var(--surface);
  border-bottom:1px solid var(--border);
}
.app-tab {
  font-size:11px; letter-spacing:.06em; text-transform:uppercase; color:var(--muted);
  padding:12px 14px; cursor:pointer; transition:color .3s; border-bottom:2px solid transparent;
  transition: all .3s;
}
.app-tab.active { color:var(--accent); border-bottom-color:var(--accent); }

.app-chart-wrap { padding:16px 10px 8px; background:var(--card); position:relative; }
.chart-labels {
  display:flex; justify-content:space-between; padding:0 12px;
  font-size:9px; color:var(--muted); letter-spacing:.06em; margin-bottom:4px;
}

canvas#appChart { width:100% !important; height:140px !important; }

.app-portfolio { padding:12px 22px 16px; }
.app-port-title {
  font-size:10px; letter-spacing:.15em; text-transform:uppercase; color:var(--muted);
  margin-bottom:12px;
}
.port-item {
  display:flex; align-items:center; gap:12px; padding:8px 0;
  border-bottom:1px solid rgba(255,255,255,.04);
}
.port-item:last-child { border-bottom:none; }
.port-dot { width:8px; height:8px; border-radius:50%; flex-shrink:0; }
.port-name { font-size:13px; flex:1; font-weight:400; }
.port-alloc { font-size:11px; color:var(--muted); }
.port-val { font-family:var(--font-mono); font-size:13px; }
.port-chg { font-family:var(--font-mono); font-size:11px; }
.port-chg.up { color:var(--accent); }
.port-chg.dn { color:var(--red); }

.app-cta-strip {
  margin:10px 22px 18px;
  background:linear-gradient(135deg,rgba(0,229,160,.15),rgba(0,170,255,.1));
  border:1px solid rgba(0,229,160,.2);
  border-radius:10px; padding:14px 16px;
  display:flex; align-items:center; gap:12px;
}
.app-cta-icon { font-size:22px; }
.app-cta-text { font-size:12px; line-height:1.4; flex:1; color:var(--muted); }
.app-cta-text strong { display:block; color:var(--text); font-weight:500; font-size:13px; }
.app-cta-btn {
  background:var(--accent); color:#000; font-size:11px; font-weight:600;
  padding:8px 14px; border-radius:6px; border:none; cursor:pointer; letter-spacing:.04em;
  white-space:nowrap; transition:all .3s;
}
.app-cta-btn:hover { background:#fff; }

/* floating badge */
.float-badge {
  position:absolute; right:-20px; top:180px;
  background: var(--card); border:1px solid var(--border);
  border-radius:14px; padding:14px 18px;
  box-shadow:0 20px 60px rgba(0,0,0,.6);
  display:flex; align-items:center; gap:12px;
  animation: floatBadge 5s ease-in-out infinite 1s;
  white-space:nowrap;
}
@keyframes floatBadge { 0%,100%{transform:translateX(0);} 50%{transform:translateX(6px);} }
.badge-icon { font-size:24px; }
.badge-text .bval { font-family:var(--font-mono); font-size:16px; font-weight:500; color:var(--accent); }
.badge-text .blbl { font-size:10px; color:var(--muted); letter-spacing:.08em; }

.float-badge2 {
  position:absolute; left:-30px; bottom:180px;
  background: var(--card); border:1px solid var(--border);
  border-radius:14px; padding:12px 16px;
  box-shadow:0 20px 60px rgba(0,0,0,.6);
  display:flex; align-items:center; gap:10px;
  animation: floatBadge2 6s ease-in-out infinite;
  white-space:nowrap;
}
@keyframes floatBadge2 { 0%,100%{transform:translateY(0);} 50%{transform:translateY(-8px);} }
.badge-avatar { width:32px; height:32px; border-radius:50%; background:linear-gradient(135deg,#0af,#00e5a0); display:flex; align-items:center; justify-content:center; font-size:14px; font-weight:700; color:#000; flex-shrink:0; }
.badge-text2 .bval2 { font-size:12px; font-weight:500; }
.badge-text2 .blbl2 { font-size:10px; color:var(--muted); }

/* ── SECTION COMMONS ── */
section { position:relative; }
.section-label {
  display:inline-flex; align-items:center; gap:10px;
  font-family:var(--font-mono); font-size:11px; letter-spacing:.2em; text-transform:uppercase;
  color:var(--accent); margin-bottom:20px;
}
.section-label::before { content:''; width:24px; height:1px; background:var(--accent); }
.section-title {
  font-family:var(--font-disp); font-size:clamp(36px,4vw,62px);
  font-weight:700; line-height:1.05; letter-spacing:-.02em; margin-bottom:18px;
}
.section-title em { font-style:italic; color:var(--accent); }
.section-sub { font-size:17px; line-height:1.75; color:var(--muted); max-width:520px; }

/* ── MARQUEE ── */
.marquee-wrap {
  overflow:hidden; border-top:1px solid var(--border); border-bottom:1px solid var(--border);
  padding:18px 0; background:rgba(0,229,160,.03);
}
.marquee-track {
  display:flex; gap:0; animation:marquee 25s linear infinite; width:max-content;
}
.marquee-track:hover { animation-play-state:paused; }
.marquee-item {
  display:inline-flex; align-items:center; gap:14px;
  font-family:var(--font-mono); font-size:13px; padding:0 36px;
  border-right:1px solid var(--border); white-space:nowrap;
}
.marquee-item .ticker { color:var(--muted); font-size:11px; letter-spacing:.1em; }
.marquee-item .price { color:var(--text); font-weight:500; }
.marquee-item .chg { font-size:12px; }
.chg.up { color:var(--accent); }
.chg.dn { color:var(--red); }
@keyframes marquee { from{transform:translateX(0);} to{transform:translateX(-50%);} }

/* ── FEATURES ── */
#features { padding:120px 56px; }
.features-grid {
  display:grid; grid-template-columns:repeat(3,1fr); gap:2px;
  margin-top:70px; border:1px solid var(--border);
}
.feat-card {
  padding:44px 36px; border-right:1px solid var(--border); position:relative; overflow:hidden;
  transition:background .4s;
  cursor:default;
}
.feat-card:last-child { border-right:none; }
.feat-card:hover { background:rgba(0,229,160,.05); }
.feat-card::before {
  content:''; position:absolute; top:0; left:0; right:0; height:2px;
  background:linear-gradient(90deg,transparent,var(--accent),transparent);
  transform:scaleX(0); transform-origin:left;
  transition:transform .6s cubic-bezier(.4,0,.2,1);
}
.feat-card:hover::before { transform:scaleX(1); }

.feat-icon {
  width:52px; height:52px; border:1px solid rgba(0,229,160,.3); border-radius:12px;
  display:flex; align-items:center; justify-content:center; margin-bottom:26px;
  font-size:22px; background:rgba(0,229,160,.08);
  transition:all .35s;
}
.feat-card:hover .feat-icon { background:rgba(0,229,160,.18); transform:scale(1.05); }
.feat-title { font-family:var(--font-disp); font-size:22px; font-weight:600; margin-bottom:14px; }
.feat-desc { font-size:14px; line-height:1.75; color:var(--muted); }
.feat-num {
  position:absolute; bottom:28px; right:28px;
  font-family:var(--font-mono); font-size:11px; color:rgba(0,229,160,.2);
  letter-spacing:.1em;
}

/* ── PERFORMANCE SECTION ── */
#performance {
  padding:120px 56px;
  background: linear-gradient(180deg, transparent, rgba(0,229,160,.025) 50%, transparent);
}
.perf-grid { display:grid; grid-template-columns:1fr 1fr; gap:80px; align-items:start; margin-top:70px; }
.perf-chart-area { position:relative; }
.perf-canvas-wrap {
  background:var(--card); border:1px solid var(--border); border-radius:16px;
  padding:24px 24px 16px; overflow:hidden; position:relative;
}
.perf-canvas-wrap::after {
  content:''; position:absolute; bottom:0; left:0; right:0; height:60px;
  background:linear-gradient(to top,var(--card),transparent); pointer-events:none; z-index:1;
}
canvas#perfChart { width:100%!important; height:280px!important; }
.perf-badges { display:flex; gap:14px; margin-top:18px; flex-wrap:wrap; }
.perf-badge {
  flex:1; min-width:130px; background:var(--card); border:1px solid var(--border);
  border-radius:10px; padding:18px 20px;
}
.perf-badge .pb-val { font-family:var(--font-mono); font-size:24px; font-weight:500; color:var(--accent); }
.perf-badge .pb-lbl { font-size:11px; letter-spacing:.1em; text-transform:uppercase; color:var(--muted); margin-top:4px; }

.perf-right { }
.returns-list { margin-top:24px; }
.return-row {
  display:flex; align-items:center; gap:16px; padding:18px 0;
  border-bottom:1px solid var(--border);
}
.return-row:first-child { border-top:1px solid var(--border); }
.return-period { font-size:13px; color:var(--muted); letter-spacing:.06em; min-width:80px; }
.return-bar-wrap { flex:1; height:4px; background:rgba(255,255,255,.07); border-radius:2px; overflow:hidden; }
.return-bar { height:100%; background:linear-gradient(90deg,var(--accent2),var(--accent)); border-radius:2px; transition:width 1.5s cubic-bezier(.4,0,.2,1); width:0; }
.return-val { font-family:var(--font-mono); font-size:14px; color:var(--accent); min-width:52px; text-align:right; }
.risk-badges { display:flex; gap:12px; margin-top:30px; flex-wrap:wrap; }
.risk-tag {
  display:flex; align-items:center; gap:8px; font-size:12px;
  background:var(--card); border:1px solid var(--border); border-radius:6px;
  padding:10px 16px; color:var(--muted);
}
.risk-tag .dot { width:8px; height:8px; border-radius:50%; }

/* ── REVIEWS ── */
#reviews { padding:120px 56px; }
.reviews-header { display:flex; justify-content:space-between; align-items:flex-end; margin-bottom:70px; flex-wrap:wrap; gap:30px; }
.reviews-rating {
  display:flex; flex-direction:column; align-items:flex-end; gap:8px;
}
.stars { display:flex; gap:4px; }
.star { color:var(--gold); font-size:20px; }
.reviews-rating .big { font-family:var(--font-disp); font-size:52px; font-weight:900; line-height:1; }
.reviews-rating .count { font-size:12px; color:var(--muted); letter-spacing:.08em; }

.reviews-grid { display:grid; grid-template-columns:1fr 1fr 1fr; gap:20px; }
.review-card {
  background:var(--card); border:1px solid var(--border); border-radius:16px;
  padding:32px; display:flex; flex-direction:column; gap:20px;
  transition:all .4s; position:relative; overflow:hidden;
  cursor:default;
}
.review-card:hover { border-color:rgba(0,229,160,.3); transform:translateY(-4px); box-shadow:0 30px 60px rgba(0,0,0,.4); }
.review-card::before { content:'"'; font-family:var(--font-disp); font-size:80px; color:rgba(0,229,160,.08); position:absolute; top:10px; right:20px; line-height:1; }
.review-stars { display:flex; gap:3px; }
.review-star { color:var(--gold); font-size:13px; }
.review-text { font-size:14px; line-height:1.8; color:rgba(240,244,248,.7); flex:1; }
.review-author { display:flex; align-items:center; gap:14px; border-top:1px solid var(--border); padding-top:18px; }
.review-avatar {
  width:42px; height:42px; border-radius:50%; display:flex; align-items:center; justify-content:center;
  font-weight:700; font-size:16px; color:#000; flex-shrink:0;
}
.review-info .name { font-size:14px; font-weight:500; }
.review-info .meta { font-size:11px; color:var(--muted); letter-spacing:.05em; margin-top:2px; }
.review-gain {
  position:absolute; top:22px; right:22px;
  background:rgba(0,229,160,.12); color:var(--accent);
  font-family:var(--font-mono); font-size:12px; font-weight:500;
  padding:4px 10px; border-radius:20px; border:1px solid rgba(0,229,160,.2);
}

/* featured review */
.review-card.featured {
  grid-column: span 2;
  background: linear-gradient(135deg, #0d1420, #111e2a);
  border-color: rgba(0,229,160,.2);
  flex-direction:row; gap:32px;
}
.review-card.featured .review-body { flex:1; display:flex; flex-direction:column; gap:20px; }
.review-card.featured .review-text { font-size:16px; }
.review-chart-mini { width:180px; flex-shrink:0; }
.mini-chart-label { font-size:10px; letter-spacing:.12em; text-transform:uppercase; color:var(--muted); margin-bottom:10px; }
canvas#miniChart { width:180px!important; height:100px!important; }
.mini-gain { font-family:var(--font-mono); font-size:26px; font-weight:500; color:var(--accent); margin-top:8px; }
.mini-gain-lbl { font-size:11px; color:var(--muted); }

/* ── CTA FINAL ── */
#cta-final {
  padding:140px 56px;
  text-align:center;
  position:relative; overflow:hidden;
}
.cta-bg {
  position:absolute; inset:0; z-index:0;
  background: radial-gradient(ellipse 80% 60% at 50% 50%, rgba(0,229,160,.08), transparent);
}
.cta-bg-lines {
  position:absolute; inset:0; z-index:0;
  background-image: repeating-linear-gradient(
    -45deg,
    transparent,
    transparent 60px,
    rgba(0,229,160,.015) 60px,
    rgba(0,229,160,.015) 61px
  );
}
#cta-final .section-label { justify-content:center; }
#cta-final .section-title { font-size:clamp(44px,6vw,90px); max-width:800px; margin:0 auto 30px; }
#cta-final .section-sub { margin:0 auto 50px; text-align:center; }
.cta-actions { display:flex; justify-content:center; align-items:center; gap:24px; flex-wrap:wrap; }
.cta-trust { margin-top:50px; display:flex; justify-content:center; align-items:center; gap:32px; flex-wrap:wrap; }
.trust-item { display:flex; align-items:center; gap:8px; font-size:13px; color:var(--muted); }
.trust-icon { color:var(--accent); font-size:16px; }

/* ── FOOTER ── */
footer {
  padding:56px; border-top:1px solid var(--border);
  display:flex; justify-content:space-between; align-items:center; flex-wrap:wrap; gap:20px;
}
.footer-logo { font-family:var(--font-disp); font-size:20px; font-weight:900; }
.footer-logo span { color:var(--accent); }
.footer-legal { font-size:12px; color:rgba(240,244,248,.25); max-width:500px; line-height:1.6; }
.footer-links { display:flex; gap:28px; list-style:none; }
.footer-links a { font-size:12px; color:var(--muted); text-decoration:none; letter-spacing:.06em; text-transform:uppercase; transition:color .3s; }
.footer-links a:hover { color:var(--text); }

/* ── SCROLL ANIMATIONS ── */
.reveal { opacity:0; transform:translateY(32px); transition:opacity .9s cubic-bezier(.2,.7,.2,1), transform .9s cubic-bezier(.2,.7,.2,1); }
.reveal.in { opacity:1; transform:translateY(0); }
.reveal-delay-1 { transition-delay:.1s; }
.reveal-delay-2 { transition-delay:.22s; }
.reveal-delay-3 { transition-delay:.34s; }
.reveal-delay-4 { transition-delay:.46s; }
.reveal-delay-5 { transition-delay:.58s; }

/* ── RESPONSIVE ── */
@media(max-width:1024px){
  #hero { grid-template-columns:1fr; padding:110px 32px 60px; }
  .hero-right { margin-top:50px; }
  .app-frame { width:min(360px, 80vw); }
  .float-badge, .float-badge2 { display:none; }
  nav { padding:18px 32px; }
  .nav-links { display:none; }
  #features, #performance, #reviews, #cta-final { padding:80px 32px; }
  .features-grid { grid-template-columns:1fr 1fr; }
  .feat-card:nth-child(3) { grid-column:span 2; border-right:none; }
  .perf-grid { grid-template-columns:1fr; gap:40px; }
  .reviews-grid { grid-template-columns:1fr; }
  .review-card.featured { flex-direction:column; grid-column:span 1; }
  .review-chart-mini { width:100%; }
  canvas#miniChart { width:100%!important; }
  footer { padding:32px; }
}
@media(max-width:600px){
  .hero-title { font-size:44px; }
  .features-grid { grid-template-columns:1fr; }
  .feat-card:nth-child(3) { grid-column:span 1; }
  .hero-stats { flex-wrap:wrap; gap:24px; }
  .reviews-header { flex-direction:column; align-items:flex-start; }
  .reviews-rating { align-items:flex-start; }
}
</style>
</head>
<body>

<!-- Custom Cursor -->
<div id="cursor"><div class="dot"></div><div class="ring"></div></div>

<!-- NAVBAR -->
<nav id="navbar">
  <div class="nav-logo">APE<span>X</span></div>
  <ul class="nav-links">
    <li><a href="#features">Funzionalità</a></li>
    <li><a href="#performance">Performance</a></li>
    <li><a href="#reviews">Recensioni</a></li>
  </ul>
  <a href="#cta-final" class="nav-cta">Inizia Gratis</a>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-bg-grid"></div>
  <div class="hero-glow"></div>
  <div class="hero-glow2"></div>

  <div class="hero-left">
    <div class="hero-eyebrow">Wealth Intelligence Platform</div>
    <h1 class="hero-title">
      Investi con<br>
      <em>precisione</em>
      <span class="outline">assoluta</span>
    </h1>
    <p class="hero-desc">
      APEX combina intelligenza artificiale avanzata e analisi dei mercati in tempo reale per massimizzare i tuoi rendimenti con rischio controllato.
    </p>
    <div class="hero-actions">
      <a href="#cta-final" class="btn-primary">
        <svg viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="2"><path d="M3 8h10M9 4l4 4-4 4"/></svg>
        Apri un conto
      </a>
      <a href="#performance" class="btn-ghost">Vedi i risultati <span>→</span></a>
    </div>
    <div class="hero-stats">
      <div class="stat-item"><div class="stat-num" data-count="47">0</div><div class="stat-label">Rendimento medio annuo %</div></div>
      <div class="stat-item"><div class="stat-num" data-count="12400">0</div><div class="stat-label">Investitori attivi</div></div>
      <div class="stat-item"><div class="stat-num" data-count="98">0</div><div class="stat-label">% soddisfazione</div></div>
    </div>
  </div>

  <div class="hero-right">
    <!-- APP MOCKUP -->
    <div class="app-frame" id="appMockup">
      <div class="app-notch"></div>
      <div class="app-header">
        <div class="app-greeting">Buongiorno, Marco 👋</div>
        <div class="app-name">Portfolio Overview</div>
        <div class="app-balance-wrap">
          <div class="app-balance-label">Balance Totale</div>
          <div class="app-balance">
            <span class="currency">€</span>
            <span id="balanceNum">0</span>
          </div>
          <div class="app-pnl" id="pnlBadge">
            <span>↑</span> <span id="pnlVal">+€2,847 oggi</span>
          </div>
        </div>
      </div>
      <div class="app-tabs">
        <div class="app-tab active">1S</div>
        <div class="app-tab">1M</div>
        <div class="app-tab">6M</div>
        <div class="app-tab">ALL</div>
      </div>
      <div class="app-chart-wrap">
        <div class="chart-labels">
          <span>Lun</span><span>Mar</span><span>Mer</span><span>Gio</span><span>Ven</span><span>Sab</span><span>Oggi</span>
        </div>
        <canvas id="appChart"></canvas>
      </div>
      <div class="app-portfolio">
        <div class="app-port-title">Asset Allocation</div>
        <div class="port-item">
          <div class="port-dot" style="background:#00e5a0"></div>
          <div class="port-name">S&P 500 ETF</div>
          <div class="port-alloc">45%</div>
          <div class="port-val">€31.204</div>
          <div class="port-chg up">+2.1%</div>
        </div>
        <div class="port-item">
          <div class="port-dot" style="background:#0af"></div>
          <div class="port-name">Tech Growth</div>
          <div class="port-alloc">30%</div>
          <div class="port-val">€20.803</div>
          <div class="port-chg up">+4.7%</div>
        </div>
        <div class="port-item">
          <div class="port-dot" style="background:#e8c96d"></div>
          <div class="port-name">Gold &amp; Comm.</div>
          <div class="port-alloc">15%</div>
          <div class="port-val">€10.401</div>
          <div class="port-chg dn">-0.3%</div>
        </div>
        <div class="port-item">
          <div class="port-dot" style="background:#a78bfa"></div>
          <div class="port-name">Bond Blend</div>
          <div class="port-alloc">10%</div>
          <div class="port-val">€6.934</div>
          <div class="port-chg up">+0.8%</div>
        </div>
      </div>
      <div class="app-cta-strip">
        <div class="app-cta-icon">⚡</div>
        <div class="app-cta-text"><strong>Opportunità rilevata</strong>NVDA +3.2% pre-mercato</div>
        <button class="app-cta-btn">Compra</button>
      </div>
    </div>

    <!-- Floating badges -->
    <div class="float-badge">
      <div class="badge-icon">📈</div>
      <div class="badge-text">
        <div class="bval">+€18.342</div>
        <div class="blbl">Guadagno totale</div>
      </div>
    </div>
    <div class="float-badge2">
      <div class="badge-avatar">M</div>
      <div class="badge-text2">
        <div class="bval2">Marco ha appena guadagnato</div>
        <div class="blbl2">+€1.204 · 2 min fa</div>
      </div>
    </div>
  </div>
</section>

<!-- MARQUEE TICKER -->
<div class="marquee-wrap">
  <div class="marquee-track" id="ticker"></div>
</div>

<!-- FEATURES -->
<section id="features">
  <div class="section-label reveal">Perché APEX</div>
  <div class="section-title reveal reveal-delay-1">Tecnologia <em>next-gen</em><br>per investitori seri</div>
  <div class="features-grid">
    <div class="feat-card reveal">
      <div class="feat-icon">🤖</div>
      <div class="feat-title">AI Portfolio Manager</div>
      <div class="feat-desc">Il nostro algoritmo monitora 4.000+ asset in tempo reale e ribilancia automaticamente il tuo portafoglio per massimizzare il rendimento risk-adjusted.</div>
      <div class="feat-num">01</div>
    </div>
    <div class="feat-card reveal reveal-delay-1">
      <div class="feat-icon">⚡</div>
      <div class="feat-title">Esecuzione Fulminea</div>
      <div class="feat-desc">Ordini eseguiti in meno di 12ms con accesso diretto ai mercati globali. Nessun intermediario, nessun ritardo, massima efficienza.</div>
      <div class="feat-num">02</div>
    </div>
    <div class="feat-card reveal reveal-delay-2">
      <div class="feat-icon">🔒</div>
      <div class="feat-title">Sicurezza Militare</div>
      <div class="feat-desc">Crittografia AES-256, autenticazione biometrica e cold storage per il 95% degli asset. I tuoi fondi sono al sicuro, sempre.</div>
      <div class="feat-num">03</div>
    </div>
  </div>
</section>

<!-- PERFORMANCE -->
<section id="performance">
  <div class="section-label reveal">Risultati verificati</div>
  <div class="section-title reveal reveal-delay-1">Performance <em>reale,</em><br>non promesse</div>
  <div class="perf-grid">
    <div class="perf-chart-area reveal">
      <div class="perf-canvas-wrap">
        <canvas id="perfChart"></canvas>
      </div>
      <div class="perf-badges">
        <div class="perf-badge">
          <div class="pb-val">+47%</div>
          <div class="pb-lbl">Rendimento 2024</div>
        </div>
        <div class="perf-badge">
          <div class="pb-val" style="color:var(--accent2)">0.82</div>
          <div class="pb-lbl">Sharpe Ratio</div>
        </div>
        <div class="perf-badge">
          <div class="pb-val" style="color:var(--gold)">-8.2%</div>
          <div class="pb-lbl">Max Drawdown</div>
        </div>
      </div>
    </div>
    <div class="perf-right reveal reveal-delay-2">
      <div class="section-sub">Performance storiche auditate e verificate da terze parti indipendenti.</div>
      <div class="returns-list" id="returnsList">
        <div class="return-row"><span class="return-period">7 Giorni</span><div class="return-bar-wrap"><div class="return-bar" data-w="15"></div></div><span class="return-val">+1.8%</span></div>
        <div class="return-row"><span class="return-period">1 Mese</span><div class="return-bar-wrap"><div class="return-bar" data-w="32"></div></div><span class="return-val">+6.4%</span></div>
        <div class="return-row"><span class="return-period">3 Mesi</span><div class="return-bar-wrap"><div class="return-bar" data-w="55"></div></div><span class="return-val">+14.2%</span></div>
        <div class="return-row"><span class="return-period">6 Mesi</span><div class="return-bar-wrap"><div class="return-bar" data-w="68"></div></div><span class="return-val">+22.7%</span></div>
        <div class="return-row"><span class="return-period">1 Anno</span><div class="return-bar-wrap"><div class="return-bar" data-w="88"></div></div><span class="return-val">+47.0%</span></div>
      </div>
      <div class="risk-badges">
        <div class="risk-tag"><div class="dot" style="background:var(--accent)"></div>Bassa volatilità</div>
        <div class="risk-tag"><div class="dot" style="background:var(--accent2)"></div>Diversificato</div>
        <div class="risk-tag"><div class="dot" style="background:var(--gold)"></div>Liquidità totale</div>
        <div class="risk-tag"><div class="dot" style="background:#a78bfa"></div>Regolamentato</div>
      </div>
    </div>
  </div>
</section>

<!-- REVIEWS -->
<section id="reviews">
  <div class="reviews-header">
    <div>
      <div class="section-label reveal">Testimonianze</div>
      <div class="section-title reveal reveal-delay-1">Cosa dicono<br>i nostri <em>clienti</em></div>
    </div>
    <div class="reviews-rating reveal">
      <div class="big">4.9</div>
      <div class="stars">
        <span class="star">★</span><span class="star">★</span><span class="star">★</span>
        <span class="star">★</span><span class="star" style="opacity:.6">★</span>
      </div>
      <div class="count">Basato su 2.847 recensioni</div>
    </div>
  </div>

  <div class="reviews-grid">

    <!-- FEATURED -->
    <div class="review-card featured reveal">
      <div class="review-body">
        <div class="review-stars">
          <span class="review-star">★</span><span class="review-star">★</span><span class="review-star">★</span>
          <span class="review-star">★</span><span class="review-star">★</span>
        </div>
        <p class="review-text">
          "Ho iniziato con €10.000 a gennaio 2024. Oggi il mio portafoglio vale €14.700. APEX ha completamente cambiato il mio approccio agli investimenti — l'AI gestisce tutto mentre io vivo la mia vita. La dashboard è una gioia da usare ogni mattina."
        </p>
        <div class="review-author">
          <div class="review-avatar" style="background:linear-gradient(135deg,#00e5a0,#0af)">L</div>
          <div class="review-info">
            <div class="name">Luca Ferrari</div>
            <div class="meta">Ingegnere · Milano · Cliente da 14 mesi</div>
          </div>
        </div>
      </div>
      <div class="review-chart-mini">
        <div class="mini-chart-label">Il suo portafoglio</div>
        <canvas id="miniChart"></canvas>
        <div class="mini-gain">+47%</div>
        <div class="mini-gain-lbl">Rendimento totale</div>
      </div>
    </div>

    <!-- REGULAR -->
    <div class="review-card reveal reveal-delay-1">
      <div class="review-gain">+€8.200</div>
      <div class="review-stars">
        <span class="review-star">★</span><span class="review-star">★</span><span class="review-star">★</span>
        <span class="review-star">★</span><span class="review-star">★</span>
      </div>
      <p class="review-text">"Finalmente una piattaforma che capisce cosa voglio. Niente grafici complicati, solo risultati chiari. In 8 mesi ho guadagnato più che con la mia banca in 5 anni."</p>
      <div class="review-author">
        <div class="review-avatar" style="background:linear-gradient(135deg,#e8c96d,#f97316)">S</div>
        <div class="review-info">
          <div class="name">Sofia Ricci</div>
          <div class="meta">Medico · Roma · Cliente da 8 mesi</div>
        </div>
      </div>
    </div>

    <div class="review-card reveal reveal-delay-2">
      <div class="review-gain">+€22.400</div>
      <div class="review-stars">
        <span class="review-star">★</span><span class="review-star">★</span><span class="review-star">★</span>
        <span class="review-star">★</span><span class="review-star">★</span>
      </div>
      <p class="review-text">"Il supporto clienti è eccezionale, rispondono in 5 minuti. Ho mosso €50k da un fondo tradizionale e non potrei essere più soddisfatto. L'AI di APEX è semplicemente un'altra categoria."</p>
      <div class="review-author">
        <div class="review-avatar" style="background:linear-gradient(135deg,#a78bfa,#0af)">M</div>
        <div class="review-info">
          <div class="name">Marco Bianchi</div>
          <div class="meta">Imprenditore · Torino · Cliente da 2 anni</div>
        </div>
      </div>
    </div>

    <div class="review-card reveal reveal-delay-1">
      <div class="review-gain">+€3.100</div>
      <div class="review-stars">
        <span class="review-star">★</span><span class="review-star">★</span><span class="review-star">★</span>
        <span class="review-star">★</span><span class="review-star" style="opacity:.5">★</span>
      </div>
      <p class="review-text">"Ero scettica sull'AI per gli investimenti. Dopo 6 mesi devo ammettere che funziona davvero. Il mio portafoglio diversificato cresce in modo costante e dormire tranquilla non ha prezzo."</p>
      <div class="review-author">
        <div class="review-avatar" style="background:linear-gradient(135deg,#f43f5e,#e8c96d)">A</div>
        <div class="review-info">
          <div class="name">Anna Colombo</div>
          <div class="meta">Designer · Venezia · Cliente da 6 mesi</div>
        </div>
      </div>
    </div>

    <div class="review-card reveal reveal-delay-2">
      <div class="review-gain">+€41.800</div>
      <div class="review-stars">
        <span class="review-star">★</span><span class="review-star">★</span><span class="review-star">★</span>
        <span class="review-star">★</span><span class="review-star">★</span>
      </div>
      <p class="review-text">"Gestisco un portafoglio da €200k su APEX. La reportistica è professionale, l'analisi fiscale è integrata, e il rendimento parla da solo. È diventato lo strumento principale della mia gestione patrimoniale."</p>
      <div class="review-author">
        <div class="review-avatar" style="background:linear-gradient(135deg,#0af,#00e5a0)">G</div>
        <div class="review-info">
          <div class="name">Giorgio Mancini</div>
          <div class="meta">Avvocato · Firenze · Cliente da 3 anni</div>
        </div>
      </div>
    </div>

  </div>
</section>

<!-- CTA FINAL -->
<section id="cta-final">
  <div class="cta-bg"></div>
  <div class="cta-bg-lines"></div>
  <div style="position:relative;z-index:1;">
    <div class="section-label reveal">Inizia oggi</div>
    <h2 class="section-title reveal reveal-delay-1">Fai lavorare<br>i tuoi soldi per <em>te</em></h2>
    <p class="section-sub reveal reveal-delay-2">Apertura del conto gratuita in 3 minuti. Deposito minimo €500. Nessun costo nascosto.</p>
    <div class="cta-actions reveal reveal-delay-3">
      <a href="#" class="btn-primary" style="font-size:16px;padding:18px 46px;">
        <svg viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="2"><path d="M3 8h10M9 4l4 4-4 4"/></svg>
        Apri il tuo conto gratis
      </a>
      <a href="#" class="btn-ghost" style="font-size:14px;">Scopri i piani <span>→</span></a>
    </div>
    <div class="cta-trust reveal reveal-delay-4">
      <div class="trust-item"><span class="trust-icon">✓</span> Regolamentato CONSOB</div>
      <div class="trust-item"><span class="trust-icon">✓</span> Fondi assicurati fino a €100k</div>
      <div class="trust-item"><span class="trust-icon">✓</span> Prelievo in 24h</div>
      <div class="trust-item"><span class="trust-icon">✓</span> Nessuna commissione di gestione</div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-logo">APE<span>X</span></div>
  <ul class="footer-links">
    <li><a href="#">Privacy</a></li>
    <li><a href="#">Termini</a></li>
    <li><a href="#">Rischi</a></li>
    <li><a href="#">Contatti</a></li>
  </ul>
  <p class="footer-legal">Investire comporta rischi, inclusa la possibile perdita del capitale. I rendimenti passati non garantiscono rendimenti futuri. APEX è autorizzata e regolamentata dalla CONSOB.</p>
</footer>

<!-- CHART.JS CDN -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.min.js"></script>

<script>
/* ═══════════════════════════════════
   CURSOR
════════════════════════════════════ */
const cursor = document.getElementById('cursor');
const dot = cursor.querySelector('.dot');
const ring = cursor.querySelector('.ring');
let mx=0,my=0,rx=0,ry=0;
document.addEventListener('mousemove',e=>{mx=e.clientX;my=e.clientY;dot.style.left=mx+'px';dot.style.top=my+'px';});
(function animRing(){rx+=(mx-rx)*.12;ry+=(my-ry)*.12;ring.style.left=rx+'px';ring.style.top=ry+'px';requestAnimationFrame(animRing);})();
document.querySelectorAll('a,button,.feat-card,.review-card,.swatch,.flip,.sizecol').forEach(el=>{
  el.addEventListener('mouseenter',()=>{ring.style.width='60px';ring.style.height='60px';ring.style.background='rgba(0,229,160,.1)';});
  el.addEventListener('mouseleave',()=>{ring.style.width='40px';ring.style.height='40px';ring.style.background='transparent';});
});

/* ═══════════════════════════════════
   NAVBAR SCROLL
════════════════════════════════════ */
window.addEventListener('scroll',()=>{
  document.getElementById('navbar').classList.toggle('scrolled',window.scrollY>60);
});

/* ═══════════════════════════════════
   COUNTER ANIMATION
════════════════════════════════════ */
function animateCounter(el,target,suffix){
  let v=0;const dur=2200,start=performance.now();
  const step=(now)=>{const p=Math.min((now-start)/dur,1);const ease=1-Math.pow(1-p,4);v=Math.round(ease*target);
    el.textContent=(v>=1000?v.toLocaleString('it-IT'):v)+(suffix||'');
    if(p<1)requestAnimationFrame(step);};
  requestAnimationFrame(step);
}
const statNums=document.querySelectorAll('[data-count]');
const statObs=new IntersectionObserver(entries=>{entries.forEach(e=>{if(e.isIntersecting){const t=+e.target.dataset.count;const s=t>1000?'+':'';animateCounter(e.target,t,s==='+'?'%':'');e.target.closest('.stat-item').querySelector('.stat-label').textContent.includes('%')&&(e.target.textContent=t+'%');statObs.unobserve(e.target);}});},{threshold:.5});
statNums.forEach(n=>statObs.observe(n));

/* ═══════════════════════════════════
   BALANCE COUNTER
════════════════════════════════════ */
function animBalance(){
  const el=document.getElementById('balanceNum');
  let v=0;const target=69342;const dur=2400;const start=performance.now();
  const step=(now)=>{const p=Math.min((now-start)/dur,1);const ease=1-Math.pow(1-p,4);v=Math.round(ease*target);
    el.textContent=v.toLocaleString('it-IT');if(p<1)requestAnimationFrame(step);};
  requestAnimationFrame(step);
}
window.addEventListener('load',()=>setTimeout(animBalance,600));

/* ═══════════════════════════════════
   APP CHART (line)
════════════════════════════════════ */
const appCtx=document.getElementById('appChart').getContext('2d');
const appGrad=appCtx.createLinearGradient(0,0,0,140);
appGrad.addColorStop(0,'rgba(0,229,160,.25)');
appGrad.addColorStop(1,'rgba(0,229,160,0)');
const appChartData={
  labels:['Lun','Mar','Mer','Gio','Ven','Sab','Oggi'],
  datasets:[{
    data:[62100,63400,61800,64200,65800,67200,69342],
    borderColor:'#00e5a0',borderWidth:2,
    backgroundColor:appGrad,fill:true,tension:.42,
    pointRadius:3,pointBackgroundColor:'#00e5a0',pointBorderColor:'#111820',pointBorderWidth:2,
    pointHoverRadius:6,
  }]
};
new Chart(appCtx,{type:'line',data:appChartData,options:{
  responsive:true,maintainAspectRatio:false,
  plugins:{legend:{display:false},tooltip:{
    backgroundColor:'rgba(13,17,23,.95)',borderColor:'rgba(0,229,160,.3)',borderWidth:1,
    titleColor:'#00e5a0',bodyColor:'#f0f4f8',
    callbacks:{label:(c)=>'€ '+c.parsed.y.toLocaleString('it-IT')}
  }},
  scales:{
    x:{grid:{color:'rgba(255,255,255,.04)',drawBorder:false},ticks:{color:'rgba(240,244,248,.4)',font:{size:9},maxRotation:0}},
    y:{display:false,grid:{display:false}},
  },
  animation:{duration:1800,easing:'easeInOutQuart'},
}});

/* ═══════════════════════════════════
   TABS
════════════════════════════════════ */
const tabData={
  '1S':{labels:['Lun','Mar','Mer','Gio','Ven','Sab','Oggi'],data:[62100,63400,61800,64200,65800,67200,69342]},
  '1M':{labels:['1A','1S','2S','3S','4S','Oggi'],data:[58000,59800,61200,63400,66100,69342]},
  '6M':{labels:['Gen','Feb','Mar','Apr','Mag','Giu'],data:[48000,51200,54800,58200,63100,69342]},
  'ALL':{labels:['2021','2022','2023','2024','2025'],data:[20000,24500,32100,47200,69342]},
};
document.querySelectorAll('.app-tab').forEach(tab=>{
  tab.addEventListener('click',()=>{
    document.querySelectorAll('.app-tab').forEach(t=>t.classList.remove('active'));
    tab.classList.add('active');
    const d=tabData[tab.textContent];
    appChartData.labels=d.labels;
    appChartData.datasets[0].data=d.data;
    Chart.getChart(appCtx).update();
  });
});

/* ═══════════════════════════════════
   PERFORMANCE CHART
════════════════════════════════════ */
const perfCtx=document.getElementById('perfChart').getContext('2d');
const perfGrad=perfCtx.createLinearGradient(0,0,0,280);
perfGrad.addColorStop(0,'rgba(0,170,255,.2)');
perfGrad.addColorStop(.5,'rgba(0,229,160,.1)');
perfGrad.addColorStop(1,'rgba(0,229,160,0)');

const months=['Gen','Feb','Mar','Apr','Mag','Giu','Lug','Ago','Set','Ott','Nov','Dic'];
const perfData=[100,104,109,107,114,119,116,124,131,138,143,147];
const benchData=[100,102,104,103,106,108,107,110,112,113,115,116];

new Chart(perfCtx,{type:'line',data:{
  labels:months,
  datasets:[
    {label:'APEX',data:perfData,borderColor:'#00e5a0',borderWidth:2.5,backgroundColor:perfGrad,fill:true,tension:.42,pointRadius:0,pointHoverRadius:5,pointHoverBackgroundColor:'#00e5a0'},
    {label:'S&P 500',data:benchData,borderColor:'rgba(0,170,255,.6)',borderWidth:1.5,backgroundColor:'transparent',fill:false,tension:.42,pointRadius:0,pointHoverRadius:4,borderDash:[4,4]},
  ]
},options:{
  responsive:true,maintainAspectRatio:false,
  plugins:{
    legend:{position:'top',align:'end',labels:{color:'rgba(240,244,248,.5)',font:{size:11},boxWidth:24,boxHeight:2,usePointStyle:false}},
    tooltip:{backgroundColor:'rgba(13,17,23,.95)',borderColor:'rgba(0,229,160,.2)',borderWidth:1,titleColor:'#00e5a0',bodyColor:'#f0f4f8',callbacks:{label:(c)=>c.dataset.label+': '+c.parsed.y+'%'}}
  },
  scales:{
    x:{grid:{color:'rgba(255,255,255,.04)',drawBorder:false},ticks:{color:'rgba(240,244,248,.4)',font:{size:10}}},
    y:{grid:{color:'rgba(255,255,255,.04)',drawBorder:false},ticks:{color:'rgba(240,244,248,.4)',font:{size:10},callback:v=>v+'%'}},
  },
  animation:{duration:2000,easing:'easeInOutQuart'},
}});

/* ═══════════════════════════════════
   MINI CHART (review)
════════════════════════════════════ */
const miniCtx=document.getElementById('miniChart').getContext('2d');
const miniGrad=miniCtx.createLinearGradient(0,0,0,100);
miniGrad.addColorStop(0,'rgba(0,229,160,.3)');
miniGrad.addColorStop(1,'rgba(0,229,160,0)');
new Chart(miniCtx,{type:'line',data:{
  labels:Array.from({length:14},(_,i)=>i),
  datasets:[{data:[100,102,101,105,108,107,112,116,118,122,125,130,138,147],
    borderColor:'#00e5a0',borderWidth:2,backgroundColor:miniGrad,fill:true,tension:.5,
    pointRadius:0,}]
},options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false},tooltip:{enabled:false}},
  scales:{x:{display:false},y:{display:false}},animation:{duration:2000}}});

/* ═══════════════════════════════════
   TICKER MARQUEE
════════════════════════════════════ */
const tickers=[
  {sym:'AAPL',price:'$213.45',chg:'+1.2%',up:true},{sym:'NVDA',price:'$892.30',chg:'+3.4%',up:true},
  {sym:'MSFT',price:'$418.70',chg:'+0.8%',up:true},{sym:'BTC',price:'$67.420',chg:'-0.6%',up:false},
  {sym:'ETH',price:'$3.241',chg:'+2.1%',up:true},{sym:'TSLA',price:'$247.15',chg:'+1.9%',up:true},
  {sym:'AMZN',price:'$185.40',chg:'+0.5%',up:true},{sym:'META',price:'$524.80',chg:'+2.7%',up:true},
  {sym:'GOLD',price:'$2.318',chg:'-0.3%',up:false},{sym:'SPX',price:'5.412',chg:'+0.9%',up:true},
];
const track=document.getElementById('ticker');
const html=tickers.map(t=>`<div class="marquee-item"><span class="ticker">${t.sym}</span><span class="price">${t.price}</span><span class="chg ${t.up?'up':'dn'}">${t.chg}</span></div>`).join('');
track.innerHTML=html+html; // duplicate for seamless loop

/* ═══════════════════════════════════
   SCROLL REVEAL
════════════════════════════════════ */
const revealObs=new IntersectionObserver(entries=>{
  entries.forEach(e=>{if(e.isIntersecting){e.target.classList.add('in');revealObs.unobserve(e.target);}});
},{threshold:.15,rootMargin:'0px 0px -60px 0px'});
document.querySelectorAll('.reveal').forEach(el=>revealObs.observe(el));

/* ═══════════════════════════════════
   RETURN BARS ANIMATE
════════════════════════════════════ */
const barObs=new IntersectionObserver(entries=>{
  entries.forEach(e=>{if(e.isIntersecting){
    e.target.querySelectorAll('.return-bar').forEach(bar=>{
      bar.style.width=bar.dataset.w+'%';
    });
    barObs.unobserve(e.target);
  }});
},{threshold:.3});
const returnsList=document.getElementById('returnsList');
if(returnsList)barObs.observe(returnsList);

/* ═══════════════════════════════════
   LIVE PRICE FLICKER (mockup effect)
════════════════════════════════════ */
const portVals=document.querySelectorAll('.port-val');
setInterval(()=>{
  const idx=Math.floor(Math.random()*portVals.length);
  const el=portVals[idx];
  el.style.color='var(--accent)';
  setTimeout(()=>el.style.color='',600);
},2800);

/* PNL badge micro-update */
const pnlVal=document.getElementById('pnlVal');
const pnls=['+€2,847 oggi','+€2,912 oggi','+€2,781 oggi','+€3,014 oggi'];
let pi=0;
setInterval(()=>{pi=(pi+1)%pnls.length;pnlVal.textContent=pnls[pi];},5000);
</script>
</body>
</html>
