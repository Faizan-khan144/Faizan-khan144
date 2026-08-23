<div align="center">

```
┌──────────────────────────────────────────────────────────┐
│ root@faizan-dev:~# whoami                                  │
│ frontend_developer                                          │
│ root@faizan-dev:~# cat role.txt                             │
│ MERN-in-progress :: Python + Data :: always shipping        │
│ root@faizan-dev:~# ./status --check                         │
│ [OK] compiling... [OK] deploying... [OK] never sleeping     │
└──────────────────────────────────────────────────────────┘
```

<img src="https://user-images.githubusercontent.com/74038190/221352989-518609ab-b4d1-459e-929f-a08cd2bd9b3c.gif" width="380"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=900&color=39FF14&center=true&vCenter=true&width=800&lines=%3E+sudo+access+granted;%3E+booting+dev_environment...;%3E+MERN+stack+compiling;%3E+status%3A+always_shipping" alt="Typing SVG"/>

<a href="https://github.com/Faizan-khan144"><img src="https://img.shields.io/github/followers/Faizan-khan144?logo=github&style=flat&color=0d1117&labelColor=000000&logoColor=39FF14"/></a>
<a href="https://github.com/Faizan-khan144"><img src="https://img.shields.io/github/stars/Faizan-khan144?logo=github&style=flat&color=0d1117&labelColor=000000&logoColor=39FF14"/></a>
<img src="https://komarev.com/ghpvc/?username=Faizan-khan144&color=0d1117&style=flat&label=Views"/>

<a href="https://www.linkedin.com/in/muhammadfaizankhan-76513041a/"><img src="https://img.shields.io/badge/LinkedIn-000000?style=flat&logo=linkedin&logoColor=39FF14"/></a>
<a href="https://x.com/faizan525nk"><img src="https://img.shields.io/badge/X-000000?style=flat&logo=x&logoColor=39FF14"/></a>
<a href="mailto:muhammadfaizankhan525@gmail.com"><img src="https://img.shields.io/badge/Email-000000?style=flat&logo=gmail&logoColor=39FF14"/></a>
<img src="https://img.shields.io/badge/Open_to_Work-000000?style=flat&logo=googlechrome&logoColor=39FF14"/>

</div>

---

## About Me

```python
from dataclasses import dataclass, field
from typing import List

@dataclass
class MuhammadFaizanKhan:
    role: str = "Frontend Developer"
    location: str = "Karachi, Pakistan"
    stack: List[str] = field(default_factory=lambda: [
        "HTML5", "CSS3", "JavaScript (ES6+)", "React", "Tailwind CSS"
    ])
    learning: List[str] = field(default_factory=lambda: [
        "Node.js", "Express", "MongoDB", "MERN Architecture"
    ])
    exploring: List[str] = field(default_factory=lambda: [
        "Python", "NumPy", "Pandas", "Matplotlib", "Seaborn"
    ])
    available_for: List[str] = field(default_factory=lambda: [
        "Open Source", "Internships", "Junior Dev Roles"
    ])

    def philosophy(self) -> str:
        return "Learn the primitive, build the abstraction, ship the product."

    def __repr__(self) -> str:
        return f"<Developer role={self.role!r} status='compiling...'>"


me = MuhammadFaizanKhan()
print(me.philosophy())
# >>> Learn the primitive, build the abstraction, ship the product.
```

---

## neofetch --dev

```
                   ./+o+-       muhammad@faizan-dev
                 yyyyy- -yyyyyy+     -----------------
              ://+//////-yyyyyyo     OS: Frontend Engineer v1.0
          .++ .:/++++++/-.+sss/`     Host: Karachi, Pakistan
        .:++o:  /++++++++/:--:/-     Kernel: JavaScript ES6+
       o:+o+:++.`..```.-/oo+++++/    Uptime: 2+ years learning
      .:+o:+o/.          `+sssoo+/   Shell: React + Tailwind
 .++/+:+oo+o:`             /sssooo.  Editor: VS Code
/+++//+:`oo+o               /::--:.  Stack: MERN (in progress)
\+/+o+++`o++o               ++////.  Toolbelt: Git, Postman, Vercel
 .++.o+++oo+:`             /dddhhh.  Learning: Node, Express, Mongo
      .+.o+oo:.          `oyhhhhh.  Exploring: NumPy, Pandas
       \+.++o+o``-````.:ohdhhhhh+   Memory: Always allocating new skills
        `:o+++ `ohhhhhhhhyo++os:
          .o:`.syhhhhhhh/.oo++o`
              /osyyyyyyo++ooo+++/
                  ````` +oo+++o\:
                          `oo++.
```

