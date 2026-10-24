<!-- CABEÇALHO OBSIDIAN & ELECTRIC BLUE (IDENTIDADE DO SITE) -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:070b14,40:0e1526,100:1d4ed8&height=200&section=header&text=Douglas%20Nunes%20da%20Silva&fontSize=38&fontColor=ffffff&fontAlignY=38&desc=Intelig%C3%AAncia%20Artificial%20%7C%20Engenharia%20de%20Software%20%7C%20Bioinform%C3%A1tica&descSize=15&descAlignY=58&descAlign=50"/>
</div>

<!-- BARRA DE STATUS & LOCALIZAÇÃO (RÉPLICA DO SEU SITE) -->
<div align="center">
  <p>
    <code>🟢 ATUANDO EM IA NA SEFAZ-RN &amp; PESQUISA NO BIOME</code> &nbsp;&bull;&nbsp; 
    <code>📍 NATAL, RN &middot; BRASIL</code> &nbsp;&bull;&nbsp;
    <code>🎓 BTI &middot; IMD / UFRN</code>
  </p>
</div>

<!-- BARRA DE AÇÕES & LINKS DIRETOS -->
<div align="center">
  <a href="https://douglaxn.github.io/curriculo/" target="_blank">
    <img src="https://img.shields.io/badge/Portfólio_Online-3b82f6?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfólio" />
  </a>
  <a href="https://douglaxn.github.io/curriculo/curriculo_douglas_nunes.pdf" target="_blank">
    <img src="https://img.shields.io/badge/Currículo_A4-0e1526?style=for-the-badge&logo=read-the-docs&logoColor=3b82f6" alt="Download CV" />
  </a>
  <a href="https://www.linkedin.com/in/douglas-nunes-da-silva-78a95319b/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:douglas.nunes.132@ufrn.edu.br" target="_blank">
    <img src="https://img.shields.io/badge/E--mail-ea4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="http://lattes.cnpq.br/8276138975780850" target="_blank">
    <img src="https://img.shields.io/badge/Lattes_CNPq-003366?style=for-the-badge&logo=academia&logoColor=white" alt="Lattes" />
  </a>
</div>

<br>

> Desenvolvedor e pesquisador com atuação prática em **IA Generativa, arquiteturas de microsserviços e sistemas multiagente (LangGraph / FastMCP)** para automação de demandas fiscais na **SEFAZ-RN**. Em **Bioinformática**, desenvolvo pipelines de análise de expressão gênica (**RNA-seq**) e modelagem de redes em **R**, com execução em lote em clusters de alta performance (**Supercomputador NPAD / Slurm**).

---

### 🌐 Campos de Especialidade

<table>
  <tr>
    <td width="33%" valign="top">
      <h4>🧠 IA &amp; Sistemas Multiagente</h4>
      <p><em>Automação e cognição na SEFAZ-RN</em></p>
      <ul>
        <li>Orquestração orientada a grafos com <strong>LangGraph</strong> (ciclos de decisão e fallbacks).</li>
        <li>Servidor <strong>FastMCP via SSE</strong> para desacoplamento de ferramentas e agentes.</li>
        <li>Busca semântica vetorial (RAG) com <strong>ChromaDB</strong> e anonimização LGPD.</li>
        <li>Classificação de chamados tributários com <strong>BERT (PyTorch)</strong> e <strong>MLflow</strong>.</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h4>🧬 Bioinformática &amp; Supercomputação</h4>
      <p><em>Pesquisa científica no BioME / IMD</em></p>
      <ul>
        <li>Análise transcriptômica de larga escala (<strong>RNA-seq</strong>) e redes gênicas em <strong>R</strong>.</li>
        <li>Administração e submissão de rotinas no <strong>Supercomputador NPAD</strong> (Linux HPC).</li>
        <li>Processamento paralelo distribuído com <strong>Slurm</strong> e pipelines automatizados em <strong>Bash</strong>.</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h4>⚡ Plataforma &amp; Microsserviços</h4>
      <p><em>Engenharia de integração e dados</em></p>
      <ul>
        <li>APIs assíncronas e webhooks em <strong>Python (FastAPI/Flask)</strong> e <strong>Node.js</strong>.</li>
        <li>Mensageria e eventos com <strong>RabbitMQ</strong> e persistência volátil com <strong>Redis</strong>.</li>
        <li>Integrações com <strong>Oracle Database (PL/SQL)</strong> e PostgreSQL.</li>
        <li>Ambientes conteinerizados com <strong>Docker</strong> e esteiras GitOps.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🚀 Soluções &amp; Agentes em Produção

