<svg viewBox="0 0 620 820" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
  <defs>
    <pattern id="dots" width="26" height="26" patternUnits="userSpaceOnUse">
      <circle cx="2" cy="2" r="1.6" fill="#eec9c9"/>
    </pattern>
    <filter id="soft" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="0" dy="4" stdDeviation="6" flood-color="#c98f8f" flood-opacity="0.35"/>
    </filter>
  </defs>

  <rect width="620" height="820" fill="#f6dcdc"/>
  <rect width="620" height="820" fill="url(#dots)"/>

  <g opacity="0.9">
    <g transform="translate(40,40)">
      <circle r="7" fill="#e2789a"/><circle cx="14" cy="-8" r="7" fill="#e2789a"/>
      <circle cx="-14" cy="-8" r="7" fill="#e2789a"/><circle cx="14" cy="8" r="7" fill="#e2789a"/>
      <circle cx="-14" cy="8" r="7" fill="#e2789a"/><circle r="5" fill="#f6c453"/>
    </g>
    <g transform="translate(575,120) rotate(15)">
      <ellipse rx="10" ry="22" fill="#9db47a"/>
      <ellipse rx="10" ry="22" fill="#9db47a" transform="rotate(50)"/>
      <ellipse rx="10" ry="22" fill="#b7c98f" transform="rotate(-50)"/>
    </g>
    <g transform="translate(30,760) rotate(-10)">
      <ellipse rx="12" ry="26" fill="#8fae72"/>
      <ellipse rx="12" ry="26" fill="#a9c98a" transform="rotate(60)"/>
    </g>
    <g transform="translate(560,760)">
      <circle r="6" fill="#e2789a"/><circle cx="12" cy="-7" r="6" fill="#e2789a"/>
      <circle cx="-12" cy="-7" r="6" fill="#e2789a"/><circle cx="12" cy="7" r="6" fill="#e2789a"/>
      <circle cx="-12" cy="7" r="6" fill="#e2789a"/><circle r="4" fill="#f6c453"/>
    </g>
  </g>

  <!-- About Me card -->
  <g transform="translate(40,40) rotate(-1.5)" filter="url(#soft)">
    <rect width="540" height="230" rx="10" fill="#fffaf3"/>
    <g transform="translate(85,95)">
      <circle r="68" fill="#eee"/>
      <clipPath id="c1"><circle r="66"/></clipPath>
      <image href="https://avatars.githubusercontent.com/u/173875224?v=4" x="-66" y="-66" width="132" height="132" clip-path="url(#c1)"/>
    </g>
    <text x="30" y="200" font-family="Georgia, serif" font-size="20" fill="#6b4a4a" font-weight="bold">Jeshal Mathias</text>
    <text x="190" y="55" font-family="Georgia, serif" font-size="22" font-weight="bold" fill="#6b4a4a">About Me</text>
    <foreignObject x="190" y="65" width="330" height="150">
      <div xmlns="http://www.w3.org/1999/xhtml" style="font-family:Georgia,serif;font-size:13px;color:#7a5c5c;line-height:1.5;">
        Final-year BCA student, curious about how things work, why they matter, and who they're for. I turn messy data into things people can actually use.
      </div>
    </foreignObject>
  </g>

  <!-- My Favorites card -->
  <g transform="translate(40,300) rotate(1.2)" filter="url(#soft)">
    <rect width="260" height="260" rx="10" fill="#fffaf3"/>
    <text x="24" y="42" font-family="Georgia, serif" font-size="20" font-weight="bold" fill="#6b4a4a">My Favorites</text>
    <foreignObject x="24" y="55" width="220" height="190">
      <div xmlns="http://www.w3.org/1999/xhtml" style="font-family:Georgia,serif;font-size:13px;color:#7a5c5c;line-height:2;">
        • Messy data → clean answer<br/>
        • Explaining tech, watching it click<br/>
        • Upcycling old materials
      </div>
    </foreignObject>
  </g>

  <!-- My Toolkit card -->
  <g transform="translate(320,300) rotate(-1.5)" filter="url(#soft)">
    <rect width="260" height="260" rx="10" fill="#fffaf3"/>
    <text x="24" y="42" font-family="Georgia, serif" font-size="20" font-weight="bold" fill="#6b4a4a">My Toolkit</text>
    <foreignObject x="20" y="55" width="228" height="195">
      <div xmlns="http://www.w3.org/1999/xhtml" style="font-family:Georgia,serif;font-size:11.5px;color:#7a5c5c;line-height:1.9;column-count:2;column-gap:14px;">
        Python<br/>SQL<br/>HTML<br/>CSS<br/>Excel<br/>Power BI<br/>Streamlit<br/>Mixpanel<br/>Android Studio<br/>Figma<br/>Canva<br/>Jira<br/>Notion
      </div>
    </foreignObject>
  </g>

  <!-- Fun Facts card -->
  <g transform="translate(40,590) rotate(-0.8)" filter="url(#soft)">
    <rect width="540" height="200" rx="10" fill="#fffaf3"/>
    <text x="24" y="42" font-family="Georgia, serif" font-size="20" font-weight="bold" fill="#6b4a4a">Fun Facts</text>
    <foreignObject x="24" y="55" width="490" height="140">
      <div xmlns="http://www.w3.org/1999/xhtml" style="font-family:Georgia,serif;font-size:13px;color:#7a5c5c;line-height:1.9;">
        • Trained 50+ students in Python & AI<br/>
        • Ran ops for a 500-person tech fest<br/>
        • Co-writing a research paper on ML risk classification
      </div>
    </foreignObject>
  </g>
</svg>
