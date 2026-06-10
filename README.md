# Awesome Agentic Evolution

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/agentic-evolution/awesome-agentic-evolution/pulls)

> A curated and continuously updated collection of research papers on **agentic evolution** — 
> persistent, experience-driven, system-level change in agentic systems through autonomous or human-involved selective pressure.
>
> Some papers appear under multiple substrates when they contribute to more than one.

## Legend

**Evolutionary Substrate** — what component of the agentic system evolves:
- **Cortex (Π)**: The deliberative substrate — base LLM weights, prompts, decoding strategies, and inference-time procedures
- **Action (A)**: The executive substrate — toolset, execution logic (workflow graphs, control flow), and multi-agent orchestration
- **Memory & Sense (M)**: The epistemic substrate — episodic/semantic/procedural memory, retention and retrieval policies, perception encoders, and world models

**Consolidation Pathway** — how experience becomes persistent change:
- `Δ` Structural: discrete, symbolic edits to non-parametric artifacts (prompts, workflow graphs, memory indices, tool configurations, and code)
- `∇` Parametric: continuous updates to model weight parameters
- `Δ+∇` Hybrid: both structural and parametric consolidation within a single system

**Selective Pressure** — what drives evolution:
- `H=0` Autonomous: selective pressure from environmental experience (including formal verification) and self-generated signals (self-play, self-rewarding)
- `H≠0` Human-involved: human input shapes the evolutionary trajectory (prescriptions, demonstrations, evaluative feedback, interactive collaboration, or implicit signals)

## Table of Contents

- [Cortex (Π) Evolution](#cortex-π-evolution)
- [Action (A) Evolution](#action-a-evolution)
- [Memory & Sense (M) Evolution](#memory-sense-m-evolution)
- [Contributing](#contributing)

## Cortex (Π) Evolution

### Δ, H=0 (Structural, Autonomous)

#### Prompt optimization

- **"Adaptive Prompt Structure Factorization: A Framework for Self-Discovering and Optimizing Compositional Prompt Programs"**  
  *Liu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.06699)]
- **"Self-Optimizing Multi-Agent Systems for Deep Research"**  
  *Câmara et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.02988)]
- **"Combee: Scaling Prompt Learning for Self-Improving Language Model Agents"**  
  *Li et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.04247)]
- **"Self-Evolving LLM Memory Extraction Across Heterogeneous Tasks"**  
  *Yang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.11610)]
- **"Evolutionary Context Search for Automated Skill Acquisition"**  
  *Sun et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.16113)]
- **"Understanding the Challenges in Iterative Generative Optimization with LLMs"**  
  *Nie et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.23994)]
- **"JTPRO: A Joint Tool-Prompt Reflective Optimization Framework for Language Agents"**  
  *Ghoshal et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.19821)]
- **"Optimizing Generative AI by Backpropagating Language Model Feedback"**  
  *Yuksekgonul et al.* Nature 2025. [[paper](https://doi.org/10.1038/s41586-025-08661-4)]
- **"REVOLVE: Optimizing AI Systems by Tracking Response Evolution in Textual Optimization"**  
  *Zhang et al.* ICML 2025. [[paper](https://arxiv.org/abs/2412.03092)]
- **"Large Language Models as Optimizers"**  
  *Yang et al.* ICLR 2024. [[paper](https://arxiv.org/abs/2309.03409)]
- **"Connecting Large Language Models with Evolutionary Algorithms Yields Powerful Prompt Optimizers"**  
  *Guo et al.* ICLR 2024. [[paper](https://doi.org/10.48550/arXiv.2309.08532)]
- **"Promptbreeder: Self-Referential Self-Improvement Via Prompt Evolution"**  
  *Fernando et al.* ICML 2024. [[paper](https://arxiv.org/abs/2309.16797)]
- **"DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines"**  
  *Khattab et al.* ICLR 2024. [[paper](https://arxiv.org/abs/2310.03714)]
- **"Large Language Models Are Human-Level Prompt Engineers"**  
  *Zhou et al.* ICLR 2023. [[paper](https://arxiv.org/abs/2211.01910)]

#### Reflection-driven

- **"Agentic Context Engineering: Evolving Contexts for Self-Improving Language Models"**  
  *Zhang et al.* ICLR 2026. [[paper](https://arxiv.org/abs/2510.04618)]
- **"Trace2Skill: Distill Trajectory-Local Lessons into Transferable Agent Skills"**  
  *Ni et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.25158)]
- **"Experience as a Compass: Multi-agent RAG with Evolving Orchestration and Agent Prompts"**  
  *Li et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.00901)]
- **"Beyond Meta-Reasoning: Metacognitive Consolidation for Self-Improving LLM Reasoning"**  
  *Zhuang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.17399)]
- **"AutoAgent: Evolving Cognition and Elastic Memory Orchestration for Adaptive Agents"**  
  *Wang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.09716)]
- **"Harnessing Pre-Resolution Signals for Future Prediction Agents"**  
  *Wei et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.15719)]
- **"ContraPrompt: Contrastive Prompt Optimization via Dyadic Reasoning Trace Analysis"**  
  *Rishav et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.17937)]
- **"AEL: Agent Evolving Learning for Open-Ended Environments"**  
  *Xu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.21725)]
- **"Discovering Agentic Safety Specifications from 1-Bit Danger Signals"**  
  *Gallego* ALA Workshop @ AAMAS 2026. [[paper](https://arxiv.org/abs/2604.23210)]
- **"EvoMaster: A Foundational Evolving Agent Framework for Agentic Science at Scale"**  
  *Zhu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.17406)]
- **"Can AI Scientist Agents Learn from Lab-in-the-Loop Feedback? Evidence from Iterative Perturbation Discovery"**  
  *Wainrib et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.26177)]
- **"STELLA: Self-Evolving LLM Agent for Biomedical Research"**  
  *Jin et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2507.02004)]
- **"Agent-Pro: Learning to Evolve via Policy-Level Reflection and Optimization"**  
  *Zhang et al.* ACL 2024. [[paper](https://arxiv.org/abs/2402.17574)]
- **"Reflexion: Language Agents with Verbal Reinforcement Learning"**  
  *Shinn et al.* NeurIPS 2023. [[paper](https://arxiv.org/abs/2303.11366)]

#### Configurations & architectures

- **"Evolving Interpretable Constitutions for Multi-Agent Coordination"**  
  *Kumar et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.00755)]
- **"SkillMOO: Multi-Objective Optimization of Agent Skills for Software Engineering"**  
  *Gong et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.09297)]
- **"Co-evolving Agent Architectures and Interpretable Reasoning for Automated Optimization"**  
  *Huang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.17708)]
- **"A Self-Evolving Agentic Framework for Metasurface Inverse Design"**  
  *Huang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.01480)]
- **"Prompt Optimization Enables Stable Algorithmic Collusion in LLM Agents"**  
  *Tian* arXiv 2026. [[paper](https://arxiv.org/abs/2604.17774)]
- **"MEMO: Memory-Augmented Model Context Optimization for Robust Multi-Turn Multi-Agent LLM Games"**  
  *Xie et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.09022)]
- **"EvoAgent: Towards Automatic Multi-Agent Generation via Evolutionary Algorithms"**  
  *Yuan et al.* NAACL 2025. [[paper](https://arxiv.org/abs/2406.14228)]
- **"Evolving Excellence: Automated Optimization of LLM-based Agents"**  
  *Brookes et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2512.09108)]

