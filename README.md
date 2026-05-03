<!--
  This file is destined for the SPECIAL profile repo: github.com/mikkeyboi/mikkeyboi
  (repo name = username . GitHub renders this README on your profile homepage.)
-->

### Hi, I'm Michael 👋

I'm Michael Min Wah Leung, ML Engineer at Microsoft Digital, with a graduate research background in neuroscience. Most interested in **making models smarter** rather than building tooling around them: RL on LLMs, mechanistic interpretability, and sequence models for things that aren't text.

📝 Long-form notes: **[mikkeyboi.github.io](https://mikkeyboi.github.io)**

#### Selected writing

- 🔬 **[Why SFT learned the words but GRPO learned the rules](https://mikkeyboi.github.io/posts/01-sft-grpo-hvac/).** SFT, GRPO, and DPO for an internal expert model on a proprietary equipment-naming taxonomy. Custom multi-component reward function, conservative LoRA-GRPO (r=4, β=0.2, 0.25 epochs), and measurable failure-mode shifts (95% reduction in false positives versus baseline).

- 🤟 **[From consuming a pretrained model to training my own](https://mikkeyboi.github.io/posts/03-cslt-seq2seq/).** A Transformer Seq2Seq trained from scratch (Keras and Apple MLX) over MediaPipe Holistic landmarks for continuous sign-language decoding, with a hybrid runtime that defers to an isolated-gloss model for short bursts. First place out of 11,000+ submissions in an organisation-wide hackathon.

- 🧠 **[Patient-specific filters as biomarkers](https://mikkeyboi.github.io/posts/02-bci-spatial-filters/).** Per-subject spectral filters (FOOOF + ICA + CSP) for EEG classification of saccade behaviour in Parkinson's research, plus parallel work on intraoperative microelectrode recordings from deep brain structures. The "filter parameters as features" framing connects directly to mechanistic interpretability of language models.

#### Background

- 💼 **Senior Software Engineer, Microsoft Digital.** Real-time fault-detection AI platform for HVAC, post-trained expert SLMs, mentoring engineers on LLM integration and deployment.
- 🛡 **Responsible AI Champ, Microsoft Digital.** Adversarial benchmarking and red-teaming for LLMs, internal white papers on Content Safety and RAI methodology, and a SaaS that wrapped impact assessment in automation, CICD, and stress-testing so product teams could ship AI features and iterate on them without compromising safety review.
- 🩺 **Graduate Research Fellow, Ottawa Hospital Research Institute and University of Ottawa Neuroscience.** Real-time decoding of neural activity for Parkinson's research; UnityVR eye-tracking psychophysics platform for intraoperative use; published work in BCI / EEG decoding and chemistry-education clustering.

#### Other work, briefly

The blog posts are the modelling-heavy slice. A throughline across the rest of my work is optimization at scale, in platform design, cloud infrastructure, and parallelization, because the cost and reliability of an enterprise solution usually gets decided long before the model does.

- **Platform / Big Data engineering** — serverless CICD and parallelized warehousing patterns that took meaningful recurring spend off the table; custom Azure ML SDKs for SQL / Parquet / Delta / Cosmos modalities (contributed back to public Azure docs); real-time HVAC telemetry pipelines into Azure Synapse and ADX.
- **Production AI tooling** — vectorizer stack on fine-tuned GPT-4 reducing hallucinations by 99% on M365 product feedback; recommendation + sentiment NLP across hyperscale GPU; multivariate IoT imputer at 0.9 F1 powering thousands of workflows daily.
- **Full-stack** — microservice SaaS on Next.js + Prisma deployable on Azure, including the Responsible AI app and a merchandise warehousing system.
- **Earlier hardware-adjacent work** — Unity3D VR eye-tracking and BCI platforms for neurosurgical use; honourable mention in a Microsoft hackathon for shipping hand-gesture functionality in M365 (the direct precursor to the sign-language project above).

📬 [LinkedIn](https://www.linkedin.com/in/michael-min-wah-leung-114b4960/) · 🌐 [mikkeyboi.github.io](https://mikkeyboi.github.io)
