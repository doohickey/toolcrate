<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>ToolCrate Privacy Policy</title>
  <meta name="description" content="How ToolCrate for iPhone and iPad handles your data: on-device processing, non-personalized ads, consent-gated analytics, and your rights.">
  <style>
    :root {
      color-scheme: light dark;
      --bg: #ffffff;
      --fg: #1c1c1e;
      --muted: #6e6e73;
      --rule: #e5e5ea;
      --accent: #0a84ff;
      --table-head: #f2f2f7;
    }
    @media (prefers-color-scheme: dark) {
      :root {
        --bg: #000000;
        --fg: #f2f2f7;
        --muted: #98989d;
        --rule: #2c2c2e;
        --accent: #0a84ff;
        --table-head: #1c1c1e;
      }
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      background: var(--bg);
      color: var(--fg);
      font: 17px/1.6 -apple-system, BlinkMacSystemFont, "SF Pro Text", "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      -webkit-font-smoothing: antialiased;
    }
    main {
      max-width: 44rem;
      margin: 0 auto;
      padding: 3rem 1.25rem 4rem;
    }
    h1 { font-size: 2rem; line-height: 1.2; margin: 0 0 .5rem; }
    h2 { font-size: 1.35rem; margin: 2.25rem 0 .75rem; padding-top: 1rem; border-top: 1px solid var(--rule); }
    p, li { margin: 0 0 .9rem; }
    ul { padding-left: 1.25rem; }
    li { margin-bottom: .4rem; }
    a { color: var(--accent); text-decoration: none; }
    a:hover { text-decoration: underline; }
    .meta { color: var(--muted); margin-bottom: 2rem; }
    .summary {
      background: var(--table-head);
      border-radius: 12px;
      padding: 1rem 1.25rem;
      margin: 1.5rem 0;
    }
    .summary h2 { border: 0; margin: 0 0 .5rem; padding: 0; font-size: 1.1rem; }
    .summary ul { margin: 0; }
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 1rem 0 1.25rem;
      font-size: .95rem;
    }
    th, td {
      text-align: left;
      vertical-align: top;
      padding: .6rem .5rem;
      border-bottom: 1px solid var(--rule);
    }
    th { background: var(--table-head); font-weight: 600; }
    @media (max-width: 600px) {
      table, thead, tbody, th, td, tr { display: block; }
      thead { display: none; }
      tr { border: 1px solid var(--rule); border-radius: 10px; padding: .5rem; margin-bottom: .75rem; }
      td { border: 0; padding: .25rem .25rem; }
      td::before { content: attr(data-label); display: block; font-weight: 600; color: var(--muted); font-size: .8rem; }
    }
    footer { margin-top: 3rem; color: var(--muted); font-size: .9rem; }
  </style>