#### Code-level

- **"Meta-Harness: End-to-End Optimization of Model Harnesses"**  
  *Lee et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.28052)]
- **"M★: Every Task Deserves Its Own Memory Harness"**  
  *Pan et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.11811)]
- **"AgentDevel: Reframing Self-Evolving LLM Agents as Release Engineering"**  
  *Zhang* arXiv 2026. [[paper](https://arxiv.org/abs/2601.04620)]
- **"Autogenesis: A Self-Evolving Agent Protocol"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.15034)]
- **"Automated Design of Agentic Systems"**  
  *Hu et al.* ICLR 2025. [[paper](https://arxiv.org/abs/2408.08435)]
- **"A Self-Improving Coding Agent"**  
  *Robeyns et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2504.15228)]
- **"Darwin Gödel Machine: Open-Ended Evolution of Self-Improving Agents"**  
  *Zhang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2505.22954)]
- **"Symbolic Learning Enables Self-Evolving Agents"**  
  *Zhou et al.* AI Open 2025. [[paper](https://arxiv.org/abs/2406.18532)]

#### Multi-agent structural

- **"LangMARL: Natural Language Multi-Agent Reinforcement Learning"**  
  *Yao et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.00722)]
- **"Learning to Evolve: A Self-Improving Framework for Multi-Agent Systems via Textual Parameter Graph Optimization"**  
  *He et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.20714)]
- **"EvoFSM: Controllable Self-Evolution for Deep Research with Finite State Machines"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2601.09465)]

### Δ, H≠0 (Structural, Human-involved)

- **"Prompt Optimization with Human Feedback"**  
  *Lin et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2405.17346)]

### ∇, H=0 (Parametric, Autonomous)

#### Iterative self-improvement

- **"ReMiT: RL-Guided Mid-Training for Iterative LLM Evolution"**  
  *Huang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.03075)]
- **"Agentic Critical Training"**  
  *Liu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.08706)]
- **"SKILL0: In-Context Agentic Reinforcement Learning for Skill Internalization"**  
  *Lu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.02268)]
- **"RLAD: Training LLMs to Discover Abstractions for Solving Reasoning Problems"**  
  *Qu et al.* ICLR 2026. [[paper](https://arxiv.org/abs/2510.02263)]
- **"Expanding the Capabilities of Reinforcement Learning via Text Feedback"**  
  *Song et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.02482)]
- **"Temporal Self-Rewarding Language Models: Decoupling Chosen-Rejected via Past-Future"**  
  *Wang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2508.06026)]
- **"Process-based Self-Rewarding Language Models"**  
  *Zhang et al.* Findings of ACL 2025. [[paper](https://arxiv.org/abs/2503.03746)]
- **"Language Models that Think, Chat Better"**  
  *Bhaskar et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2509.20357)]
- **"The Art of Scaling Reinforcement Learning Compute for LLMs"**  
  *Khatri et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2510.13786)]
- **"Learning on the Job: Test-Time Curricula for Targeted Reinforcement Learning"**  
  *Hübotter et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2510.04786)]
- **"SeRL: Self-Play Reinforcement Learning for Large Language Models with Limited Data"**  
  *Fang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2505.20347)]
- **"Co-Alignment: Rethinking Alignment as Bidirectional Human-AI Cognitive Adaptation"**  
  *Li et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2509.12179)]
- **"Self-Rewarding Language Models"**  
  *Yuan et al.* ICML 2024. [[paper](https://arxiv.org/abs/2401.10020)]
- **"STaR: Bootstrapping Reasoning With Reasoning"**  
  *Zelikman et al.* NeurIPS 2022. [[paper](https://arxiv.org/abs/2203.14465)]

#### Multi-role self-play

- **"SAGE: Multi-Agent Self-Evolution for LLM Reasoning"**  
  *Peng et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.15255)]
- **"MM-Zero: Self-Evolving Multi-Model Vision Language Models From Zero Data"**  
  *Li et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.09206)]
- **"SpatialEvo: Self-Evolving Spatial Intelligence via Deterministic Geometric Environments"**  
  *Li et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.14144)]
- **"One Model, All Roles: Multi-Turn, Multi-Agent Self-Play Reinforcement Learning for Conversational Social Intelligence"**  
  *Jiang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.03109)]
- **"SPIRAL: Self-Play on Zero-Sum Games Incentivizes Reasoning via Multi-Agent Multi-Turn Reinforcement Learning"**  
  *Liu et al.* ICLR 2026. [[paper](https://arxiv.org/abs/2506.24119)]
- **"Conversation for Non-verifiable Learning: Self-Evolving LLMs through Meta-Evaluation"**  
  *Sui et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2601.21464)]
- **"Vision-Zero: Scalable VLM Self-Evolution via Multi-Agent Self-Play"**  
  *Wang et al.* ICLR 2026. [[paper](https://arxiv.org/abs/2509.25541)]
- **"Dr. Zero: Self-Evolving Search Agents without Training Data"**  
  *Yue et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2601.07055)]
- **"The Alignment Waltz: Jointly Training Agents to Collaborate for Safety"**  
  *Zhang et al.* ICLR 2026. [[paper](https://arxiv.org/abs/2510.08240)]
- **"SELF-EMO: Emotional Self-Evolution from Recognition to Consistent Expression"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.18003)]
- **"Multi-Agent Evolve: LLM Self-Improve through Co-evolution"**  
  *Chen et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2510.23595)]
- **"R-Zero: Self-Evolving Reasoning LLM from Zero Data"**  
  *Huang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2508.05004)]
- **"MARS: Co-evolving Dual-System Deep Research via Multi-Agent Reinforcement Learning"**  
  *Chen et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2510.04935)]
- **"CoMAS: Co-Evolving Multi-Agent Systems via Interaction Rewards"**  
  *Xue et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2510.08529)]
- **"MARSHAL: Incentivizing Multi-Agent Reasoning via Self-Play with Strategic LLMs"**  
  *Yuan et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2510.15414)]
- **"Toward Training Superintelligent Software Agents through Self-Play SWE-RL"**  
  *Wei et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2512.18552)]
- **"Absolute Zero: Reinforced Self-play Reasoning with Zero Data"**  
  *Zhao et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2505.03335)]
- **"Agent0: Unleashing Self-Evolving Agents from Zero Data via Tool-Integrated Reasoning"**  
  *Xia et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2511.16043)]

#### Adversarial auditing

- **"Adversarial Reward Auditing for Active Detection and Mitigation of Reward Hacking"**  
  *Beigi et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.01750)]

#### Data synthesis & self-training

