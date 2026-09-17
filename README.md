<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7F52FF,50:4285F4,100:3DDC84&height=200&section=header&text=Sumant%20Mourya&fontSize=58&fontColor=ffffff&fontAlignY=36&desc=Android%20Developer%20·%20Kotlin%20·%20Jetpack%20Compose&descAlignY=58&descSize=18" alt="Sumant Mourya"/>

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.amigo.dialer"><img src="https://img.shields.io/badge/Google%20Play-Recline-414141?style=for-the-badge&logo=googleplay&logoColor=3DDC84" alt="Recline on Google Play"/></a>
  <a href="https://linkedin.com/in/sumant-mourya"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:sumant.mourya@faridagupta.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  I build native Android apps that feel fast and look deliberate.<br/>
  I ship a <b>published dialer on Google Play</b>, and I go deep on <b>telephony</b>, <b>custom UI systems</b> and <b>clean architecture</b>.
</p>

<br/>

## 🛠 Tech

<p align="center">
  <img src="https://skillicons.dev/icons?i=kotlin,androidstudio,gradle,py,js,html,css,git,github,firebase,sqlite,vscode&theme=dark&perline=6" alt="Tech stack"/>
</p>

<p align="center">
  <b>Mobile</b> — Kotlin · Jetpack Compose · Material 3 · Room · Paging 3 · Coroutines · Android Telecom · WorkManager<br/>
  <b>Tooling</b> — Python · Playwright · OpenCV · Google Apps Script · Bash<br/>
  <b>Practice</b> — multi-module architecture · MVVM · custom design systems · performance profiling
</p>

<br/>

## 🚀 Recline — my flagship app

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.amigo.dialer">
    <img src="https://img.shields.io/badge/Live%20on%20Google%20Play-414141?style=for-the-badge&logo=googleplay&logoColor=3DDC84" alt="Google Play"/>
  </a>
  <a href="https://sumant-mourya.github.io/Developer-Website/">
    <img src="https://img.shields.io/badge/Privacy%20Policy-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Privacy Policy"/>
  </a>
</p>

A full-featured replacement dialer for Android, shipped to production and built across
**15 Gradle modules** so features stay isolated and builds stay fast.

**What's inside**

- **Real telecom integration** — `InCallService` drives the entire call lifecycle;
  `CallScreeningService` intercepts incoming calls for blocking and spam detection
- **Call recording** in its own module, plus incognito and authenticated-call modes
- **Global phone identity** — Google's `libphonenumber` normalises every number to
  canonical E.164 as the database key, so international numbers sharing a local suffix
  never merge by accident
- **OEM-style answer UIs** — iOS slide-to-answer, Google, Huawei, Vivo and pulse-wave
  variants, all switchable at runtime
- **Production plumbing** — Firebase push, in-app updates, a referral and reward system,
  home-screen widgets and app shortcuts
- **Thoughtful details** — proximity-sensor screen blanking, audible caller announcement,
  missed-call reminders, DTMF keypad and conference controls mid-call

<p align="center">
  <img src="https://img.shields.io/badge/15%20modules-7F52FF?style=flat-square"/>
  <img src="https://img.shields.io/badge/MVVM-4285F4?style=flat-square"/>
  <img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white"/>
  <img src="https://img.shields.io/badge/Room-FF6F00?style=flat-square&logo=sqlite&logoColor=white"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black"/>
  <img src="https://img.shields.io/badge/libphonenumber-34A853?style=flat-square"/>
  <img src="https://img.shields.io/badge/minSdk-24-3DDC84?style=flat-square"/>
  <img src="https://img.shields.io/badge/targetSdk-36-3DDC84?style=flat-square"/>
</p>

<br/>

## 🔭 Other projects

<table width="100%">
<tr>
<td width="50%" valign="top">

### 📱 [Ios-Dialer](https://github.com/Sumant-Mourya/Ios-Dialer)

The open-source prototype behind Recline. Registers as the system default dialer and binds `InCallService` + `ConnectionService` directly.

Liquid-glass Compose UI, Room + Paging 3 data layer.

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Compose](https://img.shields.io/badge/Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Telecom](https://img.shields.io/badge/Telecom-34A853?style=flat-square&logo=android&logoColor=white)
<br/>
![last commit](https://img.shields.io/github/last-commit/Sumant-Mourya/Ios-Dialer?style=flat-square&color=7F52FF)
![license](https://img.shields.io/github/license/Sumant-Mourya/Ios-Dialer?style=flat-square&color=blue)

</td>
<td width="50%" valign="top">

### ⚡ [RunPod](https://github.com/Sumant-Mourya/RunPod)

**One-command provisioning** for a GPU pod — system deps, ComfyUI, custom nodes and SDXL weights, from bare container to running server.

Every step idempotent, so restarts resume instead of re-downloading.

![Bash](https://img.shields.io/badge/Bash-89E051?style=flat-square&logo=gnubash&logoColor=black)
![ComfyUI](https://img.shields.io/badge/ComfyUI-1A1A1A?style=flat-square)
![SDXL](https://img.shields.io/badge/SDXL-FF6F00?style=flat-square)
<br/>
![last commit](https://img.shields.io/github/last-commit/Sumant-Mourya/RunPod?style=flat-square&color=7F52FF)
![license](https://img.shields.io/github/license/Sumant-Mourya/RunPod?style=flat-square&color=blue)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 [Coc-Bot](https://github.com/Sumant-Mourya/Coc-Bot)

**Computer-vision automation** driven purely from screen pixels — template matching against a live window, PaddleOCR for on-screen numbers, and a watchdog that recovers from hangs.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![OCR](https://img.shields.io/badge/PaddleOCR-0062B0?style=flat-square)
<br/>
![last commit](https://img.shields.io/github/last-commit/Sumant-Mourya/Coc-Bot?style=flat-square&color=7F52FF)
![license](https://img.shields.io/github/license/Sumant-Mourya/Coc-Bot?style=flat-square&color=blue)

</td>
<td width="50%" valign="top">

### 🌐 [Developer-Website](https://github.com/Sumant-Mourya/Developer-Website)

Publisher pages for my Android apps on **GitHub Pages** — privacy policy for *Recline* and AdMob `app-ads.txt` verification.

Single self-contained page, no build step.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat-square&logo=githubpages&logoColor=white)
<br/>
![last commit](https://img.shields.io/github/last-commit/Sumant-Mourya/Developer-Website?style=flat-square&color=7F52FF)

</td>
</tr>
</table>

<br/>

## 🐍 Contributions

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sumant-Mourya/Sumant-Mourya/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Sumant-Mourya/Sumant-Mourya/output/github-snake.svg"/>
    <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/Sumant-Mourya/Sumant-Mourya/output/github-snake.svg"/>
  </picture>
</p>

<br/>

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.amigo.dialer"><b>Google Play</b></a> &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/sumant-mourya"><b>LinkedIn</b></a> &nbsp;·&nbsp;
  <a href="mailto:sumant.mourya@faridagupta.com"><b>Email</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/Sumant-Mourya?tab=repositories"><b>All repositories</b></a>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:3DDC84,50:4285F4,100:7F52FF&height=120&section=footer" alt=""/>
