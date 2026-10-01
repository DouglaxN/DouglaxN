<div align="center">

# DOUGLAS NUNES DA SILVA
### `Software & Data Engineer` • `AI Multi-Agent Systems` • `Bioinformatics`

<p align="center">
  <a href="https://linkedin.com/in/douglas-nunes-da-silva"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="http://lattes.cnpq.br/8276138975780850"><img src="https://img.shields.io/badge/Currículo_Lattes-003366?style=flat-square&logo=academia&logoColor=white" /></a>
  <a href="https://douglaxn.github.io/curriculo"><img src="https://img.shields.io/badge/Live_Portfolio_(CV)-2563EB?style=flat-square&logo=googlechrome&logoColor=white" /></a>
  <a href="mailto:douglas.nunes.132@ufrn.edu.br"><img src="https://img.shields.io/badge/Email-douglas.nunes.132@ufrn.edu.br-0f172a?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>

<p align="center">
  <sub>📍 Natal, RN — Brasil • 🎓 Discente de Tecnologia da Informação (IMD / UFRN) • 💻 Técnico em TI (IFRN)</sub>
</p>

</div>

---

> ### 📋 Resumo Executivo
> Graduando em Tecnologia da Informação (IMD/UFRN) e Técnico em TI pelo IFRN. Atuo como **Estagiário em Ciência de Dados e IA na SEFAZ-RN**, desenvolvendo arquiteturas de microsserviços multiagentes com **LangGraph**, sistemas de busca semântica **RAG** e APIs em Python com **Docker**. Como **Pesquisador de Iniciação Científica (PIBIC) no BioME/UFRN**, construo pipelines reprodutíveis em **Nextflow** e **R** para análise de dados transcriptômicos (*RNA-seq*) em larga escala. Foco em arquitetura de software resiliente, padrões de projeto e engenharia de dados.

---

### 🏛️ Projetos & Arquiteturas em Destaque

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🤖 Ecossistema Multiagentes de IA — SEFAZ-RN</h4>
      <p>Arquitetura corporativa desacoplada utilizando padrões <i>Facade</i> e <i>Factory</i>, com grafos de estados finitos (<b>LangGraph</b>), memória distribuída em <b>Redis</b> e observabilidade de tokens via <b>MLflow</b>:</p>
      <ul>
        <li><b>Agente Sofia:</b> Atendimento a postos fiscais via Telegram com leitura de QR Code em documentos fiscais e conversão de áudio.</li>
        <li><b>Agente Odin:</b> Agente operacional no Mattermost com chamadas de ferramentas (<i>tool-calling</i>) para busca automatizada de chamados e processos.</li>
        <li><b>Agente Talita:</b> Assistente virtual do Portal UVT para dúvidas tributárias com RAG semântico e direcionamento ao Fale Conosco.</li>
      </ul>
      <p>
        <code>LangGraph</code> • <code>LangChain</code> • <code>ChromaDB</code> • <code>Redis</code> • <code>Docker</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>🧬 Pipelines de Transcriptômica — BioME / UFRN</h4>
      <p>Processamento e mineração computacional de dados biológicos de sequenciamento em larga escala e reconstrução de redes regulatórias:</p>
      <ul>
        <li>Desenvolvimento de pipelines automatizados e escaláveis em <b>Nextflow</b> para clusters de alta performance (HPC/Linux).</li>
        <li>Controle de qualidade, alinhamento e análise de expressão gênica diferencial (*RNA-seq*) em <b>R</b> e <b>Shell Script</b>.</li>
        <li>Dois ciclos formais de pesquisa (PIBIC/PROPESQ) sob orientação dos professores do BioME/IMD.</li>
      </ul>
      <p>
        <code>Nextflow</code> • <code>R</code> • <code>Linux HPC</code> • <code>RNA-seq</code> • <code>Bash</code>
      </p>
    </td>
  </tr>
</table>

---

### ⚡ Microsserviços & Engenharia de Dados

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>💬 API Talita — Motor de NLP</h4>
      <p>Microsserviço REST sob arquitetura MSC (<i>Model-Service-Controller</i>) com modelo de rede neural profunda (<b>Keras/TensorFlow</b>) e normalização de texto para triagem e classificação de intenções.</p>
      <p><code>Python</code> • <code>TensorFlow</code> • <code>Flask-RESTX</code> • <code>NLTK</code></p>
    </td>
    <td width="50%" valign="top">
      <h4>📥 API Caixa de Entrada — Pipeline Fale Conosco</h4>
      <p>Pipeline de engenharia de dados com sanitização textual, remoção de ruídos e motor de inferência rápida em <b>FastText</b> para classificação automática de demandas tributárias.</p>
      <p><code>FastText</code> • <code>Pandas</code> • <code>Flask</code> • <code>Docker</code></p>
    </td>
  </tr>
</table>

---

### 💻 Habilidades & Competências Técnicas

| Área | Competências |
| :--- | :--- |
| **Inteligência Artificial & LLMs** | LangGraph (StateGraph, Tool-Calling), LangChain, RAG, ChromaDB, FastEmbed, Keras/TensorFlow, FastText, NLTK, APIs OpenAI e DeepSeek |
| **Back-end & Microsserviços** | Python (FastAPI, Flask-RESTX), Java (Fundamentos Spring Boot / POO), PHP (Laravel), Padrão RESTful, JSON, SQLAlchemy |
| **Bancos de Dados & Cache** | PostgreSQL, MySQL, Oracle DB, Redis (cache e sessão distribuída), ChromaDB (vetorial), modelagem e consultas SQL |
| **DevOps & Pipelines** | Docker, Docker Compose, Git / GitHub (Git Flow, code reviews), Linux/Bash, Nextflow, Apache Airflow, Argo CD, Harbor |
| **Metodologias & Práticas** | Padrões de Projeto (GoF: Facade, Factory, MSC), Metodologias Ágeis (Scrum, Kanban), Testes de Software, Clean Code |

---

### ⚙️ Princípios de Engenharia

1. **Arquitetura antes de scripts:** Uso de máquinas de estados explícitas, desacoplamento de responsabilidades e *fallbacks* resilientes em vez de monolitos frágeis.
2. **Reprodutibilidade por design:** Ambientes conteinerizados com Docker e pipelines determinísticos com Nextflow para garantir que o código rode igual em qualquer máquina ou cluster.
3. **Segurança e Privacidade:** Aplicação de *guardrails* na borda e anonimização preventiva de dados sensíveis sob as diretrizes da LGPD.

---

<div align="center">

### 📊 Atividade & Contribuições

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=DouglaxN&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DouglaxN&layout=compact&langs_count=6&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/DouglaxN/DouglaxN/output/github-contribution-grid-snake-dark.svg">
    <img alt="Snake animation" src="https://raw.githubusercontent.com/DouglaxN/DouglaxN/output/github-contribution-grid-snake.svg">
  </picture>
</p>

</div>