- **"AgentFrontier: Expanding the Capability Frontier of LLM Agents with ZPD-Guided Data Synthesis"**  
  *Chen et al.* ICLR 2026. [[paper](https://arxiv.org/abs/2510.24695)]
- **"Diving into Self-Evolving Training for Multimodal Reasoning"**  
  *Liu et al.* ICML 2025. [[paper](https://arxiv.org/abs/2412.17451)]
- **"MMEvol: Empowering Multimodal Large Language Models with Evol-Instruct"**  
  *Luo et al.* Findings of ACL 2025. [[paper](https://doi.org/10.18653/v1/2025.findings-acl.1009)]
- **"Skill-Targeted Adaptive Training"**  
  *He et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2510.10023)]
- **"ALAS: Autonomous Learning Agent for Self-Updating Language Models"**  
  *Atreja* arXiv 2025. [[paper](https://arxiv.org/abs/2508.15805)]
- **"NExT: Teaching Large Language Models to Reason about Code Execution"**  
  *Ni et al.* ICML 2024. [[paper](https://arxiv.org/abs/2404.14662)]

#### Tool-integrated

- **"SEARL: Joint Optimization of Policy and Tool Graph Memory for Self-Evolving Agents"**  
  *Feng et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.07791)]
- **"Computer Environments Elicit General Agentic Intelligence in LLMs"**  
  *Cheng et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2601.16206)]
- **"GrandCode: Achieving Grandmaster Level in Competitive Programming via Agentic Reinforcement Learning"**  
  *Li et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.02721)]
- **"TRACE: Capability-Targeted Agentic Training"**  
  *Kang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.05336)]
- **"Tool-Star: Empowering LLM-Brained Multi-Tool Reasoner via Reinforcement Learning"**  
  *Dong et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2505.16410)]
- **"ReTool: Reinforcement Learning for Strategic Tool Use in LLMs"**  
  *Feng et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2504.11536)]
- **"VerlTool: Towards Holistic Agentic Reinforcement Learning with Tool Use"**  
  *Jiang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2509.01055)]
- **"ToolRL: Reward is All Tool Learning Needs"**  
  *Qian et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2504.13958)]
- **"START: Self-taught Reasoner with Tools"**  
  *Li et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2503.04625)]
- **"rStar2-Agent: Agentic Reasoning Technical Report"**  
  *Shang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2508.20722)]
- **"Nemotron-Research-Tool-N1: Exploring Tool-Using Language Models with Reinforced Reasoning"**  
  *Zhang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2505.00024)]
- **"Tool-R1: Sample-Efficient Reinforcement Learning for Agentic Tool Use"**  
  *Zhang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2509.12867)]
- **"ACECODER: Acing Coder RL via Automated Test-Case Synthesis"**  
  *Zeng et al.* ACL 2025. [[paper](https://arxiv.org/abs/2502.01718)]
- **"One Tool Is Enough: Reinforcement Learning for Repository-Level LLM Agents"**  
  *Zhang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2512.20957)]
- **"ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs"**  
  *Qin et al.* ICLR 2024. [[paper](https://arxiv.org/abs/2307.16789)]
- **"ToRA: A Tool-Integrated Reasoning Agent for Mathematical Problem Solving"**  
  *Gou et al.* ICLR 2024. [[paper](https://arxiv.org/abs/2309.17452)]
- **"StepCoder: Improving Code Generation with Reinforcement Learning from Compiler Feedback"**  
  *Dou et al.* ACL 2024. [[paper](https://arxiv.org/abs/2402.01391)]

#### Interactive environments

- **"Safe and Scalable Web Agent Learning via Recreated Websites"**  
  *Chae et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.10505)]
- **"UI-Voyager: A Self-Evolving GUI Agent Learning via Failed Experience"**  
  *Lin et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.24533)]
- **"Agent-World: Scaling Real-World Environment Synthesis for Evolving General Agent Intelligence"**  
  *Dong et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.18292)]
- **"Learn the Ropes, Then Trust the Wins: Self-imitation with Progressive Exploration for Agentic Reinforcement Learning"**  
  *Qin et al.* ICLR 2026. [[paper](https://arxiv.org/abs/2509.22601)]
- **"Ask Only When Needed: Proactive Retrieval from Memory and Skills for Experience-Driven Lifelong Agents"**  
  *Cai et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.20572)]
- **"CLEAR: Context Augmentation from Contrastive Learning of Experience via Agentic Reflection"**  
  *Liu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.07487)]
- **"WebEvolver: Enhancing Web Agent Self-Improvement with Co-evolving World Model"**  
  *Fang et al.* EMNLP 2025. [[paper](https://arxiv.org/abs/2504.21024)]
- **"WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum Reinforcement Learning"**  
  *Qi et al.* ICLR 2025. [[paper](https://arxiv.org/abs/2411.02337)]
- **"Reinforcement Learning for Long-Horizon Interactive LLM Agents"**  
  *Chen et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2502.01600)]

#### Multi-turn RL

- **"RAGEN-2: Reasoning Collapse in Agentic RL"**  
  *Wang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.06268)]
- **"Does RL Expand the Capability Boundary of LLM Agents? A PASS@(k,T) Analysis"**  
  *Zhai et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.14877)]
- **"On Information Self-Locking in Reinforcement Learning for Active Reasoning of LLM Agents"**  
  *Zou et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.12109)]
- **"When Reward Hacking Rebounds: Understanding and Mitigating It with Representation-Level Signals"**  
  *Wu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.01476)]
- **"Accordion-Thinking: Self-Regulated Step Summaries for Efficient and Readable LLM Reasoning"**  
  *Yang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.03249)]
- **"MemoBrain: Executive Memory as an Agentic Brain for Reasoning"**  
  *Qian et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2601.08079)]
- **"A Practitioner's Guide to Multi-turn Agentic Reinforcement Learning"**  
  *Wang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2510.01132)]
- **"RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning"**  
  *Wang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2504.20073)]
- **"WebAgent-R1: Training Web Agents via End-to-End Multi-Turn Reinforcement Learning"**  
  *Wei et al.* EMNLP 2025. [[paper](https://arxiv.org/abs/2505.16421)]
- **"AgentGym-RL: Training LLM Agents for Long-Horizon Decision Making through Multi-Turn Reinforcement Learning"**  
  *Xi et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2509.08755)]
- **"MemAgent: Reshaping Long-Context LLM with Multi-Conv RL-based Memory Agent"**  
  *Yu et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2507.02259)]
- **"MEM1: Learning to Synergize Memory and Reasoning for Efficient Long-Horizon Agents"**  
  *Zhou et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2506.15841)]
- **"CollabLLM: From Passive Responders to Active Collaborators"**  
  *Wu et al.* ICML 2025. [[paper](https://arxiv.org/abs/2502.00640)]
- **"AgentGym: Evolving Large Language Model-based Agents across Diverse Environments"**  
  *Xi et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2406.04151)]

#### Continual/personalized

- **"SPRInG: Continual LLM Personalization via Selective Parametric Adaptation and Retrieval-Interpolated Generation"**  
  *Kim et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2601.09974)]
- **"PersonaVLM: Long-Term Personalized Multimodal LLMs"**  
  *Nie et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.13074)]
- **"Simple Recipe Works: Vision-Language-Action Models are Natural Continual Learners with Reinforcement Learning"**  
  *Hu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.11653)]
- **"PersonaMem-v2: Towards Personalized Intelligence via Learning Implicit User Personas and Agentic Memory"**  
  *Jiang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2512.06688)]
- **"Fed-SE: Federated Self-Evolution for Cross-Environment Knowledge Transfer in Privacy-Constrained LLM Agents"**  
  *Chen et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2512.08870)]
- **"Self-Updatable Large Language Models by Integrating Context into Model Parameters"**  
  *Wang et al.* ICLR 2025. [[paper](https://arxiv.org/abs/2410.00487)]

#### Multi-LLM collaborative

- **"ATLAS: A Multi-LLM Training Framework for EvoDPO with Adaptive Reference Evolution"**  
  *Jeon et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.02709)]