---

## Tech Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=html,css,js,react,tailwind,nodejs,express,mongodb,python,git,github,vscode,postman,vercel,figma,linux&perline=8&theme=dark"/>
</div>

<table align="center">
<tr>
<td valign="top" width="20%">

**Frontend**
- HTML5 / Semantic Markup
- CSS3 / Flexbox / Grid
- JavaScript (ES6+)
- React (Hooks, Context)
- Tailwind CSS

</td>
<td valign="top" width="20%">

**Backend (Learning)**
- Node.js Runtime
- Express.js Routing
- REST API Design
- Middleware Patterns

</td>
<td valign="top" width="20%">

**Database**
- MongoDB / Mongoose
- Schema Design
- Local Storage / IndexedDB

</td>
<td valign="top" width="20%">

**Python & Data**
- Python 3
- NumPy / Pandas
- Matplotlib / Seaborn
- Data Wrangling

</td>
<td valign="top" width="20%">

**Tooling**
- Git / GitHub
- VS Code
- Postman
- Vercel / Netlify
- Linux CLI

</td>
</tr>
</table>

---

## Tech Radar — Adoption Stage

```mermaid
quadrantChart
    title Technology Adoption Radar
    x-axis Low Confidence --> High Confidence
    y-axis Low Usage --> High Usage
    quadrant-1 Core Daily Tools
    quadrant-2 Growing Fast
    quadrant-3 Watching
    quadrant-4 Ramping Up
    React: [0.8, 0.8]
    Tailwind CSS: [0.85, 0.75]
    JavaScript: [0.9, 0.9]
    HTML/CSS: [0.95, 0.95]
    Node.js: [0.45, 0.5]
    Express: [0.4, 0.45]
    MongoDB: [0.35, 0.35]
    Python: [0.5, 0.4]
    Pandas: [0.35, 0.3]
    Git/GitHub: [0.85, 0.9]
```

---

## API Surface — This Profile as a REST Resource

```http
GET /api/v1/developers/faizan-khan144
```

| Field | Type | Value |
|---|---|---|
| `role` | `string` | `"Frontend Developer"` |
| `location` | `string` | `"Karachi, PK"` |
| `stack` | `string[]` | `["React", "Tailwind", "JavaScript"]` |
| `status` | `enum` | `OPEN_TO_WORK` |
| `learning` | `string[]` | `["Node.js", "Express", "MongoDB"]` |
| `response_time` | `string` | `"< 24h"` |

```json
{
  "status": 200,
  "data": {
    "available_for": ["internship", "junior_role", "open_source"],
    "compile_status": "no errors, just more features to add"
  }
}
```

---

## Language & Tooling Distribution

```mermaid
pie showData
    title Primary Languages Used
    "JavaScript" : 42
    "HTML" : 22
    "CSS" : 20
    "Python" : 12
    "Other" : 4
```

```mermaid
%%{init: {'theme': 'dark'}}%%
xychart-beta
    title "Weekly Commit Activity (avg)"
    x-axis [Mon, Tue, Wed, Thu, Fri, Sat, Sun]
    y-axis "Commits" 0 --> 20
    bar [8, 12, 10, 14, 16, 6, 4]
```

---

## MERN Architecture — System Design

```mermaid
flowchart TD
    A["Client — React UI<br/>(Components + Hooks + Context)"] -->|HTTP / JSON| B["Express API Layer<br/>(Routes + Middleware)"]
    B --> C["Node.js Runtime<br/>(Business Logic + Auth)"]
    C --> D[("MongoDB<br/>(Collections + Indexes)")]
    D -.->|Query Result| C
    C -.->|Processed Data| B
    B -.->|JSON Response| A
    E["Tailwind CSS"] -.-> A
    F["JWT / Sessions"] -.-> C

    style A fill:#0d1117,stroke:#39FF14,color:#e5e5e5
    style B fill:#0d1117,stroke:#39FF14,color:#e5e5e5
    style C fill:#0d1117,stroke:#39FF14,color:#e5e5e5
    style D fill:#0d1117,stroke:#39FF14,color:#e5e5e5
    style E fill:#000000,stroke:#78716c,color:#e5e5e5
    style F fill:#000000,stroke:#78716c,color:#e5e5e5
```

---

## Request Lifecycle — Sequence Diagram

