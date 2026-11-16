# MP Aghababa, PhD — Applied AI, Agentic Systems & ML Engineering

**Public technical portfolio** | [LinkedIn](https://www.linkedin.com/in/mpaghababa/) | [GitHub profile](https://github.com/MPAghababa)

I build and lead engineering teams that move AI from research and prototypes into useful software systems. My work spans **agentic AI, LLM/RAG systems, model evaluation and security, recommendation engines, forecasting, optimization, and applied deep learning**. I have led AI and engineering functions at Seismos, Chubb, and Walmart Global Tech, following earlier industry-sponsored R&D and academic leadership.

This repository contains **selected public research and engineering demonstrations**. It is not the source repository for the commercial systems I have delivered; those systems, their code, and their datasets belong to the respective organizations.

## Featured technical projects

### 1. RAG security: canary queries, retrieval drift, and poisoning detection

**[Open notebook](RAG/RAG_Poisoning_Final.ipynb)**

A hands-on RAG security workflow that simulates retrieval poisoning and illustrates controls beyond answer-quality scoring:

- Build a retrieval pipeline and establish a baseline using canary queries.
- Record retrieved evidence and identify retrieval/answer drift after a knowledge-base change.
- Trace suspicious results to contributing chunks, quarantine content, and evaluate behavior after quarantine.

**Focus:** RAG evaluation, retrieval traceability, detection, security monitoring, and controlled remediation.

### 2. Knowledge-graph RAG and conversational recommendation

**[Open notebook](graph_rag/querying_graph_db_with_Langchain_final_posted.ipynb)**

A fashion recommendation and question-answering demonstration combining **Neo4j**, knowledge-graph relationships, **LangChain**, and LLM-assisted querying. Shows how structured relationships can support recommendation and natural-language retrieval beyond conventional vector-only search.

**Focus:** graph data modeling, graph querying, retrieval orchestration, and explainable recommendation workflows.

### 3. Agentic dynamic pricing for short-term rentals

**[Open notebook](airbnb/AirbnbPricing_final.ipynb)**

A multi-component pricing research prototype integrating semantic representations, supervised demand prediction, a reinforcement-learning pricing agent, and LLM/tool orchestration. The notebook explores **ModernBERT-style semantic modeling, XGBoost/neural-network ensembles, reinforcement learning**, and **LangSmith** tracing.

**Focus:** business optimization, agent orchestration, model combinations, and observability.

### 4. Hidden-state steering of language models for finance audiences

**[Open notebook](<Transformer surgery/finance_focused_LLM_steering.ipynb>)** | **[Research write-up](<Transformer surgery/finance_focused_LLM_steering.pdf>)**

An experiment on intervening in transformer hidden representations to adjust how a model explains finance concepts for different audiences. Includes evaluation-oriented comparisons of generated responses and steering behavior.

**Focus:** transformer internals, representation steering, empirical evaluation, and responsible interpretation of experiments.

### 5. Agentic real-estate recommendation and explanation

**[Open notebook](real_estate/RealEstateFinal.ipynb)**

A recommendation pipeline integrating text generation, vector retrieval, and **particle swarm optimization** for query refinement, with explanations of matched properties.

**Focus:** workflow composition, optimization-assisted retrieval, and user-facing recommendations.

### 6. Two-tower recommendation using graph learning and reinforcement learning

**[Open notebook](two_tower/Two_Tower_Final.ipynb)**

A two-tower recommendation architecture exploring **graph neural networks, language-model-derived representations, and reinforcement-learning feedback** on business recommendation data.

**Focus:** recommendation architecture, graph embeddings, training workflows, and ranking.

### 7. AI adoption and operating-model roadmaps

**[Browse roadmaps](<AI Roadmap/>)**

Public-facing roadmaps covering AI adoption considerations for **finance, HR, management, marketing, and supply-chain** functions.

**Focus:** translating AI capabilities into practical business and organizational priorities.

## Enterprise engineering experience — high-level case studies

My professional work includes systems that cannot be published as source code. Selected outcomes from my professional experience:

- **Seismos — AI platforms and engineering enablement:** Built the company's AI, Data, and AI Product Engineering function; led six product/platform teams in a larger cross-functional organization. Delivered a governed customer-facing agentic AI platform serving **100+ tenants** and a private AI-assisted engineering system associated with **60%+ reductions in engineering work time for evaluated activities**.
- **Chubb — applied insurance AI:** Led globally distributed Applied AI teams developing underwriting classification, quote prioritization, decision systems, and enterprise AI knowledge management, with measured improvements in classification/decision workflows.
- **Walmart Global Tech — large-scale forecasting:** Led multi-team ML/data engineering work for retail forecasting and optimization, supporting **2M+ actively forecasted products** within a broader product catalog of **50M+**, with production outcomes in forecast accuracy and stockout reduction.

The examples above are **architecture/outcome summaries only**, not public reproductions of employer code, proprietary data, training material, infrastructure, or customer information.

## Research and leadership

- **PhD in Electrical Engineering**; more than **120 research publications**, **5,000 citations**, and an **h-index above 38**.
- Former **tenured Full Professor and R&D Director**, leading a research organization of more than 50 across nine units.
- Editorial involvement with the *International Journal of Machine Learning and Cybernetics* and other research journals.

Research informs the engineering work here, but the portfolio is intentionally focused on technical implementation and the connection between models, systems, and business problems.

## Running the notebooks

1. Open the linked notebook in GitHub and review its introduction, environment setup, datasets, and expected dependencies.
2. Run it in a suitable notebook environment (for example, Jupyter or Google Colab) with an appropriate Python version and the required packages.
3. Some demonstrations require additional model downloads, GPU resources, external services, or API credentials. Supply credentials **through environment variables or a secure secrets manager**, never in a committed notebook.
4. Public notebooks are **research/technical demonstrations**, not a packaged production deployment. Dependency versions and external APIs may have changed since publication.

**Security and data note:** No company source code, internal datasets, customer records, private prompts, or proprietary model artifacts should be added to this repository. Before publishing new notebooks, clear outputs that might contain private data or access tokens and verify dataset redistribution rights.

---

**Contact:** [LinkedIn](https://www.linkedin.com/in/mpaghababa/) | [GitHub](https://github.com/MPAghababa)