- **"CoLa: Learning to Interactively Collaborate with Large Language Models"**  
  *Sharma et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2504.02965)]
- **"AutoFlow: Automated Workflow Generation for Large Language Model Agents"**  
  *Li et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2407.12821)]

#### Meta-learning

- **"End-to-End Test-Time Training for Long Context"**  
  *Tandon et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2512.23675)]
- **"Self-Adapting Language Models"**  
  *Zweiger et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2506.10943)]

#### Neuroevolutionary hybrid

- **"Discovering Novel LLM Experts via Task-Capability Coevolution"**  
  *Dai et al.* ICLR 2026. [[paper](https://arxiv.org/abs/2604.14969)]
- **"Evolutionary Policy Optimization"**  
  *Wang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2503.19037)]

#### Domain-specific

- **"EVA: Efficient Reinforcement Learning for End-to-End Video Agent"**  
  *Zhang et al.* CVPR 2026. [[paper](https://arxiv.org/abs/2603.22918)]
- **"FlowSteer: Towards Agents Designing Agentic Workflows via Reinforced Progressive Canvas Editing"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.01664)]
- **"Co-Evolution of Policy and Internal Reward for Language Agents"**  
  *Wang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.03098)]
- **"FinEvo: From Isolated Backtests to Ecological Market Games for Multi-Agent Financial Strategy Evolution"**  
  *Zou et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.00948)]
- **"Meta-Reinforcement Learning with Self-Reflection for Agentic Search"**  
  *Xiao et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.11327)]
- **"MAS-GPT: Training LLMs to Build LLM-based Multi-Agent Systems"**  
  *Ye et al.* ICML 2025. [[paper](https://arxiv.org/abs/2503.03686)]
- **"Automated Skill Discovery for Language Agents through Exploration and Iterative Feedback"**  
  *Yang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2506.04287)]
- **"π0: A Vision-Language-Action Flow Model for General Robot Control"**  
  *Black et al.* RSS 2025. [[paper](https://arxiv.org/abs/2410.24164)]
- **"Towards Agentic Self-Learning LLMs in Search Environment"**  
  *Sun et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2510.14253)]
- **"Scaling Agent Learning via Experience Synthesis"**  
  *Chen et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2511.03773)]
- **"OMNI: Open-endedness via Models of human Notions of Interestingness"**  
  *Zhang et al.* ICLR 2024. [[paper](https://arxiv.org/abs/2306.01711)]
- **"Agent Lumos: Unified and Modular Training for Open-Source Language Agents"**  
  *Yin et al.* ACL 2024. [[paper](https://arxiv.org/abs/2311.05657)]
- **"Open-Ended Learning Leads to Generally Capable Agents"**  
  *Team et al.* arXiv 2021. [[paper](https://arxiv.org/abs/2107.12808)]

#### World-model-based

- **"Mastering Diverse Control Tasks through World Models"**  
  *Hafner et al.* Nature 2025. [[paper](https://doi.org/10.1038/s41586-025-08744-2)]
- **"EvolvingAgent: Curriculum Self-evolving Agent with Continual World Model for Long-Horizon Tasks"**  
  *Feng et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2502.05907)]
- **"Recurrent World Models Facilitate Policy Evolution"**  
  *Ha et al.* NeurIPS 2018. [[paper](https://arxiv.org/abs/1809.01999)]

### ∇, H≠0 (Parametric, Human-involved)

- **"Learning to Summarize User Information for Personalized Reinforcement Learning from Human Feedback"**  
  *Nam et al.* ICLR 2026. [[paper](https://arxiv.org/abs/2507.13579)]
- **"Pioneer Agent: Continual Improvement of Small Language Models in Production"**  
  *Atreja et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.09791)]
- **"Reinforced Interactive Continual Learning via Real-time Noisy Human Feedback"**  
  *Yang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2505.09925)]
- **"Personalized Language Modeling from Personalized Human Feedback"**  
  *Li et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2402.05133)]
- **"Improving Multimodal Interactive Agents with Reinforcement Learning from Human Feedback"**  
  *Abramson et al.* arXiv 2022. [[paper](https://arxiv.org/abs/2211.11602)]
- **"Interactive Learning from Policy-Dependent Human Feedback"**  
  *MacGlashan et al.* ICML 2017. [[paper](https://arxiv.org/abs/1701.06049)]
- **"Learning Preferences for Manipulation Tasks from Online Coactive Feedback"**  
  *Jain et al.* The International Journal of Robotics Research 2015. [[paper](https://arxiv.org/abs/1601.00741)]
- **"Coactive Learning"**  
  *Shivaswamy et al.* Journal of Artificial Intelligence Research 2015. [[paper](https://arxiv.org/abs/1205.4213)]

### Δ+∇, H=0 (Hybrid, Autonomous)

#### Experience consolidation

- **"Memory Intelligence Agent"**  
  *Qiao et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.04503)]
- **"Experiential Reinforcement Learning"**  
  *Shi et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.13949)]
- **"VERDICT: Verifiable Evolving Reasoning with Directive-Informed Collegial Teams for Legal Judgment Prediction"**  
  *Liao et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.19306)]
- **"Evaluation-driven Scaling for Scientific Discovery"**  
  *Ye et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.19341)]
- **"DeltaMem: Towards Agentic Memory Management via Reinforcement Learning"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.01560)]
- **"Self-Consolidation for Self-Evolving Agents"**  
  *Yu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.01966)]
- **"Youtu-Agent: Scaling Agent Productivity with Automated Generation and Hybrid Policy Optimization"**  
  *Shi et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2512.24615)]

#### Jointly evolving auxiliary structures

- **"SkillRL: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning"**  
  *Xia et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.08234)]
- **"SLEA-RL: Step-Level Experience Augmented Reinforcement Learning for Multi-Turn Agentic Training"**  
  *Wang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.18079)]
- **"CoEvolve: Training LLM Agents via Agent-Data Mutual Evolution"**  
  *Yang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.15840)]
- **"RetroAgent: From Solving to Evolving via Retrospective Dual Intrinsic Feedback"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.08561)]
- **"Evolutionary System Prompt Learning for Reinforcement Learning in LLMs"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.14697)]
- **"SkillOS: Learning Skill Curation for Self-Evolving Agents"**  
  *Ouyang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2605.06614)]
- **"SecureCAI: Injection-Resilient LLM Assistants for Cybersecurity Operations"**  
  *Ali et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2601.07835)]
- **"SEVerA: Verified Self-Evolving Agents"**  
  *Banerjee et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.25111)]
- **"SkillGraph: Self-Evolving Multi-Agent Collaboration with Multimodal Graph Topology"**  
  *Nie et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.17503)]
- **"EvolveRouter: Co-Evolving Routing and Prompt for Multi-Agent Question Answering"**  
  *Huang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.05149)]
- **"AgenticGEO: A Self-Evolving Agentic System for Generative Engine Optimization"**  
  *Yuan et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.20213)]
- **"HELIX: Evolutionary Reinforcement Learning for Open-Ended Scientific Problem Solving"**  
  *Su et al.* ICLR 2026. [[paper](https://arxiv.org/abs/2603.07642)]
- **"Reinforcement Learning for Self-Improving Agent with Skill Library"**  
  *Wang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2512.17102)]
- **"EvolveR: Self-Evolving LLM Agents through an Experience-Driven Lifecycle"**  
  *Wu et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2510.16079)]
