<div align="center">
<h2>    
Resources for LLM-Agents: LLM-Profiled Roles,  Tool Use, Planning, and Feedback Learning (Updated: 24 Oct 2024)
</div>

<div align="center">
<b>Xinzhe Li</b>
</div>

<!-- <div align="center">
<sup>2</sup>Huawei Inc., Shenzhen, China
</div> -->

<br />

<div align="center">
      <a href="https://arxiv.org/abs/2406.05804"><img src="https://img.shields.io/badge/arXiv-2406.05804-b31b1b.svg" alt="Paper"></a>
    <a href="https://github.com/xinzhel/llm-agent-survey"><img src="https://img.shields.io/github/last-commit/xinzhel/llm-agent-survey?color=blue" alt="Github"></a>
    <a href="https://github.com/xinzhel/llm-agent-survey/blob/main/LICENSE"> <img alt="License" src="https://img.shields.io/github/license/xinzhel/llm-agent-survey?color=green"> </a>
</div>

This repository summarizes the resoruce for LLM Agents. For more details, please refer to our papers below. 

Most of the papers are published on ICML, ICLR, NeurIPS, *ACL (including EMNLP), COLM, etc.
We use the 💡 icon to identify articles that have not been peer-reviewed and may be updated.
- [A Review of Prominent Paradigms for LLM-Based Agents: Tool Use (Including RAG), Planning, and Feedback Learning](https://arxiv.org/abs/2406.05804) 💡
  - 23 Oct 2024  The 4th version is available on [arxiv](https://arxiv.org/abs/2406.05804), retitled as "A Review of Prominent Paradigms for LLM-Based Agents: Tool Use (Including RAG), Planning, and Feedback Learning".
  - 9 Jun 2024  The 1st version is available on [arxiv](https://arxiv.org/abs/2406.05804v2), titled as "A Survey on LLM-Based Agents: Common Workflows and Reusable LLM-Profiled Components"

This reading list will be updated periodically, and if you have any suggestions or find some we missed, feel free to contact us! You can submit an issue or send an email (xinzheli212@gmail.com).


## Table of Contents
- [🎁 Surveys](#gift-surveys)
- [🚀 Tool Use](#rocket-tool-use)
- [🧠 Planning](#brain-planning)
  - [Base Workflows](#base-workflows)
  - [Search Workflows](#search-workflows)
  - [Others](#others)
- [🔄 Feedback Learning](#arrows_counterclockwise-feedback-learning)
- [🧩 Composition](#jigsaw-composition)
  - [Planning + Feedback Learning](#planning--feedback-learning)
  - [Planning + Tool Use](#planning--tool-use)
- [📊 Benchmarks](#bar_chart-benchmarks)
- [📝 Citation](#memo-citation)


## :gift: Surveys
- **A Survey on Large Language Model based Autonomous Agents**, Frontiers of Computer Science 2024 [[paper]](https://arxiv.org/abs/2308.11432) | [[code]](https://github.com/Paitesanshi/LLM-Agent-Survey)
- **Augmented Language Models: a Survey**, TMLR [[paper]](https://openreview.net/forum?id=jh7wH2AzKK)
- [2024/02/05] **Understanding the planning of LLM agents: A survey**, arXiv [[paper]](https://arxiv.org/abs/2402.02716)

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
- **Tree of Thoughts: Deliberate Problem Solving with Large Language Models**, NeurIPS 2023 [[paper](https://doi.org/10.48550/arXiv.2305.10601)]
- **Reasoning with Language Model is Planning with World Model**, EMNLP 2023 [[paper](https://api.semanticscholar.org/CorpusID:258865812)]
- **Graph of Thoughts: Solving Elaborate Problems with Large Language Models**, AAAI 2024 [[paper](https://doi.org/10.48550/arXiv.2308.09687)]
- **Tree-Planner: Efficient Close-loop Task Planning with Large Language Models**, ICLR 2024 [[paper](https://openreview.net/forum?id=Glcsog6zOe)] 
- **Plan, Verify and Switch: Integrated Reasoning with Diverse X-of-Thoughts**, EMNLP 2023 [[paper](https://doi.org/10.48550/arXiv.2310.14628)] 
- **LLM Reasoners: New Evaluation, Library, and Analysis of Step-by-Step Reasoning with Large Language Models**, COLM2024 [[paper]](https://arxiv.org/abs/2404.05221) | [[code]](https://github.com/maitrix-org/llm-reasoners)
- **Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models**, arXiv.2310.04406 [[paper](https://doi.org/10.48550/arXiv.2310.04406)] 💡
- **Large Language Model Guided Tree-of-Thought**, arXiv.2305.08291 [[paper](https://doi.org/10.48550/arXiv.2305.08291)]💡

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
- **ToolChain\*: Efficient Action Space Navigation in Large Language Models with A* Search**, ICLR 2024 [[paper](https://openreview.net/forum?id=B6pQxqUcT8)] 
- **TPTU: Task Planning and Tool Usage of Large Language Model-based AI Agents**, FMDM @ NeurIPS 2023 [[paper](https://openreview.net/forum?id=GrkgKtOjaH)] 
- **TPTU-v2: Boosting Task Planning and Tool Usage of Large Language Model-based Agents in Real-world Systems**, LLMAgents @ ICLR 2024 [[paper](https://doi.org/10.48550/arXiv.2311.11315)] 

### :bar_chart: Benchmarks
#### Tool-Use Benchmarks
- **MetaTool Benchmark: Deciding Whether to Use Tools and Which to Use**, arXiv.2310.03128 [[paper](https://doi.org/10.48550/arXiv.2310.03128)] 💡
- **TaskBench: Benchmarking Large Language Models for Task Automation**, arXiv.2311.18760 [[paper](https://doi.org/10.48550/arXiv.2311.18760)] 💡

#### Planning Benchmarks
- **Large Language Models Still Can't Plan (A Benchmark for LLMs on Planning and Reasoning about Change)**, NeurIPS 2023 [[paper](https://doi.org/10.48550/arXiv.2206.10498)] 


## :memo: Citation

If you find our work helpful, you can cite this paper as:

```bibtex
@article{li2024review,
  title={A Review of Prominent Paradigms for LLM-Based Agents: Tool Use (Including RAG), Planning, and Feedback Learning},
  author={Li, Xinzhe},
  journal={arXiv preprint arXiv:2406.05804},
  year={2024}
}
```
