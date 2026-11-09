<div align="center">

<img src="assets/profile-header.svg" width="100%" alt="From models to useful applications.">

<h1>Hi, I'm Zayne 👋</h1>

<p><strong>AI Application Development</strong><br>
Large Language Models &nbsp; · &nbsp; AI Agents &nbsp; · &nbsp; Multimodal Learning</p>

</div>

## About Me

I'm **Zehao Feng**, an MSc Applied Artificial Intelligence student at the **University of Warwick**, with a software engineering background from Taiyuan University of Technology.

I build **large language model applications and AI agents** by combining domain-specific fine-tuning with backend engineering. My main application areas are **financial analysis** and **multimodal misinformation detection**.

I'm also actively exploring how these technologies can be applied to **energy and power systems, industrial applications, and other sectors**.

## Technical Strengths

- **AI agent engineering** — I turn multi-step analytical tasks into coordinated workflows, combining model-based planning with tool-based computation and managing task state, memory, and recovery throughout execution.
- **Task-specific model adaptation** — I connect instruction-data design, LoRA/QLoRA fine-tuning, and model serving to develop models that produce structured plans and executable outputs for domain applications.
- **RAG & retrieval systems** — I design document-aware retrieval pipelines with hybrid search, rank fusion, and reranking, connecting task-scoped evidence selection with shared caching for responsive, source-grounded applications.
- **Multimodal learning** — I model text–image relationships to guide selective alignment and correction, treating cross-modal inconsistency as an informative signal for misinformation detection.

## Selected Work

### [FinEvoLab](https://github.com/Zayne-Feng/FinEvoLab)

A bilingual **financial analysis application** that connects report Q&A, financial calculations, and cross-company comparisons with traceable evidence. [Live showcase ↗](https://finevolab.lunelu.com/)

- **System design** — QLoRA-trained request planning coordinates hybrid RAG and deterministic financial tools. Source, fiscal-period, and unit validation connect calculations to cited reports; persistent tasks and checkpoints support recovery.
- **Results** — Qwen3-4B-Instruct-2507 fine-tuning improved [**strict planning success from 45.4% to 88.3%**](https://github.com/Zayne-Feng/FinEvoLab/blob/main/project_notes/evaluations/planner_formal_results.json) on 240 test requests. Shared caching reduced [**mean retrieval latency from 91.13 ms to 22.44 ms**](https://github.com/Zayne-Feng/FinEvoLab/blob/main/project_notes/evaluations/retrieval_service_comparison.json) after cache warm-up, with identical retrieved passages.

### [ObsShiftForecast](https://github.com/Zayne-Feng/ObsShiftForecast)

First-author research into how **weather-information availability shapes time-series foundation model performance** in power-load forecasting. **Manuscript submitted to SEGAN.**

- **Forecasting study** — Compared **Chronos-2, TiRex-2, and t0-beta** for forecasts covering the next 24 hours across 15 distribution feeders, with 21,600 paired forecast origins and a separate temporal replication.
- **Core contribution** — Separated the **Oracle-to-Deployable performance gap** from the effect of **information staleness**, contrasting historical weather references with archived forecasts available at the prediction time under 0/24/48/72-hour availability cutoffs.

### [Multimodal Misinformation Detection](https://github.com/Zayne-Feng/ES9U9-Multimodal-Misinformation-Evaluation)

**Mismatch-aware cross-modal learning** for misinformation detection: learning when to align text and image representations and when to preserve their disagreement as a detection signal.

- **Selective alignment** — Learned correctability scores modulate contrastive alignment over frozen MiniLM and CLIP features, while a text–image relation branch guides residual prediction corrections. Correctability-routed alignment increased [**mean fake recall on mismatch cases by 1.23 percentage points**](https://github.com/Zayne-Feng/ES9U9-Multimodal-Misinformation-Evaluation#selected-comparison-results) over uniform alignment across ten seeds.
- **Evidence-guided correction** — Extended the correction policy with an internal retrieval model that confirms candidate prediction changes, connecting text–image relationship modeling with evidence-based decisions about when to correct a prediction.

<details>
<summary>More work in AI and data applications</summary>

- [FinRAG-PEFT](https://github.com/Zayne-Feng/FinRAG-PEFT) — Financial question answering with fine-tuning, retrieval, and executable programs.
- [ETTm-Forecasting](https://github.com/Zayne-Feng/ETTm-Forecasting) — Forecasting models, interpretability, and accuracy–efficiency trade-offs.
- [DiaMetric-CDC](https://github.com/Zayne-Feng/DiaMetric-CDC) — Explainable diabetes-risk prediction.
- [EduGuard-Analytics](https://github.com/Zayne-Feng/EduGuard-Analytics) — Student-outcome prediction and early warning.
- [Market Basket Analysis](https://github.com/Zayne-Feng/Market-Basket-Analysis-System) — Graph-based product associations and recommendations.
- [Suicide Rates Analysis](https://github.com/Zayne-Feng/suicide-rates-analysis-system) — Data pipelines and interactive exploration.

</details>

## Connect

I welcome conversations and collaboration on **large language model applications, AI agents, and multimodal learning**, including their use in **finance, energy and power systems, and industry**.

I'm interested in **research collaboration, open-source development, and building AI applications**. Whether you are exploring a research idea, developing an agent workflow, or bringing a model into an application, I'd be glad to exchange ideas and discuss working together.

**[zayne_feng@163.com](mailto:zayne_feng@163.com)**