- **"AgentEvolver: Towards Efficient Self-Evolving Agent System"**  
  *Zhai et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2511.10395)]
- **"EvolveSearch: An Iterative Self-Evolving Search Agent"**  
  *Zhang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2505.22501)]
- **"Agentic Policy Optimization via Instruction-Policy Co-Evolution"**  
  *Zhou et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2512.01945)]
- **"InfiAgent: Self-Evolving Pyramid Agent Framework for Infinite Scenarios"**  
  *Yu et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2509.22502)]

#### Memory/planning joint evolution

- **"PsychAgent: An Experience-Driven Lifelong Learning Agent for Self-Evolving Psychological Counselor"**  
  *Yang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.00931)]
- **"Co-Evolving LLM Decision and Skill Bank Agents for Long-Horizon Tasks"**  
  *Wu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.20987)]
- **"S1-NexusAgent: a Self-Evolving Agent Framework for Multidisciplinary Scientific Research"**  
  *Team* arXiv 2026. [[paper](https://arxiv.org/abs/2602.01550)]
- **"Training LLM Agents for Spontaneous, Reward-Free Self-Evolution via World Knowledge Exploration"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.18131)]
- **"Memory-R1: Enhancing Large Language Model Agents to Manage and Utilize Memories via Reinforcement Learning"**  
  *Yan et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2508.19828)]

## Action (A) Evolution

### Δ, H=0 (Structural, Autonomous)

#### Tools & skills

- **"Optimizing Agentic Workflows using Meta-tools"**  
  *Abuzakuk et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2601.22037)]
- **"Mem^2Evolve: Towards Self-Evolving Agents via Co-Evolutionary Capability Expansion and Experience Distillation"**  
  *Cheng et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.10923)]
- **"Yunjue Agent Tech Report: A Fully Reproducible, Zero-Start In-Situ Self-Evolving Agent System for Open-Ended Tasks"**  
  *Li et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2601.18226)]
- **"RefTool: Reference-Guided Tool Creation for Knowledge-Intensive Reasoning"**  
  *Liu et al.* ICLR 2026. [[paper](https://arxiv.org/abs/2505.21413)]
- **"OpenGame: Open Agentic Coding for Games"**  
  *Jiang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.18394)]
- **"GenericAgent: A Token-Efficient Self-Evolving LLM Agent via Contextual Information Density Maximization (V1.0)"**  
  *Liang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.17091)]
- **"SkillForge: Forging Domain-Specific, Self-Evolving Agent Skills in Cloud Technical Support"**  
  *Liu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.08618)]
- **"Memento-Skills: Let Agents Design Agents"**  
  *Zhou et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.18743)]
- **"CORAL: Towards Autonomous Multi-Agent Evolution for Open-Ended Discovery"**  
  *Qu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.01658)]
- **"SKILLFOUNDRY: Building Self-Evolving Agent Skill Libraries from Heterogeneous Scientific Resources"**  
  *Shen et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.03964)]
- **"Evolving from Tool User to Creator via Training-Free Experience Reuse in Multimodal Reasoning"**  
  *Shen et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.01983)]
- **"SkillX: Automatically Constructing Skill Knowledge Bases for Agents"**  
  *Wang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.04804)]
- **"El Agente Forjador: Task-Driven Agent Generation for Quantum Simulation"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.14609)]
- **"AgentFactory: A Self-Evolving Framework Through Executable Subagent Accumulation and Reuse"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.18000)]
- **"CoEvoSkills: Self-Evolving Agent Skills via Co-Evolutionary Verification"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.01687)]
- **"STELLA: Self-Evolving LLM Agent for Biomedical Research"**  
  *Jin et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2507.02004)]
- **"From Exploration to Mastery: Enabling LLMs to Master Tools via Self-Driven Interactions"**  
  *Qu et al.* ICLR 2025. [[paper](https://arxiv.org/abs/2410.08197)]
- **"Alita: Generalist Agent Enabling Scalable Agentic Reasoning with Minimal Predefinition and Maximal Self-Evolution"**  
  *Qiu et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2505.20286)]
- **"Alita-G: Self-Evolving Generative Agent for Agent Generation"**  
  *Qiu et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2510.23601)]
- **"Voyager: An Open-Ended Embodied Agent with Large Language Models"**  
  *Wang et al.* TMLR 2024. [[paper](https://arxiv.org/abs/2305.16291)]

#### Program search

- **"AVO: Agentic Variation Operators for Autonomous Evolutionary Search"**  
  *Chen et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.24517)]
- **"PathWise: Planning through World Model for Automated Heuristic Design via Self-Evolving LLMs"**  
  *Gungordu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2601.20539)]
- **"AIRA_2: Overcoming Bottlenecks in AI Research Agents"**  
  *Hambardzumyan et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.26499)]
- **"Digital Red Queen: Adversarial Program Evolution in Core War with LLMs"**  
  *Kumar et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2601.03335)]
- **"OR-Agent: Bridging Evolutionary Search and Structured Research for Automated Algorithm Discovery"**  
  *Liu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.13769)]
- **"AdaptEvolve: Improving Efficiency of Evolutionary AI Agents through Adaptive Model Selection"**  
  *Ray et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.11931)]
- **"Evaluation-driven Scaling for Scientific Discovery"**  
  *Ye et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.19341)]
- **"AutoRISE: Agent-Driven Strategy Evolution for Red-Teaming Large Language Models"**  
  *Gautam et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.22871)]
- **"AlphaEvolve: A Coding Agent for Scientific and Algorithmic Discovery"**  
  *Novikov et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2506.13131)]
- **"AccelOpt: A Self-Improving LLM Agentic System for AI Accelerator Kernel Optimization"**  
  *Zhang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2511.15915)]
- **"Mathematical Discoveries from Program Search with Large Language Models"**  
  *Romera-Paredes et al.* Nature 2024. [[paper](https://doi.org/10.1038/s41586-023-06924-6)]
- **"Evolution through Large Models"**  
  *Lehman et al.* arXiv 2022. [[paper](https://arxiv.org/abs/2206.08896)]

#### Workflow & orchestration

- **"Learning to Evolve: A Self-Improving Framework for Multi-Agent Systems via Textual Parameter Graph Optimization"**  
  *He et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.20714)]
- **"Co-evolving Agent Architectures and Interpretable Reasoning for Automated Optimization"**  
  *Huang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.17708)]
- **"Meta-Harness: End-to-End Optimization of Model Harnesses"**  
  *Lee et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.28052)]
- **"Agentic Harness Engineering: Observability-Driven Automatic Evolution of Coding-Agent Harnesses"**  
  *Lin et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.25850)]
- **"Experience as a Compass: Multi-agent RAG with Evolving Orchestration and Agent Prompts"**  
  *Li et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.00901)]
- **"HyEvo: Self-Evolving Hybrid Agentic Workflows for Efficient Reasoning"**  
  *Xu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.19639)]
- **"Autogenesis: A Self-Evolving Agent Protocol"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.15034)]
- **"EvoFSM: Controllable Self-Evolution for Deep Research with Finite State Machines"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2601.09465)]
- **"Automated Design of Agentic Systems"**  
  *Hu et al.* ICLR 2025. [[paper](https://arxiv.org/abs/2408.08435)]
- **"SwarmSys: Decentralized Swarm-Inspired Agents for Scalable and Adaptive Reasoning"**  
  *Li et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2510.10047)]
