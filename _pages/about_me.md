---
layout: archive
title: "About Me"
permalink: /about_me/
author_profile: true
---

## 🔍 Research Journey

My journey into understanding complex systems began at Indian Institute of Technology Roorkee, where I completed my Bachelor's in Engineering Physics, graduating with the Department Gold Medal (9.57/10) and Best Thesis Award in 2023. What started as curiosity about signal processing and EEG-based epilepsy detection in Dr. R.S. Anand's lab evolved into a deeper fascination with neural systems and their computational understanding.

I completed my Master's in Neural Information Processing at the University of Tübingen (March 2025, grade: 1.17/4.0), supported by the Deutschlandstipendium scholarship. My thesis, "Beyond Benchmarks: A Novel Framework for Domain-Specific LLM Evaluation and Knowledge Mapping," under [Prof. Matthias Bethge](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/physik/institute/institut-fuer-theoretische-physik/arbeitsgruppen/ag-bethge/) and [Dr. Çağatay Yıldız](https://cagatayyildiz.github.io/) at the [Bethge Lab](https://bethgelab.org/), developed a deterministic pipeline for contamination-free LLM evaluation tested on large-scale datasets (arXiv: 1.56M documents, M2D2: 8.5B tokens). This work has been [released as a preprint](https://arxiv.org/abs/2506.07658), with an extended version including deeper mechanistic analysis of knowledge representation during domain adaptation currently under review at TMLR.

