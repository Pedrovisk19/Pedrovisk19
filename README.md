<!-- ======================= HEADER ======================= -->
<h1 align="center">Pedro Souza • Python & AI Engineering</h1>

<p align="center">
  <b>Python • FastAPI • LLM/agentes • RAG • PostgreSQL • Docker</b><br/>
  Sistemas de IA que operam de verdade: do banco ao WhatsApp do cliente.
</p>

<p align="center">
  <a href="mailto:contato@lumix.com.br">
    <img src="https://img.shields.io/badge/Email-Contato-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/pedrovisk19">
    <img src="https://img.shields.io/badge/GitHub-Perfil-111111?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://github.com/pedrovisk19/wappai">
    <img src="https://img.shields.io/badge/WAppAI-Projeto%20destaque-4FC08D?style=for-the-badge&logo=whatsapp&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=pedrovisk19&label=Views&color=6C63FF&style=flat" />
</p>

<hr/>

<!-- ======================= STACK ICONS ======================= -->
<h2 align="center">🧰 Stack (o que eu construo)</h2>

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,postgres,redis,docker,git,github,linux,nginx,vercel&perline=9" />
</p>

<p align="center">
  <b>FastAPI</b> · SQLAlchemy/asyncpg · Alembic · ARQ (fila) · pgvector (RAG híbrido) ·
  LLMs (Groq ou qualquer API OpenAI-compatible) · engenharia de prompt ·
  avaliação de respostas · Next.js (painel)
</p>

<hr/>

<!-- ======================= PROJETOS ======================= -->
<h2 align="center">🚀 Projetos em Python/IA</h2>

| Projeto | O que é | Destaques técnicos |
|---|---|---|
| 🔥 **[WAppAI](https://github.com/pedrovisk19/wappai)** | SaaS multi-tenant de atendimento via WhatsApp com IA — **em produção com número comercial real** | RAG híbrido (pgvector + FTS + RRF), agentes com saída JSON validada + anti-alucinação, handoff humano (fila idempotente), RLS por tenant, credenciais criptografadas (Fernet), CI |
| 🧠 **[Developer Brain AI](https://github.com/pedrovisk19/linkedin-automation)** | Segundo cérebro para devs: diário técnico, roadmap de estudos, agentes de IA (LinkedIn/GitHub/Planner/Carreira), RAG sobre a própria base, automações diárias | Python, agentes, memória persistente, integração de ferramentas |

<details>
<summary><b>Detalhes que mostram maturidade de engenharia</b></summary>

- **Isolamento multi-tenant real**: Row-Level Security no PostgreSQL, provado por testes de cross-tenant (API e banco)
- **RAG híbrido**: busca semântica (cosine/pgvector) × lexical (ts_rank) fundidas por **RRF** (reciprocal rank fusion); chunking por parágrafos; ingestão de PDF/DOCX/TXT/sites
- **Anti-alucinação**: alegações sensíveis (preço/prazo/estoque) só têm resposta com base recuperada — sem base, resposta honesta + handoff
- **Resiliência operacional**: idempotência de webhook, debounce agregando mensagens, flush pós-commit (bug de MVCC capturado com teste), rate limiter com fail-open audível
- **Credenciais por conta criptografadas** (Fernet) + token System User permanente de WhatsApp — troca de token sem expor segredos
- **Diário de bugs reais**: redis-py v5 (`redis.time()` retorna tupla), constraint + soft-delete, conversas amarradas à conta morta — tudo documentado

</details>

<hr/>

<!-- ======================= HISTÓRICO ======================= -->
<h2 align="center">📜 Histórico (exploração anterior — arquivado)</h2>

<p align="center">
  Antes do foco Python/IA, construí com TypeScript/JavaScript:
  <b>NestJS + PostgreSQL</b> (JWT, agendamento SaaS), <b>Next.js 14</b> (auth + rotas
  protegidas) e fundamentos (Node.js puro, HTML/CSS). Esses repos estão
  <b>arquivados</b> — o foco daqui para frente é <b>100% Python/IA</b>. A base
  fullstack segue a serviço: o painel do WAppAI é Next.js e os padrões de
  banco/queries são os mesmos.
</p>

<hr/>

<!-- ======================= ABOUT ======================= -->
<h2 align="center">⚡ Como eu trabalho</h2>

<ul>
  <li><b>Clareza primeiro:</b> confirmo objetivo, critérios de aceite e casos de borda antes de codar.</li>
  <li><b>Simples e forte:</b> prefiro solução enxuta + bem testada do que complexa + frágil.</li>
  <li><b>Full cycle:</b> penso em validação, logs, banco, performance prática e produção — incluindo custo de LLM.</li>
  <li><b>Time-friendly:</b> PRs pequenos, commits com intenção, docs objetivas. 93+ testes unitários em ~6s.</li>
</ul>

<h2 align="center">🎯 Próximos degraus (em progresso)</h2>

<p align="center">
  <b>Observabilidade/eval de agentes</b> · <b>RAG incremental</b> · <b>reranking</b> ·
  <b>biblioteca de tools por domínio</b> — o roadmap está anotado no
  <a href="https://github.com/pedrovisk19/wappai/blob/main/docs-public/STATUS.md"><b>STATUS do WAppAI</b></a>.
</p>

<hr/>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=pedrovisk19&theme=tokyonight&hide_border=true&date_format=j%20M%5B%20Y%5D" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=pedrovisk19&theme=tokyo-night&hide_border=true" />  
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/pedrovisk19/pedrovisk19/output/github-contribution-grid-snake-dark.svg" alt="snake animation" />
</p>

<hr/>

<p align="center">
  <b>Python, IA aplicada e produtos que funcionam — vamos conversar.</b> 👊
</p>
