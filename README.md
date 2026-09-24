<div align="center">

<img src="./assets/header.svg" alt="Abtin Badiee — Backend Engineer, .NET and Video-on-Demand at scale" width="100%" />

<br/>

<a href="https://linkedin.com/in/abtin-badiee"><img src="https://img.shields.io/badge/LinkedIn-abtin--badiee-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=0d1117" /></a>
<a href="mailto:abtinbadiee81@gmail.com"><img src="https://img.shields.io/badge/Email-abtinbadiee81-E535AB?style=flat-square&logo=gmail&logoColor=white&labelColor=0d1117" /></a>
<a href="https://t.me/Abtin_003"><img src="https://img.shields.io/badge/Telegram-Abtin__003-26A5E4?style=flat-square&logo=telegram&logoColor=white&labelColor=0d1117" /></a>
<a href="https://namava.ir"><img src="https://img.shields.io/badge/Currently-Namava-7C3AED?style=flat-square&logo=dotnet&logoColor=white&labelColor=0d1117" /></a>
<img src="https://komarev.com/ghpvc/?username=abtin81badie&style=flat-square&color=E535AB&label=Profile+views&labelColor=0d1117" />

</div>

<br/>

I'm a **Backend Engineer at [Namava](https://namava.ir)** — one of Iran's largest video-on-demand platforms — where I design and run the **.NET services** behind playback, catalog and user experiences for **millions of viewers**. I care about systems that are fast under load, boring in production and pleasant to work on.

```csharp
public sealed record Engineer
{
    public string   Name      => "Abtin Badiee";
    public string   Role      => "Backend Engineer @ Namava";
    public string   Domain    => "Video-on-Demand · Streaming · High-traffic APIs";

    public string[] Core      => [".NET", "C#", "ASP.NET Core", "EF Core", "Go", "Python"];
    public string[] Data      => ["SQL Server", "PostgreSQL", "MongoDB", "Redis"];
    public string[] Practices => ["Microservices", "Clean Architecture", "CQRS", "Event-Driven"];

    public string   Exploring => "LLM agents & ML-driven recommendations";
    public string   Motto     => "Measure first. Optimize second. Ship always.";
}
```

## ◆ What I build

<table>
<tr>
<td width="50%" valign="top">

**⚡ High-throughput backends**<br/>
<sub>ASP.NET Core microservices, async pipelines and caching layers tuned for peak-hour traffic spikes.</sub>

</td>
<td width="50%" valign="top">

**🎬 Streaming infrastructure**<br/>
<sub>Adaptive bitrate delivery (HLS / DASH), CDN integration and DRM-protected content workflows.</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🧩 Distributed architecture**<br/>
<sub>Clean Architecture, CQRS and event-driven services that scale teams as well as traffic.</sub>

</td>
<td width="50%" valign="top">

**🧠 Data & intelligence**<br/>
<sub>Real-time viewing analytics and ML-powered recommendations that keep people watching.</sub>

</td>
</tr>
</table>

## ◆ How a play button works — the systems I work on

```mermaid
flowchart LR
    U([📱 Viewer]) --> CDN[🌐 CDN / Edge]
    U --> GW[🔀 API Gateway]
    GW --> AUTH[🔐 Identity & DRM]
    GW --> CAT[🎞️ Catalog Service]
    GW --> PLAY[▶️ Playback Service]
    PLAY --> R[(⚡ Redis)]
    CAT --> DB[(🗄️ SQL Server / Mongo)]
    PLAY -- events --> BUS{{📨 Message Bus}}
    BUS --> AN[📊 Analytics]
    BUS --> REC[🧠 Recommendations]
    CDN --> ORI[(🎬 Packaged HLS / DASH)]

    classDef hot fill:#E535AB,stroke:#E535AB,color:#fff
    classDef core fill:#512BD4,stroke:#7C3AED,color:#fff
    classDef data fill:#0d1117,stroke:#E535AB,color:#fff
    class U hot
    class GW,AUTH,CAT,PLAY core
    class R,DB,ORI,BUS data
```

## ◆ Tech stack

<table>
<tr>
<td align="right"><sub><b>BACKEND</b></sub></td>
<td><img src="https://skillicons.dev/icons?i=cs,dotnet,go,py,fastapi,django,nodejs&theme=dark&perline=7" height="44" /></td>
</tr>
<tr>
<td align="right"><sub><b>DATA</b></sub></td>
<td><img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,mysql&theme=dark" height="44" /> &nbsp;<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" height="28" /></td>
</tr>
<tr>
<td align="right"><sub><b>INFRA</b></sub></td>
<td><img src="https://skillicons.dev/icons?i=docker,kubernetes,nginx,linux,githubactions,git&theme=dark" height="44" /></td>
</tr>
<tr>
<td align="right"><sub><b>AI / ML</b></sub></td>
<td><img src="https://skillicons.dev/icons?i=pytorch,tensorflow&theme=dark" height="44" /> &nbsp;<img src="https://img.shields.io/badge/LLM_Agents-8B5CF6?style=flat-square&logo=openai&logoColor=white" height="28" /></td>
</tr>
<tr>
<td align="right"><sub><b>FRONTEND</b></sub></td>
<td><img src="https://skillicons.dev/icons?i=ts,js,react,html,css&theme=dark" height="44" /></td>
</tr>
<tr>
<td align="right"><sub><b>MOBILE</b></sub></td>
<td><img src="https://skillicons.dev/icons?i=kotlin,androidstudio&theme=dark" height="44" /></td>
</tr>
</table>

## ◆ Engineering focus

| Area | What that means in practice |
|:--|:--|
| **Architecture** | Microservices · Clean Architecture · CQRS · Event-driven design |
| **Streaming** | Adaptive bitrate · CDN integration · DRM · Low-latency playback |
| **Performance** | Multi-level caching · Load balancing · Query & index tuning |
| **Security** | AuthN/AuthZ · Token-based APIs · Encryption at rest & in transit |
| **Delivery** | CI/CD · Containers · Kubernetes · Observability & monitoring |

## ◆ GitHub at a glance

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=abtin81badie&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=00000000&title_color=E535AB&icon_color=a78bfa&text_color=8b949e&rank_icon=github" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abtin81badie&layout=compact&langs_count=8&hide_border=true&bg_color=00000000&title_color=E535AB&text_color=8b949e" />

<img src="https://streak-stats.demolab.com?user=abtin81badie&hide_border=true&background=00000000&ring=E535AB&fire=E535AB&currStreakLabel=E535AB&sideLabels=8b949e&dates=8b949e&currStreakNum=a78bfa&sideNums=a78bfa&stroke=30363d" />

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/abtin81badie/abtin81badie/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/abtin81badie/abtin81badie/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/abtin81badie/abtin81badie/output/github-snake-dark.svg" />
</picture>

</div>

---

<div align="center">

<sub>Open to conversations about <b>backend architecture</b>, <b>streaming at scale</b> and <b>.NET</b> — feel free to reach out.</sub>

</div>
