<!--
  ============================================================
  littlesheep920 / GitHub Profile README
  ============================================================
  部署位置：仓库 littlesheep920/littlesheep920 的根目录，文件名为 README.md
  图片：全部放在同级的 pic/ 文件夹，清单见 pic/README-图片清单.md
  说明：视觉层为侦探主题，正文为常规英文技术表述
  ============================================================
-->

<div align="center">

<!-- ═══ 图片位置 1/6：主横幅 banner.png ═══ -->
<img src="pic/banner.png" alt="Detective Notes" width="100%" />

<br/><br/>

<!-- 打字机：开源项目 DenverCoder1/readme-typing-svg -->
<a href="https://github.com/DenverCoder1/readme-typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=900&color=4A90D9&center=true&vCenter=true&width=620&lines=AI+Agent+Engineering;Python+Backend+Development;Building+auditable+LLM+applications" alt="Typing SVG" />
</a>

<br/><br/>

<!-- 访客计数：开源项目 antonkomarev/github-profile-views-counter -->
<img src="https://komarev.com/ghpvc/?username=littlesheep920&label=profile+views&color=1F4E8C&style=for-the-badge" alt="views" />
<img src="https://img.shields.io/badge/STATUS-OPEN%20TO%20COLLABORATION-1F4E8C?style=for-the-badge" alt="status" />
<img src="https://img.shields.io/badge/FOCUS-AI%20AGENTS-D4AF37?style=for-the-badge" alt="focus" />

</div>

<!-- ═══ 图片位置 2/6：分隔线 divider.png（本文件会重复使用 5 次）═══ -->
<img src="pic/divider.png" width="100%" />

## About

<div align="center">
<table>
<tr>
<td width="38%" align="center" valign="middle">

<!-- ═══ 图片位置 3/6：插图 intro.png（建议 1:1 方图）═══ -->
<img src="pic/intro.png" width="240" alt="Portrait" />

</td>
<td width="62%" valign="top">

```yaml
name        : littlesheep920
role        : Undergraduate, Electronic Information Engineering
university  : Tianjin University
focus       : AI agent engineering / Python backend
stack       : Python · LangGraph · RAG · FastAPI
current work: SuperCoder — AI capability governance platform
```

- **Currently building** — SuperCoder, a platform for governing and orchestrating AI capabilities across enterprise R&D workflows
- **Areas of interest** — agent orchestration, tool calling, retrieval-augmented generation, multi-agent collaboration, evaluation
- **Engineering approach** — agents should plan, use tools, retain context, and leave an auditable trace of every step

</td>
</tr>
</table>
</div>

<!-- ═══ 分隔线 ═══ -->
<img src="pic/divider.png" width="100%" />

## Tech Stack

<div align="center">

<!-- ═══ 图片位置 4/6：板块标题图 stack-header.png ═══ -->
<img src="pic/stack-header.png" width="100%" alt="Technical Toolkit" />

<br/><br/>

<!-- 图标墙：开源项目 tandpfun/skill-icons -->
<img src="https://skillicons.dev/icons?i=py,pytorch,fastapi,flask,docker,kubernetes,redis,postgres,mongodb,git,github,githubactions,linux,vscode,bash&theme=dark" alt="skills" />

<br/><br/>

### Languages & Frameworks

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### AI & Agents

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF5A50?style=for-the-badge&logo=crewai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white)

