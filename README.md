<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=190&color=0:22d3ee,50:8b5cf6,100:f472b6&section=header&text=NITIKA.GOTRA.exe&fontSize=46&fontColor=ffffff&animation=twinkling&fontAlignY=36&desc=B.Tech%20CSE%20%40%20University%20of%20Lucknow&descSize=17&descAlignY=58" width="100%" alt="NITIKA.GOTRA.exe — B.Tech CSE @ University of Lucknow">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=2400&pause=800&color=22D3EE&center=true&vCenter=true&width=560&height=50&lines=initializing+nitika.exe+...+ok;loading+skills+...+ok;loading+projects+...+ok;loading+curiosity+...+overflow;system+online" alt="Boot sequence: initializing, loading skills, loading projects, loading curiosity, system online">

**Full-Stack Developer • Open Source Contributor • Competitive Programmer**

<a href="#about"><img src="https://img.shields.io/badge/ABOUT-0891b2?style=for-the-badge" alt="ABOUT"></a>
<a href="#skills"><img src="https://img.shields.io/badge/SKILLS-7c3aed?style=for-the-badge" alt="SKILLS"></a>
<a href="#projects"><img src="https://img.shields.io/badge/PROJECTS-db2777?style=for-the-badge" alt="PROJECTS"></a>
<a href="#open-source"><img src="https://img.shields.io/badge/OPEN%20SOURCE-0891b2?style=for-the-badge" alt="OPEN SOURCE"></a>
<a href="#stats"><img src="https://img.shields.io/badge/STATS-7c3aed?style=for-the-badge" alt="STATS"></a>
<a href="#connect"><img src="https://img.shields.io/badge/CONNECT-db2777?style=for-the-badge" alt="CONNECT"></a>

</div>

<br>

<h2 id="about" align="center">⟨ SYSTEM_STATUS ⟩</h2>

<table align="center">
  <tr>
    <td valign="top" width="33%">
      <b>CURRENTLY BUILDING</b><br><br>
      Full-stack projects<br>+ real-world software
    </td>
    <td valign="top" width="33%">
      <b>CURRENTLY LEARNING</b><br><br>
      › Backend development<br>
      › Advanced DSA<br>
      › Open Source<br>
      › Competitive Programming
    </td>
    <td valign="top" width="33%">
      <b>CURRENTLY EXPLORING</b><br><br>
      › AI × Software<br>
      › Developer tools<br>
      › Startups
    </td>
  </tr>
</table>

```text
MISSION   become a stronger software engineer by building, contributing and experimenting.
LOCATION  Lucknow, Uttar Pradesh   ·   YEAR 2 / SEM 3   ·   TARGET  software-development internships
```

<br>

<h2 id="skills" align="center">⟨ SKILL_CONSTELLATION ⟩</h2>

```mermaid
%%{init: {'theme':'base','themeVariables':{'lineColor':'#8b5cf6','fontFamily':'monospace','primaryTextColor':'#e2e8f0'}}}%%
graph LR
  ME((NITIKA)):::core
  subgraph sg1["Languages"]
    CPP[C++]:::lang --- DSA([DSA]):::lang
    JS[JavaScript]:::lang --- HTML[HTML]:::lang --- CSS[CSS]:::lang
  end
  subgraph sg2["Frontend"]
    REACT[React]:::fe --- VITE[Vite]:::fe
  end
  subgraph sg3["Backend"]
    NODE[Node.js]:::be --- EXP[Express.js]:::be
  end
  subgraph sg4["Database"]
    MONGO[(MongoDB)]:::db
  end
  subgraph sg5["Tools"]
    GIT[Git]:::tool --- GH[GitHub]:::tool --- VSC[VS Code]:::tool
  end
  ME --> JS
  ME --> CPP
  ME --> GIT
  JS --> REACT
  JS --> NODE
  EXP --> MONGO
  classDef core fill:#8b5cf6,stroke:#22d3ee,stroke-width:2px,color:#fff
  classDef lang fill:#0e3a4a,stroke:#22d3ee,color:#e2e8f0
  classDef fe fill:#4a1530,stroke:#f472b6,color:#e2e8f0
  classDef be fill:#14305a,stroke:#60a5fa,color:#e2e8f0
  classDef db fill:#2a1a5a,stroke:#a78bfa,color:#e2e8f0
  classDef tool fill:#2d2748,stroke:#c4b5fd,color:#e2e8f0
```

<br>

<h2 id="projects" align="center">⟨ PROJECTS // MISSION_LOG ⟩</h2>

### 01 · SIERRA &nbsp; <sub>flagship</sub>

An AI-powered backend/project generation concept: describe what you want in natural language, and the system helps generate the backend/project structure.

