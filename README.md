<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="340" viewBox="0 0 1200 340" role="img" aria-label="Nazrul Islam Jibon - Researcher, Creator, Builder" xmlns:c2pa="http://c2pa.org/manifest">
  <defs>
    <clipPath id="card"><rect width="1200" height="340" rx="18"/></clipPath>

    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M40 0H0V40" fill="none" stroke="#ffffff" stroke-opacity="0.045"/>
    </pattern>

    <filter id="blur" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="55"/>
    </filter>
    <filter id="softglow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="6" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>

    <!-- name gradient that slowly flows -->
    <linearGradient id="nameGrad" gradientUnits="userSpaceOnUse" x1="0" y1="0" x2="600" y2="0" spreadMethod="repeat">
      <stop offset="0" stop-color="#F5F5F0"/>
      <stop offset="0.35" stop-color="#C6FF3D"/>
      <stop offset="0.65" stop-color="#3DFFD0"/>
      <stop offset="1" stop-color="#F5F5F0"/>
      <animateTransform attributeName="gradientTransform" type="translate" from="0 0" to="600 0" dur="8s" repeatCount="indefinite"/>
    </linearGradient>

    <linearGradient id="wave1" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#C6FF3D" stop-opacity="0.35"/>
      <stop offset="0.5" stop-color="#3DFFD0" stop-opacity="0.25"/>
      <stop offset="1" stop-color="#8B5CFF" stop-opacity="0.35"/>
    </linearGradient>
    <linearGradient id="wave2" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#8B5CFF" stop-opacity="0.30"/>
      <stop offset="0.5" stop-color="#FF5C8A" stop-opacity="0.22"/>
      <stop offset="1" stop-color="#C6FF3D" stop-opacity="0.30"/>
    </linearGradient>
  </defs>

  <g clip-path="url(#card)">
    <rect width="1200" height="340" fill="#0A0A0A"/>

    <!-- drifting colour orbs -->
    <g filter="url(#blur)">
      <circle cx="200" cy="80" r="130" fill="#C6FF3D" opacity="0.22">
        <animate attributeName="cx" values="200;420;200" dur="14s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="80;200;80" dur="11s" repeatCount="indefinite"/>
      </circle>
      <circle cx="900" cy="60" r="140" fill="#8B5CFF" opacity="0.25">
        <animate attributeName="cx" values="900;720;900" dur="16s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="60;190;60" dur="12s" repeatCount="indefinite"/>
      </circle>
      <circle cx="1050" cy="290" r="120" fill="#3DFFD0" opacity="0.20">
        <animate attributeName="cx" values="1050;880;1050" dur="13s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="290;170;290" dur="15s" repeatCount="indefinite"/>
      </circle>
      <circle cx="560" cy="320" r="100" fill="#FF5C8A" opacity="0.16">
        <animate attributeName="cx" values="560;700;560" dur="17s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="320;240;320" dur="10s" repeatCount="indefinite"/>
      </circle>
    </g>

    <rect width="1200" height="340" fill="url(#grid)"/>

    <!-- animated waves -->
    <g>
      <path fill="url(#wave1)" d="M0 290 Q150 250 300 290 T600 290 T900 290 T1200 290 T1500 290 T1800 290 T2100 290 T2400 290 V340 H0 Z">
        <animateTransform attributeName="transform" type="translate" from="0 0" to="-600 0" dur="9s" repeatCount="indefinite"/>
      </path>
      <path fill="url(#wave2)" d="M0 305 Q150 335 300 305 T600 305 T900 305 T1200 305 T1500 305 T1800 305 T2100 305 T2400 305 V340 H0 Z">
        <animateTransform attributeName="transform" type="translate" from="-600 0" to="0 0" dur="12s" repeatCount="indefinite"/>
      </path>
    </g>

    <!-- floating particles -->
    <g fill="#F5F5F0">
      <circle cx="120" cy="260" r="2.5" opacity="0.5"><animate attributeName="cy" values="280;40" dur="7s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;0.7;0" dur="7s" repeatCount="indefinite"/></circle>
      <circle cx="330" cy="280" r="2" fill="#C6FF3D"><animate attributeName="cy" values="300;30" dur="9s" begin="1s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;0.8;0" dur="9s" begin="1s" repeatCount="indefinite"/></circle>
      <circle cx="610" cy="270" r="3" fill="#3DFFD0"><animate attributeName="cy" values="290;40" dur="8s" begin="2s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;0.7;0" dur="8s" begin="2s" repeatCount="indefinite"/></circle>
      <circle cx="860" cy="280" r="2" fill="#FF5C8A"><animate attributeName="cy" values="300;30" dur="10s" begin="0.5s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;0.8;0" dur="10s" begin="0.5s" repeatCount="indefinite"/></circle>
      <circle cx="1040" cy="270" r="2.5" fill="#8B5CFF"><animate attributeName="cy" values="290;50" dur="8.5s" begin="3s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;0.8;0" dur="8.5s" begin="3s" repeatCount="indefinite"/></circle>
      <circle cx="1130" cy="260" r="2"><animate attributeName="cy" values="280;40" dur="11s" begin="4s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;0.6;0" dur="11s" begin="4s" repeatCount="indefinite"/></circle>
    </g>

    <!-- rotating ring accent -->
    <g transform="translate(1030 110)" fill="none" stroke-width="2">
      <circle r="62" stroke="#C6FF3D" stroke-opacity="0.55" stroke-dasharray="6 14">
        <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="18s" repeatCount="indefinite"/>
      </circle>
      <circle r="42" stroke="#3DFFD0" stroke-opacity="0.5" stroke-dasharray="3 10">
        <animateTransform attributeName="transform" type="rotate" from="360" to="0" dur="12s" repeatCount="indefinite"/>
      </circle>
      <circle r="6" fill="#C6FF3D" stroke="none" filter="url(#softglow)">
        <animate attributeName="r" values="5;9;5" dur="3s" repeatCount="indefinite"/>
      </circle>
    </g>

    <!-- text -->
    <text x="70" y="84" font-family="'SFMono-Regular',Consolas,'Courier New',monospace" font-size="15" letter-spacing="5" fill="#C6FF3D">
      HELLO, WORLD
      <animate attributeName="opacity" values="0;1" dur="1.2s" fill="freeze"/>
    </text>

    <text x="70" y="172" font-family="Georgia,'Times New Roman',serif" font-size="80" font-weight="700" fill="url(#nameGrad)">
      Nazrul Islam Jibon
      <animate attributeName="opacity" values="0;1" dur="1.6s" fill="freeze"/>
    </text>

    <!-- cycling tagline -->
    <g font-family="Georgia,'Times New Roman',serif" font-size="30" font-style="italic" fill="#F5F5F0" fill-opacity="0.85">
      <text x="70" y="226">I like figuring things out.
        <animate attributeName="opacity" values="1;1;0;0;0;0" keyTimes="0;0.28;0.33;0.66;0.99;1" dur="10s" repeatCount="indefinite"/>
      </text>
      <text x="70" y="226">Researcher · Creator · Builder
        <animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.30;0.36;0.62;0.68;1" dur="10s" repeatCount="indefinite"/>
      </text>
      <text x="70" y="226">Emerging tech · AI · Web3 · Communities
        <animate attributeName="opacity" values="0;0;0;1;1;0" keyTimes="0;0.64;0.70;0.76;0.95;1" dur="10s" repeatCount="indefinite"/>
      </text>
    </g>

    <!-- blinking cursor -->
    <rect x="70" y="244" width="14" height="3" fill="#C6FF3D">
      <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
    </rect>

    <text x="1136" y="318" text-anchor="end" font-family="'SFMono-Regular',Consolas,monospace" font-size="14" fill="#F5F5F0" fill-opacity="0.55">justjibon.com</text>
  </g>

  <rect x="0.5" y="0.5" width="1199" height="339" rx="18" fill="none" stroke="#ffffff" stroke-opacity="0.10"/>
