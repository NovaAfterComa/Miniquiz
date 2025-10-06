<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>CareerMatch™ – Test orientativo</title>
  <meta name="description" content="Un test orientativo ironico in stile recruiting, con finale LinkedIn. Single‑file, offline‑friendly." />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500;700&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg: #f5f7fb;             /* neutro chiaro */
      --card: #ffffff;
      --ink: #1f2937;            /* grigio antracite */
      --muted: #6b7280;          /* grigio medio */
      --primary: #0a66c2;        /* blu LinkedIn */
      --primary-600:#0f5cab;
      --accent: #2b8af7;         /* per piccoli accenti */
      --good:#16a34a;            /* verde */
      --warn:#f59e0b;            /* giallo */
      --bad:#ef4444;             /* rosso */
      --shadow: 0 10px 30px rgba(15, 23, 42, .08);
      --radius: 18px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0; background:var(--bg); color:var(--ink);
      font-family: Roboto, Montserrat, system-ui, -apple-system, Segoe UI, Helvetica, Arial, sans-serif;
      line-height:1.5;
      overflow:hidden; /* slide-deck feel */
    }

    /* Subtle animated background */
    .bg-ornaments::before,.bg-ornaments::after{
      content:""; position:fixed; inset:auto; top:-10vh; left:-10vw; width:60vmax; height:60vmax;
      background: radial-gradient(closest-side, rgba(10,102,194,.08), rgba(10,102,194,0) 70%);
      filter:blur(30px); z-index:0; animation: float1 22s linear infinite;
    }
    .bg-ornaments::after{ top:auto; bottom:-15vh; left:auto; right:-15vw; animation: float2 28s linear infinite; }
    @keyframes float1{ 0%{transform:translateY(0) rotate(0)} 50%{transform:translateY(4vh) rotate(10deg)} 100%{transform:translateY(0) rotate(0)} }
    @keyframes float2{ 0%{transform:translateY(0) rotate(0)} 50%{transform:translateY(-3vh) rotate(-8deg)} 100%{transform:translateY(0) rotate(0)} }

    .deck{position:relative; z-index:1; height:100%; display:grid; grid-template-rows:auto 1fr auto;}

    header{
      display:flex; align-items:center; justify-content:space-between; gap:12px;
      padding:18px 22px; backdrop-filter:saturate(120%) blur(6px);
    }
    .brand{display:flex; align-items:center; gap:12px}
    .logo{
      width:42px; height:42px; border-radius:12px;
      background:linear-gradient(135deg, var(--primary), #69a5ff);
      box-shadow:var(--shadow); position:relative; overflow:hidden;
    }
    .logo::after{content:"CM"; position:absolute; inset:0; display:grid; place-items:center; color:#fff; font-weight:800; font-family:Montserrat, sans-serif; letter-spacing:.5px}
    .brand h1{font-family:Montserrat, sans-serif; font-weight:700; font-size:18px; margin:0}
    .tagline{font-size:12px; color:var(--muted)}

    .controls{display:flex; align-items:center; gap:10px}
    .badge{font-size:12px; padding:6px 10px; background:#fff; border-radius:999px; box-shadow:var(--shadow); color:var(--muted)}
    .badge strong{color:var(--ink)}
    .btn-icon{
      width:38px; height:38px; border-radius:12px; border:1px solid #e5e7eb; background:#fff; cursor:pointer; box-shadow:var(--shadow);
      display:grid; place-items:center; font-size:18px; transition:transform .06s ease, box-shadow .2s ease; user-select:none;
    }
    .btn-icon:active{transform:translateY(1px)}
    .divider{width:1px; height:30px; background:#e5e7eb;}

    /* Progress */
    .progress{flex:1; height:6px; background:#e5e7eb; border-radius:999px; overflow:hidden; margin:0 12px}
    .progress span{display:block; height:100%; width:0; background:linear-gradient(90deg, var(--primary), #69a5ff); transition:width .4s ease}

    main{padding:16px; display:grid; place-items:center;}

    .slide{
      width:min(950px, 92vw); height:min(70vh, 76vh);
      background:var(--card); border-radius:var(--radius); box-shadow:var(--shadow);
      padding: clamp(18px, 3.5vmin, 32px);
      display:none; flex-direction:column; justify-content:space-between; position:relative;
      overflow:hidden;
    }
    .slide.active{display:flex}

    .slide h2{font-family:Montserrat, sans-serif; margin:0 0 4px; font-size:clamp(20px, 3.2vmin, 36px)}
    .subtitle{color:var(--muted); margin-top:2px}

    .cta-row{display:flex; gap:12px; flex-wrap:wrap}
    .btn{
      --bg: var(--primary); --fg: #fff; --bd: transparent;
      padding:12px 18px; border-radius:14px; font-weight:600; border:1px solid var(--bd); color:var(--fg); background:var(--bg);
      cursor:pointer; box-shadow:var(--shadow); transition: transform .06s ease, filter .2s ease, box-shadow .2s ease; user-select:none;
    }
    .btn:hover{filter:brightness(1.03)}
    .btn:active{transform:translateY(1px)}
    .btn.secondary{ --bg: #fff; --fg: var(--ink); --bd: #e5e7eb; }
    .btn.ghost{ --bg: rgba(10,102,194,.1); --fg: var(--primary); --bd: rgba(10,102,194,.2); }

    .options{display:grid; gap:12px; grid-template-columns:1fr; margin-top:16px}
    .option{
      border:1px solid #e5e7eb; border-radius:14px; padding:14px 16px; background:#fff; cursor:pointer;
      display:flex; align-items:center; gap:12px; transition:border-color .15s ease, transform .06s ease, background .2s ease;
    }
    .option:hover{border-color:var(--primary)}
    .option:active{transform:translateY(1px)}
    .opt-emoji{font-size:22px}
    .opt-text{flex:1}

    .mini-comment{margin:8px 0 0; color:var(--muted); font-size:14px; min-height:22px}

    .quick-bars{display:grid; grid-template-columns:repeat(4,1fr); gap:10px; margin-top:12px}
    .bar{background:#f1f5f9; border-radius:10px; padding:8px}
    .bar b{display:block; font-size:12px; color:var(--muted)}
    .bar span{display:block; height:8px; border-radius:6px; margin-top:6px; background:linear-gradient(90deg, var(--primary), #69a5ff); width:0%}

    .loading{
      height:10px; background:#e5e7eb; border-radius:999px; overflow:hidden; margin-top:10px;
    }
    .loading span{display:block; height:100%; width:0; background:linear-gradient(90deg, var(--primary), #69a5ff);}

    .result-card{display:grid; gap:12px}
    .result-title{font-family:Montserrat,sans-serif; font-weight:700; font-size:clamp(24px,3.6vmin,40px)}
    .result-pill{display:inline-flex; align-items:center; gap:8px; padding:8px 12px; border-radius:999px; background:rgba(10,102,194,.1); color:var(--primary); font-weight:600}

    .pp-like{border:1px dashed #93c5fd; background:#f0f8ff}

    footer{display:flex; align-items:center; justify-content:space-between; gap:10px; padding:12px 18px; color:var(--muted); font-size:12px}
    .hidden-egg{opacity:0; width:22px; height:22px; cursor:pointer}
    .secret-icon{position:fixed; bottom:8px; right:8px; width:22px; height:22px; opacity:0; background:none; border:none;}

    /* Modal */
    .modal{position:fixed; inset:0; display:none; place-items:center; background:rgba(15,23,42,.42); z-index:5}
    .modal .window{
      width:min(640px,92vw); background:#fff; border-radius:20px; box-shadow:var(--shadow); padding:22px; position:relative;
    }
    .close-x{position:absolute; top:12px; right:12px; border:none; background:#0000; font-size:22px; cursor:pointer}
    .faux-form{display:grid; gap:10px; margin-top:10px}
    .faux-form label{font-size:12px; color:var(--muted)}
    .faux-form input{width:100%; padding:10px 12px; border-radius:12px; border:1px solid #e5e7eb}
    input.error{border-color:var(--bad)}

    /* Confetti */
    .confetti{position:fixed; inset:0; pointer-events:none; overflow:hidden; z-index:6}
    .confetti i{position:absolute; width:10px; height:16px; border-radius:2px; opacity:.9; top:-20px}
    @keyframes fall{ to{ transform:translateY(110vh) rotate(360deg);} }

    /* Responsive tweaks */
    @media (max-width:640px){
      header{padding:12px 14px}
      .logo{width:36px; height:36px}
      .badge:nth-child(1){display:none}
    }
  </style>
</head>
<body class="bg-ornaments">
  <div class="deck" id="deck">
    <header>
      <div class="brand" role="banner">
        <div class="logo" aria-hidden="true"></div>
        <div>
          <h1>CareerMatch™ <span style="font-weight:500;color:var(--muted)">powered by <span id="byName">Dottor Dario Sorrentino</span></span></h1>
          <div class="tagline">Scopri il lavoro più adatto a te (secondo il Dottor Dario Sorrentino)</div>
        </div>
      </div>
      <div class="controls" role="toolbar" aria-label="Comandi rapidi">
        <span class="badge">Slide <strong id="slideNow">1</strong>/<span id="slideTotal">12</span></span>
        <div class="progress" aria-hidden="true"><span id="progress"></span></div>
        <span class="badge">🔥 Burnout: <strong id="burn">0</strong></span>
        <span class="badge">🌟 Leader: <strong id="lead">0</strong></span>
        <span class="badge">👤 <strong id="participantLabel">—</strong></span>
        <div class="divider"></div>
        <button class="btn-icon" id="soundToggle" title="Suoni ON/OFF" aria-pressed="false">🔈</button>
        <button class="btn-icon" id="voiceToggle" title="Voce narrante ON/OFF" aria-pressed="false">🗣️</button>
      </div>
    </header>

    <main>
      <!-- Slide 1: start -->
      <section class="slide active" data-id="start">
        <div>
          <h2>Benvenuto al Career Test</h2>
          <div class="subtitle">Rispondi sinceramente (o quasi) alle seguenti domande per scoprire quale carriera è davvero fatta per te!</div>
          <div class="pp-like" style="margin-top:16px; padding:12px; border-radius:12px;">
            <small>Logo: <strong>CareerMatch™</strong> · stile questionario pro · mood “assessment” ma con ironia controllata ✨</small>
          </div>
          <div class="faux-form" id="participantForm" style="max-width:520px; margin-top:12px">
            <label>Dati partecipante (obbligatori per l'attestato)</label>
            <div style="display:grid; grid-template-columns:1fr 1fr; gap:10px;">
              <input id="pName" placeholder="Nome" />
              <input id="pSurname" placeholder="Cognome" />
            </div>
            <small class="subtitle">I dati sono salvati automaticamente in locale.</small>
          </div>
        </div>
        <div class="cta-row">
          <button class="btn" id="startBtn">Inizia il test ▶</button>
          <button class="btn secondary" id="howBtn">Cos'è questo?</button>
        </div>
      </section>

      <!-- Slide 2: Q1 -->
      <section class="slide" data-id="q1">
        <div>
          <h2>Domanda 1 · Come affronti lo stress lavorativo?</h2>
          <div class="subtitle">Scegli l’opzione che ti rappresenta meglio (in coscienza o con autoironia).</div>
          <div class="options" role="list">
            <div class="option" data-q="1" data-opt="A" data-emoji="🧘" data-mini="Checklist zen: approccio da manuale. Il tuo futuro HR ti amerà." data-award="lead" data-p="fixed">
              <div class="opt-emoji">🧘</div>
              <div class="opt-text"><strong>A)</strong> Respiro, analizzo, e faccio una checklist.</div>
            </div>
            <div class="option" data-q="1" data-opt="B" data-emoji="☕" data-mini="Coppia perfetta: caffè + lamento strategico." data-award="burn" data-p="lazy">
              <div class="opt-emoji">☕</div>
              <div class="opt-text"><strong>B)</strong> Cerco un caffè e un compagno di lamentele.</div>
            </div>
            <div class="option" data-q="1" data-opt="C" data-emoji="💥" data-mini="Tecnica dello struzzo: elegante finché esplode." data-award="burn" data-p="lazy">
              <div class="opt-emoji">💥</div>
              <div class="opt-text"><strong>C)</strong> Nego l’esistenza del problema finché non esplode.</div>
            </div>
            <div class="option" data-q="1" data-opt="D" data-emoji="🛠️" data-mini="Ti lanci per primo. E poi ricordi che avevi una vita." data-award="burn" data-p="site">
              <div class="opt-emoji">🛠️</div>
              <div class="opt-text"><strong>D)</strong> Mi offro volontario per risolverlo… e poi me ne pento.</div>
            </div>
          </div>
          <div class="mini-comment"></div>
          <div class="quick-bars" aria-hidden="true">
            <div class="bar"><b>🛌 Sfaticato</b><span id="bar-lazy"></span></div>
            <div class="bar"><b>🏢 Posto fisso</b><span id="bar-fixed"></span></div>
            <div class="bar"><b>👷 Cantiere</b><span id="bar-site"></span></div>
            <div class="bar"><b>🚀 Imprenditore</b><span id="bar-entre"></span></div>
          </div>
        </div>
        <div class="cta-row"><button class="btn ghost" data-next>Prossima ➜</button></div>
      </section>

      <!-- Slide 3: Q2 -->
      <section class="slide" data-id="q2">
        <div>
          <h2>Domanda 2 · Come ti comporti in un lavoro di gruppo?</h2>
          <div class="subtitle">Puoi anche ammettere di portare solo gli snack. Nessuno ti giudicherà (forse).</div>
          <div class="options">
            <div class="option" data-q="2" data-opt="A" data-emoji="🫱🫲" data-mini="Diplomatico nato. Gli altri litigano, tu faciliti." data-award="lead" data-p="fixed">
              <div class="opt-emoji">🫱🫲</div>
              <div class="opt-text"><strong>A)</strong> Cerco di mediare i conflitti.</div>
            </div>
            <div class="option" data-q="2" data-opt="B" data-emoji="📊" data-mini="Excel + Calendar: il Project Manager che è in te." data-award="lead" data-p="fixed">
              <div class="opt-emoji">📊</div>
              <div class="opt-text"><strong>B)</strong> Organizzo tutto con Excel e Google Calendar.</div>
            </div>
            <div class="option" data-q="2" data-opt="C" data-emoji="🕶️" data-mini="Mimetismo avanzato: sembri impegnato, ma…" data-award="burn" data-p="lazy">
              <div class="opt-emoji">🕶️</div>
              <div class="opt-text"><strong>C)</strong> Faccio finta di lavorare mentre gli altri discutono.</div>
            </div>
            <div class="option" data-q="2" data-opt="D" data-emoji="🥨" data-mini="Keeper del morale. Senza di te niente carboidrati." data-award="lead" data-p="site">
              <div class="opt-emoji">🥨</div>
              <div class="opt-text"><strong>D)</strong> Porto snack e mantengo alto il morale.</div>
            </div>
          </div>
          <div class="mini-comment"></div>
          <div class="quick-bars" aria-hidden="true">
            <div class="bar"><b>🛌 Sfaticato</b><span id="bar2-lazy"></span></div>
            <div class="bar"><b>🏢 Posto fisso</b><span id="bar2-fixed"></span></div>
            <div class="bar"><b>👷 Cantiere</b><span id="bar2-site"></span></div>
            <div class="bar"><b>🚀 Imprenditore</b><span id="bar2-entre"></span></div>
          </div>
        </div>
        <div class="cta-row"><button class="btn ghost" data-next>Prossima ➜</button></div>
      </section>

      <!-- Slide 4: Q3 -->
      <section class="slide" data-id="q3">
        <div>
          <h2>Domanda 3 · Qual è la tua più grande motivazione?</h2>
          <div class="subtitle">Promesso: qualunque risposta è valida (tranne il lunedì mattina).</div>
          <div class="options">
            <div class="option" data-q="3" data-opt="A" data-emoji="📈" data-mini="Crescita: mindset da startupper riflessivo." data-award="lead" data-p="entre">
              <div class="opt-emoji">📈</div>
              <div class="opt-text"><strong>A)</strong> Crescita personale</div>
            </div>
            <div class="option" data-q="3" data-opt="B" data-emoji="💸" data-mini="Onesto. Anche i sogni hanno un budget." data-award="burn" data-p="site">
              <div class="opt-emoji">💸</div>
              <div class="opt-text"><strong>B)</strong> Soldi 💸</div>
            </div>
            <div class="option" data-q="3" data-opt="C" data-emoji="🏅" data-mini="Applausi e badge: carriera a scalini." data-award="lead" data-p="fixed">
              <div class="opt-emoji">🏅</div>
              <div class="opt-text"><strong>C)</strong> Riconoscimento sociale</div>
            </div>
            <div class="option" data-q="3" data-opt="D" data-emoji="🛋️" data-mini="Resilienza weekend-centrica: rispetto." data-award="burn" data-p="lazy">
              <div class="opt-emoji">🛋️</div>
              <div class="opt-text"><strong>D)</strong> Sopravvivere fino al weekend</div>
            </div>
          </div>
          <div class="mini-comment"></div>
        </div>
        <div class="cta-row"><button class="btn ghost" data-next>Prossima ➜</button></div>
      </section>

      <!-- Slide 5: Q4 -->
      <section class="slide" data-id="q4">
        <div>
          <h2>Domanda 4 · Il tuo rapporto con la tecnologia al lavoro?</h2>
          <div class="subtitle">Sii sincero: automazioni o post-it?</div>
          <div class="options">
            <div class="option" data-q="4" data-opt="A" data-emoji="⚙️" data-mini="Automatizzi ciò che puoi. Bravo!" data-award="lead" data-p="entre">
              <div class="opt-emoji">⚙️</div>
              <div class="opt-text"><strong>A)</strong> Se posso, automatizzo (script, template, macro).</div>
            </div>
            <div class="option" data-q="4" data-opt="B" data-emoji="📧" data-mini="Suite Office e via." data-award="lead" data-p="fixed">
              <div class="opt-emoji">📧</div>
              <div class="opt-text"><strong>B)</strong> Excel, posta, procedure chiare e sono felice.</div>
            </div>
            <div class="option" data-q="4" data-opt="C" data-emoji="🆘" data-mini="IT helpdesk migliore amico." data-award="burn" data-p="lazy">
              <div class="opt-emoji">🆘</div>
              <div class="opt-text"><strong>C)</strong> Chiedo aiuto a chi ne sa e vado avanti.</div>
            </div>
            <div class="option" data-q="4" data-opt="D" data-emoji="🔧" data-mini="Tool pratici sul campo." data-award="lead" data-p="site">
              <div class="opt-emoji">🔧</div>
              <div class="opt-text"><strong>D)</strong> Strumenti pratici e operativi: imparando facendolo.</div>
            </div>
          </div>
          <div class="mini-comment"></div>
        </div>
        <div class="cta-row"><button class="btn ghost" data-next>Prossima ➜</button></div>
      </section>

      <!-- Slide 6: Q5 -->
      <section class="slide" data-id="q5">
        <div>
          <h2>Domanda 5 · Riunioni infinite: come reagisci?</h2>
          <div class="subtitle">La verità verrà usata solo a fini statistici (forse).</div>
          <div class="options">
            <div class="option" data-q="5" data-opt="A" data-emoji="🗂️" data-mini="Agenda e timebox: ordine!" data-award="lead" data-p="fixed">
              <div class="opt-emoji">🗂️</div>
              <div class="opt-text"><strong>A)</strong> Impongo agenda, obiettivi e fine in orario.</div>
            </div>
            <div class="option" data-q="5" data-opt="B" data-emoji="🎯" data-mini="Vai al dunque: sblocchi decisioni." data-award="lead" data-p="entre">
              <div class="opt-emoji">🎯</div>
              <div class="opt-text"><strong>B)</strong> Divento facilitatore: decisione > discussione.</div>
            </div>
            <div class="option" data-q="5" data-opt="C" data-emoji="🍝" data-mini="Camera off, pasta on." data-award="burn" data-p="lazy">
              <div class="opt-emoji">🍝</div>
              <div class="opt-text"><strong>C)</strong> Spengo la camera e cucino.</div>
            </div>
            <div class="option" data-q="5" data-opt="D" data-emoji="🔨" data-mini="Meglio fare che riunirsi." data-award="lead" data-p="site">
              <div class="opt-emoji">🔨</div>
              <div class="opt-text"><strong>D)</strong> Preferisco andare a fare la cosa direttamente.</div>
            </div>
          </div>
          <div class="mini-comment"></div>
        </div>
        <div class="cta-row"><button class="btn ghost" data-next>Prossima ➜</button></div>
      </section>

      <!-- Slide 7: Q6 -->
      <section class="slide" data-id="q6">
        <div>
          <h2>Domanda 6 · Orari e ambiente ideale?</h2>
          <div class="subtitle">Spoiler: il weekend è incluso in almeno una risposta.</div>
          <div class="options">
            <div class="option" data-q="6" data-opt="A" data-emoji="📅" data-mini="Routine = serenità." data-award="lead" data-p="fixed">
              <div class="opt-emoji">📅</div>
              <div class="opt-text"><strong>A)</strong> Orario fisso, routine e poche sorprese.</div>
            </div>
            <div class="option" data-q="6" data-opt="B" data-emoji="🌐" data-mini="Autonomia e responsabilità." data-award="lead" data-p="entre">
              <div class="opt-emoji">🌐</div>
              <div class="opt-text"><strong>B)</strong> Smart working / ibrido con autonomia.</div>
            </div>
            <div class="option" data-q="6" data-opt="C" data-emoji="🚚" data-mini="Movimento e concretezza." data-award="lead" data-p="site">
              <div class="opt-emoji">🚚</div>
              <div class="opt-text"><strong>C)</strong> Turni, movimento, contesti pratici.</div>
            </div>
            <div class="option" data-q="6" data-opt="D" data-emoji="🕶️" data-mini="Flessibilità… verso il venerdì." data-award="burn" data-p="lazy">
              <div class="opt-emoji">🕶️</div>
              <div class="opt-text"><strong>D)</strong> Flessibile, ma soprattutto il venerdì corto.</div>
            </div>
          </div>
          <div class="mini-comment"></div>
        </div>
        <div class="cta-row"><button class="btn ghost" data-next>Prossima ➜</button></div>
      </section>

      <!-- Slide 8: Q7 -->
      <section class="slide" data-id="q7">
        <div>
          <h2>Domanda 7 · Decisioni importanti: come procedi?</h2>
          <div class="subtitle">Se rispondi “aspetta e spera” ti vogliamo bene lo stesso.</div>
          <div class="options">
            <div class="option" data-q="7" data-opt="A" data-emoji="📊" data-mini="Data-driven doc." data-award="lead" data-p="fixed">
              <div class="opt-emoji">📊</div>
              <div class="opt-text"><strong>A)</strong> Analisi dati, pro/contro, decisione.</div>
            </div>
            <div class="option" data-q="7" data-opt="B" data-emoji="⚡" data-mini="Test rapido, feedback, iterazioni." data-award="lead" data-p="entre">
              <div class="opt-emoji">⚡</div>
              <div class="opt-text"><strong>B)</strong> Intuito + test piccolo e veloce.</div>
            </div>
            <div class="option" data-q="7" data-opt="C" data-emoji="🛋️" data-mini="Aspetto che qualcuno decida." data-award="burn" data-p="lazy">
              <div class="opt-emoji">🛋️</div>
              <div class="opt-text"><strong>C)</strong> Aspetto la decisione altrui.</div>
            </div>
            <div class="option" data-q="7" data-opt="D" data-emoji="🧭" data-mini="Sopralluogo e via." data-award="lead" data-p="site">
              <div class="opt-emoji">🧭</div>
              <div class="opt-text"><strong>D)</strong> Vado sul posto a vedere e decido.</div>
            </div>
          </div>
          <div class="mini-comment"></div>
        </div>
        <div class="cta-row"><button class="btn ghost" data-next>Prossima ➜</button></div>
      </section>

      <!-- Slide 9: Q8 -->
      <section class="slide" data-id="q8">
        <div>
          <h2>Domanda 8 · Cosa ti fa dire “è il mio posto”?</h2>
          <div class="subtitle">La scintilla giusta vale più di un benefit (forse).</div>
          <div class="options">
            <div class="option" data-q="8" data-opt="A" data-emoji="🏦" data-mini="Stabilità = focus." data-award="lead" data-p="fixed">
              <div class="opt-emoji">🏦</div>
              <div class="opt-text"><strong>A)</strong> Stabilità, percorso chiaro, benefit solidi.</div>
            </div>
            <div class="option" data-q="8" data-opt="B" data-emoji="🚀" data-mini="Sfide e crescita continua." data-award="lead" data-p="entre">
              <div class="opt-emoji">🚀</div>
              <div class="opt-text"><strong>B)</strong> Sfide, responsabilità, crescita.</div>
            </div>
            <div class="option" data-q="8" data-opt="C" data-emoji="🏗️" data-mini="Vedo i risultati, subito." data-award="lead" data-p="site">
              <div class="opt-emoji">🏗️</div>
              <div class="opt-text"><strong>C)</strong> Risultati tangibili, operatività.</div>
            </div>
            <div class="option" data-q="8" data-opt="D" data-emoji="🍕" data-mini="Buoni pasto + venerdì corto = amore." data-award="burn" data-p="lazy">
              <div class="opt-emoji">🍕</div>
              <div class="opt-text"><strong>D)</strong> Benefit pratici e clima easy.</div>
            </div>
          </div>
          <div class="mini-comment"></div>
        </div>
        <div class="cta-row"><button class="btn" id="toProcessing">Elabora il risultato 🔍</button></div>
      </section>

      <!-- Slide 10: Processing -->
      <section class="slide" data-id="processing">
        <div>
          <h2>Elaborazione profilo professionale…</h2>
          <div class="subtitle">Stiamo incrociando le tue risposte con il <em>Grande Algoritmo della Vita Lavorativa</em>™</div>
          <div class="loading" aria-hidden="true"><span id="loadbar"></span></div>
          <div class="mini-comment" id="loadingTips" style="min-height:24px; margin-top:10px"></div>
        </div>
        <div class="cta-row"><button class="btn secondary" data-prev>◀ Indietro</button></div>
      </section>

      <!-- Slide 11: Result -->
      <section class="slide" data-id="result">
        <div class="result-card">
          <div class="result-pill" id="resultPill">🎯 Risultato</div>
          <div class="result-title" id="resultTitle">—</div>
          <p id="resultDesc"></p>
          <ul id="resultAdvice"></ul>
        </div>
        <div class="cta-row">
          <button class="btn" id="toFinal">Procedi: LinkedIn ➜</button>
          <button class="btn secondary" data-prev>◀ Cambia risposte</button>
        </div>
      </section>

      <!-- Slide 12: Final / LinkedIn -->
      <section class="slide" data-id="final">
        <div>
          <h2>Ora sei pronto per il mondo del lavoro!</h2>
          <p>Congratulazioni! Il tuo profilo è stato salvato nel database <strong>CareerMatch™</strong>.<br>Prossimo passo: creare la tua rete professionale…</p>
          <div class="cta-row" style="margin-top:6px; flex-wrap:wrap">
            <button class="btn" id="finalFake">Finale ironico 😏</button>
            <a class="btn secondary" id="finalReal" href="https://www.linkedin.com/" target="_blank" rel="nofollow noopener">Vai su LinkedIn ↗</a>
            <button class="btn" id="certBtn">Genera Attestato 🧾</button>
          </div>
          <small style="display:block; color:var(--muted); margin-top:10px">Suggerimento: personalizza il link LinkedIn e il nome del Dottore nel pannello “Impostazioni”.</small>
        </div>
        <div class="cta-row">
          <button class="btn ghost" id="settingsBtn">⚙️ Impostazioni</button>
          <button class="btn secondary" data-prev>◀ Indietro</button>
        </div>
      </section>

      <!-- Slide 13: Easter Egg (segreto) -->
      <section class="slide" data-id="egg">
        <div>
          <h2>🎉 Livello segreto sbloccato!</h2>
          <p>Complimenti, hai trovato l’icona nascosta. Il vero lavoro perfetto è… <strong>festeggiare il Dottore!</strong> 🥂</p>
          <div class="cta-row"><button class="btn" id="partyBtn">Avvia i coriandoli 🎊</button></div>
          <div class="subtitle">(Tip: fai uno screenshot, invialo agli amici e fingi sia un badge ufficiale.)</div>
        </div>
        <div class="cta-row"><button class="btn secondary" data-prev>◀ Torna al test</button></div>
      </section>
    </main>

    <footer>
      <div>© <span id="year"></span> CareerMatch™ • Demo accademica in stile recruiting</div>
      <button class="secret-icon" id="secretIcon" aria-label=""></button>
    </footer>
  </div>

  <!-- Modal: How -->
  <div class="modal" id="howModal" aria-modal="true" role="dialog" aria-label="Cos'è questo?">
    <div class="window">
      <button class="close-x" data-close>✕</button>
      <h3 style="margin:0 0 8px; font-family:Montserrat,sans-serif">Che cos’è?</h3>
      <p>È un piccolo sito “tipo PowerPoint” che simula un test orientativo ironico. Funziona anche offline (salva questo file e aprilo). Naviga con i pulsanti o con le frecce della tastiera.</p>
    </div>
  </div>

  <!-- Modal: Fake LinkedIn -->
  <div class="modal" id="fakeModal" aria-modal="true" role="dialog" aria-label="Registrazione LinkedIn">
    <div class="window">
      <button class="close-x" data-close>✕</button>
      <h3 style="margin:0; font-family:Montserrat,sans-serif;">LinkedIn – Registrati</h3>
      <div class="faux-form">
        <label>Nome</label>
        <input id="fakeName" value="Dottor Dario Sorrentino" readonly>
        <label>Email</label>
        <input value="trovatelavoro@psico.it" readonly>
        <label>Password</label>
        <input type="password" value="tesi2024" readonly>
      </div>
      <p class="subtitle" style="margin-top:12px">Hai già un account? <strong>Congratulazioni, sei ufficialmente nel mondo reale!</strong> 🎉</p>
    </div>
  </div>

  <!-- Modal: Settings -->
  <div class="modal" id="settingsModal" aria-modal="true" role="dialog" aria-label="Impostazioni">
    <div class="window">
      <button class="close-x" data-close>✕</button>
      <h3 style="margin:0; font-family:Montserrat,sans-serif;">Impostazioni</h3>
      <div class="faux-form">
        <label>Nome Dottore</label>
        <input id="nameInput" placeholder="Es. Dottor Dario Sorrentino">
        <label>LinkedIn URL (finale reale)</label>
        <input id="linkedinInput" placeholder="https://www.linkedin.com/in/username/">
      </div>
      <div class="cta-row" style="margin-top:12px">
        <button class="btn" id="saveSettings">Salva</button>
      </div>
    </div>
  </div>

  <!-- Modal: Certificate -->
  <div class="modal" id="certModal" aria-modal="true" role="dialog" aria-label="Attestato di Partecipazione">
    <div class="window">
      <button class="close-x" data-close>✕</button>
      <h3 style="margin:0; font-family:Montserrat,sans-serif;">Attestato di Partecipazione</h3>
      <canvas id="certCanvas" width="1400" height="1000" style="width:100%; border:1px solid #e5e7eb; border-radius:12px; margin-top:10px"></canvas>
      <div class="cta-row" style="margin-top:12px">
        <button class="btn" id="downloadCert">Scarica PNG</button>
      </div>
      <small class="subtitle">Suggerimento: stampa in orizzontale per un risultato migliore.</small>
    </div>
  </div>

  <!-- Confetti layer -->
  <div class="confetti" id="confetti" aria-hidden="true"></div>

  <script>
    /**
     * CareerMatch™ – Single-file interactive deck
     * Works locally. No build tools, no external JS.
     */
    const $ = (sel, el=document) => el.querySelector(sel);
    const $$ = (sel, el=document) => Array.from(el.querySelectorAll(sel));

    const deck = $('#deck');
    const slides = $$('.slide');
    const progress = $('#progress');
    const slideNow = $('#slideNow');
    const slideTotal = $('#slideTotal');
    const burn = $('#burn');
    const lead = $('#lead');
    const year = $('#year');
    const byName = $('#byName');
    const participantLabel = $('#participantLabel');

    const QUESTIONS = ['q1','q2','q3','q4','q5','q6','q7','q8'];

    const state = {
      current: 0,
      answers: {},
      scores: { lazy:0, fixed:0, site:0, entre:0 },
      meta: { burn:0, lead:0 },
      config: {
        name: 'Dottor Dario Sorrentino',
        linkedin: 'https://www.linkedin.com/'
      },
      participant: { name:'', surname:'' },
      lastProfile: 'fixed'
    };

    // Init
    year.textContent = new Date().getFullYear();
    slideTotal.textContent = (slides.length - 1); // hide egg from count

    function setProgress(){
      const visibleCount = slides.length - 1; // exclude egg
      const idxForProgress = Math.min(state.current+1, visibleCount);
      const pct = Math.round((idxForProgress-1)/(visibleCount-1)*100);
      progress.style.width = pct+'%';
      slideNow.textContent = Math.min(idxForProgress, visibleCount);
    }

    function showSlide(index){
      slides.forEach((s,i)=>s.classList.toggle('active', i===index));
      state.current = index;
      setProgress();
    }

    // Sound & voice
    let soundOn = false;
    let voiceOn = false;

    $('#soundToggle').addEventListener('click', e=>{
      soundOn = !soundOn; e.currentTarget.setAttribute('aria-pressed', String(soundOn));
      e.currentTarget.textContent = soundOn ? '🔊' : '🔈';
      blip();
    });
    $('#voiceToggle').addEventListener('click', e=>{
      voiceOn = !voiceOn; e.currentTarget.setAttribute('aria-pressed', String(voiceOn));
      e.currentTarget.textContent = voiceOn ? '🗣️' : '🤐';
      blip();
    });

    function blip(){
      if(!soundOn) return;
      try{
        const ctx = new (window.AudioContext||window.webkitAudioContext)();
        const o = ctx.createOscillator();
        const g = ctx.createGain();
        o.connect(g); g.connect(ctx.destination);
        o.type = 'sine'; o.frequency.value = 720; g.gain.setValueAtTime(.0001, ctx.currentTime);
        g.gain.exponentialRampToValueAtTime(.2, ctx.currentTime+.01);
        o.start(); o.stop(ctx.currentTime+.08);
      }catch(err){/* ignore */}
    }

    // Small vibration helper
    function buzz(ms=30){ if(navigator.vibrate) navigator.vibrate(ms); }

    // Bars update
    function updateBars(){
      const {lazy,fixed,site,entre} = state.scores;
      const total = Math.max(lazy+fixed+site+entre, 1);
      const set = (id, val)=>{ const el=$(id); if(el) el.style.width = Math.round(val/total*100)+'%'; };
      set('#bar-lazy', lazy); set('#bar-fixed', fixed); set('#bar-site', site); set('#bar-entre', entre);
      set('#bar2-lazy', lazy); set('#bar2-fixed', fixed); set('#bar2-site', site); set('#bar2-entre', entre);
    }

    function chooseOption(el){
      const q = el.dataset.q; const opt = el.dataset.opt; const p = el.dataset.p; const award = el.dataset.award;
      state.answers['q'+q] = opt;
      state.scores[p]++;
      state.meta[award]++;
      burn.textContent = state.meta.burn; lead.textContent = state.meta.lead;
      const mini = el.closest('.slide')?.querySelector('.mini-comment');
      if(mini) mini.textContent = el.dataset.mini || '';
      updateBars();
      blip(); buzz(10);
      // Auto-advance
      const slideEl = el.closest('.slide');
      const sid = slideEl?.dataset.id;
      const qi = QUESTIONS.indexOf(sid);
      if(qi>-1 && qi < QUESTIONS.length-1){
        // go to next question
        showSlide(state.current+1);
      } else if(qi === QUESTIONS.length-1){
        // last question -> processing
        showSlide(getSlideIndex('processing'));
        runLoading();
      }
    }

    function getSlideIndex(id){
      return slides.findIndex(s=>s.dataset.id===id);
    }

    $$('.option').forEach(op=>op.addEventListener('click', e=>chooseOption(e.currentTarget)));

    // Navigation
    $('#startBtn').addEventListener('click', ()=>{
      // Require participant data
      const nEl = $('#pName'); const sEl = $('#pSurname');
      const n = (nEl.value||'').trim(); const s = (sEl.value||'').trim();
      nEl.classList.toggle('error', !n); sEl.classList.toggle('error', !s);
      if(!(n && s)){
        alert('Inserisci nome e cognome per iniziare.');
        return;
      }
      showSlide(getSlideIndex('q1')); blip();
    });
    $('#howBtn').addEventListener('click', ()=> openModal('#howModal'));
    $$('.slide [data-next]').forEach(btn=>btn.addEventListener('click', ()=>{ showSlide(state.current+1); blip(); }));
    $$('.slide [data-prev]').forEach(btn=>btn.addEventListener('click', ()=>{ showSlide(Math.max(state.current-1,0)); blip(); }));

    // Keyboard (left/right/space)
    window.addEventListener('keydown', (e)=>{
      if(['INPUT','TEXTAREA'].includes(document.activeElement.tagName)) return;
      const visibleMax = slides.length-2; // last visible index before egg
      if(e.key==='ArrowRight' || e.key===' '){ showSlide(Math.min(state.current+1, visibleMax)); }
      if(e.key==='ArrowLeft'){ showSlide(Math.max(state.current-1,0)); }
    });

    // Processing
    $('#toProcessing')?.addEventListener('click', ()=>{
      showSlide(getSlideIndex('processing'));
      runLoading();
    });

    const tips = [
      'Analisi CV in corso…',
      'Valutazione soft skills…',
      'Controllo referenze della nonna…',
      'Calcolo fit valoriale…',
      'Quasi pronto!'
    ];

    function runLoading(){
      const bar = $('#loadbar'); const tip = $('#loadingTips');
      let i=0; bar.style.width='0%';
      const id = setInterval(()=>{
        i+=8 + Math.random()*10; bar.style.width = Math.min(i,100)+'%';
        tip.textContent = tips[Math.floor(Math.min(i/20, tips.length-1))];
        if(i>=100){ clearInterval(id); blip(); buzz(20); computeResult(); }
      }, 120);
    }

    const PROFILES = {
      lazy: {
        pill:'🛌 Sfaticato (con stile)',
        title:'🛌 Il “Professionista del Risparmio Energetico”',
        desc:'Sai ottimizzare la risorsa più scarsa: le tue energie. Eviti conflitti, minimizzi lo stress e conosci tutte le scorciatoie etiche (o quasi).',
        advice:[
          'Consigliato per: ruoli low‑stress, back‑office, guardian of the coffee machine ☕',
          'Allenare: gestione del tempo “proattiva”, non solo del weekend',
          'Match HR: ambienti con obiettivi chiari e tempi realistici'
        ]
      },
      fixed: {
        pill:'🏢 Lavoratore da posto fisso',
        title:'🏢 Il “Pilastro dell’Ufficio”',
        desc:'Organizzato, affidabile, amante di procedure e checklist. Se c’è un Excel c’è una via d’uscita.',
        advice:[
          'Consigliato per: HR, amministrazione, PMO, segreteria organizzativa',
          'Allenare: flessibilità creativa nei cambi di priorità',
          'Match HR: aziende strutturate, PA, corporate con percorsi chiari'
        ]
      },
      site: {
        pill:'👷 Lavoratore da cantiere',
        title:'👷 “Mani in pasta & Problemi risolti”',
        desc:'Pragmatico, operativo, fai accadere le cose. Snack manageriale incluso quando serve 🥨.',
        advice:[
          'Consigliato per: operations, logistica, produzione, facility, retail dinamico',
          'Allenare: dire no agli straordinari “eroici”',
          'Match HR: contesti hands‑on con obiettivi misurabili'
        ]
      },
      entre: {
        pill:'🚀 L’imprenditore',
        title:'🚀 “Visione + Intraprendenza = Startup interiore”',
        desc:'Ambizioso, orientato alla crescita e al riconoscimento. Ti lanci e impari in corsa (checklist dopo).',
        advice:[
          'Consigliato per: business development, consulenza, startup, vendita consulenziale',
          'Allenare: gestione del rischio, delega, sostenibilità personale',
          'Match HR: ambienti meritocratici, progetti da creare ex‑novo'
        ]
      }
    };

    function computeResult(){
      const s = state.scores;
      const entries = Object.entries(s).sort((a,b)=> b[1]-a[1]);
      let winner = entries[0][0];
      if(entries.length>1 && entries[0][1]===entries[1][1]){
        if(state.meta.lead>state.meta.burn){ winner = entries.find(([k])=>k!=='lazy')?.[0]||winner; }
      }
      const prof = PROFILES[winner];
      state.lastProfile = winner;
      // Fill UI
      $('#resultPill').textContent = prof.pill;
      $('#resultTitle').textContent = prof.title;
      $('#resultDesc').textContent = prof.desc;
      const ul = $('#resultAdvice'); ul.innerHTML='';
      prof.advice.forEach(t=>{ const li=document.createElement('li'); li.textContent=t; ul.appendChild(li); });

      if(voiceOn && window.speechSynthesis){ try{
        const u = new SpeechSynthesisUtterance(`Risultato: ${prof.title}. ${prof.desc}`);
        u.lang='it-IT'; speechSynthesis.cancel(); speechSynthesis.speak(u);
      }catch(e){}
      }

      showSlide(getSlideIndex('result'));
    }

    // Final
    $('#toFinal').addEventListener('click', ()=>{ showSlide(getSlideIndex('final')); blip(); });
    $('#finalFake').addEventListener('click', ()=> openModal('#fakeModal'));

    // Settings
    $('#settingsBtn').addEventListener('click', ()=> openModal('#settingsModal'));
    $('#saveSettings').addEventListener('click', ()=>{
      const name = $('#nameInput').value.trim();
      const link = $('#linkedinInput').value.trim();
      if(name){ state.config.name = name; byName.textContent = name; $('#fakeName').value = name; }
      if(link){ state.config.linkedin = link; $('#finalReal').href = link; }
      closeModals(); blip();
    });

    // Modal helpers
    function openModal(sel){ $(sel).style.display='grid'; blip(); }
    function closeModals(){ $$('.modal').forEach(m=>m.style.display='none'); }
    $$('[data-close]').forEach(x=>x.addEventListener('click', closeModals));
    window.addEventListener('keydown', e=>{ if(e.key==='Escape') closeModals(); });

    // Participant data autosave
    function saveP(){
      const n = ($('#pName')||{}).value?.trim()||'';
      const s = ($('#pSurname')||{}).value?.trim()||'';
      state.participant.name = n; state.participant.surname = s;
      participantLabel.textContent = (n||s) ? `${n} ${s}`.trim() : '—';
      try{ localStorage.setItem('cm_name', n); localStorage.setItem('cm_surname', s); }catch(e){}
    }
    ['#pName','#pSurname'].forEach(id=>{ const el=$(id); if(el){ ['input','change','blur'].forEach(evt=> el.addEventListener(evt, saveP)); }});
    // Prefill from storage
    try{
      const n0 = localStorage.getItem('cm_name')||''; const s0 = localStorage.getItem('cm_surname')||'';
      if(n0) $('#pName').value = n0; if(s0) $('#pSurname').value = s0; if(n0||s0) saveP();
    }catch(e){}

    // Secret icon -> egg
    $('#secretIcon').addEventListener('click', ()=>{ showSlide(getSlideIndex('egg')); confettiBurst(); blip(); });
    $('#partyBtn').addEventListener('click', ()=>{ confettiBurst(240); blip(); });

    function confettiBurst(n=120){
      const layer = $('#confetti'); layer.innerHTML='';
      const colors=['#0a66c2','#69a5ff','#16a34a','#f59e0b','#ef4444'];
      for(let i=0;i<n;i++){
        const p=document.createElement('i');
        p.style.left = Math.random()*100+'%';
        p.style.background = colors[i%colors.length];
        p.style.transform = `translateY(${Math.random()*-20}vh)`;
        p.style.animation = `fall ${2+Math.random()*2.5}s linear ${Math.random()*1.2}s forwards`;
        layer.appendChild(p);
      }
      setTimeout(()=> layer.innerHTML='', 4500);
    }

    // Certificate
    $('#certBtn').addEventListener('click', ()=>{
      if(!(state.participant.name && state.participant.surname)){
        alert('Inserisci nome e cognome nella prima slide per generare l\'attestato.');
        showSlide(0); return;
      }
      openModal('#certModal');
      drawCertificate();
    });
    $('#downloadCert').addEventListener('click', ()=>{
      const cnv = $('#certCanvas');
      const a = document.createElement('a');
      const fullname = `${state.participant.name} ${state.participant.surname}`.trim();
      a.href = cnv.toDataURL('image/png');
      a.download = `Attestato_${fullname || 'CareerMatch'}.png`;
      a.click();
    });

    function drawCertificate(){
      const cnv = $('#certCanvas'); const ctx = cnv.getContext('2d');
      const W = cnv.width, H = cnv.height; ctx.clearRect(0,0,W,H);
      // background
      ctx.fillStyle = '#ffffff'; ctx.fillRect(0,0,W,H);
      // border
      ctx.strokeStyle = '#0a66c2'; ctx.lineWidth = 8; ctx.strokeRect(20,20,W-40,H-40);
      // header band
      const grad = ctx.createLinearGradient(0,0,W,0);
      grad.addColorStop(0,'#0a66c2'); grad.addColorStop(1,'#69a5ff');
      ctx.fillStyle = grad; ctx.fillRect(20,90,W-40,10);
      // Title
      ctx.fillStyle = '#1f2937';
      ctx.font = 'bold 54px Montserrat, Roboto, Arial';
      ctx.textAlign = 'center';
      ctx.fillText('ATTESTATO DI PARTECIPAZIONE', W/2, 70);
      // Subtitle
      ctx.font = '24px Roboto, Arial';
      ctx.fillText('Si attesta che', W/2, 180);
      // Name
      const fullname = `${state.participant.name||''} ${state.participant.surname||''}`.trim() || '—';
      ctx.font = 'bold 64px Montserrat, Roboto, Arial';
      ctx.fillText(fullname, W/2, 260);
      // Body text
      ctx.font = '24px Roboto, Arial';
      const prof = PROFILES[state.lastProfile||'fixed'];
      const line1 = 'ha completato il Career Test in stile assessment';
      const line2 = `Profilo risultante: ${prof.pill}`;
      ctx.fillText(line1, W/2, 320);
      ctx.fillText(line2, W/2, 360);
      // Footer: date and signature
      const d = new Date();
      const it = d.toLocaleDateString('it-IT', { day:'2-digit', month:'long', year:'numeric' });
      ctx.textAlign = 'left'; ctx.fillText(`Data: ${it}`, 60, H-120);
      ctx.textAlign = 'right'; ctx.fillText(`Firma: ${state.config.name}`, W-60, H-120);
      ctx.font = '600 18px Roboto, Arial'; ctx.textAlign = 'center';
      ctx.fillStyle = '#6b7280';
      ctx.fillText('CareerMatch™ – Demo accademica', W/2, H-50);
    }

    // Start wiring
    setProgress(); updateBars();

    // Link live updates if settings prefilled through URL params
    const params = new URLSearchParams(location.search);
    const n = params.get('name'); const l = params.get('linkedin');
    if(n){ state.config.name = n; byName.textContent = n; $('#fakeName').value = n; }
    if(l){ state.config.linkedin = l; $('#finalReal').href = l; }

    // Accessibility helpers: focus rings on keyboard nav
    let usingKeyboard=false; window.addEventListener('keydown',()=>{ usingKeyboard=true; document.body.classList.add('kb'); });
    window.addEventListener('mousedown',()=>{ usingKeyboard=false; document.body.classList.remove('kb'); });

  </script>
</body>
</html>