- **"AFlow: Automating Agentic Workflow Generation"**  
  *Zhang et al.* ICLR 2025. [[paper](https://arxiv.org/abs/2410.10762)]
- **"Symbolic Learning Enables Self-Evolving Agents"**  
  *Zhou et al.* AI Open 2025. [[paper](https://arxiv.org/abs/2406.18532)]

#### Whole-system

- **"AutoAgent: Evolving Cognition and Elastic Memory Orchestration for Adaptive Agents"**  
  *Wang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.09716)]
- **"Group-Evolving Agents: Open-Ended Self-Improvement via Experience Sharing"**  
  *Weng et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.04837)]
- **"ASI-Evolve: AI Accelerates AI"**  
  *Xu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.29640)]
- **"Learning to Continually Learn via Meta-learning Agentic Memory Designs"**  
  *Xiong et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.07755)]
- **"AgentDevel: Reframing Self-Evolving LLM Agents as Release Engineering"**  
  *Zhang* arXiv 2026. [[paper](https://arxiv.org/abs/2601.04620)]
- **"A Self-Improving Coding Agent"**  
  *Robeyns et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2504.15228)]
- **"Darwin Gödel Machine: Open-Ended Evolution of Self-Improving Agents"**  
  *Zhang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2505.22954)]

#### Domain-specific

- **"Autonomous Evolution of EDA Tools: Multi-Agent Self-Evolved ABC"**  
  *Yu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.15082)]
- **"Self-Evolving Recommendation System: End-To-End Autonomous Model Optimization With LLM Agents"**  
  *Wang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.10226)]

#### Configuration

- **"JTPRO: A Joint Tool-Prompt Reflective Optimization Framework for Language Agents"**  
  *Ghoshal et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.19821)]
- **"Symphony-Coord: Emergent Coordination in Decentralized Agent Systems"**  
  *Guan et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.00966)]
- **"Evolving Excellence: Automated Optimization of LLM-based Agents"**  
  *Brookes et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2512.09108)]

#### Framework & analysis

- **"Position: Agentic Evolution is the Path to Evolving LLMs"**  
  *Lin et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.00359)]
- **"Understanding the Challenges in Iterative Generative Optimization with LLMs"**  
  *Nie et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.23994)]

### Δ, H≠0 (Structural, Human-involved)

#### Tools & skills

- **"SkillClaw: Let Skills Evolve Collectively with Agentic Evolver"**  
  *Ma et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.08377)]
- **"EvoAgent: An Evolvable Agent Framework with Skill Learning and Multi-Agent Delegation"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.20133)]
- **"Leveraging LLMs for Dynamic IoT Systems Generation through Mixed-Initiative Interaction"**  
  *Adnan et al.* ICSA-C 2025. [[paper](https://arxiv.org/abs/2502.00689)]
- **"Democratizing AI scientists using ToolUniverse"**  
  *Gao et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2509.23426)]

### ∇, H=0 (Parametric, Autonomous)

- **"Agent Q-Mix: Selecting the Right Action for LLM Multi-Agent Systems through Reinforcement Learning"**  
  *Jiang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.00344)]
- **"π0: A Vision-Language-Action Flow Model for General Robot Control"**  
  *Black et al.* RSS 2025. [[paper](https://arxiv.org/abs/2410.24164)]
- **"RouteLLM: Learning to Route LLMs with Preference Data"**  
  *Ong et al.* ICLR 2025. [[paper](https://arxiv.org/abs/2406.18665)]

### Δ+∇, H=0 (Hybrid, Autonomous)

- **"SEVerA: Verified Self-Evolving Agents"**  
  *Banerjee et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.25111)]
- **"Agent-World: Scaling Real-World Environment Synthesis for Evolving General Agent Intelligence"**  
  *Dong et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.18292)]
- **"SEARL: Joint Optimization of Policy and Tool Graph Memory for Self-Evolving Agents"**  
  *Feng et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.07791)]
- **"EvolveRouter: Co-Evolving Routing and Prompt for Multi-Agent Question Answering"**  
  *Huang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.05149)]
- **"SkillGraph: Self-Evolving Multi-Agent Collaboration with Multimodal Graph Topology"**  
  *Nie et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.17503)]
- **"HELIX: Evolutionary Reinforcement Learning for Open-Ended Scientific Problem Solving"**  
  *Su et al.* ICLR 2026. [[paper](https://arxiv.org/abs/2603.07642)]
- **"Co-Evolving LLM Decision and Skill Bank Agents for Long-Horizon Tasks"**  
  *Wu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.20987)]
- **"SkillOS: Learning Skill Curation for Self-Evolving Agents"**  
  *Ouyang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2605.06614)]
- **"Reinforcement Learning for Self-Improving Agent with Skill Library"**  
  *Wang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2512.17102)]
- **"InfiAgent: Self-Evolving Pyramid Agent Framework for Infinite Scenarios"**  
  *Yu et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2509.22502)]
- **"AutoFlow: Automated Workflow Generation for Large Language Model Agents"**  
  *Li et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2407.12821)]

## Memory & Sense (M) Evolution

### Δ, H=0 (Structural, Autonomous)

#### Accumulation:Task-oriented

- **"AnalogAgent: Self-Improving Analog Circuit Design Automation with LLM Agents"**  
  *Bao et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.23910)]
- **"Mem^2Evolve: Towards Self-Evolving Agents via Co-Evolutionary Capability Expansion and Experience Distillation"**  
  *Cheng et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.10923)]
- **"KernelBlaster: Continual Cross-Task CUDA Optimization via Memory-Augmented In-Context Reinforcement Learning"**  
  *Dong et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.14293)]
- **"Dr. RTL: Autonomous Agentic RTL Optimization through Tool-Grounded Self-Improvement"**  
  *Fang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.14989)]
- **"AutoRISE: Agent-Driven Strategy Evolution for Red-Teaming Large Language Models"**  
  *Gautam et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.22871)]
- **"OpenGame: Open Agentic Coding for Games"**  
  *Jiang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.18394)]
- **"Memory Transfer Learning: How Memories are Transferred Across Domains in Coding Agents"**  
  *Kim et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.14004)]
- **"Experience Transfer for Multimodal LLM Agents in Minecraft Game"**  
  *Li et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.05533)]
- **"Experience as a Compass: Multi-agent RAG with Evolving Orchestration and Agent Prompts"**  
  *Li et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.00901)]
- **"Just-In-Time Reinforcement Learning: Continual Learning in LLM Agents Without Gradient Updates"**  
  *Li et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2601.18510)]
- **"Learning to Commit: Generating Organic Pull Requests via Online Repository Memory"**  
  *Li et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.26664)]
- **"Towards Self-Improving Error Diagnosis in Multi-Agent Systems"**  
  *Li et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.17658)]
- **"GenericAgent: A Token-Efficient Self-Evolving LLM Agent via Contextual Information Density Maximization (V1.0)"**  
  *Liang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.17091)]
- **"Position: Agentic Evolution is the Path to Evolving LLMs"**  
  *Lin et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.00359)]
- **"EvoScientist: Towards Multi-Agent Evolving AI Scientists for End-to-End Scientific Discovery"**  
  *Lyu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.08127)]