![AI](https://img.shields.io/badge/AI-8b5cf6?style=flat-square) ![JavaScript](https://img.shields.io/badge/JavaScript-22d3ee?style=flat-square&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-60a5fa?style=flat-square) ![Backend](https://img.shields.io/badge/Backend-a78bfa?style=flat-square) ![Docker](https://img.shields.io/badge/Docker-22d3ee?style=flat-square&logo=docker&logoColor=white) ![Full-stack](https://img.shields.io/badge/Full--stack-f472b6?style=flat-square)

```mermaid
%%{init: {'theme':'base','themeVariables':{'lineColor':'#22d3ee','fontFamily':'monospace'}}}%%
flowchart LR
  A["describe it<br/>in natural language"]:::a --> B(("SIERRA")):::b --> C["backend / project<br/>structure"]:::c
  classDef a fill:#0e3a4a,stroke:#22d3ee,color:#e2e8f0
  classDef b fill:#8b5cf6,stroke:#f472b6,stroke-width:2px,color:#fff
  classDef c fill:#14305a,stroke:#60a5fa,color:#e2e8f0
```

### 02 · SIGNAL-AI-ROUTER

An intelligent AI model-routing project: different types and complexities of queries get routed to an appropriate model, with fallback and logging.

```mermaid
%%{init: {'theme':'base','themeVariables':{'lineColor':'#8b5cf6','fontFamily':'monospace'}}}%%
flowchart LR
  Q[QUERY]:::n1 --> AN[ANALYZE]:::n2 --> R[ROUTE]:::n3 --> M[MODEL]:::n4 --> RES[RESPONSE]:::n5
  M -. fallback .-> R
  R -.-> LOG[(logging)]:::log
  classDef n1 fill:#0e3a4a,stroke:#22d3ee,color:#e2e8f0
  classDef n2 fill:#14305a,stroke:#60a5fa,color:#e2e8f0
  classDef n3 fill:#2a1a5a,stroke:#8b5cf6,color:#e2e8f0
  classDef n4 fill:#4a1530,stroke:#f472b6,color:#e2e8f0
  classDef n5 fill:#0b3b2a,stroke:#34d399,color:#e2e8f0
  classDef log fill:#0f1530,stroke:#22d3ee,stroke-dasharray:4,color:#e2e8f0
```

### 03 · EMERALD RUN — MOODRUNNER

A React + Vite + Phaser 3 forest platformer with webcam-based mood detection that can influence gameplay.

```mermaid
%%{init: {'theme':'base','themeVariables':{'lineColor':'#34d399','fontFamily':'monospace'}}}%%
flowchart LR
  W[WEBCAM]:::a --> MD[MOOD DETECTION]:::b --> GS[GAME STATE]:::c --> GP[GAMEPLAY]:::d
  classDef a fill:#0b3b2a,stroke:#34d399,color:#e2e8f0
  classDef b fill:#0e3a4a,stroke:#22d3ee,color:#e2e8f0
  classDef c fill:#2a1a5a,stroke:#8b5cf6,color:#e2e8f0
  classDef d fill:#4a1530,stroke:#f472b6,color:#e2e8f0
```

![React + Vite](https://img.shields.io/badge/React_+_Vite-22d3ee?style=flat-square) ![Phaser 3](https://img.shields.io/badge/Phaser_3-34d399?style=flat-square) ![Webcam mood detection](https://img.shields.io/badge/Webcam_mood_detection-f472b6?style=flat-square) ![Mood-influenced gameplay](https://img.shields.io/badge/Mood--influenced_gameplay-8b5cf6?style=flat-square) ![Web Audio](https://img.shields.io/badge/Web_Audio-60a5fa?style=flat-square) ![Touch controls](https://img.shields.io/badge/Touch_controls-a78bfa?style=flat-square) ![Double jump](https://img.shields.io/badge/Double_jump-22d3ee?style=flat-square) ![Multiple enemy types](https://img.shields.io/badge/Multiple_enemy_types-f472b6?style=flat-square) ![Interactive gameplay](https://img.shields.io/badge/Interactive_gameplay-34d399?style=flat-square)

<div align="center">

<a href="https://github.com/nitikagotra75-crypto?tab=repositories"><img src="https://img.shields.io/badge/BROWSE%20THE%20REPOSITORIES%20%E2%86%97-0f1530?style=for-the-badge&labelColor=0f1530&color=8b5cf6" alt="Browse the repositories"></a>

</div>

<br>

<h2 id="open-source" align="center">⟨ OPEN_SOURCE_MODE = ON ⟩</h2>

Open source isn't a side note. It's an active part of my developer journey: **GitHub issues · pull requests · repository contributions**, including work around Zulip Desktop.

```mermaid
%%{init: {'theme':'base','themeVariables':{'fontFamily':'monospace','git0':'#22d3ee','git1':'#f472b6','gitBranchLabel0':'#0a0f24','gitBranchLabel1':'#0a0f24'}}}%%
gitGraph
  commit id: "issue"
  branch fix
  checkout fix
  commit id: "branch"
  commit id: "commit"
  commit id: "pull request"
  checkout main
  merge fix id: "review"
```

<sub>↑ the contribution workflow: issue → branch → commit → pull request → review.</sub>

<div align="center">

<a href="https://github.com/zulip/zulip-desktop/pulls?q=is%3Apr+author%3Anitikagotra75-crypto"><img src="https://img.shields.io/badge/ZULIP%20DESKTOP-my%20PRs%20%E2%86%97-0f1530?style=for-the-badge&labelColor=8b5cf6" alt="My pull requests in Zulip Desktop"></a>
<a href="https://github.com/search?q=author%3Anitikagotra75-crypto+is%3Apr&type=pullrequests"><img src="https://img.shields.io/badge/ALL%20PULL%20REQUESTS-my%20trail%20%E2%86%97-0f1530?style=for-the-badge&labelColor=22d3ee" alt="All my pull requests"></a>

</div>

<br>

<h2 id="stats" align="center">⟨ PLAYER_STATS ⟩</h2>

```text
PLAYER 01 ── NITIKA GOTRA
CLASS  full-stack builder
GUILD  University of Lucknow · B.Tech CSE · Year 2 · Sem 3
MAIN QUEST   ship real-world products
SIDE QUESTS  open source · backend · competitive programming
```

<div align="center">

<img src="https://img.shields.io/badge/DSA-500%2B%20problems%20solved-0f1530?style=for-the-badge&labelColor=22d3ee" alt="500+ DSA problems solved">
<img src="https://img.shields.io/badge/CODECHEF-2%E2%98%85-0f1530?style=for-the-badge&labelColor=f472b6&logo=codechef&logoColor=white" alt="CodeChef 2 star">
<img src="https://img.shields.io/badge/CODECHEF%20DSA-%E2%89%88%201456-0f1530?style=for-the-badge&labelColor=60a5fa&logo=codechef&logoColor=white" alt="CodeChef DSA rating about 1456">
<img src="https://img.shields.io/badge/LEETCODE-%E2%89%88%201480-0f1530?style=for-the-badge&labelColor=8b5cf6&logo=leetcode&logoColor=white" alt="LeetCode rating about 1480">

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=nitikagotra75-crypto&bg_color=0a0f24&color=c4b5fd&line=8b5cf6&point=22d3ee&area=true&area_color=8b5cf6&hide_border=true&radius=16" alt="GitHub contribution activity graph" width="100%">

<img src="https://streak-stats.demolab.com?user=nitikagotra75-crypto&background=0A0F24&ring=22D3EE&fire=F472B6&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=C4B5FD&sideLabels=C4B5FD&dates=94A3B8&stroke=8B5CF6&border=8B5CF6&border_radius=16" alt="GitHub contribution streak" width="70%">

</div>

<br>

<h2 id="beyond" align="center">⟨ BEYOND_THE_CODE ⟩</h2>

<div align="center"><i>Things that somehow keep sneaking into my code.</i></div>

<br>

| | | |
|:--|:--|:--|
| 🎮 **games** <br><sub>Emerald Run — MoodRunner is a platformer</sub> | 🌸 **anime** <br><sub>always running in the background</sub> | 🎨 **creative UI** <br><sub>this README, mostly</sub> |
| 🤖 **AI experiments** <br><sub>Sierra · Signal-AI-Router</sub> | 💡 **unusual ideas** <br><sub>a game that reads your mood</sub> | 🚀 **startups** <br><sub>real products over tutorials</sub> |

<br>

<h2 id="connect" align="center">⟨ OPEN_CHANNELS ⟩</h2>

<div align="center">

<a href="https://github.com/nitikagotra75-crypto"><img src="https://img.shields.io/badge/GITHUB-nitikagotra75--crypto-0f1530?style=for-the-badge&labelColor=8b5cf6&logo=github&logoColor=white" alt="GitHub: nitikagotra75-crypto"></a>
<a href="https://github.com/nitikagotra75-crypto?tab=repositories"><img src="https://img.shields.io/badge/REPOSITORIES-everything%20I%20built-0f1530?style=for-the-badge&labelColor=22d3ee" alt="Repositories"></a>

<br><br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=2600&pause=1200&color=F472B6&center=true&vCenter=true&width=520&height=45&lines=SYSTEM+STATUS%3A+ONLINE;BUILDING%3A+CONTINUOUSLY;OPEN+SOURCE+MODE%3A+ON;NEXT+COMMIT%3A+SOON" alt="System status: online. Building: continuously. Open source mode: on. Next commit: soon.">

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:22d3ee,50:8b5cf6,100:f472b6&section=footer" width="100%" alt="">

</div>
