---
permalink: /
title: "Exploring the Inner Workings of Large Language Models"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# 🔍 Mechanistic Interpretability in Large Language Models

I am a Research Assistant at the University of Tübingen, working under [Dr. Thomas Wolfers](https://thomaswolfers.com/) and [Dr. Çağatay Yıldız](https://cagatayyildiz.github.io/) at the intersection of machine learning and neuroscience. Having recently completed my Master's thesis under [Prof. Matthias Bethge](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/physik/institute/institut-fuer-theoretische-physik/arbeitsgruppen/ag-bethge/) at the [Bethge Lab](https://bethgelab.org/), I am now advancing research on mechanistic interpretability in large language models through two complementary projects focused on understanding how these complex systems acquire, represent, and access knowledge.

## 🧪 Current Research Directions

My research has evolved from foundational work on factual associations in auto-regressive models, developing sophisticated measurement techniques that address critical limitations in current evaluation methods. Building on insights from [Öncel et al.'s (2024)](https://arxiv.org/abs/2410.05581) findings that traditional perplexity metrics can be deceptive – where lower perplexity scores don't always indicate true domain understanding – my work focuses on developing mechanistic approaches to understand and control knowledge representation in LLMs.

I'm currently advancing research along three primary axes:

### 1. **Steering Vectors for Knowledge Access**
Developing activation engineering techniques to access latent knowledge in language models without pre-training modifications. This work analyzes activation patterns across model layers to demonstrate how domain knowledge emerges as targetable directions for systematic model control. Our approach builds on [Arditi et al.'s (2024)](https://arxiv.org/abs/2406.11717) demonstration that LLMs encode features as linear directions in their activation space, enabling direct manipulation of model behavior and knowledge access.

### 2. **Domain-Specific Evaluation Frameworks**
Creating contamination-free evaluation pipelines for measuring domain-specific knowledge in LLMs. Building on my Master's thesis work, we developed a comprehensive framework published in ["Beyond Benchmarks: A Novel Framework for Domain-Specific LLM Evaluation and Knowledge Mapping"](https://arxiv.org/abs/2506.07658). This deterministic pipeline creates domain-specific benchmarks from raw corpora, enabling reliable assessment of model capabilities using large-scale datasets including the arXiv dataset (1.56M documents) and M2D2 (8.5B tokens), revealing rapid domain adaptation patterns and layer-wise knowledge representation dynamics.

### 3. **Mechanistic Understanding of Knowledge Change**
Investigating the internal mechanisms of how knowledge is stored, modified, and accessed within LLMs during learning and adaptation. This work combines causal intervention methods with activation analysis to understand how models process and adapt domain-specific knowledge while maintaining their core capabilities. Our approach extends insights from our TMLR-accepted paper ["Investigating Continual Pretraining in Large Language Models"](https://arxiv.org/abs/2402.17400), which revealed how model size affects knowledge acquisition, retention patterns, and the dynamics of knowledge transfer across different domains.

## 💡 Why Mechanistic Interpretability?

Richard Feynman's principle, "What I cannot create, I do not understand," perfectly encapsulates the mission of mechanistic interpretability. The field has achieved remarkable breakthroughs in demystifying neural networks, from [Elhage et al.'s (2021)](https://transformer-circuits.pub/2021/framework/index.html) mathematical frameworks for transformer circuits to [Elhage et al.'s (2022)](https://transformer-circuits.pub/2022/toy_model/index.html) understanding of superposition phenomena. Recent advances in automated circuit discovery [(Conmy et al., 2023)](https://arxiv.org/abs/2304.14997) and interpretable circuits in GPT-2 [(Wang et al., 2022)](https://arxiv.org/abs/2211.00593) demonstrate that systematic reverse engineering of these complex systems is not just possible – it's revolutionizing our understanding.

## 🔬 Research Contributions & Applications

My research bridges theoretical understanding with practical applications, enabling several breakthrough capabilities:

### **Enhanced Model Control**
- Direct model steering through activation engineering and steering vectors, eliminating the need for traditional fine-tuning approaches [(Turner et al., 2024)](https://arxiv.org/abs/2308.10248) [(Hendel et al., 2023)](https://arxiv.org/abs/2310.15916)
- Systematic knowledge access without pre-training modifications, as demonstrated in our ongoing steering vectors research

### **Robust Evaluation Methods**
- Contamination-free domain-specific benchmarking that reveals true model understanding beyond memorization
- Early stopping strategies during model training based on genuine knowledge acquisition rather than perplexity metrics
- Novel framework published in ["Beyond Benchmarks: A Novel Framework for Domain-Specific LLM Evaluation and Knowledge Mapping"](https://arxiv.org/abs/2506.07658)

### **Continual Learning Insights**
- Demonstrated that continual pretraining consistently improves models under 1.5B parameters and outperforms domain adaptation
- Revealed that smaller models show heightened sensitivity to continual pretraining with significant learning and forgetting rates
- Established that semantic similarity in domain sequences enables better specialization, while randomized domains improve transfer

### **Safety & Interpretability**
- Stronger safety constraints through understanding of output steering mechanisms [(Arditi et al., 2024)](https://arxiv.org/pdf/2406.11717) [(Bereska et al., 2024)](https://arxiv.org/abs/2404.14082)
- Enhanced model efficiency through targeted knowledge editing [(Meng et al., 2023)](https://proceedings.neurips.cc/paper_files/paper/2022/hash/6f1d43d5a82a37e89b0665b33bf3a182-Abstract-Conference.html)

## 🎯 Research Philosophy & Future Directions

My research explores the crucial intersection of knowledge representation and model behavior. By combining activation engineering techniques with causal intervention methods, I investigate how models process and adapt domain-specific knowledge while maintaining their core capabilities. This work is particularly inspired by knowledge localization techniques ([Meng et al., 2023](https://proceedings.neurips.cc/paper_files/paper/2022/hash/6f1d43d5a82a37e89b0665b33bf3a182-Abstract-Conference.html)), factual association tracking ([Geva et al., 2023](https://arxiv.org/abs/2304.14767)), and advances in model steering ([Arditi et al., 2024](https://arxiv.org/pdf/2406.11717)).

The most compelling aspect of this work is its potential to transform theoretical insights into practical applications, advancing both our understanding and our ability to create more reliable, controllable AI systems. Current investigations focus on understanding how activation patterns can serve as interpretable maps of knowledge representation across model layers, building on vector arithmetic approaches in language models [(Merullo et al., 2024)](https://arxiv.org/abs/2305.16130).

## 📚 Key Inspirations & Related Work

Apart from the papers mentioned above, my research draws significant inspiration from several groundbreaking works in the field:

- [A Mathematical Framework for Transformer Circuits](https://transformer-circuits.pub/2021/framework/index.html) (Elhage et al., 2021)
- [Dissecting Recall of Factual Associations in Auto-Regressive Language Models](https://arxiv.org/abs/2304.14767) (Geva et al., 2023)
- [Editing Factual Knowledge in Language Models](https://arxiv.org/abs/2104.08164) (Cao et al., 2021)
- [Language Agents Meet Causality -- Bridging LLMs and Causal World Models](https://arxiv.org/abs/2410.19923) (Gkountouras et al., 2024)
- [Talking Heads: Understanding Inter-layer Communication in Transformer Language Models](https://arxiv.org/abs/2406.09519) (Merullo et al., 2024)
- [CoSy: Evaluating Textual Explanations of Neurons](https://arxiv.org/abs/2405.20331) (Kopf et al., 2024)
- [Mechanistic Interpretability for AI Safety -- A Review](https://arxiv.org/abs/2404.14082) (Bereska et al., 2024)