```mermaid
sequenceDiagram
    actor U as User
    participant R as React Client
    participant E as Express API
    participant N as Node Logic
    participant M as MongoDB

    U->>R: Interacts with UI
    R->>E: fetch() / axios request
    E->>N: Route handler invoked
    N->>M: Query / Mutation
    M-->>N: Documents returned
    N-->>E: Processed payload
    E-->>R: JSON response
    R-->>U: Re-rendered UI
```

---

## Skill Proficiency

```mermaid
%%{init: {'theme': 'dark'}}%%
xychart-beta
    title "Self-Rated Proficiency (out of 10)"
    x-axis [HTML/CSS, JavaScript, React, Tailwind, Node/Express, MongoDB, Python]
    y-axis "Proficiency" 0 --> 10
    bar [9, 7, 7, 8, 5, 4, 5]
```

---

## 2026 Learning Roadmap

```mermaid
timeline
    title 2026 — Web Dev + Python Roadmap
    section Q1–Q2
        Frontend Mastery : Advanced React patterns : Ship polished UI projects
        Tailwind Depth : Responsive, component-driven design
    section Q3
        Backend Core : Node.js + Express fundamentals : Build REST APIs
        MongoDB : Schema design, CRUD, aggregation
    section Q4
        Full MERN Apps : Ship complete MERN projects : Deploy to production
        Python for Data : NumPy, Pandas, Matplotlib, Seaborn projects
    section 2027 Outlook
        AI with Python : Explore ML fundamentals
        Open Source : First real-world contributions
```

---

## Project State Machine

```mermaid
stateDiagram-v2
    [*] --> Idea
    Idea --> Wireframe
    Wireframe --> Development
    Development --> Debugging
    Debugging --> Development: bugs found
    Debugging --> Testing
    Testing --> Deployment
    Deployment --> Live
    Live --> Maintenance
    Maintenance --> Development: new feature
    Live --> [*]
```

---

## Current Focus Board

```mermaid
kanban
    Learning
        Advanced React Patterns
        Express.js Fundamentals
        MongoDB Schema Design
    Building
        Faizan Portfolio v2
        August & Oak E-commerce
        FZ Bank Dashboard UI
    Exploring
        REST API Design
        NumPy / Pandas Basics
    Shipped
        Vortex Agency Site
        Modern Tic-Tac-Toe
        Student Attendance Tracker
```

---

## Git Workflow

```mermaid
gitGraph
    commit id: "init"
    branch feature
    checkout feature
    commit id: "build UI"
    commit id: "wire API"
    commit id: "fix bugs"
    checkout main
    merge feature id: "release v1"
    branch hotfix
    checkout hotfix
    commit id: "patch"
    checkout main
    merge hotfix id: "deploy"
```

---

## Skill Map

```mermaid
mindmap
  root((Faizan))
    Frontend
      React
      Tailwind CSS
      Responsive Design
    Backend
      Node.js
      Express
      REST APIs
    Data
      Python
      Pandas
      Visualization
    Collaboration
      Open Source
      Code Review
      Documentation
    Goals
      Internships
      Junior Dev Roles
```

---

## Featured Projects

<table>
<tr>
<td width="50%">

