## Hi, I'm Nicolas (Nick) Desjardins

**Applied AI developer and senior full-stack developer in Greater Montreal. I work in English and French.**

I build AI that reads your documents, answers from your own files, and shows you the source.

Eight years of running production web systems for New Roots Herbal Inc. taught me that the hard part of AI is not the model call. It is the data that feeds it, the schema that checks it, the fallback that catches it, and the test that proves it worked.

[![Portfolio](https://img.shields.io/badge/Portfolio-webman.dev-22d3ee?style=flat-square)](https://webman.dev) [![Version française](https://img.shields.io/badge/Version_fran%C3%A7aise-webman.dev%2Ffr-22d3ee?style=flat-square)](https://webman.dev/fr) [![LinkedIn](https://img.shields.io/badge/LinkedIn-nicolas--desjardins-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nicolas-desjardins/) [![Resume](https://img.shields.io/badge/Resume-PDF-1f2937?style=flat-square)](https://webman.dev/Nicolas-Desjardins-Resume.pdf) [![CV en français](https://img.shields.io/badge/CV_fran%C3%A7ais-PDF-1f2937?style=flat-square)](https://webman.dev/Nicolas-Desjardins-CV.pdf)

> **Available:** open to full-time roles, contracts and agency placements. Hybrid in Montreal or remote across Canada and the US.

### What I can build for your company

| The problem, in plain words | What engineers call it | Proof |
| --- | --- | --- |
| Invoices, purchase orders and forms are still retyped by hand | Document data extraction with a validated schema and model fallback | [Invoice reader](https://webman.dev/projects/invoice-data-extraction): 21 of 21 test invoices fully correct on the 7 October 2026 benchmark |
| Staff can't find answers in your procedures and regulatory manuals | Hybrid retrieval (RAG) with verified citations | [Ask your manuals](https://webman.dev/projects/compliance-document-search): 6 of 6 recorded questions answered with verified quotes, 1 of 1 out-of-scope question declined |
| Your websites and online store must not go down when servers change | Infrastructure migration and web platform development | 30+ websites migrated with zero downtime at New Roots Herbal Inc. |
| Your team wants a site it can edit, which AI tools can also operate safely | AI-native CMS with an MCP server | [NextBlock CMS](https://nextblock.dev): 56 MCP tools, 8 npm packages |

### Live projects

**[Invoice reader](https://webman.dev/projects/invoice-data-extraction)** · [`Invoice-Extraction-Service`](https://github.com/nickdesjardins/Invoice-Extraction-Service)<br>
Turns PDFs, scans and forwarded emails into clean invoice data an accounting system can import. If one AI provider is slow or down, it switches to another on its own.<br>
<sub>FastAPI · Pydantic v2 · strict JSON schema at temperature 0 · model fallback chain · 10 provider failure classes tested offline · measured: 21/21 fully correct on the dated benchmark (7 Oct 2026)</sub>

**[Ask your manuals](https://webman.dev/projects/compliance-document-search)** · [`hybrid-knowledge-rag`](https://github.com/nickdesjardins/hybrid-knowledge-rag)<br>
Staff ask a question about procedures or regulations and get an answer that quotes the exact passage and page. When the documents do not say it, the answer says so.<br>
<sub>PostgreSQL · pgvector (HNSW) and full-text search fused with Reciprocal Rank Fusion · cross-encoder re-rank · quotes re-anchored to stored text · measured on 7 recorded runs (14 Oct 2026): 6/6 answered with verified citations, 1/1 out-of-corpus question declined</sub>

**[NextBlock CMS](https://nextblock.dev)** · [`nextblock-cms/nextblock`](https://github.com/nextblock-cms/nextblock)<br>
An open-source, AI-native CMS for Next.js and Supabase that I designed and built: block editor, commerce, an MCP server AI agents can operate, and a one-command installer.<br>
<sub>Next.js 16 · React Server Components · Supabase with row-level security · MCP server with 56 tools · 8 npm packages at v0.21.3 · 11.5k CLI downloads in the 30 days to 7 Oct 2026</sub>

**Next up, planned (their numbers are targets, not results):** supervised operations agents with human approval (LangGraph), and an AI quality gate with evaluation in CI, tracing and caching.

### Stack I ship with

**AI and Python:** Python · FastAPI · Pydantic v2 · OpenRouter · Claude and OpenAI APIs · pgvector · structured outputs · MCP<br>
**Web:** TypeScript · Next.js · React · Tailwind CSS · Laravel · PHP<br>
**Data and ops:** PostgreSQL · Supabase · MySQL · Docker · Linux VPS · GitHub Actions · Vercel · Render

### Before AI

- **Lead Web Developer, New Roots Herbal Inc.** (2018 to present): production web platforms, an internal multi-model AI pipeline for product content, and infrastructure for 30+ websites.
- **Founder, PcSquad** (2012 to 2018): IT and web consultancy for individuals and small businesses.
- **Canadian Armed Forces, RCEME** (2013 to 2016): weapons technician. Where I learned to follow a checklist when it matters most.

### En français

Développeur en IA appliquée et développeur full-stack senior dans le Grand Montréal. Je conçois des outils d'IA qui lisent vos documents, répondent à partir de vos propres fichiers et vous montrent la source. Ouvert aux postes permanents, aux contrats et aux placements par agence. Portfolio en français : **[webman.dev/fr](https://webman.dev/fr)**.

### Contact

**[nick.desjardins@live.com](mailto:nick.desjardins@live.com)** · [webman.dev/#contact](https://webman.dev/#contact) · I reply within one business day.
