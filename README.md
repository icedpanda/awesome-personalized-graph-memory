# Awesome Graph-Based Personalized Memory for LLM Agents:

[Awesome](https://awesome.re)
[PRs Welcome](http://makeapullrequest.com)
[License: MIT](https://opensource.org/licenses/MIT)
[Maintenance](#)

> A curated list of awesome papers and resources on preference-centric personalized graph memory for LLM agents, covering representation, retrieval, evolution, and evaluation of user-anchored long-term memory.

---

## 📌 Contents

- [Surveys & Overviews](#surveys--overviews)
- [Core Agent Memory Architectures](#core-agent-memory-architectures)
- [Personalization, User Modeling, and Recommendation](#personalization-user-modeling-and-recommendation)
- [Domain, Embodied, and Multi-Agent Applications](#domain-embodied-and-multi-agent-applications)
- [Memory Safety, Auditing, and Robustness](#memory-safety-auditing-and-robustness)
- [Adjacent Retrieval, GraphRAG, and Data Methods](#adjacent-retrieval-graphrag-and-data-methods)
- [Benchmarks & Evaluation](#benchmarks--evaluation)
- [Contributing](#-contributing)
- [Citation](#-citation)

---

## Surveys & Overviews

Broad surveys and position papers that frame agent memory, personalized agents, graph-augmented LLM agents, or nearby graph-learning foundations.

| Work                                                                                                  | Links                                                                                                   |
| ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| **Graph-based Agent Memory: Taxonomy, Techniques, and Applications** (arXiv'26)                       | [[paper]](https://arxiv.org/abs/2602.05665) [[code]](https://github.com/DEEP-PolyU/Awesome-GraphMemory) |
| **Memory in the LLM Era** (arXiv'26)                                                                  | [[paper]](https://arxiv.org/abs/2604.01707)                                                             |
| **From Storage to Experience: A Survey on the Evolution of LLM Agent Memory Mechanisms** (arXiv'26)   | [[paper]](https://arxiv.org/abs/2605.06716)                                                             |
| **Toward Personalized LLM-Powered Agents: Foundations, Evaluation, and Future Directions** (arXiv'26) | [[paper]](https://arxiv.org/abs/2602.22680)                                                             |
| **Graph-Augmented Large Language Model Agents: Current Progress and Future Prospects** (arXiv'25)     | [[paper]](https://arxiv.org/abs/2507.21407)                                                             |
| **Large Language Model Agent: A Survey on Methodology** (arXiv'25)                                    | [[paper]](https://arxiv.org/abs/2503.21460)                                                             |
| **Personalized Generation In Large Model Era: A Survey** (COLING'25)                                  | [[paper]](https://arxiv.org/abs/2503.02614)                                                             |

## Core Agent Memory Architectures

General-purpose long-term memory systems for agents. These are grouped here when the main contribution is a memory architecture, controller, lifecycle, or memory-management policy rather than specifically user modeling or evaluation.

### Graph, KG, and Structured Memory

| Work                                                                                                                            | Links                                                                                           |
| ------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| **Agentic Memory: Learning Unified Long-Term and Short-Term Memory Management for Large Language Model Agents** (arXiv'26)      | [[paper]](https://arxiv.org/abs/2601.01885)                                                     |
| **All-Mem: Agentic Lifelong Memory via Dynamic Topology Evolution** (arXiv'26)                                                  | [[paper]](https://arxiv.org/abs/2603.19595)                                                     |
| **AriadneMem: Threading the Maze of Lifelong Memory for LLM Agents** (arXiv'26)                                                 | [[paper]](https://arxiv.org/abs/2603.03290) [[code]](https://github.com/LLM-VLM-GSL/AriadneMem) |
| **AriGraph: Learning Knowledge Graph World Models with Episodic Memory for LLM Agents** (arXiv'24)                              | [[paper]](https://arxiv.org/abs/2407.04363)                                                     |
| **GAAMA: Graph Augmented Associative Memory for Agents** (arXiv'26)                                                             | [[paper]](https://arxiv.org/abs/2603.27910)                                                     |
| **GAM: Hierarchical Graph-based Agentic Memory for LLM Agents** (arXiv'26)                                                      | [[paper]](https://arxiv.org/abs/2604.12285)                                                     |
| **Graph-Native Cognitive Memory for AI Agents: Formal Belief Revision Semantics for Versioned Memory Architectures** (arXiv'26) | [[paper]](https://arxiv.org/abs/2603.17244)                                                     |
| **HAGE: Harnessing Agentic Memory via RL-Driven Weighted Graph Evolution** (arXiv'26)                                           | [[paper]](https://arxiv.org/abs/2605.09942)                                                     |
| **HyperMem: Hypergraph Memory for Long-Term Conversations** (arXiv'26)                                                          | [[paper]](https://arxiv.org/abs/2604.08256)                                                     |
| **MAGMA: A Multi-Graph based Agentic Memory Architecture for AI Agents** (arXiv'26)                                             | [[paper]](https://arxiv.org/abs/2601.03236)                                                     |
| **MemORAI: Memory Organization and Retrieval via Adaptive Graph Intelligence for LLM Conversational Agents** (ACL Findings'26)  | [[paper]](https://arxiv.org/abs/2605.01386)                                                     |
| **Memory Matters More: Event-Centric Memory as a Logic Map for Agent Searching and Reasoning** (arXiv'26)                       | [[paper]](https://arxiv.org/abs/2601.04726)                                                     |
| **SAGE: A Self-Evolving Agentic Graph-Memory Engine for Structure-Aware Associative Memory** (arXiv'26)                         | [[paper]](https://arxiv.org/abs/2605.12061)                                                     |
| **SGMem: Sentence Graph Memory for Long-Term Conversational Agents** (arXiv'25)                                                 | [[paper]](https://arxiv.org/abs/2509.21212)                                                     |
| **TemporalKGMemory** (arXiv'26)                                                                                                 | [[paper]](https://arxiv.org/abs/2604.11544)                                                     |
| **Zep: A Temporal Knowledge Graph Architecture for Agent Memory** (arXiv'25)                                                    | [[paper]](https://arxiv.org/abs/2501.13956)                                                     |

### Hybrid, Hierarchical, and Cognitive Memory

| Work                                                                                                            | Links                                                                                      |
| --------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| **A Simple Yet Strong Baseline for Long-Term Conversational Memory of LLM Agents** (arXiv'25)                   | [[paper]](https://arxiv.org/abs/2511.17208)                                                |
| **ActMem: Bridging the Gap Between Memory Retrieval and Reasoning in LLM Agents** (arXiv'26)                    | [[paper]](https://arxiv.org/abs/2603.00026)                                                |
| **Amory: Building Coherent Narrative-Driven Agent Memory through Agentic Reasoning** (arXiv'26)                 | [[paper]](https://arxiv.org/abs/2601.06282)                                                |
| **APEX-MEM: Agentic Semi-Structured Memory with Temporal Reasoning for Long-Term Conversational AI** (arXiv'26) | [[paper]](https://arxiv.org/abs/2604.14362)                                                |
| **AssoMem: Scalable Memory QA with Multi-Signal Associative Retrieval** (arXiv'25)                              | [[paper]](https://arxiv.org/abs/2510.10397)                                                |
| **Beyond RAG for Agent Memory: Retrieval by Decoupling and Aggregation** (arXiv'26)                             | [[paper]](https://arxiv.org/abs/2602.02007)                                                |
| **Does Memory Need Graphs? A Unified Framework and Empirical Analysis for Long-Term Dialog Memory** (arXiv'26)  | [[paper]](https://arxiv.org/abs/2601.01280)                                                |
| **G-Memory: Tracing Hierarchical Memory for Multi-Agent Systems** (arXiv'25)                                    | [[paper]](https://arxiv.org/abs/2506.07398) [[code]](https://github.com/bingreeky/GMemory) |
| **GRAVITY: Architecture-Agnostic Structured Anchoring for Long-Horizon Conversational Memory** (arXiv'26)       | [[paper]](https://arxiv.org/abs/2605.01688)                                                |
| **H-Mem: A Novel Memory Mechanism for Evolving and Retrieving Agent Memory via a Hybrid Structure** (arXiv'26)  | [[paper]](https://arxiv.org/abs/2605.15701)                                                |
| **Hierarchical Long-Term Semantic Memory for LinkedIn's Hiring Agent** (arXiv'26)                               | [[paper]](https://arxiv.org/abs/2604.26197)                                                |
| **Hindsight is 20/20: Building Agent Memory that Retains, Recalls, and Reflects** (arXiv'25)                    | [[paper]](https://arxiv.org/abs/2512.12818)                                                |
| **HingeMem: Boundary Guided Long-Term Memory with Query Adaptive Retrieval for Scalable Dialogues** (arXiv'26)  | [[paper]](https://arxiv.org/abs/2604.06845)                                                |
| **LEGOMem: Modular Procedural Memory for Multi-agent LLM Systems for Workflow Automation** (arXiv'25)           | [[paper]](https://arxiv.org/abs/2510.04851)                                                |
| **LiCoMemory: Lightweight and Cognitive Agentic Memory for Efficient Long-Term Reasoning** (arXiv'25)           | [[paper]](https://arxiv.org/abs/2511.01448)                                                |
| **Mem0** (arXiv'25)                                                                                             | [[paper]](https://arxiv.org/abs/2504.19413)                                                |
| **MemCog: From Memory-as-Tool to Memory-as-Cognition in Conversational Agents** (arXiv'26)                      | [[paper]](https://arxiv.org/abs/2605.28046)                                                |
| **MemGPT** (arXiv'23)                                                                                           | [[paper]](https://arxiv.org/abs/2310.08560)                                                |
| **MemRouter: Memory-as-Embedding Routing for Long-Term Conversational Agents** (arXiv'26)                       | [[paper]](https://arxiv.org/abs/2605.00356)                                                |
| **MemToolAgent: Leveraging Memory for Tool Using Agents Based on Environment and User Feedback** (arXiv'26)     | [[paper]](https://arxiv.org/abs/2606.07909)                                                |
| **MemWeaver: Weaving Hybrid Memories for Traceable Long-Horizon Agentic Reasoning** (arXiv'26)                  | [[paper]](https://arxiv.org/abs/2601.18204)                                                |
| **RGMem: Renormalization Group-inspired Memory Evolution for Language Agents** (ICML'26)                        | [[paper]](https://arxiv.org/abs/2510.16392) [[code]](https://github.com/fenhg297/RGMem)    |
| **Rethinking How to Remember: Beyond Atomic Facts in Lifelong LLM Agent Memory** (arXiv'26)                     | [[paper]](https://arxiv.org/abs/2605.19952)                                                |
| **What Deserves Memory: Adaptive Memory Distillation for LLM** (arXiv'25)                                       | [[paper]](https://arxiv.org/abs/2508.03341)                                                |

### Memory Evolution, Reflection, and Procedures

| Work                                                                                                                      | Links                                       |
| ------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| **Emotion-Attended Stateful Memory (EASM): The Architecture for Hyper-Personalization at Scale** (arXiv'26)               | [[paper]](https://arxiv.org/abs/2605.14833) |
| **Managing Procedural Memory** (arXiv'26)                                                                                 | [[paper]](https://arxiv.org/abs/2606.23127) |
| **Memory in the Age of AI Agents** (arXiv'26)                                                                             | [[paper]](https://arxiv.org/abs/2512.13564) |
| **Memory-R1: Enhancing Large Language Model Agents to Manage and Utilize Memories via Reinforcement Learning** (arXiv'25) | [[paper]](https://arxiv.org/abs/2508.19828) |

## Personalization, User Modeling, and Recommendation

Papers whose central objective is representing a specific user's traits, preferences, trajectory, or conversational history. Recommender-system entries live here unless their primary contribution is an evaluation benchmark.

### Personalized Dialogue and User Memory

| Work                                                                                                                                       | Links                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| **AdaMem: Adaptive User-Centric Memory for Long-Horizon Dialogue Agents** (arXiv'26)                                                       | [[paper]](https://arxiv.org/abs/2603.16496)                                                      |
| **Beyond Dialogue Time: Temporal Semantic Memory for Personalized LLM Agents** (arXiv'26)                                                  | [[paper]](https://arxiv.org/abs/2601.07468)                                                      |
| **Bi-Mem: Bidirectional Construction of Hierarchical Memory for Personalized LLMs via Inductive-Reflective Agents** (arXiv'26)             | [[paper]](https://arxiv.org/abs/2601.06490)                                                      |
| **Crafting Personalized Agents through Retrieval-Augmented Generation on Editable Memory Graphs** (EMNLP'24)                               | [[paper]](https://arxiv.org/abs/2409.19401)                                                      |
| **Hierarchical Memory Orchestration for Personalized Persistent Agents** (arXiv'26)                                                        | [[paper]](https://arxiv.org/abs/2604.01670)                                                      |
| **Knowledge Graph Tuning: Real-time Large Language Model Personalization based on Human Feedback** (arXiv'24)                              | [[paper]](https://arxiv.org/abs/2405.19686)                                                      |
| **LOOM: Personalized Learning Informed by Daily LLM Conversations Toward Long-Term Mastery via a Dynamic Learner Memory Graph** (arXiv'25) | [[paper]](https://arxiv.org/abs/2511.21037)                                                      |
| **Personalized Large Language Model Assistant with Evolving Conditional Memory** (ACL Findings'25)                                         | [[paper]](https://arxiv.org/abs/2312.17257)                                                      |
| **PersonaAgent with GraphRAG: Community-Aware Knowledge Graphs for Personalized LLM** (arXiv'25)                                           | [[paper]](https://arxiv.org/abs/2511.17467)                                                      |
| **PersonaMem-v2: Towards Personalized Intelligence via Learning Implicit User Personas and Agentic Memory** (arXiv'25)                     | [[paper]](https://arxiv.org/abs/2512.06688)                                                      |
| **PersonalAI: A Systematic Comparison of Knowledge Graph Storage and Retrieval Approaches for Personalized LLM agents** (arXiv'25)         | [[paper]](https://arxiv.org/abs/2506.17001)                                                      |
| **PersonalAI 2.0: Enhancing knowledge graph traversal/retrieval with planning mechanism for Personalized LLM Agents** (arXiv'26)           | [[paper]](https://arxiv.org/abs/2605.13481)                                                      |
| **PRISM: Pareto-Efficient Retrieval over Intent-Aware Structured Memory for Long-Horizon Agents** (arXiv'26)                               | [[paper]](https://arxiv.org/abs/2605.12260)                                                      |
| **Remember Me, Refine Me: A Dynamic Procedural Memory Framework for Experience-Driven Agent Evolution** (arXiv'25)                         | [[paper]](https://arxiv.org/abs/2512.10696)                                                      |
| **SeCom: On Memory Construction and Retrieval for Personalized Conversational Agents** (ICLR'25)                                           | [[paper]](https://arxiv.org/abs/2502.05589) [[code]](https://github.com/microsoft/SeCom)         |
| **Temporal User Profiling with LLMs: Balancing Short-Term and Long-Term Preferences for Recommendations** (arXiv'25)                       | [[paper]](https://arxiv.org/abs/2508.08454)                                                      |
| **TraceMem: Weaving Narrative Memory Schemata from User Conversational Traces** (arXiv'26)                                                 | [[paper]](https://arxiv.org/abs/2602.09712) [[code]](https://github.com/YimingShu-teay/TraceMem) |
| **User Simulator-Guided Multi-Turn Preference Optimization** (arXiv'26)                                                                    | [[paper]](https://arxiv.org/abs/2604.03671)                                                      |

### Conversational Recommendation and Preference Reasoning

| Work                                                                                                                         | Links                                       |
| ---------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| **AMEM4Rec: Leveraging Cross-User Similarity for Memory Evolution in Agentic LLM Recommenders** (arXiv'26)                   | [[paper]](https://arxiv.org/abs/2602.08837) |
| **Agentic Recommender System with Hierarchical Belief-State Memory** (arXiv'26)                                              | [[paper]](https://arxiv.org/abs/2605.14401) |
| **Empowering Retrieval-based Conversational Recommendation** (arXiv'25)                                                      | [[paper]](https://arxiv.org/abs/2503.22005) |
| **Graph Retrieval-Augmented LLM for Conversational Recommendation Systems** (GCRS'25)                                        | [[paper]](https://arxiv.org/abs/2503.06430) |
| **MemoCRS: Memory-enhanced Sequential Conversational Recommender Systems with Large Language Models** (arXiv'24)             | [[paper]](https://arxiv.org/abs/2407.04960) |
| **MemRec: Collaborative Memory-Augmented Agentic Recommender System** (arXiv'26)                                             | [[paper]](https://arxiv.org/abs/2601.08816) |
| **Reasoning over User Preferences: Knowledge Graph-Augmented LLMs for Explainable Conversational Recommendations** (ICDM'25) | [[paper]](https://arxiv.org/abs/2411.14459) |
| **User Memory Reasoning for Conversational Recommendation** (arXiv'20)                                                       | [[paper]](https://arxiv.org/abs/2006.00184) |

### Personal Memory Products and Assistants

| Work                                                                            | Links                                                                                                   |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| **Dreaming: Better Memory for ChatGPT** (OpenAI Blog'26)                        | [[link]](https://openai.com/index/chatgpt-memory-dreaming/)                                             |
| **Hermes Agent** (Project'26)                                                   | [[link]](https://hermes-agent.nousresearch.com/) [[code]](https://github.com/NousResearch/hermes-agent) |
| **OpenClaw** (Documentation'26)                                                 | [[link]](https://docs.openclaw.ai/) [[code]](https://github.com/openclaw/openclaw)                      |
| **Supermemory** (Project)                                                       | [[link]](https://supermemory.ai/)                                                                       |
| **Vellum Assistant: A Personal AI Assistant That Evolves With You** (GitHub'26) | [[link]](https://github.com/vellum-ai/vellum-assistant)                                                 |

## Domain, Embodied, and Multi-Agent Applications

Memory systems grounded in a particular task environment or application domain. These moved out of the generic graph-memory bucket because the contribution is domain-specific behavior, safety, or agent setting.

| Work                                                                                                                                         | Links                                       |
| -------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| **DEMENTIA-PLAN: An Agent-Based Framework for Multi-Knowledge Graph Retrieval-Augmented Generation in Dementia Care** (arXiv'25)             | [[paper]](https://arxiv.org/abs/2503.20950) |
| **EchoGuard: An Agentic Framework with Knowledge-Graph Memory for Detecting Manipulative Communication in Longitudinal Dialogue** (arXiv'26) | [[paper]](https://arxiv.org/abs/2603.04815) |
| **From Local to Global: A Graph RAG Approach to Query-Focused Summarization** (arXiv'24)                                                     | [[paper]](https://arxiv.org/abs/2404.16130) |
| **Open-Ended Instructable Embodied Agents** (arXiv'23)                                                                                       | [[paper]](https://arxiv.org/abs/2310.15127) |
| **Personalizing Embodied Multimodal Large Language Model Agents over Long-term User Interactions** (arXiv'26)                                | [[paper]](https://arxiv.org/abs/2605.26256) |
| **SE-GA: Memory-Augmented Self-Evolution for GUI Agents** (arXiv'26)                                                                         | [[paper]](https://arxiv.org/abs/2605.16883) |
| **Skill-Pro** (arXiv'26)                                                                                                                     | [[paper]](https://arxiv.org/abs/2602.01869) |

## Memory Safety, Auditing, and Robustness

Work focused on memory contamination, poisoning, anomaly detection, and structural auditing rather than memory architecture alone.

| Work                                                                                                                        | Links                                       |
| --------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| **MemAudit: Post-hoc Auditing of Poisoned Agent Memory via Causal Attribution and Structural Anomaly Detection** (arXiv'26) | [[paper]](https://arxiv.org/abs/2605.23723) |
| **MemGuard: Preventing Memory Contamination in Long-Term Memory-Augmented Large Language Models** (arXiv'26)                | [[paper]](https://arxiv.org/abs/2605.28009) |
| **ScrapMem: A Bio-inspired Framework for On-device Personalized Agent Memory via Optical Forgetting** (arXiv'26)            | [[paper]](https://arxiv.org/abs/2605.03804) |

## Adjacent Retrieval, GraphRAG, and Data Methods

Related methods that inform graph-memory design but are not primarily personalized graph-memory systems: graph RAG, tabular or node retrieval, synthetic graph/data generation, and latent memory baselines.

| Work                                                                                                                | Links                                       |
| ------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| **Agentic-KGR: Co-evolutionary Knowledge Graph Construction through Multi-Agent Reinforcement Learning** (arXiv'25) | [[paper]](https://arxiv.org/abs/2510.09156) |
| **GraphGen** (arXiv'25)                                                                                             | [[paper]](https://arxiv.org/abs/2505.20416) |
| **LatentMem** (arXiv'26)                                                                                            | [[paper]](https://arxiv.org/abs/2602.03036) |
| **Learning from Synthetic Data Improves Multi-hop Reasoning** (arXiv'26)                                            | [[paper]](https://arxiv.org/abs/2603.02091) |
| **NodeRAG** (arXiv'25)                                                                                              | [[paper]](https://arxiv.org/abs/2504.11544) |
| **Synthesize-on-Graph** (arXiv'25)                                                                                  | [[paper]](https://arxiv.org/abs/2505.00979) |
| **TableRAG** (arXiv'25)                                                                                             | [[paper]](https://arxiv.org/abs/2506.10380) |

## Benchmarks & Evaluation

Benchmarks, diagnostics, and empirical evaluation frameworks. Systems that also introduce memory methods are kept here when the dataset/evaluation protocol is the primary contribution.

### Long-Term Dialogue and Personal Memory Benchmarks

| Work                                                                                                                   | Links                                                                                           |
| ---------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| **According to Me: Long-Term Personalized Referential Memory QA** (arXiv'26)                                           | [[paper]](https://arxiv.org/abs/2603.01990)                                                     |
| **Do LLMs Recognize Your Preferences? Evaluating Personalized Preference Following in LLMs** (arXiv'25)                | [[paper]](https://arxiv.org/abs/2502.09597)                                                     |
| **EngramaBench: Evaluating Long-Term Conversational Memory with Structured Graph Retrieval** (arXiv'26)                | [[paper]](https://arxiv.org/abs/2604.21229)                                                     |
| **Evaluating Long-Horizon Memory for Multi-Party Collaborative Dialogues** (arXiv'26)                                  | [[paper]](https://arxiv.org/abs/2602.01313)                                                     |
| **Evaluating Very Long-Term Conversational Memory of LLM Agents** (ACL'24)                                             | [[paper]](https://arxiv.org/abs/2402.17753)                                                     |
| **Know Me, Respond to Me: Benchmarking LLMs for Dynamic User Profiling and Personalized Responses at Scale** (COLM'25) | [[paper]](https://arxiv.org/abs/2504.14225) [[code]](https://github.com/bowen-upenn/PersonaMem) |
| **LongMemEval - Supermemory Research** (Research report)                                                               | [[link]](https://supermemory.ai/research/longmemeval)                                           |
| **LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory** (arXiv'24)                               | [[paper]](https://arxiv.org/abs/2410.10813)                                                     |
| **LongMemEval-V2: Evaluating Long-Term Agent Memory Toward Experienced Colleagues** (arXiv'26)                         | [[paper]](https://arxiv.org/abs/2605.12493)                                                     |
| **MemTrace: Tracing and Attributing Errors in Large Language Model Memory Systems** (arXiv'26)                         | [[paper]](https://arxiv.org/abs/2605.28732)                                                     |
| **PerLTQA** (arXiv'24)                                                                                                 | [[paper]](https://arxiv.org/abs/2402.16288)                                                     |
| **RealMem: Benchmarking LLMs in Real-World Memory-Driven Interaction** (arXiv'26)                                      | [[paper]](https://arxiv.org/abs/2601.06966)                                                     |
| **SocialMemBench** (arXiv'26)                                                                                          | [[paper]](https://arxiv.org/abs/2605.17789)                                                     |

### Structure, Evolution, and Agent-Task Evaluation

| Work                                                                                             | Links                                                                                    |
| ------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------- |
| **Benchmarking Deep Search** (arXiv'25)                                                          | [[paper]](https://arxiv.org/abs/2506.23139)                                              |
| **Evaluating Memory Structure in LLM Agents** (arXiv'26)                                         | [[paper]](https://arxiv.org/abs/2602.11243)                                              |
| **EvoArena: Tracking Memory Evolution for Robust LLM Agents in Dynamic Environments** (arXiv'26) | [[paper]](https://arxiv.org/abs/2606.13681)                                              |
| **EvoMemBench: Benchmarking Agent Memory from a Self-Evolving Perspective** (arXiv'26)           | [[paper]](https://arxiv.org/abs/2605.18421)                                              |
| **EXG: Self-Evolving Agents with Experience Graphs** (arXiv'26)                                  | [[paper]](https://arxiv.org/abs/2605.17721)                                              |
| **HiMTM** (CIKM'24)                                                                              | [[paper]](https://dl.acm.org/doi/abs/10.1145/3627673.3679741)                            |
| **MemoryCD** (arXiv'26)                                                                          | [[paper]](https://arxiv.org/abs/2603.25973)                                              |
| **Memory is Reconstructed, Not Retrieved: Graph Memory for LLM Agents** (ICML'26)                | [[paper]](https://arxiv.org/abs/2606.06036) [[code]](https://github.com/Ji-shuo/MRAgent) |
| **WildGraphBench** (arXiv'26)                                                                    | [[paper]](https://arxiv.org/abs/2602.02053)                                              |

---

## 🤝 Contributing

PRs are very welcome. Please:

1. Keep entries in the format: `**Paper Title** (Venue'YY) [[paper]](url) [[code]](url).`
2. Add the paper to the section that best matches its **primary** contribution; cross-reference in other sections only if essential.

---