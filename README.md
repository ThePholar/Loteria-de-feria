<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Política de Privacidad — Lotería de Feria</title>
  <style>
    :root {
      --bg-dark: #080808;
      --bg-wine: #2A0813;
      --card-bg: rgba(42, 8, 19, 0.45);
      --border: rgba(230, 194, 79, 0.25);
      --accent: #E6C24F;
      --text-main: #F5F2F3;
      --text-muted: #C2B6BA;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background: radial-gradient(circle at top center, var(--bg-wine) 0%, var(--bg-dark) 65%);
      background-attachment: fixed;
      color: var(--text-main);
      line-height: 1.65;
      min-height: 100vh;
      padding: 28px 16px 48px;
    }

    .container {
      max-width: 780px;
      margin: 0 auto;
    }

    header {
      text-align: center;
      margin-bottom: 24px;
    }

    .badge {
      display: inline-block;
      font-size: 0.78rem;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      color: var(--accent);
      background: rgba(230, 194, 79, 0.12);
      border: 1px solid var(--border);
      padding: 5px 12px;
      border-radius: 999px;
      margin-bottom: 12px;
    }

    h1 {
      font-size: 1.9rem;
      font-weight: 700;
      margin-bottom: 8px;
    }

    .meta {
      color: var(--text-muted);
      font-size: 0.9rem;
    }

    .lang-switch {
      display: inline-flex;
      gap: 8px;
      margin-top: 18px;
      background: rgba(255, 255, 255, 0.04);
      border: 1px solid var(--border);
      padding: 5px;
      border-radius: 999px;
    }

    .lang-btn {
      border: none;
      background: transparent;
      color: var(--text-muted);
      font-size: 0.9rem;
      font-weight: 600;
      padding: 7px 18px;
      border-radius: 999px;
      cursor: pointer;
      transition: all 0.2s ease;
    }

    .lang-btn.active {
      background: var(--accent);
      color: #1A060C;
    }

    .card {
      background: var(--card-bg);
      backdrop-filter: blur(16px);
      -webkit-backdrop-filter: blur(16px);
      border: 1px solid var(--border);
      border-radius: 20px;
      padding: 28px 26px;
      box-shadow: 0 16px 40px rgba(0, 0, 0, 0.45);
    }

    h2 {
      color: var(--accent);
      font-size: 1.15rem;
      margin-top: 24px;
      margin-bottom: 8px;
    }

    h2:first-of-type {
      margin-top: 14px;
    }

    p {
      color: var(--text-main);
      margin-bottom: 10px;
      font-size: 0.96rem;
    }

    ul {
      margin: 8px 0 12px 20px;
      color: var(--text-muted);
      font-size: 0.95rem;
    }

    li {
      margin-bottom: 6px;
    }

    li strong {
      color: var(--text-main);
    }

    a {
      color: var(--accent);
      text-decoration: none;
      border-bottom: 1px dotted rgba(230, 194, 79, 0.5);
    }

    a:hover {
      border-bottom-style: solid;
    }

    .contact-box {
      margin-top: 10px;
      padding: 14px 16px;
      background: rgba(8, 8, 8, 0.55);
      border: 1px solid var(--border);
      border-radius: 12px;
      font-size: 0.94rem;
    }

    .contact-box div {
      margin-bottom: 4px;
    }

    .contact-box div:last-child {
      margin-bottom: 0;
    }

    .hidden {
      display: none;
    }

    footer {
      text-align: center;
      margin-top: 24px;
      color: var(--text-muted);
      font-size: 0.84rem;
    }

    @media (max-width: 540px) {
      .card {
        padding: 22px 18px;
      }
      h1 {
        font-size: 1.55rem;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="badge">Offline-First &amp; 100% Privado</div>
      <h1 id="page-title">Lotería de Feria</h1>
      <div class="meta">com.thepholar.loteriadeferia · ThePholar</div>
      <div class="lang-switch" role="tablist" aria-label="Idioma / Language">
        <button id="btn-es" class="lang-btn active" onclick="setLang('es')">Español</button>
        <button id="btn-en" class="lang-btn" onclick="setLang('en')">English</button>
      </div>
    </header>

    <!-- VERSIÓN EN ESPAÑOL -->
    <main id="content-es" class="card">
      <p class="meta"><strong>Última actualización:</strong> 25 de noviembre de 2026</p>
      <p>
        En <strong>Lotería de Feria</strong>, tu privacidad es una prioridad. Esta aplicación ha sido diseñada bajo una arquitectura <strong>100% Offline-First y privada</strong>, pensada para disfrutarse sin cuentas, registros ni rastreo de tu actividad.
      </p>

      <h2>1. Datos que recopilamos</h2>
      <p><strong>Lotería de Feria no recopila, almacena, vende ni comparte datos personales.</strong></p>
      <ul>
        <li>No requiere creación de cuentas, inicio de sesión, nombre, teléfono ni correo electrónico.</li>
        <li>No incluye anuncios publicitarios, rastreadores, SDKs de analítica de terceros ni perfiles de comportamiento.</li>
        <li>No contamos con servidores externos que reciban información de tus partidas o de tu dispositivo.</li>
      </ul>

      <h2>2. Uso de Internet (Compras y licencias en Google Play)</h2>
      <p>
        La aplicación funciona sin conexión a Internet. El acceso a la red se utiliza <strong>única y exclusivamente</strong> para comunicarse con los servicios oficiales de <strong>Google Play Billing</strong> con el fin de:
      </p>
      <ul>
        <li>Consultar precios locales y disponibilidad de la suscripción PRO (plan mensual con prueba gratuita y plan anual) y la compra única PRO de por vida.</li>
        <li>Procesar, verificar y restaurar licencias o suscripciones activas vinculadas a tu cuenta de Google Play.</li>
      </ul>
      <p>
        Todos los pagos son gestionados directamente por Google Play. El desarrollador <strong>nunca</strong> tiene acceso a tus datos bancarios ni de tarjeta. Consulta la <a href="https://policies.google.com/privacy" target="_blank" rel="noopener">Política de Privacidad de Google</a>.
      </p>

      <h2>3. Almacenamiento local en tu dispositivo</h2>
      <p>Toda la información generada permanece <strong>exclusivamente en el almacenamiento privado de tu dispositivo</strong>:</p>
      <ul>
        <li>Preferencias de idioma, voz, velocidad, estilo de narración y tema visual.</li>
        <li>Tablas favoritas y progreso de la Sala de Trofeos.</li>
        <li>Estado en caché de tu licencia PRO para permitir el uso 100% offline.</li>
      </ul>
      <p>Estos datos nunca salen de tu teléfono y se eliminan por completo si borras los datos de la app o la desinstalas.</p>

      <h2>4. Reportes de fallos y soporte técnico (Envío voluntario)</h2>
      <p>
        Si ocurre un cierre inesperado o un error técnico, la app guarda localmente un registro temporal de diagnóstico (marca, modelo, versión de Android, versión de la app y código/traza del error).
      </p>
      <ul>
        <li><strong>Este diagnóstico nunca se envía de forma automática.</strong></li>
        <li>Solo se comparte si decides voluntariamente pulsar el botón de envío mediante Correo electrónico, Telegram o Signal para solicitar soporte técnico, y se usa únicamente para corregir el fallo reportado.</li>
      </ul>

      <h2>5. Funciones locales del sistema</h2>
      <ul>
        <li><strong>Voz (Text-to-Speech):</strong> Utiliza el motor de voz instalado localmente en tu dispositivo Android.</li>
        <li><strong>Exportación e impresión (PDF):</strong> Los archivos PDF se generan localmente y solo se comparten o imprimen cuando tú lo solicitas.</li>
        <li><strong>Vibración y pantalla activa:</strong> Se utilizan únicamente durante las partidas según tus preferencias.</li>
      </ul>

      <h2>6. Privacidad de menores</h2>
      <p>
        Lotería de Feria es un juego familiar apto para todo público. Al no recopilar ningún dato personal ni identificable de ningún usuario, tampoco recopila información de menores de edad.
      </p>

      <h2>7. Cambios en esta Política de Privacidad</h2>
      <p>
        Podemos actualizar esta política ocasionalmente para reflejar mejoras en la aplicación o requisitos de Google Play. Cualquier cambio se publicará en esta misma página y dentro de la app con su fecha actualizada.
      </p>

      <h2>8. Contacto del desarrollador</h2>
      <p>Si tienes preguntas sobre esta Política de Privacidad o necesitas soporte técnico, puedes contactar a <strong>ThePholar</strong> en:</p>
      <div class="contact-box">
        <div><strong>Correo:</strong> <a href="mailto:polarxd@icloud.com">polarxd@icloud.com</a></div>
        <div><strong>Telegram:</strong> <a href="https://t.me/thepholar" target="_blank" rel="noopener">@thepholar</a></div>
        <div><strong>Signal:</strong> polar.2077</div>
      </div>
    </main>

    <!-- ENGLISH VERSION -->
    <main id="content-en" class="card hidden">
      <p class="meta"><strong>Last updated:</strong> November 25, 2026</p>
      <p>
        At <strong>Lotería de Feria</strong>, your privacy comes first. This application is built with a <strong>100% Offline-First, privacy-focused architecture</strong>, designed to be enjoyed without accounts, sign-ups, or activity tracking.
      </p>

      <h2>1. Data We Collect</h2>
      <p><strong>Lotería de Feria does not collect, store, sell, or share personal data.</strong></p>
      <ul>
        <li>No user accounts, logins, names, phone numbers, or email addresses are required.</li>
        <li>No advertisements, trackers, third-party analytics SDKs, or behavioral profiling.</li>
        <li>We do not operate external servers that receive information about your games or your device.</li>
      </ul>

      <h2>2. Internet Access (Google Play Purchases &amp; Licensing)</h2>
      <p>
        The application works offline. Network access is used <strong>strictly and exclusively</strong> to communicate with official <strong>Google Play Billing</strong> services in order to:
      </p>
      <ul>
        <li>Retrieve local pricing and availability for the PRO subscription (monthly plan with free trial and annual plan) and the Lifetime PRO one-time purchase.</li>
        <li>Process, verify, and restore active licenses or subscriptions linked to your Google Play account.</li>
      </ul>
      <p>
        All payments and billing are handled directly by Google Play. The developer <strong>never</strong> accesses your payment credentials or bank details. See the <a href="https://policies.google.com/privacy" target="_blank" rel="noopener">Google Privacy Policy</a>.
      </p>

      <h2>3. Local On-Device Storage</h2>
      <p>All app data remains <strong>strictly within your device's private local storage</strong>:</p>
      <ul>
        <li>Language, voice, speed, narration style, and visual theme preferences.</li>
        <li>Favorite boards and Trophy Room progress.</li>
        <li>Cached PRO license status so you can use the app 100% offline.</li>
      </ul>
      <p>This data never leaves your phone and is permanently deleted if you clear app data or uninstall the application.</p>

      <h2>4. Crash Reports &amp; Technical Support (Strictly Voluntary)</h2>
      <p>
        If an unexpected crash or technical error occurs, the app saves a temporary diagnostic log locally (device brand, model, Android version, app version, and error stack trace).
      </p>
      <ul>
        <li><strong>This diagnostic log is never transmitted automatically.</strong></li>
        <li>It is only shared if you manually choose to send it via Email, Telegram, or Signal for technical support, and it is used solely to fix the reported issue.</li>
      </ul>

      <h2>5. Local Device Features</h2>
      <ul>
        <li><strong>Voice (Text-to-Speech):</strong> Uses your Android device's local Text-to-Speech engine.</li>
        <li><strong>PDF Export &amp; Printing:</strong> PDF files are generated locally and only shared or printed when triggered by you.</li>
        <li><strong>Vibration &amp; Keep Screen Awake:</strong> Used locally during gameplay according to your settings.</li>
      </ul>

      <h2>6. Children's Privacy</h2>
      <p>
        Lotería de Feria is a traditional family-friendly game. Because the application does not collect any personal or identifiable information from any user, it does not knowingly collect personal information from children.
      </p>

      <h2>7. Changes to This Privacy Policy</h2>
      <p>
        We may update this policy occasionally to reflect app improvements or Google Play requirements. Any updates will be published on this page and inside the app with the revised date.
      </p>

      <h2>8. Developer Contact</h2>
      <p>If you have questions about this Privacy Policy or need technical support, contact <strong>ThePholar</strong> at:</p>
      <div class="contact-box">
        <div><strong>Email:</strong> <a href="mailto:polarxd@icloud.com">polarxd@icloud.com</a></div>
        <div><strong>Telegram:</strong> <a href="https://t.me/thepholar" target="_blank" rel="noopener">@thepholar</a></div>
        <div><strong>Signal:</strong> polar.2077</div>
      </div>
    </main>

    <footer>
      © 2026 ThePholar · Lotería de Feria
    </footer>
  </div>

  <script>
    function setLang(lang) {
      const es = document.getElementById('content-es');
      const en = document.getElementById('content-en');
      const btnEs = document.getElementById('btn-es');
      const btnEn = document.getElementById('btn-en');

      if (lang === 'en') {
        es.classList.add('hidden');
        en.classList.remove('hidden');
        btnEs.classList.remove('active');
        btnEn.classList.add('active');
        document.documentElement.lang = 'en';
        document.title = 'Privacy Policy — Lotería de Feria';
      } else {
        en.classList.add('hidden');
        es.classList.remove('hidden');
        btnEn.classList.remove('active');
        btnEs.classList.add('active');
        document.documentElement.lang = 'es';
        document.title = 'Política de Privacidad — Lotería de Feria';
      }
    }

    if ((navigator.language || '').toLowerCase().startsWith('en')) {
      setLang('en');
    }
  </script>
</body>
</html>