<metadata><c2pa:manifest>AAAWgmp1bWIAAAAeanVtZGMycGEAEQAQgAAAqgA4m3EDYzJwYQAAABZcanVtYgAAAEdqdW1kYzJtYQARABCAAACqADibcQN1cm46YzJwYTo2MGU4ZmU2My1iNGQ1LTRkNDItYTUzYS03MDQ2ZGVlZWFmYWIAAAADl2p1bWIAAAApanVtZGMyYXMAEQAQgAAAqgA4m3EDYzJwYS5hc3NlcnRpb25zAAAAALxqdW1iAAAARGp1bWRjYm9yABEAEIAAAKoAOJtxE2MycGEuaW5ncmVkaWVudC52MwAAAAAYYzJzaOW2ihwweyvrEHNfOArqresAAABwY2JvcqNpZGM6Zm9ybWF0bWltYWdlL3N2Zyt4bWxqaW5zdGFuY2VJRHgseG1wOmlpZDoyNGFiMDlkNi05YmVmLTRiODktOGMwNy1jOThiMjlkODQ1YjJscmVsYXRpb25zaGlwaHBhcmVudE9mAAAB4mp1bWIAAABBanVtZGNib3IAEQAQgAAAqgA4m3ETYzJwYS5hY3Rpb25zLnYyAAAAABhjMnNoWyMpanDcz5sSUgh4v5HtTQAAAZljYm9yomdhY3Rpb25zgqJmYWN0aW9ua2MycGEub3BlbmVkanBhcmFtZXRlcnOha2luZ3JlZGllbnRzgaJjdXJseC1zZWxmI2p1bWJmPWMycGEuYXNzZXJ0aW9ucy9jMnBhLmluZ3JlZGllbnQudjNkaGFzaFgg0n9/czbQ9qY4r+Scb2Qwtjfcd0XDIHbw+9gf8Wczjt6kZmFjdGlvbngdY29tLmFudGhyb3BpYy5jbGF1ZGUucHJvdmlkZWRqcGFyYW1ldGVyc6F4H2NvbS5hbnRocm9waWMub3JpZ2luLWNvbmZpZGVuY2VndW5rbm93bmtkZXNjcmlwdGlvbnhmQ2xhdWRlIHByb3ZpZGVkIHRoaXMgZmlsZSBhdCB0aGUgcmVxdWVzdCBvZiBhIHVzZXIgYW5kIG1heSBoYXZlIGNyZWF0ZWQgb3IgbW9kaWZpZWQgdGhlIGZpbGUgY29udGVudHMubXNvZnR3YXJlQWdlbnShZG5hbWVmQ2xhdWRlcmFsbEFjdGlvbnNJbmNsdWRlZPUAAADIanVtYgAAAEBqdW1kY2JvcgARABCAAACqADibcRNjMnBhLmhhc2guZGF0YQAAAAAYYzJzaN0pfnWULLrkefuXTMB2tvwAAACAY2JvcqVjYWxnZnNoYTI1NmNwYWRMAAAAAAAAAAAAAAAAZGhhc2hYINBmWM34MoGlNIXkNCIeLQvf5iBB377/gzIozoiHkYztZG5hbWVuanVtYmYgbWFuaWZlc3RqZXhjbHVzaW9uc4GiZXN0YXJ0GR7NZmxlbmd0aBkeBAAAAj5qdW1iAAAAJ2p1bWRjMmNsABEAEIAAAKoAOJtxA2MycGEuY2xhaW0udjIAAAACD2Nib3KlY2FsZ2ZzaGEyNTZpc2lnbmF0dXJleE1zZWxmI2p1bWJmPS9jMnBhL3VybjpjMnBhOjYwZThmZTYzLWI0ZDUtNGQ0Mi1hNTNhLTcwNDZkZWVlYWZhYi9jMnBhLnNpZ25hdHVyZWppbnN0YW5jZUlEeCx4bXA6aWlkOjI5NDE3MTMzLWZiNTUtNDc5MC1hOTZjLTExYTJjYmVjYjVkY3JjcmVhdGVkX2Fzc2VydGlvbnODomN1cmx4LXNlbGYjanVtYmY9YzJwYS5hc3NlcnRpb25zL2MycGEuaW5ncmVkaWVudC52M2RoYXNoWCDSf39zNtD2pjiv5JxvZDC2N9x3RcMgdvD72B/xZzOO3qJjdXJseCpzZWxmI2p1bWJmPWMycGEuYXNzZXJ0aW9ucy9jMnBhLmFjdGlvbnMudjJkaGFzaFggr0B3PnOmvcMjzWa35bc8fmKvtXtcfdHIRLGPqs9MgpmiY3VybHgpc2VsZiNqdW1iZj1jMnBhLmFzc2VydGlvbnMvYzJwYS5oYXNoLmRhdGFkaGFzaFgg259PMuXrxAqeb3fmSeqZBxsXSF94Yad5K/m5WbhBFJh0Y2xhaW1fZ2VuZXJhdG9yX2luZm+jZG5hbWVvQW50aHJvcGljIEZpbGVzZ3ZlcnNpb25lMS4wLjBrc3BlY1ZlcnNpb25lMi40LjAAABA4anVtYgAAAChqdW1kYzJjcwARABCAAACqADibcQNjMnBhLnNpZ25hdHVyZQAAABAIY2JvctKEWQISogEmGCFZAgowggIGMIIBjaADAgECAhRA5aAK7sI50L64g/oGQgU9Z1UTADAKBggqhkjOPQQDAzBJMRcwFQYDVQQKEw5BbnRocm9waWMsIFBCQzEuMCwGA1UEAxMlQW50aHJvcGljIENvbnRlbnQgQ3JlZGVudGlhbHMgUm9vdCBDQTAeFw0yNjA4MDcxODQzNTZaFw0yODA4MDYxOTQzNTZaMEQxFzAVBgNVBAoTDkFudGhyb3BpYywgUEJDMSkwJwYDVQQDEyBBbnRocm9waWMgQ2xhdWRlIENvbnRlbnQgU2lnbmluZzBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABJh6CmvLUBgFFNU0vUKlOVtE6djd17L5SuwX0LemFisBM3dkd/3cyjxFA3Qo5S46fX0/ihY0VZ7mfb9KF703t5OjWDBWMA4GA1UdDwEB/wQEAwIHgDAVBgNVHSUEDjAMBgorBgEEAYPoXgIBMAwGA1UdEwEB/wQCMAAwHwYDVR0jBBgwFoAUzlHiBIFOZFsj+OPEz5o+nMHXXMIwCgYIKoZIzj0EAwMDZwAwZAIwMXMdFJ4BetLLVY7ORuE9noqbbAZOZn/aArXyTwFAZfKrPzxF2vPoJNf1+UCdg1XGAjBwX1zd9WGqYkqmL5SFqw1QySjr1zJfpJM9+1rdDwSPLMOPOjKuiXjoU/pUUeG9RwmhY3BhZFkNngAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAPZYQO8SUGP2H7EqlE/Iwxf1sH4zKdRlmJtgL8zi1DdqifrtechMETOoFW5BtU6+mdwvNHLghB3QX/sw2cbhoqXZiOY=</c2pa:manifest></metadata></svg>

