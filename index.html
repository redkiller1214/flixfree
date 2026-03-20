<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>FlixFree — Watch Movies Free</title>
  <link rel="preconnect" href="https://fonts.googleapis.com"/>
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet"/>
  <style>
    /* ── Reset ── */
    *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }
 
    :root {
      --red:     #e50914;
      --red-dk:  #b0070f;
      --bg:      #080808;
      --bg2:     #111111;
      --bg3:     #1a1a1a;
      --border:  rgba(255,255,255,0.08);
      --muted:   rgba(255,255,255,0.45);
      --text:    #f0f0f0;
      --gold:    #f5c518;
      --green:   #21a621;
      --green-t: #6ef06e;
    }
 
    html { scroll-behavior: smooth; }
 
    body {
      background: var(--bg);
      color: var(--text);
      font-family: 'DM Sans', sans-serif;
      min-height: 100vh;
      cursor: default;
    }
 
    /* ── Scrollbar ── */
    ::-webkit-scrollbar { width: 6px; }
    ::-webkit-scrollbar-track { background: var(--bg); }
    ::-webkit-scrollbar-thumb { background: #333; border-radius: 3px; }
 
    /* ══════════════════════════════
       NAVBAR
    ══════════════════════════════ */
    .navbar {
      position: sticky;
      top: 0;
      z-index: 200;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 14px 32px;
      background: rgba(8,8,8,0.92);
      backdrop-filter: blur(12px);
      border-bottom: 1px solid var(--border);
      gap: 16px;
      flex-wrap: wrap;
    }
 
    .logo {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 38px;
      letter-spacing: 3px;
      color: var(--red);
      text-shadow: 0 0 30px rgba(229,9,20,0.4);
      user-select: none;
    }
    .logo span { color: #fff; }
 
    .search-wrap {
      display: flex;
      align-items: center;
      gap: 10px;
      background: rgba(255,255,255,0.06);
      border: 1px solid rgba(255,255,255,0.12);
      border-radius: 10px;
      padding: 9px 16px;
      width: 300px;
      transition: border-color 0.2s, background 0.2s;
    }
    .search-wrap:focus-within {
      border-color: var(--red);
      background: rgba(255,255,255,0.09);
    }
    .search-wrap svg { flex-shrink: 0; }
    .search-wrap input {
      background: none;
      border: none;
      outline: none;
      color: #fff;
      font-size: 14px;
      font-family: 'DM Sans', sans-serif;
      width: 100%;
    }
    .search-wrap input::placeholder { color: var(--muted); }
 
    .nav-right { display: flex; align-items: center; gap: 12px; }
    .title-count { font-size: 13px; color: var(--muted); }
    .free-badge {
      background: var(--red);
      color: #fff;
      font-size: 11px;
      font-weight: 600;
      padding: 4px 10px;
      border-radius: 5px;
      letter-spacing: 0.5px;
    }
 
    /* ══════════════════════════════
       HERO
    ══════════════════════════════ */
    .hero {
      position: relative;
      padding: 52px 32px 36px;
      overflow: hidden;
      background: radial-gradient(ellipse 80% 60% at 15% 60%, rgba(229,9,20,0.18) 0%, transparent 65%),
                  linear-gradient(160deg, #130000 0%, #0a0a0a 50%, #080808 100%);
    }
 
    /* animated grain overlay */
    .hero::after {
      content: '';
      position: absolute;
      inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
      pointer-events: none;
      opacity: 0.4;
    }
 
    .hero-inner { position: relative; z-index: 1; max-width: 560px; }
 
    .eyebrow {
      display: inline-flex;
      align-items: center;
      gap: 7px;
      font-size: 11px;
      font-weight: 600;
      letter-spacing: 2.5px;
      text-transform: uppercase;
      color: var(--red);
      margin-bottom: 14px;
    }
    .eyebrow::before {
      content: '';
      width: 24px;
      height: 2px;
      background: var(--red);
      border-radius: 1px;
    }
 
    .hero-title {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 68px;
      line-height: 0.95;
      margin-bottom: 16px;
      letter-spacing: 1px;
    }
    .hero-title em {
      color: var(--red);
      font-style: normal;
    }
 
    .hero-sub {
      font-size: 15px;
      color: var(--muted);
      line-height: 1.7;
      max-width: 440px;
      margin-bottom: 24px;
    }
 
    .hero-stats {
      display: flex;
      gap: 32px;
    }
    .stat-item { text-align: left; }
    .stat-num {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 34px;
      color: #fff;
      line-height: 1;
    }
    .stat-num span { color: var(--red); }
    .stat-label { font-size: 11px; color: var(--muted); margin-top: 2px; letter-spacing: 1px; text-transform: uppercase; }
 
    /* ══════════════════════════════
       CATEGORY BAR
    ══════════════════════════════ */
    .cat-bar {
      display: flex;
      gap: 8px;
      padding: 18px 32px;
      overflow-x: auto;
      scrollbar-width: none;
      border-bottom: 1px solid var(--border);
      background: var(--bg2);
    }
    .cat-bar::-webkit-scrollbar { display: none; }
 
    .cat-btn {
      background: transparent;
      border: 1px solid rgba(255,255,255,0.1);
      color: var(--muted);
      padding: 7px 18px;
      border-radius: 99px;
      font-size: 13px;
      font-family: 'DM Sans', sans-serif;
      font-weight: 500;
      cursor: pointer;
      white-space: nowrap;
      transition: all 0.2s;
    }
    .cat-btn:hover { border-color: rgba(229,9,20,0.5); color: #fff; background: rgba(229,9,20,0.08); }
    .cat-btn.active { background: var(--red); border-color: var(--red); color: #fff; }
 
    /* ══════════════════════════════
       SECTION
    ══════════════════════════════ */
    .section { padding: 28px 32px 60px; }
 
    .section-head {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 20px;
    }
    .section-title {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 26px;
      letter-spacing: 1px;
      display: flex;
      align-items: center;
      gap: 12px;
    }
    .count-pill {
      font-family: 'DM Sans', sans-serif;
      font-size: 12px;
      font-weight: 400;
      background: rgba(255,255,255,0.08);
      color: var(--muted);
      padding: 3px 10px;
      border-radius: 99px;
    }
 
    /* ══════════════════════════════
       GRID
    ══════════════════════════════ */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(155px, 1fr));
      gap: 14px;
    }
 
    /* ── Card ── */
    .card {
      background: var(--bg3);
      border-radius: 10px;
      overflow: hidden;
      cursor: pointer;
      position: relative;
      transition: transform 0.25s cubic-bezier(.22,.61,.36,1), box-shadow 0.25s;
      border: 1px solid transparent;
      animation: fadeUp 0.4s ease both;
    }
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(14px); }
      to   { opacity: 1; transform: translateY(0); }
    }
    .card:hover {
      transform: scale(1.06) translateY(-3px);
      box-shadow: 0 16px 40px rgba(229,9,20,0.25);
      border-color: rgba(229,9,20,0.3);
      z-index: 2;
    }
 
    .thumb {
      width: 100%;
      aspect-ratio: 2/3;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 46px;
      position: relative;
      background: linear-gradient(140deg, #1c1c2e 0%, #16213e 60%, #0f3460 100%);
    }
 
    .play-ov {
      position: absolute;
      inset: 0;
      background: rgba(0,0,0,0.55);
      display: flex;
      align-items: center;
      justify-content: center;
      opacity: 0;
      transition: opacity 0.2s;
    }
    .card:hover .play-ov { opacity: 1; }
 
    .play-circle {
      width: 52px;
      height: 52px;
      background: var(--red);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 0 0 8px rgba(229,9,20,0.2);
      transform: scale(0.85);
      transition: transform 0.2s;
    }
    .card:hover .play-circle { transform: scale(1); }
 
    .card-info { padding: 11px 12px 12px; }
    .card-title {
      font-size: 13px;
      font-weight: 500;
      white-space: nowrap;
      overflow: hidden;
      text-overflow: ellipsis;
      margin-bottom: 6px;
      color: #fff;
    }
    .card-meta {
      display: flex;
      align-items: center;
      gap: 7px;
      font-size: 11px;
      color: var(--muted);
    }
    .rating { color: var(--gold); font-weight: 600; }
    .free-tag {
      background: var(--green);
      color: var(--green-t);
      font-size: 9px;
      font-weight: 700;
      padding: 2px 6px;
      border-radius: 4px;
      letter-spacing: 0.5px;
    }
 
    /* ── Empty state ── */
    .empty {
      text-align: center;
      padding: 80px 24px;
      color: var(--muted);
    }
    .empty .big { font-size: 48px; margin-bottom: 14px; }
    .empty p { font-size: 15px; }
 
    /* ══════════════════════════════
       MODAL
    ══════════════════════════════ */
    .modal-bg {
      display: none;
      position: fixed;
      inset: 0;
      background: rgba(0,0,0,0.9);
      z-index: 999;
      align-items: center;
      justify-content: center;
      padding: 20px;
      backdrop-filter: blur(4px);
    }
    .modal-bg.open { display: flex; }
 
    .modal {
      background: #161616;
      border: 1px solid rgba(255,255,255,0.1);
      border-radius: 16px;
      max-width: 480px;
      width: 100%;
      padding: 32px;
      position: relative;
      animation: popIn 0.25s cubic-bezier(.22,.61,.36,1);
    }
    @keyframes popIn {
      from { opacity: 0; transform: scale(0.92) translateY(20px); }
      to   { opacity: 1; transform: scale(1) translateY(0); }
    }
 
    .modal-close {
      position: absolute;
      top: 16px;
      right: 18px;
      background: rgba(255,255,255,0.08);
      border: none;
      color: var(--muted);
      width: 32px;
      height: 32px;
      border-radius: 50%;
      font-size: 16px;
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: background 0.2s, color 0.2s;
    }
    .modal-close:hover { background: rgba(255,255,255,0.15); color: #fff; }
 
    .modal-emoji { font-size: 56px; margin-bottom: 16px; display: block; }
    .modal-title {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 34px;
      letter-spacing: 1px;
      margin-bottom: 10px;
      line-height: 1;
    }
    .modal-meta {
      display: flex;
      gap: 10px;
      flex-wrap: wrap;
      align-items: center;
      font-size: 13px;
      color: var(--muted);
      margin-bottom: 18px;
    }
    .genre-pill {
      background: rgba(255,255,255,0.08);
      border: 1px solid rgba(255,255,255,0.1);
      padding: 3px 10px;
      border-radius: 99px;
      text-transform: capitalize;
      font-size: 12px;
    }
    .modal-desc {
      font-size: 14px;
      color: rgba(255,255,255,0.65);
      line-height: 1.75;
      margin-bottom: 24px;
      border-left: 3px solid var(--red);
      padding-left: 14px;
    }
    .watch-btn {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      background: var(--red);
      color: #fff;
      text-decoration: none;
      padding: 15px;
      border-radius: 10px;
      font-size: 15px;
      font-weight: 600;
      font-family: 'DM Sans', sans-serif;
      letter-spacing: 0.3px;
      transition: background 0.2s, transform 0.15s;
    }
    .watch-btn:hover { background: #f40612; transform: translateY(-1px); }
    .watch-btn:active { transform: translateY(0); }
    .modal-note {
      text-align: center;
      font-size: 11px;
      color: rgba(255,255,255,0.22);
      margin-top: 12px;
      letter-spacing: 0.3px;
    }
 
    /* ══════════════════════════════
       RESPONSIVE
    ══════════════════════════════ */
    @media (max-width: 600px) {
      .navbar { padding: 12px 16px; }
      .search-wrap { width: 220px; }
      .hero { padding: 36px 16px 28px; }
      .hero-title { font-size: 48px; }
      .cat-bar { padding: 14px 16px; }
      .section { padding: 20px 16px 40px; }
      .grid { grid-template-columns: repeat(auto-fill, minmax(130px, 1fr)); gap: 10px; }
      .modal { padding: 24px 20px; }
    }
  </style>
</head>
<body>
 
<!-- ══ NAVBAR ══ -->
<nav class="navbar">
  <div class="logo">FLIX<span>FREE</span></div>
 
  <div class="search-wrap">
    <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="rgba(255,255,255,0.4)" stroke-width="2">
      <circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/>
    </svg>
    <input type="text" id="searchInput" placeholder="Search 80+ titles..." oninput="doFilter()"/>
  </div>
 
  <div class="nav-right">
    <span class="title-count" id="titleCount">80 titles</span>
    <span class="free-badge">100% FREE</span>
  </div>
</nav>
 
<!-- ══ HERO ══ -->
<section class="hero">
  <div class="hero-inner">
    <div class="eyebrow">No subscription needed</div>
    <h1 class="hero-title">Watch <em>Free.</em><br>Watch Now.</h1>
    <p class="hero-sub">80+ movies & web series — all legally free on YouTube. Click any title, get redirected instantly. No signup, no payment, no VPN.</p>
    <div class="hero-stats">
      <div class="stat-item">
        <div class="stat-num">80<span>+</span></div>
        <div class="stat-label">Titles</div>
      </div>
      <div class="stat-item">
        <div class="stat-num">10<span>+</span></div>
        <div class="stat-label">Genres</div>
      </div>
      <div class="stat-item">
        <div class="stat-num">₹<span>0</span></div>
        <div class="stat-label">Cost</div>
      </div>
    </div>
  </div>
</section>
 
<!-- ══ CATEGORY BAR ══ -->
<div class="cat-bar" id="catBar">
  <button class="cat-btn active" onclick="setCat('all',this)">🎬 All</button>
  <button class="cat-btn" onclick="setCat('action',this)">💥 Action</button>
  <button class="cat-btn" onclick="setCat('comedy',this)">😂 Comedy</button>
  <button class="cat-btn" onclick="setCat('drama',this)">🎭 Drama</button>
  <button class="cat-btn" onclick="setCat('thriller',this)">😱 Thriller</button>
  <button class="cat-btn" onclick="setCat('scifi',this)">🚀 Sci-Fi</button>
  <button class="cat-btn" onclick="setCat('horror',this)">👻 Horror</button>
  <button class="cat-btn" onclick="setCat('animation',this)">✨ Animation</button>
  <button class="cat-btn" onclick="setCat('romance',this)">❤️ Romance</button>
  <button class="cat-btn" onclick="setCat('documentary',this)">🎥 Docs</button>
  <button class="cat-btn" onclick="setCat('series',this)">📺 Series</button>
</div>
 
<!-- ══ MOVIES SECTION ══ -->
<section class="section">
  <div class="section-head">
    <div class="section-title" id="sectionTitle">
      🔥 All Titles <span class="count-pill" id="countPill">80</span>
    </div>
  </div>
  <div class="grid" id="grid"></div>
  <div class="empty" id="empty" style="display:none;">
    <div class="big">😕</div>
    <p>No results found. Try a different search!</p>
  </div>
</section>
 
<!-- ══ MODAL ══ -->
<div class="modal-bg" id="modalBg" onclick="if(event.target===this)closeModal()">
  <div class="modal">
    <button class="modal-close" onclick="closeModal()">✕</button>
    <span class="modal-emoji" id="mEmoji"></span>
    <div class="modal-title" id="mTitle"></div>
    <div class="modal-meta" id="mMeta"></div>
    <p class="modal-desc" id="mDesc"></p>
    <a id="watchLink" class="watch-btn" target="_blank" rel="noopener noreferrer">
      <svg width="18" height="18" viewBox="0 0 24 24" fill="white"><path d="M8 5v14l11-7z"/></svg>
      Watch Free on YouTube
    </a>
    <p class="modal-note">Opens YouTube · Legally free · No account needed</p>
  </div>
</div>
 
<script>
  // ── DATA ──
  const movies = [
    {id:1, t:"The Dark Knight",          y:2008, g:"action",      r:"9.0", e:"🦇", d:"Batman faces the Joker in a gripping battle for Gotham's soul.",                        q:"The Dark Knight full movie"},
    {id:2, t:"Inception",                y:2010, g:"scifi",       r:"8.8", e:"🌀", d:"A thief steals secrets through dream-sharing technology.",                              q:"Inception full movie free"},
    {id:3, t:"Interstellar",             y:2014, g:"scifi",       r:"8.6", e:"🚀", d:"Astronauts travel through a wormhole to find a new home for humanity.",                q:"Interstellar full movie"},
    {id:4, t:"The Avengers",             y:2012, g:"action",      r:"8.0", e:"⚡", d:"Earth's mightiest heroes unite to stop an alien invasion.",                            q:"The Avengers 2012 full movie"},
    {id:5, t:"Parasite",                 y:2019, g:"thriller",    r:"8.5", e:"🪲", d:"A poor family schemes to become employed by a wealthy household.",                     q:"Parasite 2019 full movie"},
    {id:6, t:"The Grand Budapest Hotel", y:2014, g:"comedy",      r:"8.1", e:"🏨", d:"A concierge and his lobby boy become embroiled in a wild adventure.",                 q:"The Grand Budapest Hotel full movie"},
    {id:7, t:"Joker",                    y:2019, g:"drama",       r:"8.4", e:"🃏", d:"A failed comedian's descent into madness sparks chaos in Gotham.",                    q:"Joker 2019 full movie"},
    {id:8, t:"Get Out",                  y:2017, g:"horror",      r:"7.7", e:"👁️", d:"A man discovers disturbing secrets about his girlfriend's family.",                   q:"Get Out 2017 full movie"},
    {id:9, t:"Knives Out",               y:2019, g:"thriller",    r:"7.9", e:"🔪", d:"A detective investigates the death of a wealthy family patriarch.",                    q:"Knives Out full movie"},
    {id:10,t:"Soul",                     y:2020, g:"animation",   r:"8.0", e:"🎷", d:"A jazz musician's soul gets separated from his body before his big break.",            q:"Soul 2020 Pixar full movie"},
    {id:11,t:"A Quiet Place",            y:2018, g:"horror",      r:"7.5", e:"🤫", d:"A family must live in silence to survive creatures that hunt by sound.",               q:"A Quiet Place full movie"},
    {id:12,t:"Dune",                     y:2021, g:"scifi",       r:"8.0", e:"🏜️", d:"A noble family's heir navigates a dangerous desert planet with a precious resource.", q:"Dune 2021 full movie"},
    {id:13,t:"Oppenheimer",              y:2023, g:"drama",       r:"8.3", e:"☢️", d:"The story of the man who built the atomic bomb and his moral reckoning.",             q:"Oppenheimer 2023 full movie"},
    {id:14,t:"The Shawshank Redemption", y:1994, g:"drama",       r:"9.3", e:"🔗", d:"Two imprisoned men find redemption through acts of common decency.",                  q:"The Shawshank Redemption full movie"},
    {id:15,t:"Pulp Fiction",             y:1994, g:"thriller",    r:"8.9", e:"💼", d:"Interweaving stories of hitmen, a boxer, and diner bandits.",                         q:"Pulp Fiction full movie"},
    {id:16,t:"Forrest Gump",             y:1994, g:"drama",       r:"8.8", e:"🏃", d:"A slow-witted man witnesses and influences key historical events.",                    q:"Forrest Gump full movie"},
    {id:17,t:"The Matrix",               y:1999, g:"scifi",       r:"8.7", e:"💊", d:"A hacker discovers reality is a simulation and joins a rebellion.",                   q:"The Matrix 1999 full movie"},
    {id:18,t:"Gladiator",                y:2000, g:"action",      r:"8.5", e:"⚔️", d:"A Roman general seeks revenge after being betrayed and enslaved.",                    q:"Gladiator 2000 full movie"},
    {id:19,t:"Titanic",                  y:1997, g:"romance",     r:"7.9", e:"🚢", d:"A poor artist and rich girl fall in love aboard the doomed Titanic.",                 q:"Titanic 1997 full movie"},
    {id:20,t:"The Godfather",            y:1972, g:"drama",       r:"9.2", e:"🌹", d:"The aging patriarch of a crime dynasty transfers control to his son.",                 q:"The Godfather 1972 full movie"},
    {id:21,t:"Fight Club",               y:1999, g:"thriller",    r:"8.8", e:"🥊", d:"An insomniac and a soap salesman build an underground fight club.",                   q:"Fight Club 1999 full movie"},
    {id:22,t:"Whiplash",                 y:2014, g:"drama",       r:"8.5", e:"🥁", d:"An ambitious drummer pursues perfection under a demanding music teacher.",            q:"Whiplash 2014 full movie"},
    {id:23,t:"The Prestige",             y:2006, g:"thriller",    r:"8.5", e:"🎩", d:"Two rival magicians compete to create the greatest illusion.",                        q:"The Prestige full movie"},
    {id:24,t:"Spirited Away",            y:2001, g:"animation",   r:"8.6", e:"🐉", d:"A girl wanders into a spirit world ruled by gods and witches.",                       q:"Spirited Away full movie"},
    {id:25,t:"Coco",                     y:2017, g:"animation",   r:"8.4", e:"💀", d:"A boy journeys to the Land of the Dead to find his great-great-grandfather.",         q:"Coco 2017 Pixar full movie"},
    {id:26,t:"Inside Out",               y:2015, g:"animation",   r:"8.2", e:"🧠", d:"A girl's emotions navigate her new life after moving cities.",                        q:"Inside Out 2015 full movie"},
    {id:27,t:"WALL-E",                   y:2008, g:"animation",   r:"8.4", e:"🤖", d:"A lonely robot on Earth falls in love while helping save humanity.",                  q:"WALL-E full movie"},
    {id:28,t:"Ratatouille",              y:2007, g:"animation",   r:"8.1", e:"🐀", d:"A rat dreams of becoming a chef in Paris's finest restaurant.",                       q:"Ratatouille 2007 full movie"},
    {id:29,t:"La La Land",               y:2016, g:"romance",     r:"8.0", e:"🎭", d:"A pianist and actress fall in love while chasing their dreams in LA.",                q:"La La Land full movie"},
    {id:30,t:"Eternal Sunshine",         y:2004, g:"romance",     r:"8.3", e:"🧊", d:"A couple undergo a procedure to erase each other from their memories.",               q:"Eternal Sunshine of the Spotless Mind full movie"},
    {id:31,t:"1917",                     y:2019, g:"action",      r:"8.3", e:"🪖", d:"Two soldiers race to deliver a message that could save 1600 lives.",                  q:"1917 2019 full movie"},
    {id:32,t:"Mad Max: Fury Road",       y:2015, g:"action",      r:"8.1", e:"💥", d:"In a post-apocalyptic wasteland, a woman escapes with enslaved women.",               q:"Mad Max Fury Road full movie"},
    {id:33,t:"The Revenant",             y:2015, g:"action",      r:"8.0", e:"🐻", d:"A frontiersman survives a bear attack and seeks revenge against his betrayers.",      q:"The Revenant 2015 full movie"},
    {id:34,t:"Spider-Man: No Way Home",  y:2021, g:"action",      r:"8.3", e:"🕷️", d:"Spider-Man seeks help from Doctor Strange when his identity is revealed.",           q:"Spider-Man No Way Home full movie"},
    {id:35,t:"Guardians of the Galaxy",  y:2014, g:"action",      r:"8.0", e:"🌌", d:"Misfits must stop a fanatical warrior from destroying the universe.",                 q:"Guardians of the Galaxy full movie"},
    {id:36,t:"Catch Me If You Can",      y:2002, g:"comedy",      r:"8.1", e:"✈️", d:"A master con artist is pursued across the globe by an FBI agent.",                   q:"Catch Me If You Can full movie"},
    {id:37,t:"The Wolf of Wall Street",  y:2013, g:"comedy",      r:"8.2", e:"💰", d:"A stockbroker's rise and fall through excess, corruption and fraud.",                 q:"Wolf of Wall Street full movie"},
    {id:38,t:"Home Alone",               y:1990, g:"comedy",      r:"7.7", e:"🏠", d:"An 8-year-old defends his home against bumbling burglars.",                           q:"Home Alone 1990 full movie"},
    {id:39,t:"The Truman Show",          y:1998, g:"drama",       r:"8.2", e:"📺", d:"A man discovers his entire life is a reality TV show.",                               q:"The Truman Show full movie"},
    {id:40,t:"Cast Away",                y:2000, g:"drama",       r:"7.8", e:"🏝️", d:"A FedEx employee is stranded on an uninhabited island after a crash.",                q:"Cast Away 2000 full movie"},
    {id:41,t:"Bohemian Rhapsody",        y:2018, g:"drama",       r:"7.9", e:"🎤", d:"The story of the legendary band Queen and Freddie Mercury.",                          q:"Bohemian Rhapsody full movie"},
    {id:42,t:"The Pursuit of Happyness", y:2006, g:"drama",       r:"8.0", e:"🏃", d:"A struggling salesman fights to build a better life for his son.",                   q:"Pursuit of Happyness full movie"},
    {id:43,t:"Gravity",                  y:2013, g:"scifi",       r:"7.7", e:"🛰️", d:"Two astronauts survive after debris destroys their shuttle.",                         q:"Gravity 2013 full movie"},
    {id:44,t:"The Martian",              y:2015, g:"scifi",       r:"8.0", e:"👨‍🚀", d:"An astronaut stranded on Mars must survive until a rescue mission arrives.",         q:"The Martian 2015 full movie"},
    {id:45,t:"Jurassic Park",            y:1993, g:"scifi",       r:"8.2", e:"🦕", d:"A theme park with cloned dinosaurs suffers a catastrophic breakdown.",                q:"Jurassic Park 1993 full movie"},
    {id:46,t:"Se7en",                    y:1995, g:"thriller",    r:"8.6", e:"📦", d:"Two detectives hunt a serial killer using the seven deadly sins as motifs.",          q:"Se7en 1995 full movie"},
    {id:47,t:"Memento",                  y:2000, g:"thriller",    r:"8.4", e:"📸", d:"A man with short-term memory loss investigates his wife's murder.",                   q:"Memento 2000 full movie"},
    {id:48,t:"The Silence of the Lambs", y:1991, g:"thriller",    r:"8.6", e:"🦋", d:"An FBI trainee seeks help from a cannibalistic killer to catch another.",            q:"Silence of the Lambs full movie"},
    {id:49,t:"Planet Earth III",         y:2023, g:"documentary", r:"9.2", e:"🌍", d:"Attenborough presents the most spectacular stories from our planet.",                 q:"Planet Earth III documentary full"},
    {id:50,t:"Breaking Bad S1",          y:2008, g:"series",      r:"9.5", e:"⚗️", d:"A chemistry teacher turns to drug manufacturing after a cancer diagnosis.",           q:"Breaking Bad Season 1 full episodes"},
    {id:51,t:"The Office",               y:2005, g:"series",      r:"9.0", e:"📋", d:"A mockumentary about daily life in a paper company's regional office.",               q:"The Office US full episodes free"},
    {id:52,t:"Stranger Things S1",       y:2016, g:"series",      r:"8.7", e:"🔦", d:"A boy disappears and his friends discover supernatural mysteries.",                    q:"Stranger Things Season 1 full episodes"},
    {id:53,t:"Sherlock S1",              y:2010, g:"series",      r:"9.1", e:"🔍", d:"The famous sleuth solves crime in 21st century London.",                              q:"Sherlock BBC Season 1 full episodes"},
    {id:54,t:"Game of Thrones S1",       y:2011, g:"series",      r:"9.2", e:"🐲", d:"Noble families battle for control of the Iron Throne.",                              q:"Game of Thrones Season 1 full episodes"},
    {id:55,t:"Money Heist S1",           y:2017, g:"series",      r:"8.3", e:"💣", d:"A criminal mastermind orchestrates the biggest heist in history.",                    q:"Money Heist Season 1 full episodes English"},
    {id:56,t:"Friends S1",               y:1994, g:"series",      r:"8.9", e:"☕", d:"Six friends navigate love, career, and life in New York City.",                       q:"Friends Season 1 full episodes"},
    {id:57,t:"Dark S1",                  y:2017, g:"series",      r:"8.8", e:"⏳", d:"A German town is haunted by disappearances and a wormhole connecting four time periods.", q:"Dark Netflix Season 1 full episodes"},
    {id:58,t:"Peaky Blinders S1",        y:2013, g:"series",      r:"8.8", e:"🎩", d:"A gangster family controls the streets of Birmingham after World War I.",             q:"Peaky Blinders Season 1 full episodes"},
    {id:59,t:"Squid Game S1",            y:2021, g:"series",      r:"8.0", e:"🟢", d:"Desperate people compete in deadly children's games for a huge cash prize.",          q:"Squid Game Season 1 full episodes"},
    {id:60,t:"Narcos S1",                y:2015, g:"series",      r:"8.8", e:"🌿", d:"The story of Pablo Escobar's rise and fall as a drug kingpin.",                       q:"Narcos Season 1 full episodes"},
    {id:61,t:"The Lion King",            y:1994, g:"animation",   r:"8.5", e:"🦁", d:"A lion cub flees his home after his father's death and learns to be king.",           q:"The Lion King 1994 full movie"},
    {id:62,t:"Shrek",                    y:2001, g:"animation",   r:"7.9", e:"🧅", d:"An ogre and a talking donkey embark on a quest to rescue a princess.",                q:"Shrek 2001 full movie"},
    {id:63,t:"Moana",                    y:2016, g:"animation",   r:"7.6", e:"🌊", d:"A Polynesian girl sails across the ocean to save her people.",                        q:"Moana 2016 full movie"},
    {id:64,t:"Frozen",                   y:2013, g:"animation",   r:"7.4", e:"❄️", d:"A young woman journeys to find her sister whose icy powers trapped the kingdom.",     q:"Frozen 2013 full movie"},
    {id:65,t:"Up",                       y:2009, g:"animation",   r:"8.3", e:"🎈", d:"A 78-year-old ties balloons to his house to fly to South America.",                   q:"Up 2009 Pixar full movie"},
    {id:66,t:"The Notebook",             y:2004, g:"romance",     r:"7.8", e:"📓", d:"A poor man falls in love with a wealthy girl in 1940s South Carolina.",               q:"The Notebook full movie"},
    {id:67,t:"Pride & Prejudice",        y:2005, g:"romance",     r:"7.8", e:"🌹", d:"Sparks fly between Elizabeth Bennet and the proud Mr Darcy.",                        q:"Pride and Prejudice 2005 full movie"},
    {id:68,t:"Amélie",                   y:2001, g:"romance",     r:"8.3", e:"🫖", d:"A shy Parisian woman decides to help others find happiness.",                         q:"Amélie 2001 full movie"},
    {id:69,t:"Harry Potter 1",           y:2001, g:"action",      r:"7.6", e:"⚡", d:"An orphan boy discovers he is a wizard and enrolls in a school of magic.",            q:"Harry Potter Sorcerers Stone full movie"},
    {id:70,t:"The Hobbit",               y:2012, g:"action",      r:"7.8", e:"🧙", d:"A hobbit joins a wizard and dwarves on a quest to reclaim their homeland.",            q:"The Hobbit An Unexpected Journey full movie"},
    {id:71,t:"Doctor Strange",           y:2016, g:"action",      r:"7.5", e:"🔮", d:"A surgeon discovers the world of magic and alternate dimensions.",                    q:"Doctor Strange 2016 full movie"},
    {id:72,t:"Black Panther",            y:2018, g:"action",      r:"7.3", e:"🐾", d:"A new king must defend his technologically advanced African nation.",                  q:"Black Panther 2018 full movie"},
    {id:73,t:"Thor: Ragnarok",           y:2017, g:"comedy",      r:"7.9", e:"🌩️", d:"Thor must stop his sister Hela from destroying Asgard.",                             q:"Thor Ragnarok full movie"},
    {id:74,t:"Free Guy",                 y:2021, g:"comedy",      r:"7.1", e:"🎮", d:"A background NPC in a video game discovers he can choose his own path.",              q:"Free Guy 2021 full movie"},
    {id:75,t:"Everything Everywhere",    y:2022, g:"scifi",       r:"8.1", e:"🌌", d:"A laundromat owner discovers she can access skills from parallel universes.",          q:"Everything Everywhere All at Once full movie"},
    {id:76,t:"The Godfather II",         y:1974, g:"drama",       r:"9.0", e:"🌃", d:"The rise of young Vito Corleone and the fall of his son Michael.",                    q:"The Godfather Part 2 full movie"},
    {id:77,t:"Schindler's List",         y:1993, g:"drama",       r:"9.0", e:"📜", d:"A businessman saves Jewish refugees during the Holocaust.",                           q:"Schindlers List full movie"},
    {id:78,t:"12 Angry Men",             y:1957, g:"drama",       r:"9.0", e:"👔", d:"A jury deliberates the fate of a boy accused of murder.",                            q:"12 Angry Men 1957 full movie"},
    {id:79,t:"Goodfellas",               y:1990, g:"thriller",    r:"8.7", e:"🕴️", d:"The rise and fall of a mob associate in the New York gangster world.",               q:"Goodfellas full movie"},
    {id:80,t:"Black Mirror S1",          y:2011, g:"series",      r:"8.8", e:"📱", d:"Anthology exploring dark aspects of technology and modern society.",                  q:"Black Mirror Season 1 full episodes"},
  ];
 
  // ── STATE ──
  let activeCat = 'all';
 
  // ── FILTER & RENDER ──
  function doFilter() {
    const q = document.getElementById('searchInput').value.toLowerCase().trim();
    let list = activeCat === 'all' ? movies : movies.filter(m => m.g === activeCat);
    if (q) list = list.filter(m => m.t.toLowerCase().includes(q) || m.d.toLowerCase().includes(q));
 
    // Update count
    document.getElementById('titleCount').textContent = list.length + ' titles';
    document.getElementById('countPill').textContent = list.length;
 
    // Update section title
    const labels = {
      all:'🔥 All Titles', action:'💥 Action', comedy:'😂 Comedy', drama:'🎭 Drama',
      thriller:'😱 Thriller', scifi:'🚀 Sci-Fi', horror:'👻 Horror',
      animation:'✨ Animation', romance:'❤️ Romance', documentary:'🎥 Documentaries', series:'📺 Series'
    };
    document.getElementById('sectionTitle').innerHTML =
      (q ? `🔎 "${q}"` : (labels[activeCat] || '🎬 Movies')) +
      ` <span class="count-pill" id="countPill">${list.length}</span>`;
 
    renderGrid(list);
  }
 
  function renderGrid(list) {
    const grid = document.getElementById('grid');
    const empty = document.getElementById('empty');
 
    if (!list.length) {
      grid.innerHTML = '';
      empty.style.display = 'block';
      return;
    }
    empty.style.display = 'none';
 
    grid.innerHTML = list.map((m, i) => `
      <div class="card" onclick="openModal(${m.id})" style="animation-delay:${Math.min(i * 0.03, 0.5)}s">
        <div class="thumb">
          <span>${m.e}</span>
          <div class="play-ov">
            <div class="play-circle">
              <svg width="20" height="20" viewBox="0 0 24 24" fill="white"><path d="M8 5v14l11-7z"/></svg>
            </div>
          </div>
        </div>
        <div class="card-info">
          <div class="card-title">${m.t}</div>
          <div class="card-meta">
            <span class="rating">★ ${m.r}</span>
            <span>${m.y}</span>
            <span class="free-tag">FREE</span>
          </div>
        </div>
      </div>
    `).join('');
  }
 
  function setCat(cat, btn) {
    activeCat = cat;
    document.querySelectorAll('.cat-btn').forEach(b => b.classList.remove('active'));
    btn.classList.add('active');
    document.getElementById('searchInput').value = '';
    doFilter();
  }
 
  // ── MODAL ──
  function openModal(id) {
    const m = movies.find(x => x.id === id);
    if (!m) return;
    document.getElementById('mEmoji').textContent = m.e;
    document.getElementById('mTitle').textContent = m.t;
    document.getElementById('mMeta').innerHTML =
      `<span class="rating">★ ${m.r}</span><span>${m.y}</span><span class="genre-pill">${m.g}</span>`;
    document.getElementById('mDesc').textContent = m.d;
    document.getElementById('watchLink').href =
      `https://www.youtube.com/results?search_query=${encodeURIComponent(m.q)}`;
    document.getElementById('modalBg').classList.add('open');
    document.body.style.overflow = 'hidden';
  }
 
  function closeModal() {
    document.getElementById('modalBg').classList.remove('open');
    document.body.style.overflow = '';
  }
 
  // Close modal on Escape key
  document.addEventListener('keydown', e => { if (e.key === 'Escape') closeModal(); });
 
  // ── INIT ──
  doFilter();
</script>
</body>
</html>