**Faizan Portfolio**
Personal developer portfolio showcasing projects, skills, and journey.
`HTML` `CSS` `JavaScript`
[Repo](https://github.com/Faizan-khan144/faizan-portfolio) · [Live](https://faizan-khan144.github.io/faizan-portfolio/)

</td>
<td width="50%">

**August & Oak**
Modern e-commerce storefront — filtering, cart, wishlist, Local Storage.
`HTML` `CSS` `JavaScript`
[Repo](https://github.com/Faizan-khan144/august-and-oak-ecommerce)

</td>
</tr>
<tr>
<td width="50%">

**Vortex Agency**
Premium agency site — responsive sections, animation, modern UI.
`HTML` `CSS` `JavaScript`
[Repo](https://github.com/Faizan-khan144/vortex-agency)

</td>
<td width="50%">

**FZ Bank**
Banking interface with clean layouts and a dashboard experience.
`HTML` `CSS` `JavaScript`
[View](https://github.com/Faizan-khan144)

</td>
</tr>
</table>

---

## Experience

<table>
<tr>
<td width="100%">

**Frontend Developer** — *Freelance / Self-Directed Projects*
*2024 — Present*

Designing and building responsive, production-style web interfaces using HTML, CSS, JavaScript, React, and Tailwind CSS. Focused on clean component architecture, accessibility, and performance across multiple client-style projects, including e-commerce storefronts, agency websites, and dashboard interfaces.

- Built and shipped 4+ complete front-end projects, from wireframe to deployment
- Implemented cart, wishlist, and filtering logic using client-side state and Local Storage
- Currently extending skill set into the MERN stack (Node.js, Express, MongoDB) to deliver full-stack solutions
- Exploring Python for data analysis (NumPy, Pandas, Matplotlib, Seaborn) to broaden technical range

</td>
</tr>
</table>

**Core Competencies:** Responsive Web Design · Component-Based Architecture · REST API Integration · Version Control (Git/GitHub) · UI/UX Implementation · Cross-Browser Compatibility

**Currently Seeking:** Junior Frontend Developer roles · Internships · Open-source collaboration

---

## GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Faizan-khan144&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=000000&title_color=39FF14&icon_color=39FF14&text_color=e5e5e5"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Faizan-khan144&layout=compact&hide_border=true&bg_color=000000&title_color=39FF14&text_color=e5e5e5"/>

<img width="90%" src="https://github-readme-streak-stats.herokuapp.com/?user=Faizan-khan144&hide_border=true&background=000000&stroke=0d1117&ring=39FF14&fire=39FF14&currStreakLabel=39FF14&sideLabels=e5e5e5&currStreakNum=ffffff&sideNums=e5e5e5&dates=78716c"/>

<img width="92%" src="https://github-readme-activity-graph.vercel.app/graph?username=Faizan-khan144&bg_color=000000&color=e5e5e5&line=39FF14&point=ffffff&area_color=0d1117&area=true&hide_border=true"/>

<img src="https://github-profile-trophy.vercel.app/?username=Faizan-khan144&theme=matrix&no-frame=true&no-bg=true&column=4&margin-w=15"/>

</div>

---

## Repo Metrics Snapshot

```mermaid
%%{init: {'theme': 'dark'}}%%
xychart-beta
    title "Focus Time by Domain (last 90 days, est. hrs)"
    x-axis [React, Tailwind, JavaScript, Node/Express, MongoDB, Python]
    y-axis "Hours" 0 --> 100
    bar [85, 60, 70, 40, 25, 30]
```

---

## Contribution Graph

<div align="center">

**Contribution snake** *(needs the included `snake.yml` workflow running once)*
<img src="https://raw.githubusercontent.com/Faizan-khan144/Faizan-khan144/output/github-contribution-grid-snake-dark.svg" width="100%"/>

**3D contribution profile** *(needs the included `3d-contrib.yml` workflow running once)*
<img src="https://raw.githubusercontent.com/Faizan-khan144/Faizan-khan144/3d-contrib/profile-3d-contrib/profile-night-rainbow.svg" width="100%"/>

**GitHub Skyline** — 3D-print your contribution history: [skyline.github.com](https://skyline.github.com/Faizan-khan144/2026)

**GitHub City** — drive through your contributions: [honzaap.github.io/GithubCity](https://honzaap.github.io/GithubCity?name=Faizan-khan144)

</div>

---

## Random Dev Quote

<div align="center">
<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark"/>
</div>

---

## Guestbook

Drop a hello or say what you're building — opens a quick issue on this repo.

<div align="center">
<a href="https://github.com/Faizan-khan144/Faizan-khan144/issues/new?title=Hello!&body=Say%20hi%20or%20share%20what%20you're%20building!&labels=guestbook"><img src="https://img.shields.io/badge/Sign_the_Guestbook-0d1117?style=for-the-badge&logo=githubactions&logoColor=39FF14"/></a>
<a href="https://github.com/Faizan-khan144/Faizan-khan144/issues?q=label%3Aguestbook"><img src="https://img.shields.io/badge/Read_Past_Entries-0d1117?style=for-the-badge&logo=readdotcv&logoColor=39FF14"/></a>
</div>

---

## Connect

<div align="center">

<a href="https://github.com/Faizan-khan144"><img src="https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=39FF14"/></a>
<a href="https://www.linkedin.com/in/muhammadfaizankhan-76513041a/"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=39FF14"/></a>
<a href="https://x.com/faizan525nk"><img src="https://img.shields.io/badge/X-0d1117?style=for-the-badge&logo=x&logoColor=39FF14"/></a>
<a href="mailto:muhammadfaizankhan525@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=39FF14"/></a>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:0d1117,100:000000&height=120&section=footer" width="100%"/>

**Learn → Build → Debug → Improve → Repeat**

</div>
