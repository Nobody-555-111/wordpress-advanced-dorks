<!--
  WordPress Advanced Dorks Arsenal
  Professional GitHub Profile README
  Designed by Nobody-555-111
-->

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1E1E2F,100:0D1117&height=200&section=header&text=WordPress%20Advanced%20Dorks%20Arsenal&fontSize=32&fontColor=5865F2&animation=fadeIn&fontAlignY=38" alt="header" />
</div>

<div align="center">
  <p>
    <strong><font size="4">🔍 A curated collection of 5000+ high‑precision Google dorks for uncovering sensitive information in WordPress sites.</font></strong><br>
    <em>Designed for authorized security testing, CTF challenges, and hardening your own web assets.</em>
  </p>
  <p>
    <img src="https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square&color=5865F2" />
    <img src="https://img.shields.io/badge/Target-WordPress-21759b?style=flat-square&logo=wordpress" />
    <img src="https://img.shields.io/badge/version-2.0-red?style=flat-square" />
    <img src="https://img.shields.io/badge/Dorks-5000%2B-brightgreen?style=flat-square" />
  </p>
</div>

<br>

<!-- ========== LEGAL NOTICE (Creative Card) ========== -->
<div align="center" style="margin: 0 auto 30px auto; max-width: 900px;">
  <div style="background: #1A1E2E; border-left: 6px solid #E03A3A; border-radius: 20px; padding: 20px; text-align: left;">
    <div style="display: flex; gap: 16px; align-items: flex-start;">
      <div style="font-size: 40px;">⚠️</div>
      <div>
        <strong style="color: #E03A3A; font-size: 18px;">LEGAL & ETHICAL NOTICE</strong><br>
        This repository is provided for <strong>educational and defensive purposes only</strong>.<br>
        Using these dorks against any website without explicit written permission is <strong>illegal</strong> and violates:<br>
        • CFAA (US), GDPR & national cybercrime laws (Europe), and similar regulations worldwide.<br><br>
        <strong>By using this material you agree:</strong><br>
        1. To test <strong>only your own WordPress sites</strong> or those you are authorized to audit.<br>
        2. To never use automated scanning tools without permission.<br>
        3. To responsibly disclose any findings.<br><br>
        <font color="#B5BAC1">The author (<code>@Nobody-555-111</code>) assumes <strong>zero liability</strong> for misuse. You have been warned.</font>
      </div>
    </div>
  </div>
</div>

<!-- ========== WHAT ARE THESE DORKS? (Glass Card) ========== -->
<div style="background: #0F131F; border-radius: 28px; padding: 24px; margin: 30px auto; max-width: 1000px; border: 1px solid #2A2F3F;">
  <h2 style="color:#5865F2; margin-top: 0;">📖 What are these dorks?</h2>
  <p>Google dorks are advanced search operators (<code>site:</code>, <code>inurl:</code>, <code>intitle:</code>, <code>filetype:</code>, etc.) that reveal data not meant to be public. This arsenal focuses <strong>exclusively on WordPress</strong> – the world's most popular CMS (43% of all websites).</p>
  <p>Each dork is crafted to find:</p>

  <!-- TABLE with creative gradient row -->
  <div style="overflow-x: auto;">
    <table style="width: 100%; border-collapse: collapse; background: #1A1E2E; border-radius: 20px; overflow: hidden;">
      <thead>
        <tr style="background: #5865F2; color: white;">
          <th style="padding: 12px; text-align: left;">Category</th>
          <th style="padding: 12px; text-align: left;">Examples of discovered data</th>
        </tr>
      </thead>
      <tbody>
        <tr style="border-bottom:1px solid #2A2F3F;"><td style="padding: 10px;">⚙️ <strong>Configuration</strong></td><td style="padding: 10px;"><code>wp-config.php</code>, <code>.env</code>, <code>phpinfo()</code>, database credentials</td></tr>
        <tr style="border-bottom:1px solid #2A2F3F;"><td style="padding: 10px;">💾 <strong>Backups</strong></td><td style="padding: 10px;"><code>.sql</code>, <code>.zip</code>, <code>.tar.gz</code>, <code>.wpress</code>, <code>.bak</code> files</td></tr>
        <tr style="border-bottom:1px solid #2A2F3F;"><td style="padding: 10px;">📜 <strong>Logs & Debug</strong></td><td style="padding: 10px;"><code>debug.log</code>, <code>error_log</code>, PHP fatal errors, SQL syntax leaks</td></tr>
        <tr style="border-bottom:1px solid #2A2F3F;"><td style="padding: 10px;">🗄️ <strong>Database dumps</strong></td><td style="padding: 10px;">Full <code>wp_users</code>, <code>wp_options</code>, WooCommerce orders</td></tr>
        <tr style="border-bottom:1px solid #2A2F3F;"><td style="padding: 10px;">🔑 <strong>API keys & secrets</strong></td><td style="padding: 10px;">Stripe, AWS, Mailgun, SMTP passwords, JWT secrets</td></tr>
        <tr style="border-bottom:1px solid #2A2F3F;"><td style="padding: 10px;">📂 <strong>Open directories</strong></td><td style="padding: 10px;">Index of <code>/uploads/</code>, <code>/cache/</code>, <code>/backup/</code>, <code>/logs/</code></td></tr>
        <tr style="border-bottom:1px solid #2A2F3F;"><td style="padding: 10px;">🧩 <strong>Plugin/Theme leaks</strong></td><td style="padding: 10px;">Version disclosure, config files, license keys (Yoast, Elementor, Jetpack, etc.)</td></tr>
        <tr><td style="padding: 10px;">🌐 <strong>REST & XML‑RPC</strong></td><td style="padding: 10px;">User enumeration, post metadata exposure</td></tr>
      </tbody>
    </table>
  </div>
