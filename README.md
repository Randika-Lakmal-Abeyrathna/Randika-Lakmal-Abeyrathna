<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e1e2e,50:89b4fa,100:cba6f7&height=210&section=header&text=Randika%20Abeyrathna&fontSize=48&fontColor=ffffff&fontAlignY=36&desc=Lead%20Software%20Engineer%20%E2%80%A2%20Java%20%E2%80%A2%20Spring%20Boot%20%E2%80%A2%20Oracle%20%E2%80%A2%20AWS&descAlignY=58&descSize=17&animation=fadeIn" alt="header" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=89B4FA&center=true&vCenter=true&width=650&lines=Hi+there!+I'm+Randika+%F0%9F%91%8B;Lead+Software+Engineer+%40+IFS;8%2B+years+building+enterprise+Java+backends;Turning+slow+queries+into+fast+ones+%E2%9A%A1;Building+AI-powered+backends+with+Spring+AI+%F0%9F%A4%96;Mentoring+engineers%2C+still+hands-on" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/randika-abeyrathna"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:randika.l.abeyrathna@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Open%20to-Backend%20Collaborations-a6e3a1?style=for-the-badge" alt="Open to collaborations" />
  <img src="https://komarev.com/ghpvc/?username=Randika-Lakmal-Abeyrathna&style=for-the-badge&color=89b4fa&label=Profile+Views" alt="Profile views" />
</p>

---

## 👨‍💻 About Me

I'm a **Lead Software Engineer** with **8+ years** of experience designing and building enterprise Java backends.
I've shipped software across **aerospace, banking, healthcare and financial services**, and I enjoy the hard parts:
untangling legacy systems, tuning databases, and helping engineers grow — while staying hands-on with the code.

- 🏢 Currently leading a backend team at **IFS**, modernizing legacy Java/JSP modules onto **IFS Cloud (Aurena)**
- 🤖 Exploring **AI in the Java world**: building LLM-powered features with **Spring AI** & **LangChain4j**
- ⚡ I like reading **execution plans** more than most people should
- 🧑‍🏫 I mentor engineers through code reviews, pairing and knowledge sharing
- 🧠 Always sharpening my **Data Structures & Algorithms**
- 🌍 Based in **Colombo, Sri Lanka** 🇱🇰
- 🤝 Open to collaborating on **backend & system design** projects

```java
public class Randika extends SoftwareEngineer {

    String role       = "Lead Software Engineer";
    int    experience = 8; // years, and counting
    String[] domains  = { "Aerospace", "Banking", "Healthcare", "Financial Services" };

    String[] currentFocus = {
        "Enterprise modernization (IFS Cloud / Aurena)",
        "Oracle SQL & PL/SQL performance tuning",
        "Scalable Spring Boot microservices",
        "AI-powered backends with Spring AI",
        "Leading & mentoring engineering teams"
    };

    String funFact = "A query plan with a FULL TABLE SCAN keeps me up at night.";
}
```

---

## 🤖 AI × Backend Engineering

I believe the next wave of enterprise software is **Java backends that can think**. I'm bringing AI into the
Spring ecosystem I know best: same reliability, security and observability, now with LLMs in the loop.

| 🔍 What I'm exploring | 💡 Why it matters |
|---|---|
| **Spring AI** `ChatClient`, prompt templates & structured output | Add LLM features to existing Spring Boot services without leaving Java |
| **RAG** with embeddings & vector stores (**pgvector**) | Let AI answer from real enterprise data, not guesses |
| **Tool / function calling** & **MCP** | Let models safely call existing APIs and business logic |
| **AI-assisted development** (Claude Code, Copilot) | Ship faster and review smarter as a team lead |

```java
@RestController
class AskController {

    private final ChatClient chat;

    AskController(ChatClient.Builder builder) {
        this.chat = builder
            .defaultSystem("You are a helpful assistant for enterprise backend engineers.")
            .build();
    }

    @GetMapping("/ask")
    String ask(@RequestParam String question) {
        return chat.prompt().user(question).call().content();
    }
}
```

---

## 🛠️ Tech Stack