<div align="center">

| Projeto / Solução | Escopo &amp; Arquitetura | Tecnologias Centrais | Status |
| :--- | :--- | :---: | :---: |
| **Core MAS &amp; FastMCP** | Plataforma de microsserviços integrando agentes via Server-Sent Events, mensageria e telemetria. | `Flask-RESTX` `LangGraph` `FastMCP` `RabbitMQ` `Redis` | `🟢 Produção` |
| **Agente Odin** | Assistente para auditores fiscais integrado ao Mattermost com consultas tributárias em tempo real. | `Node.js` `WebSockets` `FastMCP (SSE)` `Oracle DB` | `🟢 Produção` |
| **Agente EFD** | Consultor especialista em Escrituração Fiscal Digital (SPED/ICMS) com busca vetorial de normativas. | `LangGraph` `ChromaDB` `SPED/EFD` `Python` | `🟢 Produção` |
| **Agente Sofia** | Assistente de campo com leitura de NF-e por QR Code, geolocalização e checagem no Oracle SIGAT. | `Telegram API` `Oracle SIGAT` `pyzbar` `Python` | `🟡 Homologação` |
| **Agente Talita** | Atendimento virtual ao contribuinte no Portal UVT com anonimização de dados e busca legislativa. | `Portal UVT` `ChromaDB` `FastEmbed` `DeepSeek` | `🟡 Homologação` |
| **Pipeline RNA-seq** | Pipeline de análise diferencial e modelagem de redes booleanas rodando no cluster de supercomputação. | `R` `Linux HPC` `NPAD / Slurm` `Bash` | `🔬 BioME/UFRN` |

</div>

---

### 🛠️ Tech Radar

<div align="center">

| Categoria | Tecnologias &amp; Ferramentas |
| :--- | :--- |
| **Linguagens &amp; Scripts** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![PL/SQL](https://img.shields.io/badge/PL%2FSQL-F80000?style=flat-square&logo=oracle&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) |
| **Backend &amp; Integração** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |
| **IA, Dados &amp; HPC** | ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=chainlink&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF4B4B?style=flat-square&logo=databricks&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![NPAD HPC](https://img.shields.io/badge/NPAD%20Supercomputer-FCC624?style=flat-square&logo=linux&logoColor=black) ![Oracle DB](https://img.shields.io/badge/Oracle_DB-F80000?style=flat-square&logo=oracle&logoColor=white) |

</div>

---

### 📊 GitHub Activity &amp; Métricas (Tema Customizado Obsidian Slate)

<div align="center">
  <img
    src="https://streak-stats.demolab.com?user=DouglaxN&locale=pt-br&mode=daily&background=0e1526&border=1e293b&stroke=3b82f6&ring=3b82f6&fire=3b82f6&currStreakNum=ffffff&sideNums=94a3b8&currStreakLabel=3b82f6&dates=64748b&hide_border=false&border_radius=8"
    height="175"
    alt="GitHub Streak"  
  />
  <img
    alt="GitHub Stats"
    height="175"
    src="https://github-readme-stats.vercel.app/api?username=DouglaxN&show_icons=true&bg_color=0e1526&title_color=3b82f6&text_color=94a3b8&icon_color=3b82f6&border_color=1e293b&border_radius=8&locale=pt-br&hide_title=true"
  />
</div>

<br>

<div align="center">
  <img
    alt="Linguagens Mais Utilizadas"
    height="175"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=DouglaxN&bg_color=0e1526&title_color=3b82f6&text_color=94a3b8&border_color=1e293b&border_radius=8&custom_title=Linguagens%20em%20Destaque&layout=compact&langs_count=6"
  />
</div>

---

<!-- RODAPÉ SUTIL -->
<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=DouglaxN.DouglaxN&color=3b82f6" alt="Visitor Badge" />
</div>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:070b14,60:0e1526,100:070b14&height=100&section=footer"/>
</div>
