---
permalink: /
title: "Mechanistic Interpretability in Large Language Models"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## 🔍 Research Focus: Understanding the Inner Workings of LLMs

I am a Research Associate at the University of Tübingen, working with [Dr. Thomas Wolfers](https://thomaswolfers.com/) and [Dr. Çağatay Yıldız](https://cagatayyildiz.github.io/) on the mechanistic interpretability of large language models. My research centers on developing novel approaches to understand how these complex systems acquire, represent, and access knowledge.

## 📰 Recent News

<div class="news-box" style="max-height: 420px; overflow-y: auto; padding-right: 8px;">
<ul>
<li><strong>June 2026:</strong> Presenting oral talk and poster (#2032, Wed–Thu) at <a href="https://www.humanbrainmapping.org/OHBM2026/">OHBM 2026</a> Annual Meeting (Bordeaux, France); oral in "Modeling and Analysis of Multimodal Data" session on June 17, 3:45–5:00 PM (Palais 2 l'Atlantique, Room E) on "Transferable and Conditional Norms: Profiling Cortico-Subcortical Individual-level Variation"</li>
<li><strong>June 2026:</strong> Co-authored paper "Lamellar Normative Modelling of the Hippocampus Across the Human Lifespan" submitted to <em>Nature Communications</em></li>
<li><strong>May 2026:</strong> Submitted short paper "<a href="https://openreview.net/forum?id=2A1D7T3zSe">Multiple-Choice Completion: A Format-Sensitive Failure Mode of Cloze-Style LLM Evaluation</a>" to ARR May 2026 (EMNLP track); exposes a format-sensitive failure mode where prompt phrasing alone shifts downstream accuracy by several points</li>
<li><strong>May 2026:</strong> Submitted paper "<a href="https://openreview.net/forum?id=omkNoIbFh7">Where You Steer Depends on What You Steer: Component Selection Across Steering Axes in LLMs</a>" to Mech Interp Workshop at ICML 2026; establishes that component choice is axis-dependent: MLP-output steering dominates for factual axes, attention for behavioral axes</li>
<li><strong>March 2026:</strong> Abstract accepted for both Poster and Oral presentation at <a href="https://www.humanbrainmapping.org/OHBM2026/">OHBM 2026</a> (Bordeaux, France, June 14–18); oral talk in the "Modeling and Analysis of Multimodal Data" session on "Transferable and Conditional Norms: Profiling Cortico-Subcortical Individual-level Variation"</li>
<li><strong>March 2026:</strong> Co-authored paper "<a href="https://doi.org/10.64898/2026.03.06.710057">A normative reference for large-scale human brain dynamics across the lifespan</a>" submitted to <em>Nature Neuroscience</em></li>
<li><strong>February 2026:</strong> Co-led two-day hands-on workshop on normative modeling at Friedrich-Schiller-University Jena, presenting custom-developed GAMLSS Python package (<a href="https://nbviewer.org/github/nsharma3150/nsharma3150.github.io/blob/master/files/Normative_Modeling_Tutorial_8th_Feb_2026_Jena.ipynb">tutorial notebook</a>)</li>
<li><strong>January 2026:</strong> Extended benchmarking work (<a href="https://arxiv.org/abs/2506.07658">preprint</a>) submitted to TMLR</li>
<li><strong>December 2025:</strong> Abstract submitted to OHBM 2026 on normative modeling for neuroimaging</li>
<li><strong>August 2025:</strong> Started supervising PhD student Jijia Xing on extending the benchmarking framework to medical and mental health domains</li>
<li><strong>June 2025:</strong> New preprint released: "<a href="https://arxiv.org/abs/2506.07658">Beyond Benchmarks: A Novel Framework for Domain-Specific LLM Evaluation and Knowledge Mapping</a>" on arXiv</li>
<li><strong>April 2025:</strong> Paper "<a href="https://openreview.net/forum?id=aKjJoEVKgO">Investigating Continual Pretraining in Large Language Models</a>" accepted at TMLR</li>
<li><strong>April 2025:</strong> Started Research Associate position at University of Tübingen under <a href="https://thomaswolfers.com/">Dr. Thomas Wolfers</a> and <a href="https://cagatayyildiz.github.io/">Dr. Çağatay Yıldız</a></li>
<li><strong>March 2025:</strong> Received Master's degree in Neural Information Processing (grade: 1.17), University of Tübingen; thesis: "Mechanistic Understanding of Factual Knowledge in LLMs" at <a href="https://bethgelab.org/">Bethge Lab</a></li>
<li><strong>2024:</strong> Awarded Deutschlandstipendium scholarship for outstanding academic achievements</li>
<li><strong>November 2023:</strong> Best Presentation Award for essay rotation "Large Language Models and Psychotherapy: Bridging the Gap with Mechanistic Interpretability" from Graduate Training Centre of Neuroscience, Tübingen</li>
<li><strong>2022:</strong> Graduated with Department Gold Medal and Best Bachelor Thesis Award, Physics Department, Indian Institute of Technology Roorkee</li>
</ul>
</div>

## 🧪 Current Research

My work focuses on two complementary areas:

**Steering Vectors for Knowledge Access**: Developing activation engineering techniques using tuned lens, logit lens, causal tracing, and activation patching to localize domain-specific knowledge representations across model layers. Recent work (submitted to Mech Interp Workshop, ICML 2026) systematically compares residual stream, MLP output, and attention output components across all layers of three 7–9B models, finding that MLP-output steering dominates for factual axes (45% mean rank improvement) while attention outperforms MLP for behavioral axes such as toxicity—establishing component choice as a meaningful, axis-dependent design decision.

**Domain-Specific LLM Evaluation**: Created a deterministic pipeline for contamination-free benchmark generation from raw corpora, tested on large-scale datasets (arXiv: 1.56M documents, M2D2: 8.5B tokens). Recent work (submitted to ARR May 2026/EMNLP) exposes a format-sensitive failure mode of cloze-style evaluation—MCQ completion—where prompt phrasing alone shifts downstream accuracy by several points and the effect is strongest on medical questions and newer models. Currently extending this framework to medical and mental health domains with focus on safety-critical evaluation and data contamination effects.

## 💡 Research Philosophy

Following Richard Feynman's principle "What I cannot create, I do not understand," my research aims to reverse-engineer the internal mechanisms of language models. By understanding how these systems process and represent knowledge, we can build more reliable, controllable, and interpretable AI systems.

## 🔬 Key Contributions

- **Domain-Specific Evaluation**: Created deterministic pipelines for contamination-free LLM evaluation using large-scale datasets (arXiv: 1.56M documents, M2D2: 8.5B tokens); identified MCQ completion as a format-sensitive failure mode that shifts accuracy by several points depending on prompt phrasing alone
- **Continual Learning**: Investigated how model size affects knowledge acquisition and retention during continual pretraining across diverse domains (TMLR, 55+ citations)
- **Activation Engineering**: Established that optimal steering component is axis-dependent—MLP-output achieves 45% mean rank improvement on factual axes with global token injection; attention dominates for behavioral axes such as toxicity (submitted, ICML 2026 Mech Interp Workshop)
- **Layer-wise Knowledge Representation**: Revealed that initial-to-mid layers are primarily responsible for attribute extraction while later layers focus on next token prediction, with implications for targeted fine-tuning and catastrophic forgetting mitigation

## 🎯 Impact & Applications

This research enables practical breakthroughs in:
- **Model Efficiency**: Targeted knowledge editing without full retraining; early stopping strategies during model training
- **Safety & Control**: Direct model steering through activation engineering  
- **Robust Evaluation**: Better understanding of what models truly know vs. memorize
- **Knowledge Transfer**: Optimizing how models adapt to new domains while preserving critical knowledge

## 🤝 Opportunities & Collaboration

I am actively seeking collaborations and am open to supervising research projects in mechanistic interpretability. 

**Research Collaboration**: If you're working on related topics in mechanistic interpretability, circuit discovery, activation engineering, or knowledge representation in LLMs, I'd be delighted to discuss potential synergies and collaborative opportunities.

**Student Supervision**: I welcome Bachelor's and Master's students for theses, rotations, and internships on topics including:
- Knowledge localization and steering vectors in language models
- Circuit discovery and causal interventions
- Domain adaptation and continual learning mechanisms
- Activation engineering for model control
- Safety-critical evaluation in specialized domains

Please reach out via email at [nitinsharma3150@gmail.com](mailto:nitinsharma3150@gmail.com) to discuss how we might work together.

---

*Research conducted at the [Bethge Lab](https://bethgelab.org/), [Vernade Lab](https://www.cvernade.com/), and in collaboration with the [Mental Health Mapping Lab](https://mhm-lab.github.io/), University of Tübingen.*