</head>
<body>
<main>
  <h1>ToolCrate Privacy Policy</h1>
  <p class="meta"><strong>Effective date:</strong> September 28, 2026</p>

  <p>ToolCrate is a collection of measurement utilities for iPhone and iPad: Compass, Level, Protractor, Ruler, Altimeter, Speedometer, Sound Meter, Magnifier, Color Identifier, Magnetometer, and Flashlight. This policy explains what information the app handles, what stays on your device, what reaches third parties, and the choices you have.</p>

  <h2 id="who-we-are">Who we are</h2>
  <p>ToolCrate is developed and published by Moaloop, an individual developer based in Brazil. Moaloop is the data controller for any personal data described in this policy.</p>
  <p>Contact: <a href="mailto:hello.moaloop@gmail.com">hello.moaloop@gmail.com</a></p>

  <section class="summary" aria-labelledby="short-version">
    <h2 id="short-version">The short version</h2>
    <ul>
      <li>Every measurement tool works entirely on your device. Location, microphone, camera, and motion data are never sent to us.</li>
      <li>We do not create accounts, and we do not ask for your name, email, or any other personal detail.</li>
      <li>The free version shows non-personalized ads through Google AdMob. We do not track you across apps or websites, and the app never shows Apple's App Tracking Transparency prompt because it does not track.</li>
      <li>Anonymous usage analytics (Firebase Analytics) is off by default and turns on only when you consent.</li>
      <li>We do not sell personal information and do not share it for cross-context behavioral advertising.</li>
      <li>ToolCrate Pro, a one-time purchase, removes ads. Apple processes the payment. We never see your payment details.</li>
    </ul>
  </section>

  <h2 id="on-device">Information processed on your device only</h2>
  <p>The tools below request device permissions. The data they use is processed in memory to power the tool you are looking at and is not stored by the app or transmitted to us.</p>
  <table>
    <thead>
      <tr><th>Permission</th><th>Tools that use it</th><th>What happens</th></tr>
    </thead>
    <tbody>
      <tr>
        <td data-label="Permission">Location (while using the app)</td>
        <td data-label="Tools">Compass, Altimeter, Speedometer</td>
        <td data-label="What happens">Used to compute heading, true north, altitude, and speed. Your location is not stored or transmitted.</td>
      </tr>
      <tr>
        <td data-label="Permission">Microphone</td>
        <td data-label="Tools">Sound Meter</td>
        <td data-label="What happens">Used to estimate ambient sound level in decibels. Audio is never recorded, stored, or transmitted.</td>
      </tr>
      <tr>
        <td data-label="Permission">Camera</td>
        <td data-label="Tools">Magnifier, Color Identifier</td>
        <td data-label="What happens">Used to show a live preview and read colors. Images are never captured, saved, or transmitted.</td>
      </tr>
      <tr>
        <td data-label="Permission">Motion and sensors</td>
        <td data-label="Tools">Level, Compass, Protractor, Altimeter, Magnetometer</td>
        <td data-label="What happens">Accelerometer, gyroscope, barometer, and magnetometer readings power the tool display. Readings are not stored or transmitted.</td>
      </tr>
    </tbody>
  </table>
  <p>Ruler and Flashlight do not use any permission-protected data.</p>
  <p>You can grant or revoke any of these permissions at any time in the iOS Settings app. A tool that needs a permission you have declined will explain what it needs and remain otherwise usable where possible.</p>

  <h2 id="local-storage">Information stored on your device</h2>
  <p>ToolCrate saves a small set of preferences locally using the standard iOS preferences store. These stay on your device, are included in your normal iCloud or iTunes device backup like any other app data, and are deleted when you delete the app. They are never sent to us.</p>
  <ul>
    <li>Unit choices: metric or imperial, speed unit, altitude unit</li>
    <li>Appearance: system, light, or dark</li>
    <li>Haptics and sound feedback toggles</li>
    <li>Whether the Level calibration guide has been shown</li>
    <li>A count of app launches and the time the last full-screen ad was shown, used only to limit how often ads appear</li>
  </ul>

  <h2 id="advertising">Advertising (Google AdMob)</h2>
  <p>The free version of ToolCrate shows banner ads on the Home screen, in Settings, and on a few passive tools, plus an occasional full-screen ad when you return to the Home screen. Ads are served by Google AdMob, part of Google LLC.</p>
  <p><strong>Ads are non-personalized.</strong> Every ad request is tagged for non-personalized treatment, and the Google Mobile Ads SDK is configured to disable ad personalization. Ads are selected based on context such as the app, your approximate region, and the current session, not on a profile of you.</p>
  <p><strong>No cross-app tracking.</strong> ToolCrate does not request the Advertising Identifier (IDFA) and never displays Apple's App Tracking Transparency prompt. Our privacy manifest declares that the app does not track.</p>
  <p><strong>Consent.</strong> In the European Economic Area, the United Kingdom, Switzerland, and other regions where the law requires it, ToolCrate uses Google's User Messaging Platform (UMP) to show a consent message before any ad is requested. If you decline, no ad requests are made. Where a "privacy options" entry point is legally required, you can change your choice at any time from the Privacy Options button in the app's Settings screen.</p>
  <p><strong>What Google receives.</strong> To serve and measure ads, the Google Mobile Ads SDK may process information such as your IP address (from which an approximate location is derived), device model and operating system version, app identifier and version, language, screen size, and ad interaction events (impressions and taps). Google may also use Apple's SKAdNetwork framework and on-device conversion measurement to attribute app installs in aggregate, without identifying you. Google acts as an independent controller for this processing under its own terms. See:</p>
  <ul>
    <li><a href="https://policies.google.com/privacy" rel="noopener">Google Privacy Policy</a></li>
    <li><a href="https://policies.google.com/technologies/partner-sites" rel="noopener">How Google uses information from apps that use its services</a></li>
    <li><a href="https://support.google.com/admob/answer/6128543" rel="noopener">Google Ads and Ad Manager privacy</a></li>
  </ul>
  <p>Purchasing ToolCrate Pro removes all ads, and the app stops making ad requests.</p>

  <h2 id="analytics">Analytics (Firebase Analytics)</h2>
  <p>We use Google Firebase Analytics to learn which tools are used most, so we can prioritize improvements. Collection is <strong>disabled by default</strong> and is enabled only after you give consent through the same UMP consent flow described above. If you decline, no analytics events are sent.</p>
  <p>When enabled, the app logs:</p>
  <ul>
    <li>Screen views (which tool was opened)</li>
    <li>Standard session events that Firebase collects automatically, such as session start, app update, and first open</li>
    <li>A "build environment" property that tells us whether the data came from a production or test build</li>
  </ul>
  <p>We deliberately use the variant of the Firebase Analytics SDK that excludes Apple's Advertising Identifier. Firebase generates a random app-instance identifier to group events from the same installation. Analytics events never contain your location, audio, images, sensor readings, or any content from the tools.</p>
  <p>Firebase Analytics is operated by Google LLC. Event data is retained by Google for the retention period configured in our Firebase project and is then deleted automatically.</p>

  <h2 id="remote-config">Remote configuration (Firebase Remote Config)</h2>
  <p>The app fetches a single configuration value from Firebase Remote Config: the minimum supported app version. This lets us ask you to update if a critical fix is required. The fetch sends the standard information any network request carries (IP address, app identifier, app version, device platform) and nothing else. No personal data is stored for this purpose.</p>

  <h2 id="purchases">In-app purchase (ToolCrate Pro)</h2>
  <p>ToolCrate Pro is a one-time, non-consumable purchase that removes ads. Purchases are made through Apple's App Store using Apple's StoreKit framework. Apple handles the transaction, your payment method, and billing information under <a href="https://www.apple.com/legal/privacy/" rel="noopener">Apple's Privacy Policy</a>. We receive only a signed confirmation that the purchase is valid for this device or Apple Account, which the app uses to hide ads. We do not run a server, store receipts, or keep any record of who purchased.</p>

  <h2 id="how-we-use">How we use information</h2>
  <ul>
    <li>To provide the measurement tools you open</li>
    <li>To show ads in the free version, when permitted</li>
    <li>To understand which tools are used, when you consent to analytics</li>
    <li>To keep the app compatible by checking the minimum supported version</li>
    <li>To unlock ToolCrate Pro after purchase</li>
  </ul>

  <h2 id="legal-bases">Legal bases (GDPR, UK GDPR, LGPD)</h2>
  <ul>
    <li><strong>Performance of a contract:</strong> providing the tools you request and honoring your Pro purchase.</li>
    <li><strong>Consent:</strong> advertising in regions where consent is required, and analytics everywhere.</li>
    <li><strong>Legitimate interests:</strong> the minimum-version check, which keeps the app functioning securely and is limited to non-identifying request metadata.</li>
  </ul>

  <h2 id="recipients">Who receives information</h2>
  <p>ToolCrate has no server of its own. Information leaves your device only to the following recipients:</p>
  <table>
    <thead>
      <tr><th>Recipient</th><th>Purpose</th><th>Role</th></tr>
    </thead>
    <tbody>
      <tr>
        <td data-label="Recipient">Google LLC (AdMob, User Messaging Platform)</td>
        <td data-label="Purpose">Non-personalized ad serving, consent management</td>
        <td data-label="Role">Independent controller</td>
      </tr>
      <tr>
        <td data-label="Recipient">Google LLC (Firebase Analytics, Firebase Remote Config)</td>
        <td data-label="Purpose">Usage analytics (with consent), minimum-version check</td>
        <td data-label="Role">Processor on our behalf</td>
      </tr>
      <tr>
        <td data-label="Recipient">Apple Inc. (App Store, StoreKit)</td>
        <td data-label="Purpose">Purchase processing and entitlement verification</td>
        <td data-label="Role">Independent controller</td>
      </tr>
    </tbody>
  </table>
  <p>We do not sell personal information, do not share it for cross-context behavioral advertising, and do not disclose it to anyone else except where required by law.</p>

  <h2 id="transfers">International transfers</h2>
  <p>Moaloop is based in Brazil. Google and Apple process data in the United States and other countries where they operate. Where personal data is transferred out of the EEA, UK, Switzerland, or Brazil, our providers rely on recognized safeguards such as the European Commission's Standard Contractual Clauses and equivalent mechanisms under UK and Brazilian law.</p>

  <h2 id="retention">Data retention</h2>
  <ul>
    <li>On-device sensor data is processed in real time and never stored.</li>
    <li>Local preferences remain on your device until you delete the app or reset them.</li>
    <li>Consent choices recorded by UMP are stored on your device and remain until you change them or delete the app.</li>
    <li>Analytics data is retained by Google for the period described in the Analytics section above.</li>
    <li>Ad-serving data is retained by Google under its own retention policies.</li>
  </ul>

  <h2 id="children">Children</h2>
  <p>ToolCrate is a general-audience app and is not directed at children under 13, or under the applicable age of digital consent in your region. We do not knowingly collect personal information from children. Consent requests are not tagged as under the age of consent. If you believe a child has provided personal information through the app, contact us and we will address it.</p>

  <h2 id="rights">Your rights and choices</h2>
  <p><strong>Permissions.</strong> Turn Location, Camera, and Microphone access on or off at any time in iOS Settings under ToolCrate.</p>
  <p><strong>Ads and analytics consent.</strong> If you are in a region where consent is required, use Privacy Options in the app's Settings screen to review or change your choice. Elsewhere, you can stop all ads by purchasing ToolCrate Pro, and you can contact us to ask about analytics.</p>
  <p><strong>Delete your data.</strong> Because the app keeps no account and no server-side record about you, deleting the app removes everything ToolCrate stored locally. To ask Google to delete analytics data associated with your installation, contact us and we will submit the request through the Firebase console using the app-instance identifier, or you can reset it yourself by deleting and reinstalling the app.</p>
  <p><strong>Regional rights.</strong></p>
  <ul>
    <li><em>EEA, UK, Switzerland:</em> you may request access, rectification, erasure, restriction, portability, and object to processing based on legitimate interests. You may withdraw consent at any time without affecting prior processing. You may lodge a complaint with your local data protection authority.</li>
    <li><em>Brazil (LGPD):</em> you may request confirmation of processing, access, correction, anonymization or deletion of unnecessary data, portability, information about sharing, and revocation of consent. You may file a complaint with the Autoridade Nacional de Proteção de Dados (ANPD).</li>
    <li><em>California (CCPA/CPRA) and other U.S. states:</em> you have the right to know what personal information is collected, to delete it, to correct it, and to be free from discrimination for exercising these rights. We do not sell or share personal information as those terms are defined under the CCPA, so there is no opt-out to exercise.</li>
  </ul>
  <p>To exercise any right, email <a href="mailto:hello.moaloop@gmail.com">hello.moaloop@gmail.com</a>. We will respond within the timeframe required by applicable law, typically within 30 days. We may ask you for enough information to confirm the request relates to your installation.</p>

  <h2 id="security">Security</h2>
  <p>ToolCrate communicates with Google and Apple only over encrypted HTTPS connections. Because the app collects no account data and holds no personal information on any server, the main risk surface is your device itself, which is protected by iOS's app sandbox. No method of transmission or storage is completely secure, and we cannot guarantee absolute security.</p>

  <h2 id="changes">Changes to this policy</h2>
  <p>We may update this policy when the app changes or the law requires. The effective date at the top will change, and a copy of the current policy is always available inside the app under Settings and at this address. Material changes that affect how your data is handled will be highlighted in the app.</p>

  <h2 id="contact">Contact</h2>
  <p>Moaloop (individual developer), Brazil<br>
  Email: <a href="mailto:hello.moaloop@gmail.com">hello.moaloop@gmail.com</a></p>

  <footer>
    <p>&copy; 2026 Moaloop. ToolCrate is available on the App Store for iPhone and iPad.</p>
  </footer>
</main>
</body>
</html>
