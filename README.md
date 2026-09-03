<div align="center">

# 🚦 X-ACTDT
## An E**x**plainable **A**utonomous **C**ognitive **T**ransportation **D**igital **T**win 

</div>

E**X**plainable **A**utonomous **C**ognitive **T**ransportation **D**igital **T**win (**X-ACTDT**) is an advanced framework for next-generation transportation digital twins that bridges the gap between static simulation and adaptive, real-time urban management. By seamlessly integrating state-of-the-art machine learning paradigms, the system delivers secure, self-updating, and audit-ready intelligence for complex transportation networks.

## 🚀 Core Technical Pillars

* **[X] Explainability via MLLMs:** Utilizing explainable multimodal large language models (MLLMs) for transparent cross-modal synthesis and audit-ready intelligence.
* **[A] Autonomous Control:** Empowering self-governing agents to manage dynamic traffic environments without constant human intervention.
* **[C] Cognitive Intelligence:** Powered by a comprehensive cognitive suite—integrating **Reinforcement Learning** for optimal policy control and decision-making, **Continual Learning** to prevent catastrophic forgetting in non-stationary environments, and **Meta-Learning** for dynamic meta-feature extraction and model routing.
* **[T] Transportation Domain:** Designed specifically for complex, large-scale urban traffic and mobility networks.
* **[DT] Digital Twin Architecture:** Operating at **Level Autonomy**—evolving far beyond passive visualization or simulation into an active, self-optimizing closed-loop twin that dynamically enacts intelligent control policies on physical transportation systems.

## 📚 Core Architecture


A cutting-edge architecture for next-generation transportation digital twins, integrating **Reinforcement Learning (RL)**, **Continual Learning (CL)**, **Meta-Learning**, and **Explainable Multimodal Large Language Models (MLLMs)**.

<p align="center">
  <img src="assets/autonomous_cognitive_transportation.gif" alt="Cognitive Transportation Digital Twin Architecture Overview" width="800"/>
</p>

### Phases 1–3: From Real-World Data to a Live Digital Twin

The first three phases establish the foundation of the Explainable Autonomous Cognitive Transportation Digital Twin (X-ACTDT) by transforming observations of the physical transportation environment into a continuously updated virtual representation.

* Phase 1 — Data Collection gathers heterogeneous observations from road networks, traffic sensors, signals, transit systems, vehicles, incidents, weather, mobility demand, infrastructure, events, and environmental sources while preserving their spatial, temporal, quality, and provenance information.

* Phase 2 — Data Ingestion and Integration validates, standardizes, synchronizes, georeferences, harmonizes, and fuses these heterogeneous observations into a consistent and trustworthy data environment. 

* Phase 3 — Digital Twin Engine uses the integrated information to maintain a live, dynamic, spatiotemporal model of the transportation system, representing roads, traffic, transit, signals, incidents, demand, weather, infrastructure, and environmental conditions. 

Together, Phases 1–3 transform raw observations into a synchronized and traceable digital representation of reality that provides the trusted foundation for cognitive reasoning, prediction, and autonomous decision-making.

### Phases 4–6: From Understanding to Decision and Action

The next three phases transform the live digital twin into an intelligent decision-making and intervention system. 

* Phase 4 — Cognitive AI interprets the current transportation state by combining information from multiple sources, performing spatial-temporal reasoning, detecting anomalies and incidents, forecasting traffic and travel demand, exploring alternative scenarios, and generating explainable insights with associated confidence levels. 
* Phase 5 — Decision evaluates possible responses against operational objectives, safety requirements, policies, constraints, resources, and predicted outcomes, selecting the most appropriate action while maintaining a traceable explanation of why that decision was chosen. 
* Phase 6 — Action/Intervention converts the selected decision into executable operational commands, validates them for safety and feasibility, and dispatches them to real-world transportation systems such as traffic signals, variable message signs, transit operations, routing systems, infrastructure controls, and traveler-information platforms. 

Together, Phases 4–6 transform the digital twin from a representation of the transportation system into an explainable autonomous intelligence capable of understanding situations, selecting appropriate interventions, and initiating real-world action.

### Phases 7–9: From Real-World Execution to Continuous Learning

The final three phases close the autonomous learning loop by determining what actually happened after an intervention and using the results to improve future operations. 

* Phase 7 — Real-World Execution deploys the selected intervention through transportation agencies, traffic-control systems, transit operators, infrastructure systems, connected vehicles, and traveler-information services, while recording what was actually implemented and when. 

* Phase 8 — Monitor and Measure continuously observes the transportation environment after the intervention and evaluates its effects using mobility, safety, reliability, sustainability, equity, and user-experience indicators, comparing actual outcomes against objectives, baselines, and expected results. 

* Phase 9 — Feedback and Learning analyzes these results to identify successes, shortcomings, causal factors, new patterns, and uncertainties, then updates AI models, digital-twin parameters, knowledge bases, decision policies, and intervention strategies. 

The resulting knowledge is fed back into the earlier phases, creating a closed-loop AC-TDT that continuously observes, understands, decides, acts, measures, learns, and improves while maintaining traceability and explainability throughout the entire operational cycle.

