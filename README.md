

# **Recent Work on Autonomous AI Research and Recursive Self-Improvement**

**Period: August–November 2026**

## **1. Open-Weight Model Training**

These studies train LLMs to improve their capabilities in experimental prediction, research planning, model development, or cross-task experience learning.

| No. | Paper                                                                         | Base Model                  | Key Research Focus                                                                                                         |
| --- | ----------------------------------------------------------------------------- | --------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| 1   | [**LM2LM**](https://arxiv.org/abs/2610.23344?utm_source=chatgpt.com)          | Qwen3.8-27B                 | Training research models through real experiments and predicted rewards.                                                   |
| 2   | [**MLE-World**](https://arxiv.org/abs/2610.37175?utm_source=chatgpt.com)      | Qwen3.5-4B                  | Teaching models to understand and predict ML training dynamics, experimental outcomes, and execution failures.             |
| 3   | [**MetaExp**](https://arxiv.org/abs/2610.21492?utm_source=chatgpt.com)        | Qwen3.5-122B-A10B           | Learning to extract, update, and transfer experience across tasks through a meta-learning-like framework.                  |
| 4   | [**RSI-Dojo**](https://arxiv.org/abs/2611.03698?utm_source=chatgpt.com)       | Qwen3.5-9B, Qwen3.6-35B-A3B | Constructing large-scale post-training research environments and training agents to improve performance on PostTrainBench. |
| 5   | [**MLExpert**](https://arxiv.org/abs/2610.22344?utm_source=chatgpt.com)       | Qwen3.6-35B-A3B             | Training autonomous ML research agents through reinforcement learning with long-horizon experimental feedback.             |
| 6   | [**ResearchTrails**](https://arxiv.org/abs/2610.07184?utm_source=chatgpt.com) | Qwen3-8B                    | Mining research decision trajectories from historical scientific activities and using them as training data.               |
| 7   | [**RPG**](https://arxiv.org/abs/2609.36393?utm_source=chatgpt.com)            | Qwen3.5-4B                  | Optimizing research decisions and experimental exploration under computational and time constraints.                       |

## **2. Closed-Source and Fixed-Backbone Research Agents**

These studies primarily improve research capabilities through knowledge retrieval, experimental feedback, hypothesis revision, memory construction, and search optimization. Some evaluate both proprietary and open-weight backbones.

| No. | Paper                                                                                      | Key Research Focus                                                                                                                                               |
| --- | ------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 8   | [**Pro² Agent**](https://arxiv.org/abs/2611.25357?utm_source=chatgpt.com)                  | Identifying underlying research bottlenecks, generating testable hypotheses, and revising beliefs about unexplored solutions through controlled experiments.     |
| 9   | [**NeoResearch**](https://arxiv.org/abs/2611.18235?utm_source=chatgpt.com)                 | Mining scientific literature, extracting mechanisms and applicability conditions, and accumulating experimental experience for cross-task model discovery.       |
| 10  | [**EEM**](https://arxiv.org/abs/2609.39392?utm_source=chatgpt.com)                         | Extracting reusable knowledge from experimental trajectories, assessing evidence sufficiency, and acquiring missing evidence through targeted pilot experiments. |
| 11  | [**Research World Models (RWM)**](https://arxiv.org/abs/2610.12235?utm_source=chatgpt.com) | Predicting the outcomes of unseen research interventions using accumulated experimental knowledge and transferring experience across research environments.      |
| 12  | [**AIBuildAI-2.5**](https://arxiv.org/abs/2609.25047?utm_source=chatgpt.com)               | Improving autonomous AI development through knowledge-grounded proposal evaluation, LLM-guided tree search, and resource-aware scheduling.                       |
| 13  | [**AIM**](https://arxiv.org/abs/2609.38445?utm_source=chatgpt.com)                         | Managing competing research ideas, selecting promising directions, and allocating experimental budgets through surrogate-guided search.                          |
| 14  | [**Dream-RSI**](https://arxiv.org/abs/2609.14858?utm_source=chatgpt.com)                   | Recursively improving exploration strategies through offline simulation and replay of historical experimental search trees.                                      |
| 15  | [**Athanor**](https://arxiv.org/abs/2610.21055?utm_source=chatgpt.com)                     | Building an agent-native infrastructure for continuous and long-horizon autonomous post-training research.                                                       |
| 16  | [**RSI-Master**](https://arxiv.org/abs/2609.35561?utm_source=chatgpt.com)                  | Structuring experimental evidence and managing competing research directions to prevent premature convergence on suboptimal strategies.                          |
| 17  | [**AIDE²**](https://arxiv.org/abs/2609.26457?utm_source=chatgpt.com)                       | Recursively improving AI research agents by modifying their own research and experimental execution frameworks.                                                  |
| 18  | [**MLEvolver**](https://arxiv.org/abs/2611.28244?utm_source=chatgpt.com)                   | Improving self-evolving research agents through context management, experience consolidation, and dynamic skill evolution.                                       |

**Note:** Fixed-backbone approaches do not necessarily require closed-source models. For example, NeoResearch evaluates both proprietary and open-weight LLMs. Conversely, LM2LM trains an open-weight model but uses proprietary components in its training pipeline.

## **3. Experimental Understanding and Mechanism Discovery**

These studies are particularly relevant to causal knowledge mining, hypothesis refinement, and understanding the underlying mechanisms of ML training.

| No. | Paper                                                                                                                         | Key Research Focus                                                                                                                       |
| --- | ----------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| 19  | [**Can LLMs Predict the Outcomes of Machine Learning Experiments?**](https://arxiv.org/abs/2610.22599?utm_source=chatgpt.com) | Evaluating whether LLMs can anticipate the direction and magnitude of performance changes before executing ML experiments.               |
| 20  | [**WhatWorkedBench**](https://arxiv.org/abs/2609.27490?utm_source=chatgpt.com)                                                | Evaluating whether agents can identify conditional component effects and interactions through budget-constrained experimentation.        |
| 21  | [**MechHypoBench**](https://arxiv.org/abs/2610.05197?utm_source=chatgpt.com)                                                  | Discovering underlying scientific mechanisms from empirical observations and validating hypotheses under unseen experimental conditions. |
| 22  | [**rTaste**](https://arxiv.org/abs/2610.40488?utm_source=chatgpt.com)                                                         | Evaluating research judgment, experimental proposal quality, outcome prediction, and candidate prioritization.                           |
| 23  | [**Causal Discovery Bench**](https://arxiv.org/abs/2611.09934?utm_source=chatgpt.com)                                         | Evaluating causal discovery, active experimentation, and belief revision under limited resources and conflicting evidence.               |

## **4. Summary by Research Direction**

| Research Direction                        | Representative Works                              |
| ----------------------------------------- | ------------------------------------------------- |
| Research Model Training                   | LM2LM, MLExpert, RSI-Dojo                         |
| Experimental Outcome Prediction           | MLE-World, RWM                                    |
| Meta-Learning and Experience Transfer     | MetaExp, EEM, NeoResearch                         |
| Scientific Data and Knowledge Mining      | ResearchTrails, NeoResearch, MechHypoBench        |
| Causal Reasoning and Hypothesis Revision  | Pro² Agent, MechHypoBench, Causal Discovery Bench |
| Experimental Design and Budget Allocation | RPG, AIM, WhatWorkedBench                         |
| Recursive Self-Improvement                | Dream-RSI, AIDE², MLEvolver                       |
| Autonomous Post-Training                  | RSI-Dojo, Athanor, AIBuildAI-2.5                  |


> **Can a research model learn to build better AI systems by continuously discovering, validating, and internalizing the underlying mechanisms of machine learning?**

The most relevant combination of existing work for this direction is **LM2LM + MLE-World + MetaExp + NeoResearch + Pro² Agent + ResearchTrails**.