<!-- 下面三个项目的 logo 已被 Simple Icons 移除，只能做纯文字徽章，属正常现象 -->
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge)
![AutoGen](https://img.shields.io/badge/Microsoft%20AutoGen-0078D4?style=for-the-badge)

### Infrastructure & Tooling

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

</div>

<!-- ═══ 分隔线 ═══ -->
<img src="pic/divider.png" width="100%" />

## Agent Architecture

<div align="center">

<!-- ═══ 图片位置 5/6：Agent 架构图 agent-flow.png ═══ -->
<img src="pic/agent-flow.png" width="100%" alt="Agent Architecture" />

</div>

| Module | Responsibility | Implementation |
| :--- | :--- | :--- |
| **Planner** | Break down goals and decide the next step | LLM planning with a ReAct loop |
| **Tool Use** | Call external capabilities | Function calling / MCP servers |
| **Memory** | Retain context across turns | Session memory plus a long-term vector store |
| **RAG** | Ground answers in retrieved sources | Chroma vector search with re-ranking |
| **Multi-Agent** | Divide work across specialised agents | LangGraph state machine / CrewAI role design |
| **Evaluation** | Verify whether the output holds up | Trajectory replay and automated scoring |

<!-- ═══ 分隔线 ═══ -->
<img src="pic/divider.png" width="100%" />

## Projects

| Repository | Description | Stack | Activity |
| :--- | :--- | :--- | :--- |
| **[SuperCoder](https://github.com/littlesheep920/SuperCoder)** | AI capability governance and orchestration platform for enterprise R&D workflows. Six resource protocols, a seven-state lifecycle model, hybrid retrieval and an evaluation pipeline, with six frozen contract documents carrying the same authority as the code | `Python` `FastAPI` `MySQL` `Hybrid Retrieval` | ![](https://img.shields.io/github/last-commit/littlesheep920/SuperCoder?style=flat-square&color=1F4E8C&label=updated&display_timestamp=committer&labelColor=0D1117) ![](https://img.shields.io/github/stars/littlesheep920/SuperCoder?style=flat-square&color=D4AF37&label=stars&labelColor=0D1117) |
| **[FTO-AGENT](https://github.com/littlesheep920/FTO-AGENT)** | Multi-agent freedom-to-operate analysis system for the Chinese jurisdiction, focused on steerable catheters. Delegates patent infringement screening to agents that gather evidence and compare claims item by item | `FastAPI` `LangGraph` `Tortoise ORM` `MySQL` | ![](https://img.shields.io/github/last-commit/littlesheep920/FTO-AGENT?style=flat-square&color=1F4E8C&label=updated&display_timestamp=committer&labelColor=0D1117) |
| **[ai-agent-learning](https://github.com/littlesheep920/ai-agent-learning)** | Retrieval-augmented question answering: document chunking, embedding, vector search, prompt assembly and generation. Ships both a CLI and a Gradio web interface | `LangChain` `Chroma` `GLM-4-Flash` `Gradio` | ![](https://img.shields.io/github/last-commit/littlesheep920/ai-agent-learning?style=flat-square&color=1F4E8C&label=updated&display_timestamp=committer&labelColor=0D1117) |
| **[pdf-textbook-slides](https://github.com/littlesheep920/pdf-textbook-slides)** | Converts textbook and course-material PDFs, including scanned documents, into single-file HTML slide decks for teaching, and exports them as 16:9 PDFs. Includes rendering, chunk stitching, crop QA and export scripts | `Python` `PDF Processing` | ![](https://img.shields.io/github/last-commit/littlesheep920/pdf-textbook-slides?style=flat-square&color=1F4E8C&label=updated&display_timestamp=committer&labelColor=0D1117) |

<div align="center">

<a href="https://github.com/littlesheep920?tab=repositories">
  <img src="https://img.shields.io/badge/View%20all%20repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="repos" />
</a>

</div>

<!-- ═══ 分隔线 ═══ -->
<img src="pic/divider.png" width="100%" />

## GitHub Activity

<div align="center">

<!-- 开源项目 anuraghazra/github-readme-stats -->
<img height="165" src="https://github-readme-stats.vercel.app/api?username=littlesheep920&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&title_color=4A90D9&icon_color=D4AF37&text_color=c9d1d9&bg_color=0D1117" alt="stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=littlesheep920&layout=compact&hide_border=true&langs_count=8&title_color=4A90D9&text_color=c9d1d9&bg_color=0D1117" alt="top langs" />

<br/>

<!-- 开源项目 DenverCoder1/github-readme-streak-stats -->
<img src="https://streak-stats.demolab.com?user=littlesheep920&hide_border=true&background=0D1117&stroke=1F4E8C&ring=D4AF37&fire=D4AF37&currStreakLabel=4A90D9&sideLabels=4A90D9&dates=8B949E" alt="streak" />

<br/>

<!-- 开源项目 Ashutosh00710/github-readme-activity-graph -->
<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=littlesheep920&bg_color=0D1117&color=4A90D9&line=D4AF37&point=FFFFFF&hide_border=true&area=true" alt="activity" />

<br/>

<!-- 开源项目 Platane/snk（贪吃蛇吃掉贡献格，需开启 Actions 工作流）-->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/littlesheep920/littlesheep920/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/littlesheep920/littlesheep920/output/github-contribution-grid-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/littlesheep920/littlesheep920/output/github-contribution-grid-snake.svg" />
</picture>

<br/><br/>

<!-- 开源项目 yoshi389111/github-profile-3d-contrib（需开启 Actions 工作流）-->
<img width="100%" src="https://raw.githubusercontent.com/littlesheep920/littlesheep920/main/profile-3d-contrib/profile-night-rainbow.svg" alt="3D contributions" />

<br/>

<!-- 开源项目 ryo-ma/github-profile-trophy -->
<img src="https://github-profile-trophy.vercel.app/?username=littlesheep920&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8" alt="trophy" />

</div>

<!-- ═══ 分隔线 ═══ -->
<img src="pic/divider.png" width="100%" />

<div align="center">

<!-- ═══ 图片位置 6/6：结尾横幅 footer.png ═══ -->
<img src="pic/footer.png" width="100%" alt="Keep Observing" />

<br/><br/>

<a href="mailto:3023234119@tju.edu.cn">
  <img src="https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="email" />
</a>
<a href="https://github.com/littlesheep920">
  <img src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white" alt="github" />
</a>

<br/><br/>

<sub>Built with <a href="https://github.com/anuraghazra/github-readme-stats">github-readme-stats</a> ·
<a href="https://github.com/DenverCoder1/readme-typing-svg">readme-typing-svg</a> ·
<a href="https://github.com/DenverCoder1/github-readme-streak-stats">streak-stats</a> ·
<a href="https://github.com/tandpfun/skill-icons">skill-icons</a> ·
<a href="https://github.com/Platane/snk">snk</a> ·
<a href="https://github.com/yoshi389111/github-profile-3d-contrib">3d-contrib</a></sub>

</div>
