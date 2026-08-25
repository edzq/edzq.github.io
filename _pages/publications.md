---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

Two questions run through most of my work: **how much structure a language model needs in order to act reliably**, and **how much structure it can recover from unstructured text**. The first is what I work on now, on agents and their security; the second is what led me there, through information extraction on scientific writing.

## Research

### Agents that use tools and catch their own mistakes

*RIMRULE* (ACL 2026) learns rules for tool-using agents under an MDL objective, so that what the agent learns stays compact enough to be inspected. *Metacognitive Self-Correction for Multi-Agent Systems* (ACL 2026) reconstructs what a multi-agent system was about to do next, and uses the mismatch as a signal for catching its own errors mid-execution.

### AI agent security

This is my current focus at AWS: tool-use security, robustness, and anomaly detection for agents that take real actions in real systems. An agent that can call tools is an agent that can be made to call the wrong one — the reliability question and the security question turn out to be the same question.

### Structured knowledge from text

Most of my Ph.D. work is about pulling entities, relations, and mentions out of scientific writing — and about making that extraction hold up when supervision is noisy or scarce. *SciER* (EMNLP 2024) is an entity and relation extraction dataset covering datasets, methods, and tasks in scientific documents; *DMDD* (TACL) and *SciDMT* (LREC-COLING 2024) target dataset and scientific-mention detection at scale. *DynClean* (NAACL 2025) uses training dynamics to clean labels for distantly-supervised NER, and *Many-Shot In-Context Learning for NER* (ACL 2026) asks how far in-context learning can substitute for annotation in the low-resource case.

### Structure for scientific domains

A related thread applies this to specific scientific fields, where the vocabulary is the hard part. *Taxonomy-Driven Knowledge Graph Construction* (ACL 2025) builds domain knowledge graphs from a taxonomy rather than a flat schema; *ClimateIE* and *Querying Climate Knowledge* (both 2025) bring information extraction and semantic retrieval to climate science; *FlowLearn* (ECAI 2024) extends the question past text, evaluating how well vision-language models read flowcharts.

## Publications

<u>Underline</u> marks equal contribution. A continuously updated list lives on <a href="https://scholar.google.com/citations?hl=en&user=PDQYP3EAAAAJ&view_op=list_works&sortby=pubdate">Google Scholar</a>.

### 2026
{: .year}

<ul class="pubs">
  <li>
    <span class="t"><a href="https://arxiv.org/abs/2608.20617">Dual-Cache Latent Space Communication between Heterogeneous Language Models</a></span>
    <span class="a">Jiyao Liu, <span class="me">Qi Zhang</span>, Yaoyi Jia, Ziwen Kan, Song Wang</span>
    <span class="v">arXiv preprint &middot; 2026</span>
  </li>
  <li>
    <span class="t">Scaling Performance and Low-Resource Annotation with Many-Shot In-Context Learning for Named Entity Recognition</span>
    <span class="a"><span class="me">Qi Zhang</span>, Fangping Lan, Cornelia Caragea, Longin Jan Latecki, Eduard Dragut</span>
    <span class="v">ACL 2026 &middot; Findings</span>
  </li>
  <li>
    <span class="t"><a href="https://scholar.google.com/citations?hl=en&user=PDQYP3EAAAAJ&view_op=list_works&sortby=pubdate">RIMRULE: Improving Tool-Using Language Agents via MDL-Guided Rule Learning</a></span>
    <span class="a">Xiang Gao, Yuguang Yao, <span class="me">Qi Zhang</span>, Kun Dong, Avirup Baidya, Rui Guo, Hugo Hasson, Kanak Das</span>
    <span class="v">ACL 2026 &middot; Main</span>
  </li>
  <li>
    <span class="t"><a href="https://arxiv.org/abs/2510.14319">Metacognitive Self-Correction for Multi-Agent Systems via Prototype-Guided Next-Execution Reconstruction</a></span>
    <span class="a"><span class="me"><u>Qi Zhang</u></span>, <u>Xu Shen</u>, Song Wang, Zhen Tan, Xinyu Zhao, Laura Yao, Vaishnav Tadiparthi, Hossein Nourkhiz Mahjoub, Ehsan Moradi Pari, Kwonjoon Lee, Tianlong Chen</span>
    <span class="v">ACL 2026 &middot; Findings</span>
  </li>
  <li>
    <span class="t">Making Revisions Understandable: A Survey of Edit Intentions, Methods, and Applications</span>
    <span class="a">Fangping Lan, <span class="me">Qi Zhang</span>, Eduard Dragut</span>
    <span class="v">ACL 2026 &middot; Findings</span>
  </li>
