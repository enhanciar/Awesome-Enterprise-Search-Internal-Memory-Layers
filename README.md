# Awesome-Enterprise-Search-Internal-Memory-Layers

# Top Enterprise Search & Internal Memory Layers Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Unified Corporate Knowledge, Permission-Aware Retrieval & Internal Memory*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Search & Internal Memory Layers**. These tools map unstructured team documentation—wikis, chat, tickets, code, drives—into a unified, permission-aware corporate knowledge layer that both humans and AI agents can query.

**Examples** include Glean, Hebbia, Guru, Coveo, Perplexity Enterprise, Dashworks, Qatalog, GoSearch, Slite, and Amazon Kendra (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, permission-mirroring connectors, and open retrieval infrastructure—ideal for platform engineers, knowledge managers, and developers seeking transparent, vendor-independent enterprise search.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Glean](https://www.glean.com/)**  
  The category-defining enterprise search and AI platform. **100+ connectors**, permissions-aware retrieval that inherits source-system ACLs, and Glean Assistant for natural-language Q&A grounded in corporate knowledge. **No public pricing**—quoted annually, typically six figures for mid-market and above. Unusually horizontal—works for engineering, sales, support, and HR without vertical-specific configuration. **The benchmark most open-source alternatives are measured against.**

- **[Coveo](https://www.coveo.com/)**  
  Enterprise AI search platform with a strong **relevance engine** and mature connector library. Features Coveo Relevance Generative Answering (RGA) for RAG over indexed content. **Credit-based pricing** tied to search and query volumes. Strongest for **customer-facing support search** and product catalog search alongside internal knowledge. **The most mature relevance tuning** in the category.

- **[Guru](https://www.getguru.com/)**  
  Knowledge management platform with **verified cards**—content is captured, verified by subject-matter experts, and surfaced in the flow of work (Slack, Teams, browser). Features Guru's AI Assistant grounded in verified knowledge. **$15/user/month** for the Knowledge plan (annual) as of 2026 . Best for **support and customer-facing teams** where answer accuracy matters more than comprehensive coverage.

- **[Hebbia](https://www.hebbia.com/)**  
  AI research and document analysis platform. **Matrix** interface enables structured analysis across thousands of documents simultaneously—extract, compare, and synthesize without reading each one. **No public pricing**; enterprise contracts. Best for **financial services, legal, and consulting** where document-heavy diligence is the core workflow.

- **[Perplexity Enterprise](https://www.perplexity.ai/enterprise)**  
  Enterprise version of Perplexity's answer engine. Features **internal knowledge search combined with web search**, user management, and data retention controls. **$40/user/month** (annual) as of 2026 . Best for teams already using Perplexity who want internal connectors added.

- **[Dashworks](https://www.dashworks.ai/)**  
  AI-powered enterprise search and assistant. Features **100+ integrations**, permissions-aware retrieval, and Dashworks Answers. **$19/user/month** (annual) for the Team plan . Positioned as **lower-cost Glean alternative** for startups and mid-market.

- **[Qatalog](https://qatalog.com/)**  
  Work intelligence platform unifying search, people, and projects. Acquired by **ZoomInfo (2026)**—roadmap under new ownership is still settling . Strong at **people and project discovery** alongside document search.

- **[GoSearch](https://www.gosearch.ai/)**  
  AI-powered enterprise search with **100+ connectors** and customizable AI answers. **$15/user/month** (annual) for the Starter plan . Positioned as **affordable Glean alternative** for smaller organizations.

- **[Slite](https://slite.com/)**  
  AI-powered knowledge base with "Ask" search over internal documentation. Features verification workflows and templates. **$8/user/month** (annual) for the Standard plan . Best for teams using Slite as their primary documentation platform.

- **[Amazon Kendra](https://aws.amazon.com/kendra/)**  
  Fully managed AWS enterprise search service. Features **native ML-based relevance ranking** and connectors for S3, SharePoint, Salesforce, and 40+ sources. **$810/month for Enterprise Edition** (up to 2,000 documents). **Note**: AWS announced Kendra's end-of-support for **December 31, 2026**—evaluate alternatives before committing . Best for AWS-committed organizations requiring managed search infrastructure.

## Open-Source GitHub Projects

- **[Onyx (formerly Danswer)](https://github.com/onyx-dot-app/onyx)**  
  **The leading open-source enterprise search and AI assistant platform** (MIT for core). **The most mature open-source Glean alternative available.** Features **40+ connectors** (Slack, Google Drive, Confluence, Jira, Notion, GitHub, SharePoint, Teams, and more), **permission-aware retrieval** that mirrors source-system ACLs, **Onyx Assistant** for natural-language Q&A with citations, **custom assistants** with scoped knowledge and personas, and **multi-LLM support** (OpenAI, Anthropic, local models via Ollama). Self-hosted via Docker Compose or Kubernetes. **Used by Netflix, Ramp, and other enterprises.** The core is open source; Enterprise edition adds SSO, RBAC, and advanced analytics .

- **[Quivr](https://github.com/QuivrHQ/quivr)**  
  Open-source **second brain** and RAG framework (Apache 2.0). **35,000+ GitHub stars**. Ingests documents, text, and media into a personal or team knowledge base. Features multiple LLM backends, vector store options, and API access. **The most popular open-source personal/team knowledge assistant.** Less enterprise-focused than Onyx—no permission mirroring to source systems.

- **[AnythingLLM](https://github.com/Mintplex-Labs/anything-llm)**  
  Open-source all-in-one AI application for document chat and RAG (MIT). **35,000+ GitHub stars**. Features **multi-user support with permissions**, document ingestion from local files and URLs, multiple vector databases, and **desktop app + Docker deployment**. **The most accessible open-source RAG application** for teams wanting a Glean-like experience without enterprise complexity.

- **[Khoj](https://github.com/khoj-ai/khoj)**  
  Open-source AI personal assistant that searches the web and your documents (AGPL-3.0). **25,000+ GitHub stars**. Features **semantic search across PDFs, Markdown, Org-mode, Notion, Word docs**, chat with local or cloud LLMs, and integrations with Emacs, Obsidian, and browser. **The most flexible open-source personal knowledge search**—strong for individuals, weaker for team permissions.

- **[RAGFlow](https://github.com/infiniflow/ragflow)**  
  Open-source RAG engine based on deep document understanding (Apache 2.0). **40,000+ GitHub stars**. Features **DeepDoc engine** with OCR, table structure recognition (TSR), and layout analysis to accurately extract merged cells and formulas from complex documents. Multi-path retrieval combining Elasticsearch keyword search and Infinity vector search with fusion reranking. **The strongest open-source document parsing** for enterprise search—critical when your knowledge is trapped in PDFs and scanned docs.

- **[Danswer (legacy)](https://github.com/danswer-ai/danswer)**  
  The original name of Onyx—same project, rebranded. Historical references may point here.

- **[SearchX (Alibaba)](https://github.com/alibaba/SearchX)**  
  Open-source enterprise-level search platform (Apache 2.0). Built by Alibaba for **large-scale distributed search**. Features plugin-based architecture, real-time indexing, and ML ranking. **The most enterprise-scaled open-source search platform**—but documentation is primarily Chinese.

- **[Apache Solr](https://github.com/apache/solr)**  
  Open-source enterprise search platform built on Apache Lucene (Apache 2.0). **The most mature open-source search engine**—20+ years of production use. Features faceted search, highlighting, spell-check, and rich document parsing. **Not permission-aware out of the box**—requires custom ACL integration.

- **[Elasticsearch](https://github.com/elastic/elasticsearch)**  
  Distributed search and analytics engine (Elastic License 2.0 / SSPL / AGPL tri-license). **The most widely deployed open-source search engine.** Features vector search, hybrid retrieval, and machine learning. **License restrictions apply for managed service providers.**

- **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**  
  Apache 2.0-licensed fork of Elasticsearch 7.10.1 led by AWS. **The most permissively licensed enterprise search engine.** Features vector search, security plugin with document-level ACL, and OpenSearch Dashboards. **Best for teams wanting Elasticsearch capabilities without license concerns.**

- **[Meilisearch](https://github.com/meilisearch/MeiliSearch)**  
  Lightning-fast open-source search engine (MIT). **40,000+ GitHub stars**. Features typo tolerance, faceted search, and **extremely simple setup**. **The best open-source search for smaller datasets**—e-commerce, documentation, applications. Less suited for enterprise ACL mirroring.

- **[Typesense](https://github.com/typesense/typesense)**  
  Open-source typo-tolerant search engine (GPL-3.0). **20,000+ GitHub stars**. Features instant search, faceted navigation, and vector search. **The most modern open-source search engine** for application search.

### Additional Strong Open-Source Options

- **[Permit.io](https://github.com/permitio/permit)** — Open-source authorization layer that can bridge source-system ACLs to search indexes—critical for permission-aware retrieval in custom builds.
- **[SpiceDB (Authzed)](https://github.com/authzed/spicedb)** — Open-source permissions database (Apache 2.0) designed for consistent authorization across systems. Google Zanzibar-inspired—the gold standard for ACL mirroring.
- **[OpenFGA](https://github.com/openfga/openfga)** — Open-source fine-grained authorization (Apache 2.0) from CNCF. Zanzibar-inspired permission modeling.
- **[LangChain](https://github.com/langchain-ai/langchain)** / **[LlamaIndex](https://github.com/run-llama/llama_index)** — RAG frameworks for building custom search and Q&A over indexed content.
- **[Unstructured](https://github.com/Unstructured-IO/unstructured)** — Open-source document parsing library (Apache 2.0) for ingesting PDFs, HTML, Office docs into search-ready text.
- **[Haystack](https://github.com/deepset-ai/haystack)** — Open-source NLP framework (Apache 2.0) for building search and RAG pipelines.
- Community **n8n** workflows for connector orchestration and index refresh automation.

**Frameworks for building custom systems**: Combine **Onyx** for permission-aware enterprise search with **RAGFlow** for deep document parsing, **OpenSearch** for permissive search infrastructure, **SpiceDB** or **OpenFGA** for ACL mirroring, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade internal memory layer.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Enterprise search systems indexing corporate knowledge must **mirror source-system permissions**—returning documents a user cannot access is a security incident. Compliance with data protection regulations (GDPR, CCPA, etc.) is mandatory.
- **Permission mirroring is the hardest open-source problem.** Onyx is the only mature open-source platform that inherits source-system ACLs across 40+ connectors . Solr, Elasticsearch, and Meilisearch provide search infrastructure but **no permission awareness**—you must build ACL integration using SpiceDB, OpenFGA, or custom logic. **A search engine that returns unauthorized results is worse than no search.**
- **Amazon Kendra is sunsetting.** AWS announced end-of-support for **December 31, 2026** . Do not start new deployments on Kendra; migrate to OpenSearch or a commercial alternative.
- **Document parsing quality determines answer quality.** RAGFlow's DeepDoc engine handles complex tables, formulas, and scanned documents that simpler parsers fail on . If your knowledge lives in PDFs and legacy documents, parsing is the bottleneck.
- **Zanzibar-inspired permissions are the gold standard.** SpiceDB and OpenFGA model authorization as a graph—supporting hierarchical, relationship-based, and nested permissions that flat ACLs cannot express . Critical for enterprise search that must respect sharing boundaries across Drive folders, Confluence spaces, and Slack channels.
- Self-hosted open-source solutions require proper security hardening, connector credential management, and ongoing maintenance. Indexing is expensive—plan for embedding compute and storage costs.

---

**Made for platform engineers, knowledge managers, and developers building transparent enterprise memory solutions.**  
Let's make Enterprise Search & Internal Memory Layers more open, data-driven, and permission-aware.
