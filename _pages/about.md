---
permalink: /
title: "Exploring the Inner Workings of Large Language Models"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="announcement-box">
<p>🎓 <strong>Open to Opportunities:</strong> I am currently seeking PhD positions and research internships in the field of Machine Learning and AI, particularly focusing on LLM interpretability and mechanistic understanding.</p>
</div>

# 🔍 Current Research: Mechanistic Interpretability in LLMs

As a master's thesis student at [Bethge Lab](https://bethgelab.org/), working under the guidance of [Prof. Matthias Bethge](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/physik/institute/institut-fuer-theoretische-physik/arbeitsgruppen/ag-bethge/) and [Dr. Cagatay Yildiz](https://cagatayyildiz.github.io/), I'm delving deep into the fascinating world of large language models. My research focuses on developing novel approaches to quantify and track knowledge acquisition in these complex systems through mechanistic interpretability.

## 🧪 Current Research Directions

Our research extends [Geva et al.'s (2023)](https://arxiv.org/abs/2304.14767) foundational work on factual associations in auto-regressive models, developing more sophisticated measurement techniques. A critical insight emerged from [Öncel et al.'s (2024)](https://arxiv.org/abs/2410.05581) findings that traditional perplexity metrics can be deceptive – high perplexity scores don't always indicate true domain understanding.

I'm currently advancing research along two primary axes:

1. **Knowledge Measurement Pipeline**: Developing transferable methodologies for measuring domain-specific knowledge across model layers, building on ["Dissecting Recall of Factual Associations in Auto-Regressive Language Models"](https://arxiv.org/abs/2304.14767).

2. **Domain-Specific Pre-training**: Investigating how specialized pre-training shapes model capabilities, extending insights from ["Investigating Continual Pretraining in Large Language Models"](https://arxiv.org/abs/2402.17400).

A key innovation in our approach is the application of activation engineering through steering vectors – essentially creating interpretable maps of knowledge representation across model layers. This builds on [Arditi et al.'s (2024)](https://arxiv.org/abs/2406.11717) demonstration that LLMs encode features as linear directions in their activation space, complemented by [Merullo et al.'s (2024)](https://arxiv.org/abs/2305.16130) work on vector arithmetic in language models.

## 💡 Why Mechanistic Interpretability?

Richard Feynman's principle, "What I cannot create, I do not understand," perfectly encapsulates the mission of mechanistic interpretability. The field has achieved remarkable breakthroughs in demystifying neural networks, from [Elhage et al.'s (2021)](https://transformer-circuits.pub/2021/framework/index.html) mathematical frameworks for transformer circuits to [Elhage et al.'s (2022)](https://transformer-circuits.pub/2022/toy_model/index.html) understanding of superposition phenomena. Recent advances in automated circuit discovery [(Conmy et al., 2023)](https://arxiv.org/abs/2304.14997) and interpretable circuits in GPT-2 [(Wang et al., 2022)](https://arxiv.org/abs/2211.00593) demonstrate that systematic reverse engineering of these complex systems is not just possible – it's revolutionizing our understanding.

## 🔬 Practical Applications

These theoretical advances have enabled significant practical breakthroughs:

- Enhanced model efficiency through targeted knowledge editing [(Meng et al., 2023)](https://proceedings.neurips.cc/paper_files/paper/2022/hash/6f1d43d5a82a37e89b0665b33bf3a182-Abstract-Conference.html) [(Dai et al., 2021)](https://arxiv.org/abs/2104.08696)
- Enable direct model control through activation engineering and steering vectors, eliminating the need for traditional fine-tuning approaches [(Turner et al., 2024)](https://arxiv.org/abs/2308.10248) [(Hendel et al., 2023)](https://arxiv.org/abs/2310.15916) [(Ilharco et al., 2022)](https://arxiv.org/abs/2212.04089)
- Implement stronger safety constraints by understanding how outputs can be steered and regulated [(Arditi et al., 2024)](https://arxiv.org/pdf/2406.11717) [(Bereska et al., 2024)](https://arxiv.org/abs/2404.14082)
- Enhance model performance through targeted modifications of internal representations, as demonstrated by work on singular value decomposition and rank reductions [(Chen et al., 2024)](https://arxiv.org/abs/2305.19798) [(Sharma et al., 2023)](https://arxiv.org/abs/2312.13558)
- Develop more robust evaluation methods by understanding how knowledge is stored and accessed [(Geva et al., 2020)](https://arxiv.org/abs/2012.14913) [(Dar et al., 2022)](https://arxiv.org/abs/2209.02535)

## 🎯 Research Focus

My research explores the crucial intersection of knowledge representation and model behavior. By combining activation engineering techniques with causal intervention methods, I investigate how models process and adapt domain-specific knowledge while maintaining their core capabilities. This work is particularly inspired by knowledge localization techniques ([Meng et al., 2023](https://proceedings.neurips.cc/paper_files/paper/2022/hash/6f1d43d5a82a37e89b0665b33bf3a182-Abstract-Conference.html)), factual association tracking ([Geva et al., 2023](https://arxiv.org/abs/2304.14767)), and advances in model steering ([Arditi et al., 2024](https://arxiv.org/pdf/2406.11717)).

The most compelling aspect of this work is its potential to transform theoretical insights into practical applications, advancing both our understanding and our ability to create more reliable, controllable AI systems. Apart from the papers mentioned above, I draw significant inspiration from several groundbreaking works in the field, including:

- [A Mathematical Framework for Transformer Circuits](https://transformer-circuits.pub/2021/framework/index.html) (Elhage et al., 2021)
- [Editing Factual Knowledge in Language Models](https://arxiv.org/abs/2104.08164) (Cao et al., 2021)
- [Language Agents Meet Causality -- Bridging LLMs and Causal World Models](https://arxiv.org/abs/2410.19923) (Gkountouras et al., 2024)
- [Talking Heads: Understanding Inter-layer Communication in Transformer Language Models](https://arxiv.org/abs/2406.09519) (Merullo et al., 2024)
- [CoSy: Evaluating Textual Explanations of Neurons](https://arxiv.org/abs/2405.20331) (Kopf et al., 2024)
- [Mechanistic Interpretability for AI Safety -- A Review](https://arxiv.org/abs/2404.14082) (Bereska et al., 2024)