During my studies, I explored diverse aspects of AI interpretability through research rotations and collaborations. My essay rotation on "Large Language Models and Psychotherapy: Bridging the Gap with Mechanistic Interpretability" under Dr. Thomas Wolfers earned the Best Presentation Award from the Graduate Training Centre of Neuroscience. A lab rotation at the [Dayan lab](https://www.kyb.tuebingen.mpg.de/computational-neuroscience) (MPI for Biological Cybernetics) under [Dr. Sara Ershadmanesh](https://www.kyb.tuebingen.mpg.de/person/106573/2549) on metacognitive abilities in reversal learning deepened my understanding of how both biological and artificial systems adapt to changing environments.

Throughout my Master's, I contributed to collaborative research at the [Mental Health Mapping Lab](https://mhm-lab.github.io/) under [Dr. Thomas Wolfers](https://thomaswolfers.github.io/) and with [Dr. Çağatay Yıldız](https://cagatayyildiz.github.io/). I co-first authored work on [postoperative delirium prediction](https://aging.jmir.org/2025/1/e67958/) (published in JMIR Aging), emphasizing model interpretability through SHAP values to ensure clinical relevance. I also contributed to projects on [continual pretraining in LLMs](https://arxiv.org/abs/2402.17400) (published in TMLR, 55+ citations) and [cerebellar normative features for predicting mental illness](https://www.bpsgos.org/article/S2667-1743(25)00095-3/fulltext) (published in Biological Psychiatry: Global Open Science). I am a co-author on "<a href="https://doi.org/10.64898/2026.03.06.710057">A normative reference for large-scale human brain dynamics across the lifespan</a>," submitted to *Nature Neuroscience*, and most recently on "Lamellar Normative Modelling of the Hippocampus Across the Human Lifespan," submitted to *Nature Communications* (June 2026). These experiences highlighted the crucial role of interpretability in building trustworthy AI systems for high-stakes applications.

## 🧪 What Drives My Research

Since April 2025, I have been working as a Research Associate at the University of Tübingen under [Dr. Thomas Wolfers](https://thomaswolfers.com/) and [Dr. Çağatay Yıldız](https://cagatayyildiz.github.io/), pursuing a question that has fascinated me since my Master's thesis: **How do language models internally organize and access knowledge?**

My work bridges two complementary perspectives on this question. On one side, I'm developing methods to systematically measure and evaluate what models know—moving beyond surface-level metrics to understand genuine domain expertise. On the other, I'm investigating the internal mechanisms that make this knowledge accessible, exploring whether we can directly steer model behavior by manipulating their internal representations rather than through traditional fine-tuning.

What excites me most is discovering that knowledge in these models isn't randomly distributed—it emerges in structured, interpretable patterns across layers. By understanding these patterns, we can build models that are not just powerful, but controllable and trustworthy. This work spans from theoretical investigations of how knowledge evolves during training to practical applications in safety-critical domains like healthcare.

Recent submissions capture both directions concretely. Work submitted to the Mech Interp Workshop at ICML 2026 ([preprint](https://openreview.net/forum?id=omkNoIbFh7)) establishes that the choice of internal component for activation steering is axis-dependent: MLP-output steering achieves a 45% mean rank improvement on factual axes while attention output dominates for behavioral axes such as toxicity, with global token injection critical for realizing the MLP advantage. Complementary work submitted to ARR May 2026 (EMNLP track, [preprint](https://openreview.net/forum?id=2A1D7T3zSe)) identifies MCQ completion as a format-sensitive failure mode of cloze-style evaluation, where prompt phrasing alone shifts downstream accuracy by several points—with the effect strongest on medical questions and in newer models.

Parallel to this, I am presenting at [OHBM 2026](https://www.humanbrainmapping.org/OHBM2026/) (Bordeaux, June 14–18) with both a poster (#2032, Wed–Thu) and an oral talk in the "Modeling and Analysis of Multimodal Data" session (June 17, 3:45–5:00 PM, Palais 2 l'Atlantique) on the GAMLSS-based normative modeling work, and supervising PhD student Jijia Xing on extending evaluation frameworks to medical domains where reliability is paramount. An extended version of the benchmarking work ([preprint](https://arxiv.org/abs/2506.07658)) is currently under review at TMLR.

**Research Philosophy**: Following Richard Feynman's principle "What I cannot create, I do not understand," my work aims to reverse-engineer the internal mechanisms of language models. By understanding how these systems process and represent knowledge, we can build more reliable, controllable, and interpretable AI systems that truly serve human needs.

## 👨‍🏫 Teaching & Mentoring

I believe in giving back to the academic community through teaching and mentorship. Most recently (February 2026), I co-led a two-day intensive hands-on workshop on normative modeling at Friedrich-Schiller-University Jena as part of the "Parsing Individual Differences in Brain Disorders" course. I presented my custom-developed GAMLSS Python package for neuroimaging, teaching psychology students data simulation, model fitting, visualization, transfer functions, and real-world neuroimaging data analysis ([tutorial notebook](https://nbviewer.org/github/nsharma3150/nsharma3150.github.io/blob/master/files/Normative_Modeling_Tutorial_8th_Feb_2026_Jena.ipynb)).

Previously, I served as a Teaching Assistant for the Neuromatch Academy's Deep Learning Course (2024), where I guided international students through complex concepts in an intensive three-week program. My teaching experience also includes mentoring first-year students at IIT Roorkee and leading programming tutorials in the Academic Reinforcement Program.

**Current Supervision**: Since August 2025, I have been supervising PhD student Jijia Xing on extending the benchmarking framework to medical and mental health domains, focusing on safety-critical evaluation and data contamination effects across newer model architectures. Previously, I co-supervised a master's student on ML applications in nerve disease diagnostics (October 2024 - January 2025).

I am always happy to discuss potential supervision opportunities for Bachelor's and Master's theses, rotations, or internships on topics in mechanistic interpretability.

## 🌱 Beyond Research

When I'm not delving into neural networks, you'll find me on the beach volleyball court or training for long-distance runs—I've participated in 100km marathons at university! I am also passionate about community service, having led initiatives like 'Daan Petika' during my time as an Executive at NSS IIT Roorkee, organizing blood donation camps and environmental cleanup drives. I believe in maintaining a balanced life that combines intellectual pursuits with physical activity and giving back to the community.

## 🤝 Let's Connect

I am passionate about advancing the field of interpretable AI and am always excited to discuss research, potential collaborations, or the fascinating world of mechanistic interpretability. Whether you're interested in knowledge representation in LLMs, activation engineering, circuit discovery, or the intersection of AI and neuroscience, I would be delighted to connect.

If my work interests you—whether for collaboration, supervision opportunities, or simply to discuss ideas—feel free to reach out at [nitinsharma3150@gmail.com](mailto:nitinsharma3150@gmail.com). I'm also always up for a chat about volleyball and bouldering!

Let's explore how we might work together to push the boundaries of what we understand about these remarkable AI systems!
