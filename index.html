<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>J'ai quelque chose à te demander... 💌</title>
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
      min-height: 100vh;
      background: #fff0f5;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 1.5rem;
      overflow-x: hidden;
    }

    /* Floating hearts background */
    .hearts-bg {
      position: fixed;
      inset: 0;
      pointer-events: none;
      z-index: 0;
      overflow: hidden;
    }
    .heart-float {
      position: absolute;
      bottom: -40px;
      font-size: 20px;
      color: #e8829e;
      opacity: 0.18;
      animation: floatUp linear infinite;
    }
    @keyframes floatUp {
      0%   { transform: translateY(0) rotate(-10deg); opacity: 0.18; }
      80%  { opacity: 0.18; }
      100% { transform: translateY(-105vh) rotate(10deg); opacity: 0; }
    }

    /* Card */
    .card {
      background: #fff;
      border-radius: 20px;
      box-shadow: 0 8px 40px rgba(212, 83, 126, 0.12);
      padding: 2.5rem 2rem 2rem;
      width: 100%;
      max-width: 460px;
      position: relative;
      z-index: 1;
    }

    /* Header */
    .header {
      text-align: center;
      margin-bottom: 2rem;
    }
    .header-icon {
      font-size: 48px;
      display: block;
      margin-bottom: 0.75rem;
      animation: heartbeat 1.2s ease-in-out infinite;
    }
    @keyframes heartbeat {
      0%, 100% { transform: scale(1); }
      50%       { transform: scale(1.15); }
    }
    .header h1 {
      font-size: 20px;
      font-weight: 600;
      color: #2c1a22;
      margin-bottom: 6px;
    }
    .header p {
      font-size: 13.5px;
      color: #9b7085;
    }

    /* Form fields */
    .row { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; }
    .field { margin-bottom: 1.1rem; }
    label {
      display: block;
      font-size: 12.5px;
      font-weight: 600;
      color: #9b7085;
      text-transform: uppercase;
      letter-spacing: 0.05em;
      margin-bottom: 6px;
    }
    input[type="text"] {
      width: 100%;
      height: 42px;
      border: 1.5px solid #f0c0d0;
      border-radius: 10px;
      padding: 0 14px;
      font-size: 14px;
      color: #2c1a22;
      background: #fff;
      outline: none;
      transition: border-color 0.2s, box-shadow 0.2s;
    }
    input[type="text"]:focus {
      border-color: #D4537E;
      box-shadow: 0 0 0 3px rgba(212, 83, 126, 0.15);
    }
    input[type="text"]::placeholder { color: #cca8b8; }

    /* Status buttons */
    .status-options { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-top: 4px; }
    .status-btn {
      border: 1.5px solid #f0c0d0;
      border-radius: 12px;
      padding: 12px 8px;
      text-align: center;
      cursor: pointer;
      font-size: 13.5px;
      font-weight: 600;
      background: #fff8fb;
      color: #9b7085;
      transition: all 0.18s;
      user-select: none;
    }
    .status-btn:hover { border-color: #D4537E; color: #993556; background: #fdeaf1; }
    .status-btn .s-icon { font-size: 22px; display: block; margin-bottom: 5px; }
    .status-btn.selected-celibataire {
      border: 2px solid #D4537E;
      background: #fdeaf1;
      color: #993556;
    }
    .status-btn.selected-couple {
      border: 2px solid #aaa;
      background: #f8f8f8;
      color: #555;
    }

    /* Error */
    .error { font-size: 11.5px; color: #E24B4A; margin-top: 4px; min-height: 16px; }

    /* Submit */
    .btn-submit {
      width: 100%;
      margin-top: 1.5rem;
      height: 46px;
      background: linear-gradient(135deg, #e8607e 0%, #D4537E 100%);
      color: #fff;
      border: none;
      border-radius: 12px;
      font-size: 15px;
      font-weight: 600;
      cursor: pointer;
      letter-spacing: 0.03em;
      transition: opacity 0.15s, transform 0.1s;
      box-shadow: 0 4px 18px rgba(212, 83, 126, 0.3);
    }
    .btn-submit:hover { opacity: 0.92; }
    .btn-submit:active { transform: scale(0.98); }

    /* Result page */
    .result-page { display: none; text-align: center; }
    .result-page.show { display: block; }
    .form-page.hide { display: none; }

    .result-big-heart {
      font-size: 72px;
      display: block;
      margin-bottom: 0.75rem;
      animation: heartbeat 0.7s ease-in-out infinite;
    }
    .result-tag {
      display: inline-block;
      background: #fdeaf1;
      color: #993556;
      border-radius: 20px;
      font-size: 12px;
      font-weight: 700;
      padding: 5px 16px;
      margin-bottom: 1rem;
      letter-spacing: 0.04em;
      text-transform: uppercase;
    }
    .result-title {
      font-size: 22px;
      font-weight: 700;
      color: #2c1a22;
      line-height: 1.4;
      margin-bottom: 1rem;
    }
    .result-name { color: #D4537E; }
    .result-msg {
      font-size: 14.5px;
      color: #7a5060;
      line-height: 1.75;
      margin-bottom: 1.5rem;
    }
    .result-msg strong { color: #D4537E; }

    /* Couple result */
    .sad-icon { font-size: 56px; display: block; margin-bottom: 0.75rem; }
    .couple-title { font-size: 20px; font-weight: 700; color: #2c1a22; margin-bottom: 0.75rem; }
    .couple-msg { font-size: 14px; color: #7a5060; line-height: 1.7; }

    /* Retry */
    .btn-retry {
      margin-top: 1.5rem;
      background: transparent;
      border: 1.5px solid #f0c0d0;
      border-radius: 10px;
      padding: 8px 24px;
      font-size: 13px;
      color: #9b7085;
      cursor: pointer;
      transition: background 0.15s;
    }
    .btn-retry:hover { background: #fff0f5; }

    /* Confetti */
    .confetti-piece {
      position: fixed;
      width: 9px;
      height: 9px;
      pointer-events: none;
      z-index: 9999;
      animation: confettiFall linear forwards;
    }
    @keyframes confettiFall {
      0%   { transform: translateY(-10px) rotate(0deg); opacity: 1; }
      100% { transform: translateY(105vh) rotate(720deg); opacity: 0; }
    }

    @media (max-width: 480px) {
      .card { padding: 2rem 1.25rem 1.5rem; }
      .row { grid-template-columns: 1fr; gap: 0; }
    }
  </style>
</head>
<body>

  <div class="hearts-bg" id="heartsBg"></div>

  <div class="card">

    <!-- FORMULAIRE -->
    <div class="form-page" id="formPage">
      <div class="header">
        <span class="header-icon">💌</span>
        <h1>J'ai quelque chose à te demander...</h1>
        <p>Réponds honnêtement, je promets que c'est important ✨</p>
      </div>

      <div class="row">
        <div class="field">
          <label>Prénom</label>
          <input type="text" id="prenom" placeholder="Ton prénom" autocomplete="off" />
          <div class="error" id="err-prenom"></div>
        </div>
        <div class="field">
          <label>Nom</label>
          <input type="text" id="nom" placeholder="Ton nom" autocomplete="off" />
          <div class="error" id="err-nom"></div>
        </div>
      </div>

      <div class="field">
        <label>Lieu de naissance</label>
        <input type="text" id="ville" placeholder="Ta ville de naissance" autocomplete="off" />
        <div class="error" id="err-ville"></div>
      </div>

      <div class="field">
        <label>Ton statut amoureux</label>
        <div class="status-options">
          <div class="status-btn" id="btn-celibataire" onclick="selectStatus('celibataire')">
            <span class="s-icon">🌹</span>
            Célibataire
          </div>
          <div class="status-btn" id="btn-couple" onclick="selectStatus('couple')">
            <span class="s-icon">💑</span>
            En couple
          </div>
        </div>
        <div class="error" id="err-status"></div>
      </div>

      <button class="btn-submit" onclick="submitForm()">💝 Envoyer ma réponse</button>
    </div>

    <!-- RÉSULTAT -->
    <div class="result-page" id="resultPage"></div>

  </div>

  <script>
    let selectedStatus = null;

    // Floating hearts
    (function () {
      const bg = document.getElementById('heartsBg');
      const icons = ['♥', '♡', '❤', '💕', '🌹'];
      for (let i = 0; i < 20; i++) {
        const h = document.createElement('span');
        h.className = 'heart-float';
        h.textContent = icons[Math.floor(Math.random() * icons.length)];
        h.style.left = (Math.random() * 100) + '%';
        h.style.fontSize = (12 + Math.random() * 14) + 'px';
        const dur = 7 + Math.random() * 9;
        h.style.animationDuration = dur + 's';
        h.style.animationDelay = (-Math.random() * dur) + 's';
        bg.appendChild(h);
      }
    })();

    function selectStatus(val) {
      selectedStatus = val;
      document.getElementById('btn-celibataire').className =
        'status-btn' + (val === 'celibataire' ? ' selected-celibataire' : '');
      document.getElementById('btn-couple').className =
        'status-btn' + (val === 'couple' ? ' selected-couple' : '');
      document.getElementById('err-status').textContent = '';
    }

    function validate() {
      let ok = true;
      const prenom = document.getElementById('prenom').value.trim();
      const nom    = document.getElementById('nom').value.trim();
      const ville  = document.getElementById('ville').value.trim();

      document.getElementById('err-prenom').textContent = prenom ? '' : 'Ce champ est requis';
      document.getElementById('err-nom').textContent    = nom    ? '' : 'Ce champ est requis';
      document.getElementById('err-ville').textContent  = ville  ? '' : 'Ce champ est requis';

      if (!prenom || !nom || !ville) ok = false;
      if (!selectedStatus) {
        document.getElementById('err-status').textContent = 'Choisis une option';
        ok = false;
      } else {
        document.getElementById('err-status').textContent = '';
      }
      return ok;
    }

    function submitForm() {
      if (!validate()) return;
      const prenom = document.getElementById('prenom').value.trim();
      const nom    = document.getElementById('nom').value.trim();
      const ville  = document.getElementById('ville').value.trim();
      showResult(prenom, nom, ville, selectedStatus);
    }

    function showResult(prenom, nom, ville, status) {
      document.getElementById('formPage').classList.add('hide');
      const rp = document.getElementById('resultPage');
      rp.classList.add('show');

      if (status === 'celibataire') {
        launchConfetti();
        rp.innerHTML = `
          <span class="result-big-heart">❤️</span>
          <div class="result-tag">✨ C'était écrit dans les étoiles</div>
          <p class="result-title">
            <span class="result-name">${escHtml(prenom)} ${escHtml(nom)}</span>,<br>
            tu seras ma chérie et mon amour 🌹
          </p>
          <p class="result-msg">
            Née à <strong>${escHtml(ville)}</strong>, tu es la personne<br>
            que mon cœur attendait depuis toujours.<br>
            Ce formulaire n'était pas un hasard — c'était le destin. 💌
          </p>
          <button class="btn-retry" onclick="resetForm()">↩ Recommencer</button>
        `;
      } else {
        rp.innerHTML = `
          <span class="sad-icon">💔</span>
          <p class="couple-title">Ahh, <span style="color:#D4537E">${escHtml(prenom)}</span>...</p>
          <p class="couple-msg">
            Née à <strong>${escHtml(ville)}</strong>, tu es déjà prise.<br>
            Quelqu'un a beaucoup de chance. 🍀<br><br>
            <em>Si jamais tu changes d'avis, tu sais où me trouver...</em>
          </p>
          <button class="btn-retry" onclick="resetForm()">↩ Recommencer</button>
        `;
      }
    }

    function launchConfetti() {
      const colors = ['#D4537E','#F4C0D1','#FBEAF0','#ED93B1','#FAC775','#85B7EB','#ff9eb5'];
      for (let i = 0; i < 70; i++) {
        setTimeout(() => {
          const c = document.createElement('div');
          c.className = 'confetti-piece';
          c.style.left = (Math.random() * 100) + 'vw';
          c.style.top = '-12px';
          c.style.background = colors[Math.floor(Math.random() * colors.length)];
          const size = 6 + Math.random() * 9;
          c.style.width = size + 'px';
          c.style.height = size + 'px';
          c.style.animationDuration = (1.8 + Math.random() * 2) + 's';
          c.style.borderRadius = Math.random() > 0.5 ? '50%' : '3px';
          document.body.appendChild(c);
          setTimeout(() => c.remove(), 4500);
        }, i * 35);
      }
    }

    function resetForm() {
      selectedStatus = null;
      ['prenom', 'nom', 'ville'].forEach(id => document.getElementById(id).value = '');
      ['err-prenom','err-nom','err-ville','err-status'].forEach(id => document.getElementById(id).textContent = '');
      document.getElementById('btn-celibataire').className = 'status-btn';
      document.getElementById('btn-couple').className = 'status-btn';
      document.getElementById('formPage').classList.remove('hide');
      const rp = document.getElementById('resultPage');
      rp.classList.remove('show');
      rp.innerHTML = '';
    }

    function escHtml(str) {
      return str.replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;');
    }
  </script>

</body>
</html>
