---
title: "GreenMind: A Next-Generation Vietnamese Large Language Model for Structured and Logical Reasoning"
collection: publications
category: conferences
permalink: /publication/2025-04-23-GreenMind
excerpt: 'This paper is about technical detail of first Vietnamese LLM on Nvidia NIM'
date: 2025-04-23
venue: 'Arvix'
paperurl: '/files/papers/GreenMind_Arvix.pdf'
citation: '@misc{tung2025greenmindnextgenerationvietnameselarge,
      title={GreenMind: A Next-Generation Vietnamese Large Language Model for Structured and Logical Reasoning}, 
      author={Luu Quy Tung and Hoang Quoc Viet and Pham Bao Loc and Vo Trong Thu},
      year={2025},
      eprint={2504.16832},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2504.16832}, 
}'
---

Chain-of-Thought (CoT) is a robust approach for tackling LLM tasks that require intermediate reasoning steps prior to generating a final answer. In this paper, we present GreenMind-Medium-14B-R1, the Vietnamese reasoning model inspired by the finetuning strategy based on Group Relative Policy Optimization. We also leverage a high-quality Vietnamese synthesized reasoning dataset and design two reward functions to tackle the main limitations of this technique: (i) language mixing, where we explicitly detect the presence of biased language characters during the process of sampling tokens, and (ii) we leverage Sentence Transformer-based models to ensure that the generated reasoning content maintains factual correctness and does not distort the final output. Experimental results on the Vietnamese dataset from the VLSP 2023 Challenge demonstrate that our model outperforms prior works and enhances linguistic consistency in its responses. Furthermore, we extend our evaluation to SeaExam-a multilingual multiple-choice dataset, showing the effectiveness of our reasoning method compared to few-shot prompting techniques.