| | |
|---|---|
| **💬 Languages** | <img src="https://skillicons.dev/icons?i=java,js&theme=dark" height="40" alt="Java, JavaScript" /> <img src="https://img.shields.io/badge/PL%2FSQL-F80000?style=for-the-badge" alt="PL/SQL" /> |
| **⚙️ Backend** | <img src="https://skillicons.dev/icons?i=spring&theme=dark" height="40" alt="Spring" /> <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" /> <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white" alt="Spring Security" /> <img src="https://img.shields.io/badge/Java%20EE-007396?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java EE" /> <img src="https://img.shields.io/badge/REST%20APIs-313244?style=for-the-badge" alt="REST APIs" /> <img src="https://img.shields.io/badge/Microservices-313244?style=for-the-badge" alt="Microservices" /> <img src="https://img.shields.io/badge/IFS%20Cloud%20Aurena-7D3C98?style=for-the-badge" alt="IFS Cloud Aurena" /> |
| **🗄️ Databases** | <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge" alt="Oracle" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" /> <img src="https://img.shields.io/badge/IBM%20DB2-052FAD?style=for-the-badge" alt="IBM DB2" /> |
| **☁️ Cloud** | <img src="https://skillicons.dev/icons?i=aws&theme=dark" height="40" alt="AWS" /> <img src="https://img.shields.io/badge/EC2-FF9900?style=for-the-badge" alt="EC2" /> <img src="https://img.shields.io/badge/RDS-FF9900?style=for-the-badge" alt="RDS" /> <img src="https://img.shields.io/badge/S3-FF9900?style=for-the-badge" alt="S3" /> <img src="https://img.shields.io/badge/Route%2053-FF9900?style=for-the-badge" alt="Route 53" /> <img src="https://img.shields.io/badge/SNS-FF9900?style=for-the-badge" alt="SNS" /> <img src="https://img.shields.io/badge/SQS-FF9900?style=for-the-badge" alt="SQS" /> |
| **🤖 AI & LLMs** | <img src="https://img.shields.io/badge/Spring%20AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring AI" /> <img src="https://img.shields.io/badge/LangChain4j-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain4j" /> <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude" /> <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge" alt="OpenAI" /> <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" /> <img src="https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="pgvector" /> <img src="https://img.shields.io/badge/RAG-313244?style=for-the-badge" alt="RAG" /> <img src="https://img.shields.io/badge/MCP-313244?style=for-the-badge" alt="MCP" /> |
| **🚀 DevOps & Tools** | <img src="https://skillicons.dev/icons?i=docker,jenkins,git,github,bitbucket,rabbitmq&theme=dark" height="40" alt="DevOps tools" /> <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="Jira" /> |
| **🧭 Ways of Working** | <img src="https://img.shields.io/badge/Agile-313244?style=for-the-badge" alt="Agile" /> <img src="https://img.shields.io/badge/Scrum-313244?style=for-the-badge" alt="Scrum" /> <img src="https://img.shields.io/badge/TDD-313244?style=for-the-badge" alt="TDD" /> <img src="https://img.shields.io/badge/CI%2FCD-313244?style=for-the-badge" alt="CI/CD" /> |
| **🧪 Also played with** | <img src="https://skillicons.dev/icons?i=python,django,angular,vue,html,bootstrap,mysql&theme=dark" height="40" alt="Other technologies" /> |

---

## 🚀 Career Journey

```mermaid
timeline
    2017 : Associate Software Engineer
         : Swarnamahal Financial Services
    2019 : Software Engineer
         : Digital banking (Silverlake, Malaysia)
    2021 : Senior Software Engineer
         : Healthcare - HCL Technologies
    2024 : Senior Software Engineer
         : MEXXAR, then IFS
    2025 : Lead Software Engineer
         : IFS
```

<details>
<summary><b>🏆 A few things I'm proud of</b> (click to expand)</summary>
<br>

- 🔄 Driving a large-scale **legacy Java/JSP → IFS Cloud Aurena** modernization at IFS
- ⚡ Speeding up enterprise apps by **tuning Oracle SQL**, redesigning views and reading a *lot* of execution plans
- 👥 Leading a **team of 5 backend engineers** and introducing Agile + Jira sprint planning at MEXXAR
- ☁️ Owning **AWS infrastructure and deployment pipelines** for production releases
- 🏦 Building digital banking features for **People's Bank Sri Lanka**
- 🏪 Building a pawning system used across **17 branches** and an HR system for **500+ employees**

</details>

<details>
<summary><b>🎓 Education</b> (click to expand)</summary>
<br>

- **MSc in Information Technology** — Cardiff Metropolitan University · *Distinction*
- **B.Eng. in Software Engineering** — IIC University of Technology · *Second Upper Class*

</details>

---

## 💬 Ask Me About

`Spring Boot microservices` · `Oracle performance tuning` · `Legacy modernization` · `AWS deployments` · `Spring AI & RAG` · `Leading backend teams` · `Code reviews that actually help`

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Randika-Lakmal-Abeyrathna&theme=tokyonight" alt="Stats" />
  <img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Randika-Lakmal-Abeyrathna&theme=tokyonight" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Randika-Lakmal-Abeyrathna&theme=catppuccin-mocha&hide_border=true&border_radius=10" alt="GitHub streak" />
</p>

<p align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Randika-Lakmal-Abeyrathna&theme=tokyonight" alt="Contribution graph" />
</p>

---

## 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Randika-Lakmal-Abeyrathna/Randika-Lakmal-Abeyrathna/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Randika-Lakmal-Abeyrathna/Randika-Lakmal-Abeyrathna/output/github-snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/Randika-Lakmal-Abeyrathna/Randika-Lakmal-Abeyrathna/output/github-snake-dark.svg" />
  </picture>
</p>

---

## ✍️ Random Dev Quote

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random dev quote" />
</p>

<!-- Footer -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:cba6f7,50:89b4fa,100:1e1e2e&height=120&section=footer" alt="footer" />
</p>
