<!--
  This file is destined for the SPECIAL profile repo: github.com/mikkeyboi/mikkeyboi
  (repo name = username . GitHub renders this README on your profile homepage.)
-->

### Hi, I'm Michael 👋

I'm Michael Min Wah Leung, ML Engineer at Microsoft Digital, with a graduate research background in neuroscience. Most interested in **making models smarter** rather than building tooling around them: RL on LLMs, mechanistic interpretability, and sequence models for things that aren't text.

📝 Long-form notes: **[mikkeyboi.github.io](https://mikkeyboi.github.io)**

#### Selected writing

- 🧭 **[One direction is enough to move refusal both ways](https://mikkeyboi.github.io/posts/05-h005-refusal-direction/).** A reproduction of Arditi et al. 2024 on a 1.5B chat model. Ablating one difference-of-means direction dropped held-out harmful refusal from 1.00 to 0.00, and adding it raised harmless refusal from 0.16 to 0.84; a norm-matched random direction of the same size did neither. The control, and a decision rule fixed in code before any run, are the point: they keep a sufficient handle on the behaviour from being read as refusal living on one axis. A first model refused too little at baseline to test, returning a pre-registered null. Includes an interactive view of the measured rates beside a planted-direction toy you can steer.

- 🔍 **[A probe at layer 0 is a lie detector for your experiment](https://mikkeyboi.github.io/posts/04-h001-depth-profile/).** Two linear probes on Gemma 3 1B both reached 1.000 held-out accuracy yet meant opposite things. The finding is the accuracy-by-layer curve, not the number: vocab-disjoint splits and shuffled-label selectivity controls separate a concept the embedding already encodes (flat at ceiling from layer 0) from one the model has to build across an allocation zone (negation-composed sentiment climbing from chance to linearly separable by layer 8).

- 🔬 **[Why SFT learned the words but GRPO learned the rules](https://mikkeyboi.github.io/posts/01-sft-grpo-hvac/).** SFT, GRPO, and DPO for an internal expert model on a proprietary equipment-naming taxonomy. Custom multi-component reward function, conservative LoRA-GRPO (r=4, β=0.2, 0.25 epochs), and measurable failure-mode shifts (95% reduction in false positives versus baseline).

- 🤟 **[From consuming a pretrained model to training my own](https://mikkeyboi.github.io/posts/03-cslt-seq2seq/).** A Transformer Seq2Seq trained from scratch (Keras and Apple MLX) over MediaPipe Holistic landmarks for continuous sign-language decoding, with a hybrid runtime that defers to an isolated-gloss model for short bursts. First place out of 11,000+ submissions in an organisation-wide hackathon.

- 🧠 **[Patient-specific filters as biomarkers](https://mikkeyboi.github.io/posts/02-bci-spatial-filters/).** Per-subject spectral filters (FOOOF + ICA + CSP) for EEG classification of saccade behaviour in Parkinson's research, plus parallel work on intraoperative microelectrode recordings from deep brain structures. The "filter parameters as features" framing connects directly to mechanistic interpretability of language models.

#### Background

- 💼 **Senior Software Engineer, Microsoft Digital.** I build and post-train the models behind a production agentic platform for autonomous building operations. An orchestrator reads an operator's request and hands off to specialised agents for system health, power, air quality, and fault detection, each with the retrieval its own data needs, so the platform reasons over telemetry volumes no single context window could hold by decomposing the work across agents and tools instead of one prompt. One agent is a small model I fine-tuned, SFT then GRPO, to learn a proprietary equipment taxonomy rather than guess at hardware. I also built the observability layer that surfaces why the system makes its cross-agent decisions, the seam that pulled me toward interpretability, and I mentor engineers on LLM integration and deployment.
- 🔗 **Enterprise knowledge-graph analytics, Microsoft Digital.** Earlier I designed and shipped a natural-language analytics system over a petabyte-scale, highly relational estate (real estate, organisations, people, buildings, rooms, IoT) spanning a warehouse and delta lakes. I structured it as a knowledge graph, extracting entities and relationships with language models against typed schemas, then added an auto-metadata layer so agents could reason about each data modality and a hybrid-search vector index, so retrieval moved along the connections in the data instead of guessing where to look: ask about one building and the answer already carries its neighbours, occupancy, size, and lease agency. It retired hand-built per-process dashboards; stakeholders now self-serve any cross-domain view in plain language. I built this before graph-structured retrieval was a familiar pattern.
- 🛡 **Responsible AI Champ, Microsoft Digital.** Adversarial benchmarking and red-teaming for LLMs, internal white papers on Content Safety and RAI methodology, and a SaaS that wrapped impact assessment in automation, CICD, and stress-testing so product teams could ship AI features and iterate on them without compromising safety review.
- 🩺 **Graduate Research Fellow, Ottawa Hospital Research Institute and University of Ottawa Neuroscience.** Real-time decoding of neural activity for Parkinson's research; UnityVR eye-tracking psychophysics platform for intraoperative use; published work in BCI / EEG decoding and chemistry-education clustering.

#### Other work, briefly

The blog posts are the modelling-heavy slice. A throughline across the rest of my work is optimization at scale, in platform design, cloud infrastructure, and parallelization, because the cost and reliability of an enterprise solution usually gets decided long before the model does.

- **Platform / Big Data engineering** — serverless CICD and parallelized warehousing patterns that took meaningful recurring spend off the table; custom Azure ML SDKs for SQL / Parquet / Delta / Cosmos modalities (contributed back to public Azure docs); real-time HVAC telemetry pipelines into Azure Synapse and ADX.
- **Production AI tooling** — vectorizer stack on fine-tuned GPT-4 reducing hallucinations by 99% on M365 product feedback; recommendation + sentiment NLP across hyperscale GPU; multivariate IoT imputer at 0.9 F1 powering thousands of workflows daily.
- **Full-stack** — microservice SaaS on Next.js + Prisma deployable on Azure, including the Responsible AI app and a merchandise warehousing system.
- **Earlier hardware-adjacent work** — Unity3D VR eye-tracking and BCI platforms for neurosurgical use; honourable mention in a Microsoft hackathon for shipping hand-gesture functionality in M365 (the direct precursor to the sign-language project above).

📬 [LinkedIn](https://www.linkedin.com/in/michael-min-wah-leung-114b4960/) · 🌐 [mikkeyboi.github.io](https://mikkeyboi.github.io)