---

# 📌 Key Considerations

---

## 📖 Beyond Black Boxes

The Explainable Necessity in Autonomous Transportation:

**Explainable Autonomous Cognitive Transportation Digital Twins (X-ACTDT)** is a next-generation framework designed to transition urban management from static simulation to adaptive and cognitive control. The architecture achieves secure, audit-ready intelligence through:
* **Optimal Policy Control:** Powered by reinforcement learning.
* **Non-Stationary Adaptation:** Using continual learning to eliminate catastrophic forgetting.
* **Dynamic Model Routing:** Leveraging meta-learning for advanced meta-feature extraction.
* **Transparent Synthesis:** Utilizing explainable multimodal large language models (MLLMs) for cross-modal reasoning.


A live demonstration of our Explainable Autonomous Cognitive Transportation Digital Twin, highlighting how cognitive modeling and real-time visualization empower safer, more transparent AI-driven traffic systems.

<p align="center">
  <img src="assets/explainable.gif" alt="Explainable Autonomous Cognitive Transportation Digital Twin" width="800"/>
</p>

## 🏗️ Multimodal Selection

Selecting an optimal multimodal foundation model remains a fundamental challenge in transportation digital twins. Traditionally, a single architecture struggled to excel simultaneously across text, time series, video streams, and graph topologies because each modality demands distinct mathematical formalisms—such as sequential semantics for text, temporal dependencies for time series, spatial representations for video, and relational structures for transit networks. 

However, modern foundation models increasingly overcome these boundaries by projecting diverse modalities into a unified embedding space, mitigating the performance compromises once inherent in rigid, siloed frameworks.

<p align="center">
  <img src="assets/multimodal_selection.gif" alt="Multimodal Selection for A Transportation Digital Twin" width="800"/>
</p>

