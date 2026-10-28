<p align="center">
  <svg width="1000" height="420" viewBox="0 0 1000 420" fill="none" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="bgGlow" x1="140" y1="40" x2="860" y2="380" gradientUnits="userSpaceOnUse">
        <stop stop-color="#0B1020"/>
        <stop offset="0.35" stop-color="#111827"/>
        <stop offset="1" stop-color="#090D16"/>
      </linearGradient>
      <linearGradient id="ringGrad" x1="220" y1="80" x2="780" y2="340" gradientUnits="userSpaceOnUse">
        <stop stop-color="#8B5CF6"/>
        <stop offset="0.5" stop-color="#22D3EE"/>
        <stop offset="1" stop-color="#34D399"/>
      </linearGradient>
      <radialGradient id="coreGlow" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(500 210) rotate(90) scale(150 150)">
        <stop stop-color="#A78BFA" stop-opacity="1"/>
        <stop offset="0.45" stop-color="#22D3EE" stop-opacity="0.7"/>
        <stop offset="1" stop-color="#0B1020" stop-opacity="0"/>
      </radialGradient>
      <filter id="blurBig" x="-40%" y="-40%" width="180%" height="180%">
        <feGaussianBlur stdDeviation="25"/>
      </filter>
      <filter id="blurSoft" x="-40%" y="-40%" width="180%" height="180%">
        <feGaussianBlur stdDeviation="8"/>
      </filter>
    </defs>

    <rect x="20" y="20" width="960" height="380" rx="40" fill="url(#bgGlow)" stroke="rgba(255,255,255,0.08)"/>

    <g opacity="0.9" filter="url(#blurBig)">
      <circle cx="220" cy="120" r="86" fill="#8B5CF6" opacity="0.18"/>
      <circle cx="810" cy="300" r="90" fill="#22D3EE" opacity="0.16"/>
      <circle cx="770" cy="120" r="70" fill="#34D399" opacity="0.12"/>
    </g>

    <g>
      <path d="M150 290C250 195 330 160 430 170C520 180 590 140 705 80" stroke="url(#ringGrad)" stroke-width="3" stroke-linecap="round" opacity="0.7">
        <animate attributeName="stroke-dasharray" values="0 900;420 480;0 900" dur="5s" repeatCount="indefinite"/>
      </path>
      <path d="M245 330C330 250 390 220 500 225C600 230 660 200 785 120" stroke="url(#ringGrad)" stroke-width="2" stroke-linecap="round" opacity="0.6">
        <animate attributeName="stroke-dasharray" values="0 900;350 550;0 900" dur="4.2s" repeatCount="indefinite"/>
      </path>
    </g>

    <g>
      <circle cx="500" cy="210" r="150" fill="url(#coreGlow)"/>
      <circle cx="500" cy="210" r="150" fill="none" stroke="url(#ringGrad)" stroke-width="2.5" opacity="0.9">
        <animateTransform attributeName="transform" type="rotate" from="0 500 210" to="360 500 210" dur="18s" repeatCount="indefinite"/>
      </circle>
      <circle cx="500" cy="210" r="120" fill="none" stroke="url(#ringGrad)" stroke-width="1.5" opacity="0.7">
        <animateTransform attributeName="transform" type="rotate" from="360 500 210" to="0 500 210" dur="14s" repeatCount="indefinite"/>
      </circle>
      <circle cx="500" cy="210" r="88" fill="none" stroke="#A78BFA" stroke-width="1.3" opacity="0.8" stroke-dasharray="4 12">
        <animateTransform attributeName="transform" type="rotate" from="0 500 210" to="360 500 210" dur="10s" repeatCount="indefinite"/>
      </circle>
    </g>

    <g opacity="0.95">
      <g>
        <circle cx="500" cy="210" r="8" fill="#F5F3FF">
          <animate attributeName="r" values="6;10;6" dur="2.4s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.7;1;0.7" dur="2.4s" repeatCount="indefinite"/>
        </circle>
      </g>
      <g>
        <circle cx="500" cy="210" r="5" fill="#22D3EE">
          <animate attributeName="r" values="4;8;4" dur="1.8s" repeatCount="indefinite"/>
        </circle>
      </g>
    </g>

    <g fill="#DDE7FF" opacity="0.9" filter="url(#blurSoft)">
      <circle cx="350" cy="180" r="4"><animate attributeName="cy" values="180;150;180" dur="2.5s" repeatCount="indefinite"/></circle>
      <circle cx="660" cy="165" r="4"><animate attributeName="cy" values="165;140;165" dur="2.2s" repeatCount="indefinite"/></circle>
      <circle cx="600" cy="285" r="4"><animate attributeName="cx" values="600;640;600" dur="2.8s" repeatCount="indefinite"/></circle>
      <circle cx="400" cy="285" r="4"><animate attributeName="cx" values="400;360;400" dur="3s" repeatCount="indefinite"/></circle>
      <circle cx="780" cy="200" r="4"><animate attributeName="cy" values="200;165;200" dur="2.7s" repeatCount="indefinite"/></circle>
      <circle cx="225" cy="230" r="4"><animate attributeName="cy" values="230;200;230" dur="3.1s" repeatCount="indefinite"/></circle>
    </g>

    <g opacity="0.85">
      <circle cx="200" cy="255" r="2.5" fill="#8B5CF6"><animate attributeName="cy" values="255;220;255" dur="2.8s" repeatCount="indefinite"/></circle>
      <circle cx="810" cy="220" r="2.5" fill="#34D399"><animate attributeName="cy" values="220;190;220" dur="2.5s" repeatCount="indefinite"/></circle>
      <circle cx="280" cy="120" r="2.5" fill="#22D3EE"><animate attributeName="cx" values="280;320;280" dur="3.2s" repeatCount="indefinite"/></circle>
      <circle cx="705" cy="314" r="2.5" fill="#A78BFA"><animate attributeName="cx" values="705;750;705" dur="2.9s" repeatCount="indefinite"/></circle>
    </g>

    <g opacity="0.65">
      <path d="M150 210H240" stroke="url(#ringGrad)" stroke-width="2" stroke-linecap="round">
        <animate attributeName="opacity" values="0.25;0.9;0.25" dur="2.2s" repeatCount="indefinite"/>
      </path>
      <path d="M760 210H850" stroke="url(#ringGrad)" stroke-width="2" stroke-linecap="round">
        <animate attributeName="opacity" values="0.25;0.9;0.25" dur="2.6s" repeatCount="indefinite"/>
      </path>
      <path d="M500 70V140" stroke="url(#ringGrad)" stroke-width="2" stroke-linecap="round">
        <animate attributeName="opacity" values="0.25;0.9;0.25" dur="2.1s" repeatCount="indefinite"/>
      </path>
      <path d="M500 280V350" stroke="url(#ringGrad)" stroke-width="2" stroke-linecap="round">
        <animate attributeName="opacity" values="0.25;0.9;0.25" dur="2.8s" repeatCount="indefinite"/>
      </path>
    </g>
  </svg>
</p>
