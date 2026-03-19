<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>InsuDose Pro – Disclaimer Médical / Medical Disclaimer</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Sans:wght@300;400;500;600&display=swap');

  :root {
    --blue: #1a3a5c;
    --blue-mid: #2563a8;
    --blue-light: #e8f0fb;
    --accent: #e74c3c;
    --accent-light: #fdf0ef;
    --gold: #c8a84b;
    --text: #1a1a2e;
    --muted: #6b7280;
    --border: #dde5f0;
    --white: #ffffff;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    font-family: 'DM Sans', sans-serif;
    background: #f4f7fb;
    color: var(--text);
    min-height: 100vh;
  }

  /* HEADER */
  .header {
    background: var(--blue);
    color: white;
    padding: 48px 40px 36px;
    position: relative;
    overflow: hidden;
  }
  .header::before {
    content: '';
    position: absolute;
    top: -60px; right: -60px;
    width: 280px; height: 280px;
    border-radius: 50%;
    background: rgba(255,255,255,0.04);
  }
  .header::after {
    content: '';
    position: absolute;
    bottom: -80px; left: 30%;
    width: 200px; height: 200px;
    border-radius: 50%;
    background: rgba(255,255,255,0.03);
  }
  .logo-row {
    display: flex;
    align-items: center;
    gap: 14px;
    margin-bottom: 20px;
  }
  .logo-icon {
    width: 44px; height: 44px;
    background: var(--gold);
    border-radius: 12px;
    display: flex; align-items: center; justify-content: center;
    font-size: 22px;
  }
  .logo-text {
    font-family: 'DM Serif Display', serif;
    font-size: 22px;
    letter-spacing: 0.02em;
  }
  .logo-text span { color: var(--gold); }
  .header h1 {
    font-family: 'DM Serif Display', serif;
    font-size: clamp(26px, 4vw, 38px);
    font-weight: 400;
    line-height: 1.2;
    margin-bottom: 12px;
  }
  .header-sub {
    font-size: 14px;
    color: rgba(255,255,255,0.55);
    letter-spacing: 0.08em;
    text-transform: uppercase;
  }

  /* LANG TABS */
  .lang-tabs {
    display: flex;
    gap: 0;
    background: white;
    border-bottom: 2px solid var(--border);
    padding: 0 40px;
  }
  .lang-tab {
    padding: 14px 28px;
    font-size: 14px;
    font-weight: 500;
    letter-spacing: 0.04em;
    cursor: pointer;
    border-bottom: 2px solid transparent;
    margin-bottom: -2px;
    color: var(--muted);
    transition: all 0.2s;
    user-select: none;
  }
  .lang-tab.active {
    color: var(--blue-mid);
    border-bottom-color: var(--blue-mid);
  }

  /* CONTAINER */
  .container {
    max-width: 820px;
    margin: 0 auto;
    padding: 40px 24px 80px;
  }

  /* WARNING BANNER */
  .warning-banner {
    background: var(--accent-light);
    border: 1.5px solid #f5c6c2;
    border-left: 5px solid var(--accent);
    border-radius: 10px;
    padding: 20px 24px;
    margin-bottom: 36px;
    display: flex;
    gap: 16px;
    align-items: flex-start;
  }
  .warning-icon { font-size: 24px; flex-shrink: 0; margin-top: 2px; }
  .warning-text { font-size: 15px; line-height: 1.65; color: #7f1d1d; }
  .warning-text strong { display: block; font-size: 16px; margin-bottom: 4px; }

  /* SECTION */
  .section {
    background: white;
    border-radius: 14px;
    border: 1px solid var(--border);
    margin-bottom: 20px;
    overflow: hidden;
  }
  .section-header {
    display: flex;
    align-items: center;
    gap: 14px;
    padding: 20px 24px;
    border-bottom: 1px solid var(--border);
    background: var(--blue-light);
  }
  .section-num {
    width: 30px; height: 30px;
    background: var(--blue);
    color: white;
    border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    font-size: 13px;
    font-weight: 600;
    flex-shrink: 0;
  }
  .section-title {
    font-family: 'DM Serif Display', serif;
    font-size: 17px;
    color: var(--blue);
  }
  .section-body {
    padding: 22px 24px;
    font-size: 15px;
    line-height: 1.75;
    color: #374151;
  }
  .section-body ul {
    padding-left: 20px;
    margin-top: 10px;
  }
  .section-body li {
    margin-bottom: 8px;
  }
  .section-body strong {
    color: var(--text);
  }

  /* ACCEPTANCE BOX */
  .acceptance {
    background: var(--blue);
    color: white;
    border-radius: 14px;
    padding: 30px 28px;
    margin-top: 32px;
  }
  .acceptance h3 {
    font-family: 'DM Serif Display', serif;
    font-size: 20px;
    font-weight: 400;
    margin-bottom: 14px;
  }
  .acceptance p {
    font-size: 14px;
    line-height: 1.7;
    color: rgba(255,255,255,0.75);
    margin-bottom: 20px;
  }
  .checkbox-row {
    display: flex;
    align-items: flex-start;
    gap: 12px;
    background: rgba(255,255,255,0.08);
    border-radius: 10px;
    padding: 16px 18px;
    cursor: pointer;
  }
  .checkbox-row input[type=checkbox] {
    width: 20px; height: 20px;
    flex-shrink: 0;
    margin-top: 2px;
    accent-color: var(--gold);
    cursor: pointer;
  }
  .checkbox-label {
    font-size: 14px;
    line-height: 1.6;
    color: rgba(255,255,255,0.9);
  }

  /* VERSION NOTE */
  .version-note {
    text-align: center;
    font-size: 12px;
    color: var(--muted);
    margin-top: 32px;
    letter-spacing: 0.03em;
  }

  /* LANG PANELS */
  .lang-panel { display: none; }
  .lang-panel.active { display: block; }

  @media (max-width: 600px) {
    .header { padding: 32px 20px 28px; }
    .lang-tabs { padding: 0 16px; }
    .container { padding: 24px 16px 60px; }
    .section-body { padding: 18px 18px; }
  }
</style>
</head>
<body>

<div class="header">
  <div class="logo-row">
    <div class="logo-icon">💉</div>
    <div class="logo-text">Insu<span>Dose</span> Pro</div>
  </div>
  <h1>Disclaimer Médical<br><em style="font-style:italic;opacity:0.7;font-size:0.75em">Medical Disclaimer</em></h1>
  <div class="header-sub">Version 1.0 — Décembre 2025</div>
</div>

<div class="lang-tabs">
  <div class="lang-tab active" onclick="switchLang('fr')">🇫🇷 Français</div>
  <div class="lang-tab" onclick="switchLang('en')">🇬🇧 English</div>
</div>

<!-- ===================== FRANÇAIS ===================== -->
<div class="lang-panel active" id="panel-fr">
<div class="container">

  <div class="warning-banner">
    <div class="warning-icon">⚠️</div>
    <div class="warning-text">
      <strong>À lire avant toute utilisation</strong>
      InsuDose Pro est un outil d'aide au calcul. Il ne remplace en aucun cas l'avis, le suivi ou les prescriptions d'un professionnel de santé qualifié.
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">1</div>
      <div class="section-title">Nature de l'application</div>
    </div>
    <div class="section-body">
      InsuDose Pro est un <strong>calculateur d'aide à la gestion du diabète</strong>, conçu et distribué à titre strictement personnel et communautaire, sans but commercial.
      <ul>
        <li>L'application <strong>n'est pas un dispositif médical</strong> au sens du règlement européen MDR 2017/745.</li>
        <li>Elle <strong>ne pose aucun diagnostic</strong>, ne prescrit aucun traitement et ne remplace aucune décision médicale.</li>
        <li>Les résultats affichés sont <strong>purement indicatifs</strong> et basés uniquement sur les paramètres que vous avez saisis.</li>
      </ul>
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">2</div>
      <div class="section-title">Responsabilité de l'utilisateur</div>
    </div>
    <div class="section-body">
      En utilisant InsuDose Pro, vous reconnaissez et acceptez que :
      <ul>
        <li>Vous êtes <strong>seul(e) responsable</strong> des décisions prises sur la base des calculs affichés.</li>
        <li>Toute dose d'insuline doit être <strong>validée par rapport à votre ressenti clinique</strong>, votre expérience personnelle et les recommandations de votre médecin ou diabétologue.</li>
        <li>L'application ne tient pas compte de facteurs individuels tels que le stress, l'activité physique, la maladie, les interactions médicamenteuses ou d'autres paramètres physiologiques susceptibles d'affecter votre glycémie.</li>
        <li><strong>En cas de doute, ne vous injectez pas d'insuline</strong> et consultez immédiatement un professionnel de santé.</li>
      </ul>
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">3</div>
      <div class="section-title">Analyse des repas par photo (IA)</div>
    </div>
    <div class="section-body">
      La fonctionnalité d'analyse nutritionnelle par photo utilise un service d'intelligence artificielle. À ce titre :
      <ul>
        <li>Les estimations de glucides fournies sont <strong>approximatives</strong> et peuvent varier en fonction de la qualité de l'image, des aliments présents et des limites inhérentes à l'IA.</li>
        <li>Ces estimations ne constituent <strong>pas une valeur nutritionnelle certifiée</strong> et doivent être traitées avec discernement.</li>
        <li>L'image est transmise temporairement à un service tiers pour analyse et <strong>n'est pas conservée</strong> après traitement.</li>
      </ul>
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">4</div>
      <div class="section-title">Limitation de responsabilité du développeur</div>
    </div>
    <div class="section-body">
      Franck Malherbe, développeur d'InsuDose Pro, est un particulier diabétique ayant créé cet outil pour sa propre gestion et celle de la communauté diabétique.
      <ul>
        <li>Il n'est <strong>pas professionnel de santé</strong>.</li>
        <li>Il ne peut être tenu responsable d'aucun préjudice direct, indirect, corporel ou médical résultant de l'utilisation ou de la mauvaise utilisation de l'application.</li>
        <li>L'application est fournie <strong>"telle quelle"</strong>, sans garantie d'exactitude, de fiabilité ou d'adéquation à un usage médical.</li>
        <li>En cas de litige, la loi belge est applicable et les tribunaux de Belgique sont compétents.</li>
      </ul>
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">5</div>
      <div class="section-title">Recommandations importantes</div>
    </div>
    <div class="section-body">
      <ul>
        <li>Consultez régulièrement votre <strong>médecin ou diabétologue</strong> pour ajuster vos ratios et paramètres.</li>
        <li>Ne modifiez jamais votre traitement sans avis médical.</li>
        <li>Gardez toujours un <strong>sucre rapide à portée de main</strong> en cas d'hypoglycémie.</li>
        <li>En cas d'urgence glycémique, appelez le <strong>112</strong> ou votre médecin traitant.</li>
      </ul>
    </div>
  </div>

  <div class="acceptance">
    <h3>Acceptation du disclaimer</h3>
    <p>En cochant cette case et en utilisant InsuDose Pro, vous confirmez avoir lu, compris et accepté l'intégralité de ce disclaimer dans sa version française et anglaise. Vous reconnaissez utiliser cet outil en pleine connaissance de ses limites.</p>
    <label class="checkbox-row">
      <input type="checkbox" id="accept-fr">
      <span class="checkbox-label">J'ai lu et j'accepte le disclaimer médical d'InsuDose Pro. Je comprends que cette application est un outil d'aide au calcul et non un dispositif médical, et que je suis seul(e) responsable des décisions prises.</span>
    </label>
  </div>

  <div class="version-note">
    InsuDose Pro v2 — Disclaimer Médical v1.0 — Décembre 2025<br>
    Développé par Franck Malherbe — Belgique<br>
    Contact : peak.beryl8090@eagereverest.com
  </div>

</div>
</div>

<!-- ===================== ENGLISH ===================== -->
<div class="lang-panel" id="panel-en">
<div class="container">

  <div class="warning-banner">
    <div class="warning-icon">⚠️</div>
    <div class="warning-text">
      <strong>Please read before use</strong>
      InsuDose Pro is a calculation assistance tool. It does not replace the advice, monitoring, or prescriptions of a qualified healthcare professional.
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">1</div>
      <div class="section-title">Nature of the Application</div>
    </div>
    <div class="section-body">
      InsuDose Pro is a <strong>diabetes management calculation assistant</strong>, designed and distributed on a strictly personal and community basis, with no commercial intent.
      <ul>
        <li>The application <strong>is not a medical device</strong> within the meaning of European Regulation MDR 2017/745.</li>
        <li>It <strong>does not diagnose</strong> any condition, prescribe any treatment, or substitute any medical decision.</li>
        <li>The results displayed are <strong>purely indicative</strong> and based solely on the parameters you have entered.</li>
      </ul>
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">2</div>
      <div class="section-title">User Responsibility</div>
    </div>
    <div class="section-body">
      By using InsuDose Pro, you acknowledge and agree that:
      <ul>
        <li>You are <strong>solely responsible</strong> for decisions made based on the calculations displayed.</li>
        <li>Any insulin dose must be <strong>validated against your clinical judgement</strong>, personal experience, and the recommendations of your physician or diabetologist.</li>
        <li>The application does not account for individual factors such as stress, physical activity, illness, drug interactions, or other physiological parameters that may affect your blood glucose.</li>
        <li><strong>If in doubt, do not inject insulin</strong> and immediately consult a healthcare professional.</li>
      </ul>
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">3</div>
      <div class="section-title">AI-Based Meal Photo Analysis</div>
    </div>
    <div class="section-body">
      The nutritional analysis feature using photos relies on an artificial intelligence service. As such:
      <ul>
        <li>Carbohydrate estimates provided are <strong>approximate</strong> and may vary depending on image quality, foods present, and the inherent limitations of AI.</li>
        <li>These estimates do <strong>not constitute certified nutritional values</strong> and should be treated with careful judgement.</li>
        <li>The image is temporarily transmitted to a third-party service for analysis and is <strong>not retained</strong> after processing.</li>
      </ul>
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">4</div>
      <div class="section-title">Developer Liability Limitation</div>
    </div>
    <div class="section-body">
      Franck Malherbe, developer of InsuDose Pro, is an individual living with diabetes who created this tool for personal use and for the benefit of the diabetic community.
      <ul>
        <li>He is <strong>not a healthcare professional</strong>.</li>
        <li>He cannot be held liable for any direct, indirect, physical, or medical damage resulting from the use or misuse of the application.</li>
        <li>The application is provided <strong>"as is"</strong>, without any guarantee of accuracy, reliability, or fitness for medical use.</li>
        <li>In the event of any dispute, Belgian law shall apply and Belgian courts shall have jurisdiction.</li>
      </ul>
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">5</div>
      <div class="section-title">Important Recommendations</div>
    </div>
    <div class="section-body">
      <ul>
        <li>Consult your <strong>physician or diabetologist</strong> regularly to adjust your ratios and parameters.</li>
        <li>Never change your treatment without medical advice.</li>
        <li>Always keep <strong>fast-acting sugar readily available</strong> in case of hypoglycemia.</li>
        <li>In the event of a glycemic emergency, call <strong>112</strong> or your GP immediately.</li>
      </ul>
    </div>
  </div>

  <div class="acceptance">
    <h3>Acceptance of Disclaimer</h3>
    <p>By checking this box and using InsuDose Pro, you confirm that you have read, understood, and accepted this disclaimer in full, in both its French and English versions. You acknowledge using this tool with full knowledge of its limitations.</p>
    <label class="checkbox-row">
      <input type="checkbox" id="accept-en">
      <span class="checkbox-label">I have read and accept the InsuDose Pro medical disclaimer. I understand that this application is a calculation assistance tool and not a medical device, and that I am solely responsible for any decisions made.</span>
    </label>
  </div>

  <div class="version-note">
    InsuDose Pro v2 — Medical Disclaimer v1.0 — December 2025<br>
    Developed by Franck Malherbe — Belgium<br>
    Contact: peak.beryl8090@eagereverest.com
  </div>

</div>
</div>

<script>
function switchLang(lang) {
  document.querySelectorAll('.lang-tab').forEach(t => t.classList.remove('active'));
  document.querySelectorAll('.lang-panel').forEach(p => p.classList.remove('active'));
  document.querySelector(`[onclick="switchLang('${lang}')"]`).classList.add('active');
  document.getElementById(`panel-${lang}`).classList.add('active');
}
</script>

</body>
</html>
