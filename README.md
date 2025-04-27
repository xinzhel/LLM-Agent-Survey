<div align="center">
<h2>    
A Reading List for LLM-Agents (Last Major Updated: 14 Mar 2025)
</div>
<!-- About: Surveys on LLM Agents (Published on CoLing 2025) and Test-Time Compute via Search (Preprint) -->

<div align="center">
<b>Xinzhe Li</b>
</div>
<br />

<div align="center">
    <a href="https://arxiv.org/abs/2406.05804"><img src="https://img.shields.io/badge/CoLing-2025-b31b1b" alt="Paper"></a>
    <a href="https://github.com/xinzhel/llm-agent-survey"><img src="https://img.shields.io/github/last-commit/xinzhel/llm-agent-survey?color=blue" alt="Github"></a>
    <a href="https://github.com/xinzhel/llm-agent-survey/blob/main/LICENSE"> <img alt="License" src="https://img.shields.io/github/license/xinzhel/llm-agent-survey?color=green"> </a>
</div>



### This Repository vs. Others
Our Github Repository follows the selection criteria below:
- **Allowing Coherent Understanding**: They can be systematically categoried into the unified framework in my survey, according to the use of LLM-Profiled Roles (LMPRs).
  - A general survey (Accepted at CoLing 2025): [A Review of Prominent Paradigms for LLM-Based Agents: Tool Use (Including RAG), Planning, and Feedback Learning](https://arxiv.org/abs/2406.05804)
    <!-- - **Limitations**: The above survey only defines the LMPR-specific, universal workflow, i.e., lacking both task-specific implementatinos and procedures that not necessarily involve LLMs. The following survey is published to address this limitation in terms of search workflows. -->
    <!-- - [17 Jan 2025] Initial version published on [arxiv](https://arxiv.org/abs/2501.10069) -->
- **High Quality**: Papers are published on ICML, ICLR, NeurIPS, *ACL (including EMNLP), and COLING. Or unpublished papers contain useful analysis and insightful novelty 
  - Unpublished papers are marked with 💡 and will be updated upon publication.
  - Paper Reviews: The paper links to OpenReview (if available) are alwasy given. I often learn much more from and resonate with many reviews about the papers and evaluate some rejected papers with the reviews. (That's why I always like NeurIPS/ICLR papers).
- **Exhasutive Review on [Search Workflows](https://github.com/xinzhel/LLM-Search)**
    - A corresponding survey on TMLR 2025: [A Survey on LLM Test-Time Compute via Search: Tasks, LLM Profiling, Search Algorithms, and Relevant Frameworks](https://openreview.net/forum?id=x9VQFjtOPS) 

> From Apr 2025, I will not actively update this repo since my recent research focuses on [LLM Inference via Search or LIS](https://github.com/xinzhel/LLM-Search). But I am sure that you can follow some actively updated repos below for the latest papers. Here is some reason for my transfer: 1) the LIS algorithms/workflows contain less heuristic, delibrate design, and human-aligned slow thinking while generally applicable. 2) with the limited energy as an individual researcher on inference-time workflows/agents, I do not have enough energy to discover the details of newly published work in this general field. Putting all the energy on LIS can help me maintain the quality of my work delivered to the community. Hopefully I can find a professional team later to work more ambitiously. 

Other Github Repositories summarize related papers with less constrained selection criteria:
* [AGI-Edgerunners/LLM-Agents-Papers](https://github.com/AGI-Edgerunners/LLM-Agents-Papers?tab=readme-ov-file)<a href="https://github.com/AGI-Edgerunners/LLM-Agents-Papers?tab=readme-ov-file"><img src="https://img.shields.io/github/last-commit/AGI-Edgerunners/LLM-Agents-Papers?color=blue" alt="Github"></a>
* [zjunlp/LLMAgentPapers](https://github.com/zjunlp/LLMAgentPapers) <a href="https://github.com/zjunlp/LLMAgentPapers"><img src="https://img.shields.io/github/last-commit/zjunlp/LLMAgentPapers?color=blue" alt="Github"></a>
* [Paitesanshi/LLM-Agent-Survey](https://github.com/Paitesanshi/LLM-Agent-Survey) <a href="https://github.com/Paitesanshi/LLM-Agent-Survey"><img src="https://img.shields.io/github/last-commit/Paitesanshi/LLM-Agent-Survey?color=blue" alt="Github"></a>
* [woooodyy/llm-agent-paper-list](https://github.com/woooodyy/llm-agent-paper-list) <a href="https://github.com/woooodyy/llm-agent-paper-list"><img src="https://img.shields.io/github/last-commit/woooodyy/llm-agent-paper-list?color=blue" alt="Github"></a>
* [Autonomous-Agents](https://github.com/tmgthb/Autonomous-Agents) <a href="https://github.com/tmgthb/Autonomous-Agents"><img src="https://img.shields.io/github/last-commit/tmgthb/Autonomous-Agents?color=blue" alt="Github"></a>

Other Github Repositories summarize related papers focusing on specific perspectives:
* [LLM-Search](https://github.com/xinzhel/LLM-Search) <a href="https://github.com/xinzhel/LLM-Search"><img src="https://img.shields.io/github/last-commit/xinzhel/LLM-Search?color=blue" alt="Github"></a>
* [nuster1128/LLM_Agent_Memory_Survey](https://github.com/nuster1128/LLM_Agent_Memory_Survey) <a href="https://github.com/nuster1128/LLM_Agent_Memory_Survey"><img src="https://img.shields.io/github/last-commit/nuster1128/LLM_Agent_Memory_Survey?color=blue" alt="Github"></a>: Focus on memory
* [teacherpeterpan/self-correction-llm-papers](https://github.com/teacherpeterpan/self-correction-llm-papers) <a href="https://github.com/teacherpeterpan/self-correction-llm-papers"><img src="https://img.shields.io/github/last-commit/teacherpeterpan/self-correction-llm-papers?color=blue" alt="Github"></a>: Focus on feedback learning (Self Correction)
* [git-disl/awesome-LLM-game-agent-papers](https://github.com/git-disl/awesome-LLM-game-agent-papers) <a href="https://github.com/git-disl/awesome-LLM-game-agent-papers"><img src="https://img.shields.io/github/last-commit/git-disl/awesome-LLM-game-agent-papers?color=blue" alt="Github"></a>: Focus on gaming applications


## Table of Contents
- [🎁 Surveys](#gift-surveys)
- [🚀 Tool Use](#rocket-tool-use)
- [🧠 Planning](#brain-planning)
  - [Base Workflows](#base-workflows)
  - [Search Workflows](#search-workflows)
  - [Decomposition](#decomposition)
  - [PDDL + Local Search](#pddl+local-search)
  - [Others](#others)
- [🔄 Feedback Learning](#arrows_counterclockwise-feedback-learning)
- [🧩 Composition](#jigsaw-composition)
  - [Planning + Feedback Learning](#planning--feedback-learning)
  - [Planning + Tool Use](#planning--tool-use)
- [🌍 World Modeling](#world_map-world-modeling)
  <!-- - [LLM as World Models](#llm-as-world-models)
  - [LLM-Generated World Models](#llm-generated-world-models) -->
- [📊 Benchmarks](#bar_chart-benchmarks)
- [📝 Citation](#memo-citation)


## :gift: Surveys
- **A Review of Prominent Paradigms for LLM-Based Agents: Tool Use (Including RAG), Planning, and Feedback Learning**, CoLing 2025 [[paper]](https://arxiv.org/abs/2406.05804)
- **A Survey on Large Language Model based Autonomous Agents**, Frontiers of Computer Science 2024 [[paper]](https://arxiv.org/abs/2308.11432) | [[code]](https://github.com/Paitesanshi/LLM-Agent-Survey)
- **Augmented Language Models: a Survey**, TMLR [[paper]](https://openreview.net/forum?id=jh7wH2AzKK)
- **Understanding the planning of LLM agents: A survey**, arXiv [[paper]](https://arxiv.org/abs/2402.02716) 💡
- **The Rise and Potential of Large Language Model Based Agents: A Survey**, arxiv [[paper]](https://arxiv.org/abs/2309.07864) 💡
- **A Survey on the Memory Mechanism of Large Language Model based Agents**, arxiv [[paper]](https://arxiv.org/abs/2404.13501) 💡

### :rocket: Tool Use
- **ReAct: Synergizing Reasoning and Acting in Language Models**, ICLR 2023 [[paper](https://openreview.net/pdf?id=WE_vluYUL-X)]
- **Toolformer: Language Models Can Teach Themselves to Use Tools**, NeurIPS 2023 [[paper](https://doi.org/10.48550/arXiv.2302.04761)]
- **HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face**, NeurIPS 2023 [[paper](https://api.semanticscholar.org/CorpusID:257833781)]
- **API-Bank: A Benchmark for Tool-Augmented LLMs**, EMNLP 2023 [[paper](https://api.semanticscholar.org/CorpusID:258179056)]
- **ToolkenGPT: Augmenting Frozen Language Models with Massive Tools via Tool Embeddings**, NeurIPS 2023 [[paper](https://doi.org/10.48550/arXiv.2305.11554)] 
- **MultiTool-CoT: GPT-3 Can Use Multiple External Tools with Chain of Thought Prompting**, ACL 2023 [[paper](https://aclanthology.org/2023.acl-short.130/)] 
- **ChatCoT: Tool-Augmented Chain-of-Thought Reasoning on Chat-based Large Language Models**, EMNLP 2023 [[paper](https://doi.org/10.48550/arXiv.2305.14323)] 
- **ART: Automatic multi-step reasoning and tool-use for large language models**, arXiv.2303.09014 [[paper](https://doi.org/10.48550/arXiv.2303.09014)] 💡
- **TALM: Tool Augmented Language Models**, arXiv.2205.12255 [[paper](https://doi.org/10.48550/arXiv.2205.12255)] 💡
- **On the Tool Manipulation Capability of Open-source Large Language Models**, arXiv.2305.16504 [[paper](https://doi.org/10.48550/arXiv.2305.16504)] 💡
- **Large Language Models as Tool Makers**, arXiv.2305.17126 [[paper](https://doi.org/10.48550/arXiv.2305.17126)] 💡
- **GEAR: Augmenting Language Models with Generalizable and Efficient Tool Resolution**, arXiv.2307.08775 [[paper](https://doi.org/10.48550/arXiv.2307.08775)] 💡
- **ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs**, arXiv.2307.16789 [[paper](https://doi.org/10.48550/arXiv.2307.16789)] 💡
- **Tool Documentation Enables Zero-Shot Tool-Usage with Large Language Models**, arXiv.2308.00675 [[paper](https://doi.org/10.48550/arXiv.2308.00675)] 💡
- **MINT: Evaluating LLMs in Multi-turn Interaction with Tools and Language Feedback**, arXiv.2309.10691 [[paper](https://doi.org/10.48550/arXiv.2309.10691)] 💡
- **Natural Language Embedded Programs for Hybrid Language Symbolic Reasoning**, arXiv.2309.10814 [[paper](https://doi.org/10.48550/arXiv.2309.10814)] 💡

### :brain: Planning

#### Base Workflows
- **On the Planning Abilities of Large Language Models -- A Critical Investigation**, NeurIPS 2023 [[paper](https://doi.org/10.48550/arXiv.2305.15771)] 

#### Search Workflows 
Details in [the page (on the way to be publised)](https://github.com/xinzhel/LLM-Search).
- **Alphazero-like Tree-Search can guide large language model decoding and training**, ICML 2024 [[paper](https://arxiv.org/abs/2309.17179)]
    + Search Algorithm: MCTS
- **Language Agent Tree Search Unifies Reasoning, Acting, and Planning in Language Models**, ICML 2024 [[paper](https://openreview.net/forum?id=6LNTSrJjBe)]
    + Search Algorithm: MCTS
- **When is Tree Search Useful for {LLM} Planning? It Depends on the Discriminator**, ACL 2024 [[paper](https://aclanthology.org/2024.acl-long.738/)]
    + Search Algorithm: MCTS
- **Everything of Thoughts: Defying the Law of Penrose Triangle for Thought Generation**, ACL findings 2024 [[paper](https://aclanthology.org/2024.findings-acl.95/)]
    + Search Algorithm: MCTS
- **Tree-of-Traversals: A Zero-Shot Reasoning Algorithm for Augmenting Black-box Language Models with Knowledge Graphs**, ACL 2024 [[paper](https://aclanthology.org/2024.acl-long.665/)]
    + Search Algorithm: BFS/DFS
- **LLM-A\*: Large Language Model Enhanced Incremental Heuristic Search on Path Planning**, EMNLP findings 2024 [[paper](https://arxiv.org/pdf/2407.02511)] | [[code]](https://github.com/SilinMeng0510/llm-astar/)
    + Search Algorithm: A*
- **LLM Reasoners: New Evaluation, Library, and Analysis of Step-by-Step Reasoning with Large Language Models**, COLM2024 [[paper]](https://arxiv.org/abs/2404.05221) | [[code]](https://github.com/maitrix-org/llm-reasoners)
- **Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models**, arXiv.2310.04406 [[paper](https://doi.org/10.48550/arXiv.2310.04406)] 💡
- **Large Language Model Guided Tree-of-Thought**, arXiv.2305.08291 [[paper](https://doi.org/10.48550/arXiv.2305.08291)]💡
- **Tree Search for Language Model Agents**, Under Review [[paper](https://openreview.net/forum?id=kpL66Mvd2a)]💡
    + Search Algorithm: Best-First Search
- **Q\*: Improving multi-step reasoning for llms with deliberative planning**, Under Review [[paper](https://openreview.net/forum?id=F7QNwDYG6I)]💡
    + Search Algorithm: A*
- **Planning with Large Language Models for Code Generation**, ICLR 2023 [[paper](ttps://openreview.net/forum?id=Lr8cOOtYbfL)]
    + Search Algorithm: MCTS
- **Tree of Thoughts: Deliberate Problem Solving with Large Language Models**, NeurIPS 2023 [[paper](https://doi.org/10.48550/arXiv.2305.10601)]
    + Search Algorithm: BFS/DFS
- **LLM-MCTS:Large Language Models as Commonsense Knowledge for Large-Scale Task Planning**, NeurIPS 2023 [[paper](https://openreview.net/forum?id=tED747HURfX)] | [[code]](https://github.com/1989Ryan/llm-mcts)
    + Search Algorithm: MCTS
- **Self-Evaluation Guided Beam Search for Reasoning**, NeurIPS 2023 [[paper](https://openreview.net/forum?id=Bw82hwg5Q3)]
    + Search Algorithm: BFS/DFS
- **PathFinder: Guided Search over Multi-Step Reasoning Paths**, NeurIPS 2023 R0-FoMo [[paper](https://openreview.net/forum?id=Bw82hwg5Q3)]
    + Search Algorithm: Beam Search
- **Plan, Verify and Switch: Integrated Reasoning with Diverse X-of-Thoughts**, EMNLP 2023 [[paper](https://doi.org/10.48550/arXiv.2310.14628)] 
- **RAP: Reasoning with Language Model is Planning with World Model**, EMNLP 2023 [[paper](https://api.semanticscholar.org/CorpusID:258865812)]
    + Search Algorithm: MCTS
- **Prompt-Based Monte-Carlo Tree Search for Goal-oriented Dialogue Policy Planning**, EMNLP 2023 [[paper](https://aclanthology.org/2023.emnlp-main.439/)]
    + Search Algorithm: MCTS
- **Monte Carlo Thought Search: Large Language Model Querying for Complex Scientific Reasoning in Catalyst Design**, EMNLP findings 2023 [[paper](https://aclanthology.org/2023.findings-emnlp.560/)]
    + Search Algorithm: MCTS
- **Agent q: Advanced reasoning and learning for autonomous ai agents**, arXiv.2309.10814 [[paper](https://arxiv.org/abs/2408.07199)] 💡
    + Search Algorithm: MCTS


#### Decomposition
- **HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face**, NeurIPS 2023 [[paper](https://openreview.net/forum?id=yHdTscY6Ci)] | [[code]](https://github.com/microsoft/JARVIS/tree/main/hugginggpt)
- **Least-to-Most Prompting Enables Complex Reasoning in Large Language Models**, NeurIPS 2023 [[paper](https://openreview.net/forum?id=WZH7099tgfM)]

#### PDDL+Local Search
- **Leveraging Pre-trained Large Language Models to Construct and Utilize World Models for Model-based Task Planning**, NeurIPS 2023 [[paper](https://arxiv.org/abs/2305.14909)] | [[code]](https://github.com/GuanSuns/LLMs-World-Models-for-Planning)
- **On the Planning Abilities of Large Language Models - A Critical Investigation**, NeurIPS 2023 [[paper](https://openreview.net/forum?id=X6dEqXIsEW)] | [[code]](https://github.com/karthikv792/LLMs-Planning)
- **PlanBench: An Extensible Benchmark for Evaluating Large Language Models on Planning and Reasoning about Change**, NeurIPS 2023 [[paper](https://openreview.net/forum?id=YXogl4uQUO)] | [[code]](https://github.com/karthikv792/LLMs-Planning)

#### Others
- **LLM+P: Empowering Large Language Models with Optimal Planning Proficiency**, arXiv.2304.11477 [[paper](https://doi.org/10.48550/arXiv.2304.11477)]💡

### :arrows_counterclockwise: Feedback Learning
- **Reflexion: Language Agents with Verbal Reinforcement Learning**, NeurIPS 2023 [[paper](https://doi.org/10.48550/arXiv.2303.11366)]
- **Self-Refine: Iterative Refinement with Self-Feedback**, NeurIPS 2023 [[paper](https://doi.org/10.48550/arXiv.2303.17651)]
- **SelfCheck: Using LLMs to Zero-Shot Check Their Own Step-by-Step Reasoning**, ICLR 2024 [[paper]](https://arxiv.org/abs/2308.00436) | [[code]](https://github.com/ningmiao/selfcheck)
- **Learning From Correctness Without Prompting Makes LLM Efficient Reasoner**, COLM2024 [[paper]](https://openreview.net/forum?id=dcbNzhVVQj#discussion)
- **Learning From Mistakes Makes LLM Better Reasoner**, arXiv [[paper]](https://arxiv.org/abs/2310.20689) | [[code]](https://github.com/microsoft/LEMA)💡
- **LLM-based Rewriting of Inappropriate Argumentation using Reinforcement Learning from Machine Feedback** ACL 2024 [[paper]](https://arxiv.org/abs/2406.03363)


### :jigsaw: Composition
#### Planning + Feedback Learning
- **AdaPlanner: Adaptive Planning from Feedback with Language Models**, NeurIPS 2023 [[paper](https://doi.org/10.48550/arXiv.2305.16653)] 
- **CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing**, ICLR 2024 [[paper](https://openreview.net/forum?id=Sx038qxjek)]
- **ISR-LLM: Iterative Self-Refined Large Language Model for Long-Horizon Sequential Task Planning**, arXiv.2308.13724 [[paper](https://doi.org/10.48550/arXiv.2308.13724)] 💡

#### Planning + Tool Use
- **ToolChain: Efficient Action Space Navigation in Large Language Models with A\* Search**, ICLR 2024 [[paper](https://openreview.net/forum?id=B6pQxqUcT8)] 
- **TPTU: Task Planning and Tool Usage of Large Language Model-based AI Agents**, FMDM @ NeurIPS 2023 [[paper](https://openreview.net/forum?id=GrkgKtOjaH)] 
- **TPTU-v2: Boosting Task Planning and Tool Usage of Large Language Model-based Agents in Real-world Systems**, LLMAgents @ ICLR 2024 [[paper](https://doi.org/10.48550/arXiv.2311.11315)] 

### :world_map: World Modeling
<!-- #### LLM as World Models -->
- **Can Language Models Serve as Text-Based World Simulators?**, ACL 2024 [[paper](https://arxiv.org/abs/2406.06485)] | [[code]](https://github.com/cognitiveailab/GPT-simulator)
- **Making Large Language Models into World Models with Precondition and Effect Knowledge**, arXiv [[paper](https://arxiv.org/abs/2409.12278)] 💡
<!-- #### LLM-Generated World Models -->
- **Leveraging Pre-trained Large Language Models to Construct and Utilize World Models for Model-based Task Planning**, NeurIPS 2023 [[paper](https://arxiv.org/abs/2305.14909)] | [[code]](https://github.com/GuanSuns/LLMs-World-Models-for-Planning)
- **ByteSized32: A Corpus and Challenge Task for Generating Task-Specific World Models Expressed as Text Games**, EMNLP 2023 [[paper](https://aclanthology.org/2023.emnlp-main.830/)] | [[code]](https://github.com/cognitiveailab/BYTESIZED32/tree/main)

### :bar_chart: Benchmarks
#### Tool-Use Benchmarks
- **MetaTool Benchmark: Deciding Whether to Use Tools and Which to Use**, arXiv.2310.03128 [[paper](https://doi.org/10.48550/arXiv.2310.03128)] 💡
- **TaskBench: Benchmarking Large Language Models for Task Automation**, arXiv.2311.18760 [[paper](https://doi.org/10.48550/arXiv.2311.18760)] 💡

#### Planning Benchmarks
- **Large Language Models Still Can't Plan (A Benchmark for LLMs on Planning and Reasoning about Change)**, NeurIPS 2023 [[paper](https://doi.org/10.48550/arXiv.2206.10498)] 

## :star: Star History

<a href="https://www.star-history.com/#xinzhel/LLM-Agent-Survey&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=xinzhel/LLM-Agent-Survey&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=xinzhel/LLM-Agent-Survey&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=xinzhel/LLM-Agent-Survey&type=Date" />
 </picture>
</a>

## :memo: Citation

If you find our work helpful, you can cite this paper as:

```bibtex
@inproceedings{li-2025-review,
    title = "A Review of Prominent Paradigms for {LLM}-Based Agents: Tool Use, Planning (Including {RAG}), and Feedback Learning",
    author = "Li, Xinzhe",
    editor = "Rambow, Owen  and
      Wanner, Leo  and
      Apidianaki, Marianna  and
      Al-Khalifa, Hend  and
      Eugenio, Barbara Di  and
      Schockaert, Steven",
    booktitle = "Proceedings of the 31st International Conference on Computational Linguistics",
    month = jan,
    year = "2025",
    address = "Abu Dhabi, UAE",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.coling-main.652/",
    pages = "9760--9779",
}
```

```bibtex
@article{li2025survey,
  title={A Survey on LLM Test-Time Compute via Search: Tasks, LLM Profiling, Search Algorithms, and Relevant Frameworks},
  author={Li, Xinzhe},
  journal={arXiv preprint arXiv:2501.10069},
  year={2025}
}
```