<br/>

[![Website](https://img.shields.io/badge/justjibon.com-0A0A0A?style=for-the-badge&logo=safari&logoColor=C6FF3D)](https://justjibon.com)
[![X](https://img.shields.io/badge/@Just__Jibon-0A0A0A?style=for-the-badge&logo=x&logoColor=white)](https://x.com/Just_Jibon)
[![LinkedIn](https://img.shields.io/badge/in/justjibon-0A0A0A?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/justjibon/)
[![Telegram](https://img.shields.io/badge/@justjibon-0A0A0A?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/justjibon)
[![Email](https://img.shields.io/badge/Say_hello-0A0A0A?style=for-the-badge&logo=maildotru&logoColor=C6FF3D)](mailto:justjibon@yahoo.com)

</div>

<br/>

### 👋 Hey, I'm Jibon

I like figuring things out. I research what's happening in emerging tech, talk to people building interesting things, and try building a few things of my own.

- 🔭 Exploring **AI**, **Web3** and emerging tech
- 🛠️ Experimenting with small projects and ideas
- 🌱 Always learning something new
- 💬 Happy to chat about research, creators, communities or a good rabbit hole

<br/>

### 📈 GitHub stats

<div align="center">

<img height="170" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=justjibon&show_icons=true&hide_border=true&bg_color=0A0A0A&title_color=C6FF3D&text_color=F5F5F0&icon_color=3DFFD0&ring_color=C6FF3D" />
<img height="170" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=justjibon&layout=compact&hide_border=true&bg_color=0A0A0A&title_color=C6FF3D&text_color=F5F5F0" />

<img alt="GitHub streak" src="https://streak-stats.demolab.com?user=justjibon&hide_border=true&background=0A0A0A&ring=C6FF3D&fire=FF5C8A&currStreakLabel=F5F5F0&sideLabels=F5F5F0&currStreakNum=F5F5F0&sideNums=F5F5F0&dates=8a8a85" />

</div>

<br/>

<div align="center">

<sub>Stay curious. Build momentum. · <a href="https://justjibon.com">justjibon.com</a></sub>

</div>