</div>

<!-- ========== CREATIVE STATS BARS (Chart) ========== -->
<div style="background: #0F131F; border-radius: 28px; padding: 24px; margin: 30px auto; max-width: 1000px; border: 1px solid #2A2F3F;">
  <h2 style="color:#5865F2; margin-top: 0;">📊 Dork Coverage by Category (Visual Breakdown)</h2>
  <div style="margin: 20px 0;">
    <div><span style="color:#B5BAC1;">⚙️ Config & Secrets</span> <span style="float:right;">35%</span></div>
    <div style="background:#2A2F3F; border-radius: 20px; margin: 5px 0 15px 0;"><div style="width:35%; background: #5865F2; height: 10px; border-radius: 20px;"></div></div>
    
    <div><span style="color:#B5BAC1;">💾 Backups & Database</span> <span style="float:right;">25%</span></div>
    <div style="background:#2A2F3F; border-radius: 20px; margin: 5px 0 15px 0;"><div style="width:25%; background: #00FF9D; height: 10px; border-radius: 20px;"></div></div>
    
    <div><span style="color:#B5BAC1;">📜 Logs & Debug</span> <span style="float:right;">15%</span></div>
    <div style="background:#2A2F3F; border-radius: 20px; margin: 5px 0 15px 0;"><div style="width:15%; background: #FFB347; height: 10px; border-radius: 20px;"></div></div>
    
    <div><span style="color:#B5BAC1;">📂 Open Directories</span> <span style="float:right;">15%</span></div>
    <div style="background:#2A2F3F; border-radius: 20px; margin: 5px 0 15px 0;"><div style="width:15%; background: #E03A3A; height: 10px; border-radius: 20px;"></div></div>
    
    <div><span style="color:#B5BAC1;">🧩 Plugin/Theme Leaks</span> <span style="float:right;">10%</span></div>
    <div style="background:#2A2F3F; border-radius: 20px; margin: 5px 0 5px 0;"><div style="width:10%; background: #9B59B6; height: 10px; border-radius: 20px;"></div></div>
  </div>
  <p align="center"><font size="2" color="#8A94B7">* Approximate distribution based on internal collection of 5000+ dorks.</font></p>
</div>

<!-- ========== HOW TO USE (with code block) ========== -->
<div style="background: #0F131F; border-radius: 28px; padding: 24px; margin: 30px auto; max-width: 1000px; border: 1px solid #2A2F3F;">
  <h2 style="color:#5865F2; margin-top: 0;">🚀 How to use</h2>
  <ol>
    <li>Replace <code>target</code> with the domain you are testing (e.g., <code>mysite.com</code>).</li>
    <li>Execute the dork in <strong>Google Search</strong> (or Bing, DuckDuckGo – operators may vary).</li>
    <li>Analyse the results <strong>manually</strong> – do not use automated scrapers without permission.</li>
  </ol>
  <h3>Example</h3>
  <div style="background: #0D1117; padding: 16px; border-radius: 16px; font-family: monospace; border: 1px solid #5865F2;">
    site:mysite.com inurl:wp-config.php.bak
  </div>
  <p>Search for exposed <code>wp-config.php</code> backups (just an example – real dorks are in the <code>dorks.txt</code> file).</p>
</div>

<!-- ========== PRO TIPS & CALL TO ACTION ========== -->
<div align="center" style="margin: 40px auto; max-width: 1000px;">
  <div style="background: linear-gradient(145deg, #1A1E2E, #0F131F); border-radius: 28px; padding: 28px; border: 1px solid #5865F2;">
    <h2 style="color:#FFF; margin-top: 0;">💡 Pro Tips for Responsible Use</h2>
    <p style="color:#B5BAC1;">• Always use a VPN and a dedicated browser when researching.<br>
    • Set up a local WordPress playground to test dorks without affecting live sites.<br>
    • Join the <strong>#infosec</strong> community to share findings and learn from others.</p>
    <br>
    <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 16px;">
      <img src="https://img.shields.io/badge/Follow-@Nobody_555_111-5865F2?style=for-the-badge&logo=github" />
      <img src="https://img.shields.io/badge/Contribute-Open%20to%20PRs-brightgreen?style=for-the-badge" />
      <img src="https://komarev.com/ghpvc/?username=Nobody-555-111&label=Repository%20Views&color=5865F2&style=flat-square" alt="views" />
    </div>
  </div>
</div>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:1E1E2F&height=120&section=footer" alt="footer" />
</div>