</ul>

### 2025
{: .year}

<ul class="pubs">
  <li>
    <span class="t"><a href="https://arxiv.org/abs/2504.04616">DynClean: Training Dynamics-based Label Cleaning for Distantly-Supervised Named Entity Recognition</a></span>
    <span class="a"><span class="me">Qi Zhang</span>, Huitong Pan, Zhijia Chen, Longin Jan Latecki, Cornelia Caragea, Eduard Dragut</span>
    <span class="v">NAACL 2025 &middot; Findings</span>
  </li>
  <li>
    <span class="t"><a href="https://aclanthology.org/2025.findings-acl.223/">Taxonomy-Driven Knowledge Graph Construction for Domain-Specific Scientific Applications</a></span>
    <span class="a">Huitong Pan, <span class="me">Qi Zhang</span>, Eduard Dragut, Cornelia Caragea, Longin Jan Latecki</span>
    <span class="v">ACL 2025 &middot; Findings</span>
  </li>
  <li>
    <span class="t"><a href="https://arxiv.org/abs/2509.10087">Querying Climate Knowledge: Semantic Retrieval for Scientific Discovery</a></span>
    <span class="a">Mustapha Adamu, <span class="me">Qi Zhang</span>, Huitong Pan, Eduard Dragut, Longin Jan Latecki</span>
    <span class="v">SIGIR 2025 &middot; MANILA Workshop</span>
  </li>
  <li>
    <span class="t"><a href="https://aclanthology.org/2025.climatenlp-1.6/">ClimateIE: A Dataset for Climate Science Information Extraction</a></span>
    <span class="a">Huitong Pan, Mustapha Adamu, <span class="me">Qi Zhang</span>, Eduard Dragut, Longin Jan Latecki</span>
    <span class="v">ACL 2025 &middot; 2nd ClimateNLP Workshop</span>
  </li>
</ul>

### 2024
{: .year}

<ul class="pubs">
  <li>
    <span class="t"><a href="https://aclanthology.org/2024.emnlp-main.726/">SciER: An Entity and Relation Extraction Dataset for Datasets, Methods, and Tasks in Scientific Documents</a></span>
    <span class="a"><span class="me">Qi Zhang</span>, Zhijia Chen, Huitong Pan, Cornelia Caragea, Longin Jan Latecki, Eduard Dragut</span>
    <span class="v">EMNLP 2024 &middot; Main <span class="note">(20.8% acceptance)</span></span>
  </li>
  <li>
    <span class="t"><a href="https://ebooks.iospress.nl/volumearticle/69568">FlowLearn: Evaluating Large Vision-Language Models on Flowchart Understanding</a></span>
    <span class="a">Huitong Pan, <span class="me">Qi Zhang</span>, Cornelia Caragea, Eduard Dragut, Longin Jan Latecki</span>
    <span class="v">ECAI 2024 <span class="note">(23% acceptance)</span></span>
  </li>
  <li>
    <span class="t"><a href="https://aclanthology.org/2024.lrec-main.1256/">SciDMT: A Large-Scale Corpus for Detecting Scientific Mentions</a></span>
    <span class="a">Huitong Pan, <span class="me">Qi Zhang</span>, Cornelia Caragea, Eduard Dragut, Longin Jan Latecki</span>
    <span class="v">LREC-COLING 2024</span>
  </li>
</ul>

### 2023
{: .year}

<ul class="pubs">
  <li>
    <span class="t"><a href="https://aclanthology.org/2023.tacl-1.64/">DMDD: A Large-Scale Dataset for Dataset Mention Detection</a></span>
    <span class="a">Huitong Pan, <span class="me">Qi Zhang</span>, Eduard Dragut, Cornelia Caragea, Longin Jan Latecki</span>
    <span class="v">Transactions of the ACL <span class="note">(TACL)</span></span>
  </li>
</ul>

### 2022
{: .year}

<ul class="pubs">
  <li>
    <span class="t"><a href="https://www.sciencedirect.com/science/article/abs/pii/S1746809422000088">A Novel Sleep Staging Network Based on Multi-Scale Dual Attention</a></span>
    <span class="a">Huafeng Wang, Chongang Lu, <span class="me">Qi Zhang</span>, Zhimin Hu, Xiaodong Yuan, Pingshu Zhang, Wanquan Liu</span>
    <span class="v">Biomedical Signal Processing and Control</span>
  </li>
</ul>
