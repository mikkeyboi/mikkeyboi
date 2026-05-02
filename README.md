<!--
  This file is destined for the SPECIAL profile repo: github.com/mikkeyboi/mikkeyboi
  (repo name = username . GitHub renders this README on your profile homepage.)
-->

### Hi, I'm Michael 👋

I'm Michael Min Wah Leung. ML engineer at Microsoft working on LLM post-training, with a graduate research background in neuroscience. Most interested in **making models smarter** rather than building tooling around them: RL on LLMs, mechanistic interpretability, and sequence models for things that aren't text.

📝 Long-form notes: **[mikkeyboi.github.io](https://mikkeyboi.github.io)**

#### What I'm working on

- 🔬 **Post-training in production.** SFT, GRPO, and DPO for an internal expert model on a proprietary equipment-naming taxonomy. Custom multi-component reward function, conservative LoRA-GRPO (r=4, β=0.2, 0.25 epochs), and measurable failure-mode shifts. *Writeup: [Why SFT learned the words but GRPO learned the rules](https://mikkeyboi.github.io/posts/01-sft-grpo-hvac/).*

- 🤟 **Continuous sign-language modelling.** A Transformer Seq2Seq trained from scratch (Keras and Apple MLX) over MediaPipe Holistic landmarks, with a hybrid runtime that defers to an isolated-gloss model for short bursts. The interesting work was the *transition* from consuming a pretrained model to designing, training, and integrating a new one. That same see-the-ceiling-then-train-something-better loop is what I think most modelling work eventually becomes. *Writeup: [From consuming a pretrained model to training my own](https://mikkeyboi.github.io/posts/03-cslt-seq2seq/).*

- 🧠 **From neural decoding to neural networks.** Graduate thesis built per-subject spectral filters (FOOOF + ICA + CSP) for EEG classification, plus parallel work on intraoperative microelectrode recordings from deep brain structures. The "filter parameters as features" framing is the same intuition I now apply to mechanistic interpretability of language models, and the bridge from classical signal-decomposition to sparse autoencoders is closer than the literature usually treats it. *Writeup: [Patient-specific filters as biomarkers](https://mikkeyboi.github.io/posts/02-bci-spatial-filters/).*

#### Background

- 🩺 Graduate research in Neuroscience, University of Ottawa. ML modelling for EEG and intraoperative microelectrode recordings.
- 💼 Senior Software Engineer, Microsoft. AI frameworks, Responsible AI tooling, and post-training for internal expert models.
- 📚 Earlier publications in BCI / EEG decoding.

📬 [LinkedIn](https://www.linkedin.com/in/michael-min-wah-leung-114b4960/) · 🌐 [mikkeyboi.github.io](https://mikkeyboi.github.io)