- **"ReasoningBank: Scaling Agent Self-Evolving with Reasoning Memory"**  
  *Ouyang et al.* ICLR 2026. [[paper](https://arxiv.org/abs/2509.25140)]
- **"MAPLE: Multi-Agent Adaptive Planning with Long-Term Memory for Table Reasoning"**  
  *Bai et al.* ALTA 2025. [[paper](https://arxiv.org/abs/2506.05813)]
- **"Building Self-Evolving Agents via Experience-Driven Lifelong Learning: A Framework and Benchmark"**  
  *Cai et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2508.19005)]
- **"FLEX: Continuous Agent Evolution via Forward Learning from Experience"**  
  *Cai et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2511.06449)]
- **"Remember Me, Refine Me: A Dynamic Procedural Memory Framework for Experience-Driven Agent Evolution"**  
  *Cao et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2512.10696)]
- **"MDTeamGPT: A Self-Evolving LLM-based Multi-Agent Framework for Multi-Disciplinary Team Medical Consultation"**  
  *Chen et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2503.13856)]
- **"Memp: Exploring Agent Procedural Memory"**  
  *Fang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2508.06433)]
- **"Self-Generated In-Context Examples Improve LLM Agents for Sequential Decision-Making Tasks"**  
  *Sarukkai et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2505.00234)]
- **"Agent Workflow Memory"**  
  *Wang et al.* ICML 2025. [[paper](https://arxiv.org/abs/2409.07429)]
- **"Evo-Memory: Benchmarking LLM Agent Test-time Learning with Self-Evolving Memory"**  
  *Wei et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2511.20857)]
- **"Agent Hospital: A Simulacrum of Hospital with Evolvable Medical Agents"**  
  *Li et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2405.02957)]
- **"ToolChain*: Efficient Action Space Navigation in Large Language Models with A* Search"**  
  *Zhuang et al.* ICLR 2024. [[paper](https://arxiv.org/abs/2310.13227)]

#### Accumulation:Embodied

- **"Evolvable Embodied Agent for Robotic Manipulation via Long Short-Term Reflection and Optimization"**  
  *Wang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.13533)]
- **"ELITE: Experiential Learning and Intent-Aware Transfer for Self-improving Embodied Agents"**  
  *Wei et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.24018)]
- **"MineEvolve: Self-Evolution with Accumulated Knowledge for Long-Horizon Embodied Minecraft Agents"**  
  *Xie et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.13131)]

#### Accumulation:Game-strategic

- **"Self-Evolving Multi-Agent Framework for Efficient Decision Making in Real-Time Strategy Scenarios"**  
  *Ma et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.23875)]
- **"MEMO: Memory-Augmented Model Context Optimization for Robust Multi-Turn Multi-Agent LLM Games"**  
  *Xie et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.09022)]
- **"Richelieu: Self-Evolving LLM-Based Agents for AI Diplomacy"**  
  *Guan et al.* NeurIPS 2024. [[paper](https://arxiv.org/abs/2407.06813)]

#### Accumulation:Domain-specific

- **"GSEM: Graph-based Self-Evolving Memory for Experience Augmented Clinical Reasoning"**  
  *Han et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.22096)]
- **"OpenHospital: A Thing-in-itself Arena for Evolving and Benchmarking LLM-based Collective Intelligence"**  
  *Liu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.14771)]
- **"Emulating Clinician Cognition via Self-Evolving Deep Clinical Research"**  
  *Ren et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.10677)]
- **"Evo-MedAgent: Beyond One-Shot Diagnosis with Agents That Remember, Reflect, and Improve"**  
  *Shen et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.14475)]
- **"PhysNote: Self-Knowledge Notes for Evolvable Physical Reasoning in Vision-Language Model"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.24443)]
- **"HealthFlow: A Self-Evolving AI Agent with Meta Planning for Autonomous Healthcare Research"**  
  *Zhu et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2508.02621)]

#### Accumulation:Multi-agent

- **"CORAL: Towards Autonomous Multi-Agent Evolution for Open-Ended Discovery"**  
  *Qu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.01658)]
- **"AutoAgent: Evolving Cognition and Elastic Memory Orchestration for Adaptive Agents"**  
  *Wang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.09716)]
- **"Forage V2: Knowledge Evolution and Transfer in Autonomous Agent Organizations"**  
  *Xie* arXiv 2026. [[paper](https://arxiv.org/abs/2604.19837)]
- **"G-Memory: Tracing Hierarchical Memory for Multi-Agent Systems"**  
  *Zhang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2506.07398)]

#### Accumulation:Research/discovery

- **"OR-Agent: Bridging Evolutionary Search and Structured Research for Automated Algorithm Discovery"**  
  *Liu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.13769)]
- **"AI-Supervisor: Autonomous AI Research Supervision via a Persistent Research World Model"**  
  *Long* arXiv 2026. [[paper](https://arxiv.org/abs/2603.24402)]
- **"ASI-Evolve: AI Accelerates AI"**  
  *Xu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.29640)]

#### Accumulation:Conversational/persona

- **"EvoSpark: Endogenous Interactive Agent Societies for Unified Long-Horizon Narrative Evolution"**  
  *He et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.12776)]
- **"Embodied Agents Meet Personalization: Investigating Challenges and Solutions Through the Lens of Memory Utilization"**  
  *Kwon et al.* ICLR 2026. [[paper](https://arxiv.org/abs/2505.16348)]
- **"Choosing How to Remember: Adaptive Memory Structures for LLM Agents"**  
  *Lu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.14038)]
- **"GAM: Hierarchical Graph-based Agentic Memory for LLM Agents"**  
  *Wu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.12285)]
- **"Lightweight LLM Agent Memory with Small Language Models"**  
  *Zhang et al.* ACL 2026. [[paper](https://arxiv.org/abs/2604.07798)]
- **"To Know is to Construct: Schema-Constrained Generation for Agent Memory"**  
  *Zheng et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.20117)]
- **"HeLa-Mem: Hebbian Learning and Associative Memory for LLM Agents"**  
  *Zhu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.16839)]
- **"What Deserves Memory: Adaptive Memory Distillation for LLM Agents"**  
  *Ma et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2508.03341)]
- **"A-MEM: Agentic Memory for LLM Agents"**  
  *Xu et al.* NeurIPS 2025. [[paper](https://arxiv.org/abs/2502.12110)]
- **"Generative Agents: Interactive Simulacra of Human Behavior"**  
  *Park et al.* UIST 2023. [[paper](https://arxiv.org/abs/2304.03442)]

#### Curation/operators

- **"MemMA: Coordinating the Memory Cycle through Multi-Agent Reasoning and In-Situ Self-Evolution"**  
  *Lin et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.18718)]
- **"PRIME: Training Free Proactive Reasoning via Iterative Memory Evolution for User-Centric Agent"**  
  *Wang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.07645)]
- **"Live-Evo: Online Evolution of Agentic Memory from Continuous Feedback"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.02369)]
- **"EvoFSM: Controllable Self-Evolution for Deep Research with Finite State Machines"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2601.09465)]
- **"Memento 2: Learning by Stateful Reflective Memory"**  
  *Wang* arXiv 2025. [[paper](https://arxiv.org/abs/2512.22716)]
- **"AccelOpt: A Self-Improving LLM Agentic System for AI Accelerator Kernel Optimization"**  
  *Zhang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2511.15915)]

#### Forgetting/lifecycle

