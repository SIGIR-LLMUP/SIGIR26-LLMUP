---

layout: default
title: "LLM-UP: LLM-powered User Profiling for Search and Recommendation"
description: "SIGIR 2026 Workshop"

[//]: # "authors:"
[//]: # "  - name: \"Hongzhi Yin\""
[//]: # "    affiliation: \"The University of Queensland, Brisbane, Australia\""
[//]: # "  - name: \"Wei Yuan\""
[//]: # "    affiliation: \"The University of Queensland, Brisbane, Australia\""
[//]: # "  - name: \"Yi Zhang\""
[//]: # "    affiliation: \"Anhui University, Hefei, China\""
[//]: # "  - name: \"Joel Mackenzie\""
[//]: # "    affiliation: \"The University of Queensland, Brisbane, Australia\""
[//]: # "  - name: \"Quoc Viet Hung Nguyen\""
[//]: # "    affiliation: \"Griffith University, Gold Coast, Australia\""
[//]: # "  - name: \"Wayne Xin Zhao\""
[//]: # "    affiliation: \"Gaoling School of Artificial Intelligence, Renmin University of China, Beijing, China\""
[//]: # "  - name: \"Yong Li\""
[//]: # "    affiliation: \"Department of Electronic Engineering, Tsinghua University, Beijing, China\""
[//]: # "  - name: \"Lina Yao\""
[//]: # "    affiliation: \"University of New South Wales, Sydney, Australia\""

---

<style>
  body {
    font-size: 15px;
    line-height: 1.65;
  }

  .intro-text {
    text-align: justify;
  }

  .section-divider {
    border-top: 1px solid #eee;
    margin: 40px 0 20px 0;
  }

  .program-note {
    margin-bottom: 24px;
    color: #555;
    text-align: justify;
  }

  .program-item {
    padding: 18px 22px;
    margin: 18px 0;
    border-left: 4px solid #2f6f9f;
    background: #f8fafc;
    border-radius: 10px;
  }

  .program-item h3 {
    margin: 0 0 6px 0;
    font-size: 1.1rem;
  }

  .program-meta {
    color: #666;
    font-size: 0.92rem;
    font-weight: 600;
  }

  .speaker-card {
    display: flex;
    gap: 24px;
    align-items: flex-start;
    padding: 24px;
    margin: 24px 0;
    border: 1px solid #e6e6e6;
    border-radius: 16px;
    background: #fff;
    box-shadow: 0 4px 14px rgba(0, 0, 0, 0.04);
  }

  .speaker-photo {
    width: 112px;
    height: 112px;
    border-radius: 50%;
    object-fit: cover;
    flex-shrink: 0;
    border: 3px solid #f2f2f2;
    background: #f5f5f5;
  }

  .speaker-info h3 {
    margin: 6px 0 8px;
    font-size: 1.25rem;
    line-height: 1.35;
  }

  .talk-label {
    font-size: 0.82rem;
    color: #666;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 0.04em;
  }

  .speaker-name {
    font-weight: 700;
    margin: 4px 0;
  }

  .affiliation {
    color: #666;
    margin-top: 0;
    margin-bottom: 14px;
  }

  .speaker-info p {
    margin-bottom: 10px;
    text-align: justify;
  }

  .chairs-list {
    list-style-type: disc;
    padding-left: 20px;
    text-align: justify;
  }

  .chairs-list li {
    margin-bottom: 12px;
  }

  .program-section-title {
  padding: 18px 22px;
  margin: 18px 0 10px 0;
  border-left: 4px solid #2f6f9f;
  background: #f8fafc;
  border-radius: 10px;
}

.program-section-title h3 {
  margin: 0;
  font-size: 1.1rem;
}

  @media (max-width: 700px) {
    .speaker-card {
      flex-direction: column;
      align-items: center;
      text-align: center;
    }

    .speaker-info p {
      text-align: left;
    }

    .speaker-photo {
      width: 96px;
      height: 96px;
    }
  }
</style>

## Introduction

<div class="intro-text">
The rapid advancement of large language models (LLMs) has opened new possibilities for understanding users in search and recommendation. While traditional behavior-based or feature-driven user models rely primarily on explicit interactions or handcrafted representations, LLMs introduce a fundamentally different paradigm: LLM-powered user profiling, where user preferences, intents, and contextual attributes can be extracted, summarized, or reasoned about directly through natural language. 
This shift unlocks powerful new paths to achieve personalization but also raises pressing questions related to modeling fidelity, temporal dynamics, evaluation methodology, privacy, and responsible deployment. 
The LLM-UP workshop aims to bring together researchers and practitioners to systematize emerging progress in LLM-powered user profiling, identify open challenges, and explore opportunities for integrating such techniques into search and recommendation pipelines. 
The LLM-UP workshop adopts an interactive structure featuring lightning talks, panel discussions, and paper presentations to foster active engagement, cross-disciplinary dialogue, and community-driven agenda setting for this rapidly evolving field.
</div>

[//]: # "<p align=\"center\">"
[//]: # "<img src=\"main.jpg\" alt=\"GC\" width=\"750\">"
[//]: # "</p>"

<hr class="section-divider">

## Time Schedule

**Workshop Date**: Friday 24 July 2026

**Venue**: TBA

<hr class="section-divider">

## Program

<div class="program-note">
The main focus of the workshop is to provide a venue for researchers and practitioners to exchange ideas and consolidate emerging progress in LLM-powered user profiling.
<br>
<strong>The exact time schedule for each part will be announced soon.</strong>
</div>

<div class="program-item">
  <h3>Section 1: Welcome and Opening Remarks</h3>
  <div class="program-meta">30 mins</div>
</div>

<!-- <h3>Section 2: Invited Keynotes</h3> -->
<div class="program-section-title">
  <h3>Section 2: Invited Keynotes</h3>
</div>

<div class="speaker-card">
  <img src="{{ '/assets/css/zhaochun.jpeg' | relative_url }}" alt="Zhaochun Ren" class="speaker-photo">

  <div class="speaker-info">
    <div class="talk-label">Invited Keynote 1 · 45 mins</div>
    <h3>Generative retrieval: from search to recommendation</h3>
    <p class="speaker-name">Prof. Zhaochun Ren</p>
    <p class="affiliation">Leiden University, the Netherlands</p>


<p><strong>Abstract:</strong> Generative retrieval is reshaping search and recommendation by embedding corpus knowledge directly within generative models. This emerging framework moves beyond traditional indexing, mapping queries and user contexts directly to document or item identifiers. In this talk, I will provide an in-depth overview of generative retrieval with recent key advancements. These methods are bridging the gap between search and recommendation by leveraging semantic representations that capture both content-based and collaborative signals. Building on recent studies, I will outline the core concepts, methodological innovations, and practical applications driving this field, and conclude by discussing open challenges and promising directions for future research.</p>

<p><strong>Bio:</strong> Zhaochun Ren is an Associate Professor at Leiden University, the Netherlands. He is interested in information retrieval and natural language processing, with an emphasis on generative information retrieval and recommender systems. He aims to develop intelligent agents that can address complex user requests and solve core challenges in NLP and IR towards that goal. His research has been recognized with multiple awards at RecSys, SIGIR, WSDM, EMNLP, and CIKM. Prior to joining Leiden, he was a Professor at Shandong University and a Research Scientist at JD.com.</p>


  </div>
</div>

<div class="speaker-card">
  <img src="{{ '/assets/css/RockyChen.jpeg' | relative_url }}" alt="Zhaochun Ren" class="speaker-photo">

  <div class="speaker-info">
    <div class="talk-label">Invited Keynote 2 · 45 mins</div>
    <h3>Do LLMs Introduce New Vulnerabilities to Recommender Systems?</h3>
    <p class="speaker-name">Prof. Tong (Rocky) Chen</p>
    <p class="affiliation">The University of Queensland</p>


<p><strong>Abstract:</strong> Sequential recommendation is a fundamental task in recommender systems, which aims to estimate a ranked item list based on each user’s interaction history. Recently, large language model-powered sequential recommender systems (LLM-SRSs) have demonstrated remarkable performance by leveraging their natural strength in modelling interacted items as a sequence of textual descriptions. However, this paradigm also introduces new security vulnerabilities, particularly text-level manipulations, rendering them appealing targets for promotion attacks that purposely boost the ranking of specific target items. In this talk, I will present our recent work that investigates such new vulnerabilities by probing a mechanism for promotion attacks on LLM-SRSs. Distinct from existing studies that mostly rely on an unrealistic assumption of access to either the victim model or system prompt, our attack can operate in a real-world setting where both the system prompt and victim model are unknown. Our findings reveal critical security risks in modern LLM-SRSs even when both prompts and models are protected, and highlight the need for more robust defensive means. Following this study, I will further present a research agenda to discuss the technical landscape of secure recommender systems, and share my thoughts on the roadmap towards future research in this area.</p>
<p><strong>Bio:</strong> Rocky (Tong) Chen is currently an Associate Professor with the Data Science Discipline at The University of Queensland. Rocky’s main research interests include recommender systems, LLM agents, graph and sequential data mining, and social media content moderation. To date, Rocky and his team have published 90+ peer-reviewed papers in the most prestigious, CORE A*/A-ranked conferences and journals like KDD, SIGIR, WWW, ICDE, ICML, ICLR, IEEE TKDE, and ACM TOIS. Rocky is an area chair of the KDD, WWW, and SIGIR conferences, and an associate editor of the Neural Networks Journal. His research contributions have received several recognitions, including the 2025 Brisbane Lord Mayor’s Trailblazer Award, 2024 CIKM Best Student Paper Award, and the 2023 ARC Discovery Early Career Researcher Award.</p>


  </div>
</div>

<div class="speaker-card">
  <img src="{{ '/assets/css/andrew.jpeg' | relative_url }}" alt="Andrew Drozdov" class="speaker-photo">

  <div class="speaker-info">
    <div class="talk-label">Invited Keynote 3 · 45 mins</div>
    <h3>Training Adaptive Search Agents for Dynamic Environments</h3>
    <p class="speaker-name">Dr. Andrew Drozdov</p>
    <p class="affiliation">Databricks</p>


<p><strong>Abstract:</strong> This talk covers three directions toward adaptive search agents: using reinforcement learning to train large agents for slow, deliberative search, using reinforcement learning to train smaller models for fast search with parallel test-time compute, and evaluating agents in dynamic environments where questions and their answers change over time. The broader goal is to ask what the future of search should look like from both system design and evaluation perspectives, as search evolves from retrieving static results to powering interactive systems that increasingly rely on richer representations of fresh information, user context, and personalized information needs.</p>

<p><strong>Bio:</strong> Andrew Drozdov is a Senior Research Scientist at Databricks, where he works on language-model-powered search, ranking, and grounded reasoning for knowledge-intensive tasks. His research spans information retrieval, efficient and scalable AI, and reinforcement learning, with a focus on modern search systems for both humans and agents. He received his PhD from the University of Massachusetts Amherst and his Master’s degree from New York University.</p>


  </div>
</div>

<div class="program-item">
  <h3>Section 3: Discussion with SIGIR'26 Authors</h3>
  <div class="program-meta">40 mins</div>
</div>

<div class="program-item">
  <h3>Section 4: Wrap-up and Closing Remarks</h3>
  <div class="program-meta">10 mins</div>
</div>

<hr class="section-divider">

## Workshop Chairs

<div>
<ul class="chairs-list">

<li><strong>Prof. Hongzhi Yin</strong>, full professor and ARC Future Fellow at the University of Queensland.</li>

<li><strong>Dr. Wei Yuan</strong>, postdoc at The University of Queensland.</li>

<li><strong>Mr. Yi Zhang</strong>, PhD student at Anhui University.</li>

<li><strong>Dr. Joel Mackenzie</strong>, senior lecturer and DECRA Fellow at The University of Queensland.</li>

<li><strong>Prof. Quoc Viet Hung Nguyen</strong>, associate Professor at Griffith University.</li>

<li><strong>Prof. Wayne Xin Zhao</strong>, full professor at Renmin University of China.</li>

<li><strong>Prof. Yong Li</strong>, full professor at Tsinghua University.</li>

<li><strong>Prof. Lina Yao</strong>, full professor at UNSW.</li>

</ul>
</div>

<hr class="section-divider">

[//]: # "## Our Papers on Graph Condensation"
[//]: #
[//]: # "<ul style=\"list-style: none; padding-left: 0; font-size: smaller;\">"
[//]: # "    <li style=\"margin-bottom: 5px;\">"
[//]: # "        <strong><a href=\"https://arxiv.org/abs/2401.11720v2\">Graph Condensation: A Survey</a></strong> "
[//]: # "        <a href=\"https://github.com/XYGaoG/Graph-Condensation-Papers\">📖</a><br>"
[//]: # "        <em>Transactions on Knowledge and Data Engineering (TKDE), 2025</em><br>"
[//]: # "        Xinyi Gao, Junliang Yu, Tong Chen, Guanhua Ye, Wentao Zhang, Hongzhi Yin"
[//]: # "    </li>"
[//]: #
[//]: # "    <li style=\"margin-bottom: 5px;\">"
[//]: # "        <strong><a href=\"https://arxiv.org/abs/2405.13707\">Rethinking and Accelerating Graph Condensation: A Training-Free Approach with Class Partition</a></strong><br>"
[//]: # "        <em>ACM Web Conference (WWW), 2025</em><br>"
[//]: # "        Xinyi Gao, Guanhua Ye, Tong Chen, Wentao Zhang, Junliang Yu, Hongzhi Yin"
[//]: # "    </li>"
[//]: #
[//]: # "    <li style=\"margin-bottom: 5px;\">"
[//]: # "        <strong><a href=\"https://arxiv.org/abs/2405.17003\">Graph Condensation for Open-World Graph Learning</a></strong><br>"
[//]: # "        <em>ACM SIGKDD Conference on Knowledge Discovery and Data Mining (SIGKDD), 2024</em><br>"
[//]: # "        Xinyi Gao, Tong Chen, Wentao Zhang, Yayong Li, Xiangguo Sun, Hongzhi Yin"
[//]: # "    </li>"
[//]: #
[//]: # "    <li style=\"margin-bottom: 5px;\">"
[//]: # "        <strong><a href=\"https://arxiv.org/abs/2307.15967\">Graph Condensation for Inductive Node Representation Learning</a></strong><br>"
[//]: # "        <em>IEEE International Conference on Data Engineering (ICDE), 2024</em><br>"
[//]: # "        Xinyi Gao, Tong Chen, Yilong Zang, Wentao Zhang, Quoc Viet Hung Nguyen, Kai Zheng, Hongzhi Yin"
[//]: # "    </li>"
[//]: #
[//]: # "    <li style=\"margin-bottom: 5px;\">"
[//]: # "        <strong><a href=\"https://arxiv.org/abs/2412.16250\">Training-free Heterogeneous Graph Condensation via Data Selection</a></strong><br>"
[//]: # "        <em>IEEE International Conference on Data Engineering (ICDE), 2025</em><br>"
[//]: # "        Yuxuan Liang, Wentao Zhang, Xinyi Gao, Ling Yang, Chong Chen, Hongzhi Yin, Yunhai Tong, Bin Cui"
[//]: # "    </li>"
[//]: #
[//]: # "    <li style=\"margin-bottom: 5px;\">"
[//]: # "        <strong><a href=\"https://arxiv.org/abs/2406.13200\">RobGC: Towards Robust Graph Condensation</a></strong><br>"
[//]: # "        Xinyi Gao, Hongzhi Yin, Tong Chen, Guanhua Ye, Wentao Zhang, Bin Cui"
[//]: # "    </li>"
[//]: # "</ul>"