As shown in the figure above—which provides a general example rather than a complete set of options—choosing an architecture has historically depended on human expertise to tailor models to specific tasks. While manual designs provide strong general-purpose baselines, they might be not sufficient when apply to specialized or domain specific modalities. Thus, rather than depending on rigid, single-instance selections when conventional designs prove insufficient, it is crucial to iteratively update and optimize these models. Automated approaches such as neural architecture search or network growth techniques can be used to extend or improve the existing solutions (learn more at [greenmoo](https://github.com/phamdps/greenmoo)).

## 🌐 Exploring Typical Architectures

Evaluating existing multimodal models requires careful consideration of their **explainability and interpretability**. A prime example of such a model applied to a digital twin is Qwen2-VL, with its architecture detailed below:

<p align="center">
  <img src="assets/qwen2-VL_architecture.gif" alt="Multimodal Selection for A Transportation Digital Twin" width="800"/>
</p>

Examining the architecture of each multimodal model is essential to understanding its internal mechanics and how it generates system reasoning, ensuring transparency in all decision-making processes. For further details on multimodal explainability, visit [explainable-fm](https://github.com/phamdps/explainable-fm). To dive deeper into the operational mechanics of Multimodal Large Language Models (MLLMs), check out [MLLMs](https://github.com/phamdps/MLLMs).

## 🧠 Enabling Autonomous Decision and Planning

While cognitive capabilities enable a digital twin to understand intentions and perceive the system state, autonomous management further requires the capacity to make decisions, plan actions, and adapt to changing conditions without explicit human intervention. This section discusses how agent-based reasoning and adaptive learning provide the mechanism for decision-making, and how self-optimization and closed-loop control complete the cycle of autonomous management.

* Agent-based Reasoning and Adaptive Learning: Agent-based reasoning allows the digital twin with a modular structure capable of acting intelligently in complex environments. Each agent embodies autonomy, perception, reasoning, and learning, functioning as both a decision-maker and an executor of management tasks. Within a digital twin system, agents perceive environmental inputs, analyze contextual information, generate management plans, and execute actions through interactions with the underlying physical or simulated systems. Reinforcement and continual learning further allow these agents to refine strategies from experience and coordinate with others in multi-agent settings.

<p align="center">
  <img src="assets/autonomous_agents.png" alt="Enabling Autonomous Decision and Planning for A Transportation Digital Twin" width="800"/>
</p>

* Self-Optimization and Closed-Loop Control: Self-optimization is the culmination of autonomous management, where digital twins no longer rely on external commands but continuously refine their performance through closed-loop feedback. The system observes its own behavior, identifies inefficiencies, and implements corrective actions automatically. When combined with predictive and cognitive capabilities, closed-loop control transforms the twin into an autonomous entity capable of sustaining optimal performance with minimal supervision.

Further information for this step will be clarified in the [ai-assistant](https://github.com/phamdps/ai-assistant) repository.

---

# 📌 Project Architecture & Structure

```text
cognitive_transdt/
├── configs/                       # Hyperparameters and system configurations
│   ├── rl_config.yaml             # RL agent and environment parameters
│   ├── cl_config.yaml             # Continual learning memory & rehearsal settings
│   ├── meta_config.yaml           # Meta-feature extractor & model routing rules
│   └── mllm_config.yaml           # Multimodal large model & explanation hooks
├── data/                          # Data pipelines and metadata storage
│   ├── raw/                       # Raw feeds (CCTV video, LiDAR point clouds, loop detectors)
│   ├── processed/                 # Synchronized and aligned telemetry
│   └── meta_features/             # Extracted meta-features for model routing
├── models/                        # Core algorithmic implementations
│   ├── reinforcement_learning/    # RL policies for dynamic control & safe-to-fail simulation
│   ├── continual_learning/        # Memory buffers and regularization against catastrophic forgetting
│   ├── meta_learning/             # Few-shot adaptation and dynamic model selection
│   └── mllms/                     # Multimodal integration and explainability (XAI) layers
├── environment/                   # Digital twin simulation sandbox
│   ├── simulator_interface.py     # Bridges physical feeds with virtual simulation (SUMO/CityFlow)
│   └── state_observer.py          # Real-time state synchronization
├── evaluation/                    # Testing, verification, and audit metrics
│   ├── safety_metrics.py          # Stress-testing against extreme disruption scenarios
│   └── explainability_eval.py     # Validating operator trust and interpretability
├── scripts/                       # Execution entry points
│   ├── train_rl.py
│   ├── update_cl.py
│   ├── meta_route.py
│   └── run_digital_twin.py
└── README.md
```

---

## 🚀 Core Technical Components

### 1. Reinforcement Learning (RL) for Dynamic Control
*   **Optimal Policy Testing:** Solves complex multi-objective problems such as adaptive traffic signal control and dynamic congestion pricing inside the digital twin sandbox.
*   **Safe-to-Fail Experimentation:** Stress-tests extreme disruption scenarios (accidents, severe weather) virtually before deploying interventions to live infrastructure.

### 2. Continual Learning (CL) for Evolving Environments
*   **Preventing Catastrophic Forgetting:** Incremental updates allow the system to absorb new urban layouts, construction zones, and seasonal traffic flows without erasing historical knowledge.
*   **Edge-Cloud Synchronization:** Distributes lightweight continual learning updates across edge nodes for zero-downtime adaptation.

### 3. Meta-Learning for Modality Adaptation & Model Selection
*   **Meta-Feature Extraction:** Evaluates statistical and structural properties of incoming data streams (e.g., spatial sparsity of LiDAR vs. temporal density of loop detectors).
*   **Dynamic Routing & Few-Shot Adaptation:** Instantly selects, combines, or fine-tunes the optimal multimodal model configuration for unprecedented or sudden operational states.

### 4. Explainable Multimodal Large Language Models (MLLMs)
*   **Cross-Modal Synthesis:** Fuses CCTV, LiDAR, and emergency dispatch logs into a unified semantic understanding of traffic events.
*   **Operator Transparency:** Provides human-interpretable rationales for automated routing and signal overrides, ensuring regulatory compliance and high-stakes accountability.

---

## 📚 References & Related Literature (2025–2026)

1. **Digital Twin AI Lifecycles and Frameworks**
   * Research collaboration on Digital Twin AI. (2026). *Digital Twin AI: Opportunities and Challenges from Large Language Models*. arXiv. https://arxiv.org/html/2601.01321v1

2. **Transport Planning Digital Twins Review**
   * Nag, D., et al. (2025). Exploring digital twins for transport planning: a review. *European Transport Research Review*, 17(15). https://doi.org/10.1186/s12544-025-00713-0

3. **Intelligent Transport Systems Resilience & Digital Twins**
   * Machkour, B. (2025). Digital Twins in Intelligent Transport Systems: A Systematic Review. *Digital*, 9(8), 123. https://www.mdpi.com/2624-6511/9/8/123

4. **In-Context Learning and Updating Digital Twins**
   * Conference on Machine Learning (ICML) Proceedings. (2025). *Continuously Updating Digital Twins using Large Language Models (CALM-DT)*. ICML Virtual Poster Session. https://icml.cc/virtual/2025/poster/44291

5. **Hybrid Meta-Learning and Reinforcement Learning Frameworks**
   * Harshinni, B. (2025/2026). Hybrid Digital Twin Framework with Meta-Learning and Reinforcement Learning. *Advances in Production*. https://proceedings.aijr.org/index.php/ap/article/view/4/4

6. **Cognitive Digital Twins and MLLM Integration**
   * Wu, S., Xu, X., Wang, C., Wu, D., & Zhu, H. (2026). Towards Large Language Model–Enabled Cognitive Digital Twins for Urban Mobility Systems. *Conference on Computer...* https://ieeexplore.ieee.org/abstract/document/11582620

7. **Advanced Modeling and Trends in Digital Twins**
   * Yang, L., Luo, S., & Yu, L. (2025). Leveraging Large Language Models for Enhanced Digital Twin Modeling: Trends, Methods, and Challenges. *arXiv preprint arXiv:2503.xxxxx*. https://www.semanticscholar.org/paper/Leveraging-Large-Language-Models-for-Enhanced-Twin-Yang-Luo/b1f636a6ecc341c3f77060373f044feef50fe726

