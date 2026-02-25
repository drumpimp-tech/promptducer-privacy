[privacy_policy.html](https://github.com/user-attachments/files/25538533/privacy_policy.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Privacy Policy — Prompt-Ducer</title>
  <style>
    :root {
      --bg:      #080C10;
      --surface: #0D1117;
      --border:  #1E2D3D;
      --cyan:    #06B6D4;
      --cyan-l:  #22D3EE;
      --text:    #E8F4F8;
      --subtext: #5B7A8E;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.75;
      padding: 40px 20px 80px;
    }
    .container { max-width: 760px; margin: 0 auto; }

    header {
      text-align: center;
      padding: 60px 0 48px;
      border-bottom: 1px solid var(--border);
      margin-bottom: 48px;
    }
    .logo-mark {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      width: 64px; height: 64px;
      border-radius: 16px;
      background: linear-gradient(135deg, #1A2E40, #0A1825);
      border: 1px solid rgba(34,211,238,0.3);
      box-shadow: 0 0 24px rgba(6,182,212,0.2);
      margin-bottom: 20px;
      font-size: 28px; font-weight: 900;
      background-clip: text;
      -webkit-background-clip: text;
    }
    .logo-p {
      font-size: 32px; font-weight: 900;
      background: linear-gradient(135deg, #22D3EE, #06B6D4);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      filter: drop-shadow(0 0 8px rgba(6,182,212,0.6));
    }
    h1 {
      font-size: 28px; font-weight: 800;
      background: linear-gradient(90deg, #22D3EE, #06B6D4);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      margin-bottom: 8px;
    }
    .subtitle {
      color: var(--subtext);
      font-size: 14px;
    }
    .effective {
      display: inline-block;
      margin-top: 12px;
      font-size: 12px;
      color: var(--cyan);
      background: rgba(6,182,212,0.08);
      border: 1px solid rgba(6,182,212,0.2);
      padding: 4px 12px;
      border-radius: 20px;
      font-family: 'SF Mono', 'Fira Code', monospace;
    }

    section {
      margin-bottom: 40px;
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 28px 32px;
    }
    h2 {
      font-size: 15px;
      font-weight: 700;
      color: var(--cyan-l);
      letter-spacing: 1.5px;
      text-transform: uppercase;
      font-family: 'SF Mono', 'Fira Code', monospace;
      margin-bottom: 14px;
      padding-bottom: 10px;
      border-bottom: 1px solid var(--border);
    }
    p { color: var(--text); font-size: 15px; margin-bottom: 12px; }
    p:last-child { margin-bottom: 0; }
    ul { padding-left: 20px; color: var(--text); font-size: 15px; }
    li { margin-bottom: 8px; }
    a { color: var(--cyan); text-decoration: none; }
    a:hover { text-decoration: underline; }

    .highlight {
      background: rgba(6,182,212,0.06);
      border-left: 3px solid var(--cyan);
      border-radius: 0 8px 8px 0;
      padding: 14px 18px;
      margin: 14px 0;
      font-size: 14px;
      color: var(--subtext);
    }

    footer {
      text-align: center;
      color: var(--subtext);
      font-size: 13px;
      padding-top: 40px;
      border-top: 1px solid var(--border);
    }
  </style>
</head>
<body>
<div class="container">

  <header>
    <div class="logo-mark"><span class="logo-p">P</span></div>
    <h1>Privacy Policy</h1>
    <p class="subtitle">Prompt-Ducer — From Idea To Creation</p>
    <span class="effective">Effective: February 24, 2026</span>
  </header>

  <section>
    <h2>Overview</h2>
    <p>Prompt-Ducer ("the App") is developed by TrevBeats Multimedia. This Privacy Policy explains how we handle information when you use our iOS application.</p>
    <div class="highlight">
      We do not collect, store, or sell your personal data. The App is designed to run with minimal data exposure.
    </div>
  </section>

  <section>
    <h2>Information We Do Not Collect</h2>
    <p>Prompt-Ducer does not collect, transmit, or store any of the following:</p>
    <ul>
      <li>Your name, email address, or any personally identifiable information</li>
      <li>Account credentials or authentication data</li>
      <li>Location data</li>
      <li>Device identifiers beyond standard iOS system identifiers</li>
      <li>Photos, contacts, calendar data, or any on-device content</li>
      <li>Health or biometric data</li>
    </ul>
  </section>

  <section>
    <h2>AI Prompt Generation</h2>
    <p>When you use the AI generation feature, your prompt topic or idea is sent to our secure cloud proxy (Firebase Cloud Functions), which forwards the request to Anthropic's Claude API to generate a response.</p>
    <ul>
      <li>Your input text is transmitted securely over HTTPS</li>
      <li>We do not log or store the content of your prompts on our servers</li>
      <li>Anthropic may process your input in accordance with their own <a href="https://www.anthropic.com/privacy" target="_blank">Privacy Policy</a></li>
      <li>Your Anthropic API key is never stored on your device — all API calls are proxied through our secure server</li>
    </ul>
  </section>

  <section>
    <h2>Local Data Storage</h2>
    <p>Prompt history and saved prompts are stored locally on your device using iOS UserDefaults. This data:</p>
    <ul>
      <li>Never leaves your device unless you explicitly share it</li>
      <li>Is not backed up to our servers</li>
      <li>Can be deleted at any time by deleting the App</li>
    </ul>
  </section>

  <section>
    <h2>Voice Input (Speech Recognition)</h2>
    <p>The App includes an optional voice input feature powered by Apple's Speech Recognition framework. If you use this feature:</p>
    <ul>
      <li>Audio is processed by Apple's on-device or server-based speech recognition</li>
      <li>We do not receive, store, or transmit your voice data</li>
      <li>Apple's use of this data is governed by <a href="https://www.apple.com/privacy/" target="_blank">Apple's Privacy Policy</a></li>
    </ul>
  </section>

  <section>
    <h2>Third-Party Services</h2>
    <p>The App uses the following third-party services:</p>
    <ul>
      <li><strong style="color: var(--cyan-l);">Anthropic Claude API</strong> — AI prompt generation. <a href="https://www.anthropic.com/privacy" target="_blank">Privacy Policy</a></li>
      <li><strong style="color: var(--cyan-l);">Google Firebase</strong> — Secure API proxy. <a href="https://firebase.google.com/support/privacy" target="_blank">Privacy Policy</a></li>
      <li><strong style="color: var(--cyan-l);">Apple Speech Framework</strong> — Optional voice input. <a href="https://www.apple.com/privacy/" target="_blank">Privacy Policy</a></li>
    </ul>
  </section>

  <section>
    <h2>Children's Privacy</h2>
    <p>Prompt-Ducer is not directed at children under the age of 13. We do not knowingly collect any personal information from children. If you believe a child has provided personal information through the App, please contact us immediately.</p>
  </section>

  <section>
    <h2>Changes to This Policy</h2>
    <p>We may update this Privacy Policy from time to time. Any changes will be posted at this URL with an updated effective date. Continued use of the App after changes constitutes your acceptance of the updated policy.</p>
  </section>

  <section>
    <h2>Contact</h2>
    <p>If you have any questions about this Privacy Policy, please contact us:</p>
    <p>
      <strong style="color: var(--cyan-l);">TrevBeats Multimedia</strong><br>
      <a href="mailto:trevbeatsmultimedia@gmail.com">trevbeatsmultimedia@gmail.com</a><br>
      <a href="https://github.com/drumpimp-tech" target="_blank">github.com/drumpimp-tech</a>
    </p>
  </section>

  <footer>
    <p>© 2026 TrevBeats Multimedia · Prompt-Ducer v3.0</p>
    <p style="margin-top: 6px;">This policy is hosted at <a href="https://drumpimp-tech.github.io/promptducer-privacy">drumpimp-tech.github.io/promptducer-privacy</a></p>
  </footer>

</div>
</body>
</html>