- **"ZenBrain: A Neuroscience-Inspired 7-Layer Memory Architecture for Autonomous AI Systems"**  
  *Bering* arXiv 2026. [[paper](https://arxiv.org/abs/2604.23878)]
- **"FSFM: A Biologically-Inspired Framework for Selective Forgetting of Agent Memory"**  
  *Gu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.20300)]
- **"When to Forget: A Memory Governance Primitive"**  
  *Simsek* arXiv 2026. [[paper](https://arxiv.org/abs/2604.12007)]
- **"AEL: Agent Evolving Learning for Open-Ended Environments"**  
  *Xu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.21725)]

#### Meta-evolution

- **"Prism: An Evolutionary Memory Substrate for Multi-Agent Open-Ended Discovery"**  
  *Mishra* arXiv 2026. [[paper](https://arxiv.org/abs/2604.19795)]
- **"M★: Every Task Deserves Its Own Memory Harness"**  
  *Pan et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.11811)]
- **"MemEvolve: Meta-Evolution of Agent Memory Systems"**  
  *Zhang et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2512.18746)]

#### Retrieval innovation

- **"Thought-Retriever: Don't Just Retrieve Raw Data, Retrieve Thoughts for Memory-Augmented Agentic Systems"**  
  *Feng et al.* TMLR 2026. [[paper](https://arxiv.org/abs/2604.12231)]
- **"ROZA Graphs: Self-Improving Near-Deterministic RAG through Evidence-Centric Feedback"**  
  *Penaroza* arXiv 2026. [[paper](https://arxiv.org/abs/2604.07595)]
- **"Latent Preference Modeling for Cross-Session Personalized Tool Calling"**  
  *Yoon et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.17886)]
- **"Buffer of Thoughts: Thought-Augmented Reasoning with Large Language Models"**  
  *Yang et al.* NeurIPS 2024. [[paper](https://arxiv.org/abs/2406.04271)]

#### Sense/compression

- **"A Self-Evolving Framework for Efficient Terminal Agents via Observational Context Compression"**  
  *Ren et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.19572)]

### Δ, H≠0 (Structural, Human-involved)

#### Conversational/persona

- **"Synthius-Mem: Brain-Inspired Hallucination-Resistant Persona Memory Achieving 94.4% Memory Accuracy and 99.6% Adversarial Robustness on LoCoMo"**  
  *Gadzhiev et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.11563)]
- **"PersonaVLM: Long-Term Personalized Multimodal LLMs"**  
  *Nie et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.13074)]
- **"Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory"**  
  *Chhikara et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2504.19413)]
- **"Zep: A Temporal Knowledge Graph Architecture for Agent Memory"**  
  *Rasmussen et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2501.13956)]
- **"RGMem: Renormalization Group-inspired Memory Evolution for Language Agents"**  
  *Tian et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2510.16392)]
- **"Enabling Personalized Long-term Interactions in LLM-based Agents through Persistent Memory and User Profiles"**  
  *Westhäusser et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2510.07925)]
- **"MemoryBank: Enhancing Large Language Models with Long-Term Memory"**  
  *Zhong et al.* AAAI 2024. [[paper](https://arxiv.org/abs/2305.10250)]
- **"MemGPT: Towards LLMs as Operating Systems"**  
  *Packer et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2310.08560)]

#### Human-in-the-loop

- **"SkinGPT-X: A Self-Evolving Collaborative Multi-Agent System for Transparent and Trustworthy Dermatological Diagnosis"**  
  *Chen et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.26122)]
- **"Your Code Agent Can Grow Alongside You with Structured Memory"**  
  *Deng et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.13258)]
- **"EvoAgent: An Evolvable Agent Framework with Skill Learning and Multi-Agent Delegation"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.20133)]
- **"Enabling Self-Improving Agents to Learn at Test Time With Human-In-The-Loop Guidance"**  
  *He et al.* EMNLP 2025. [[paper](https://arxiv.org/abs/2507.17131)]
- **"Magentic-UI: Towards Human-in-the-loop Agentic Systems"**  
  *Mozannar et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2507.22358)]

### ∇, H=0 (Parametric, Autonomous)

#### World models (Sense)

- **"Self-Improving World Modelling with Latent Actions"**  
  *Qiu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.06130)]
- **"Mastering Diverse Control Tasks through World Models"**  
  *Hafner et al.* Nature 2025. [[paper](https://doi.org/10.1038/s41586-025-08744-2)]
- **"Recurrent World Models Facilitate Policy Evolution"**  
  *Ha et al.* NeurIPS 2018. [[paper](https://arxiv.org/abs/1809.01999)]

#### Memory fine-tuning

- **"Learning to (Learn at Test Time): RNNs with Expressive Hidden States"**  
  *Sun et al.* ICML 2025. [[paper](https://arxiv.org/abs/2407.04620)]
- **"Continual Learning via Sparse Memory Finetuning"**  
  *Lin et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2510.15103)]

### Δ+∇, H=0 (Hybrid, Autonomous)

#### Memory+RL

- **"Ask Only When Needed: Proactive Retrieval from Memory and Skills for Experience-Driven Lifelong Agents"**  
  *Cai et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.20572)]
- **"SPRInG: Continual LLM Personalization via Selective Parametric Adaptation and Retrieval-Interpolated Generation"**  
  *Kim et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2601.09974)]
- **"VERDICT: Verifiable Evolving Reasoning with Directive-Informed Collegial Teams for Legal Judgment Prediction"**  
  *Liao et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.19306)]
- **"Memory Intelligence Agent"**  
  *Qiao et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.04503)]
- **"SLEA-RL: Step-Level Experience Augmented Reinforcement Learning for Multi-Turn Agentic Training"**  
  *Wang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.18079)]
- **"SkillRL: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning"**  
  *Xia et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.08234)]
- **"Self-Consolidation for Self-Evolving Agents"**  
  *Yu et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.01966)]
- **"MemSkill: Learning and Evolving Memory Skills for Self-Evolving Agents"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2602.02474)]
- **"RetroAgent: From Solving to Evolving via Retrospective Dual Intrinsic Feedback"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2603.08561)]
- **"EvolveR: Self-Evolving LLM Agents through an Experience-Driven Lifecycle"**  
  *Wu et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2510.16079)]
- **"AgentEvolver: Towards Efficient Self-Evolving Agent System"**  
  *Zhai et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2511.10395)]
- **"Memento: Fine-tuning LLM Agents without Fine-tuning LLMs"**  
  *Zhou et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2508.16153)]

#### Domain hybrid

- **"S1-NexusAgent: a Self-Evolving Agent Framework for Multidisciplinary Scientific Research"**  
  *Team* arXiv 2026. [[paper](https://arxiv.org/abs/2602.01550)]
- **"PsychAgent: An Experience-Driven Lifelong Learning Agent for Self-Evolving Psychological Counselor"**  
  *Yang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.00931)]
- **"Training LLM Agents for Spontaneous, Reward-Free Self-Evolution via World Knowledge Exploration"**  
  *Zhang et al.* arXiv 2026. [[paper](https://arxiv.org/abs/2604.18131)]
- **"EvolvingAgent: Curriculum Self-evolving Agent with Continual World Model for Long-Horizon Tasks"**  
  *Feng et al.* arXiv 2025. [[paper](https://arxiv.org/abs/2502.05907)]

## Contributing

Contributions are welcome. Please open a pull request or issue to suggest papers.
