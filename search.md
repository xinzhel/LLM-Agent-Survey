Papers related to LLM inference via search are generally introduced in the following perspectives:
1. **Year of Publication and Publication Venue**: We choose to organize the paper based on the publication information, as shown in the Table of Contents below. 
> The reason why not organize the paper list based on other persepctives is because one paper have to be listed more than once, since some papers are devised for different tasks and contains multiple LLM-Profiled Roles.
2. **Tasks**, including Reasoning, Code Generation, Web Navigation
3. **LLM-Profiled Roles**, including policy, evaluator, and transition.
4. **Search Algorithms**, including BFS, DFS, MCTS, Beam Search, and others.

For most of the papers, please refer to the Section 5 in our surveys for details, unless otherwise specified.

## Table of Contents
- [ICLR 2025](#iclr-2025)
- [Other Venues or Preprint 2025](#other-venues-or-preprint-2025)
- [ICML/ICLR/NeuIPS 2024](#icml/iclr/neuips-2024)
- [*ACL 2024](#*acl-2024)
- [Other Venues or Preprint 2024](#other-venues-or-preprint-2024)
- [ICML/ICLR/NeuIPS 2023](#icml/iclr/neuips-2023)
- [*ACL 2023](#*acl-2023)
- [Other Venues or Preprint 2023](#other-venues-or-preprint-2023)
- [Graph/Tree-Based Planning w.o. Search](#tree-or-graph-planning-without-search)

## ICLR 2025
- **Think-on-Graph 2.0: Deep and Faithful Large Language Model Reasoning with Knowledge-guided Retrieval Augmented Generation**, ICLR 2025 [[paper](https://openreview.net/forum?id=oFBu7qaZpS)]
    + Search Algorithm: Beam Search
- **Mutual Reasoning Makes Smaller LLMs Stronger Problem-Solver**, ICLR 2025 [[paper](https://openreview.net/forum?id=6aHUmotXaw)]
    + Search Algorithm: MCTS
- **Monte Carlo Planning with Large Language Model for Text-Based Game Agents**, ICLR 2025 [[paper](https://openreview.net/forum?id=r1KcapkzCt)]
    + Search Algorithm: MCTS
- **Efficient Evolutionary Search Over Chemical Space with Large Language Models**, ICLR 2025 [[paper](https://openreview.net/forum?id=awWiNvQwf3)]
    + Search Algorithm: Evolutionary Search
- **DOTS: Learning to Reason Dynamically in LLMs via Optimal Reasoning Trajectories Search**, ICLR 2025 [[paper](https://openreview.net/forum?id=tn2mjzjSyR)]
    + See Section 6: LLM Inference + Search Beyond Sequential Decision Making
- **What Makes Large Language Models Reason in (Multi-Turn) Code Generation?**, ICLR 2025 [[paper](https://openreview.net/forum?id=Zk9guOl9NS)]
    + See Section 6: LLM Inference + Search Beyond Sequential Decision Making 
- **Strategist: Self-improvement of LLM Decision Making via Bi-Level Tree Search**, ICLR 2025 [[paper](https://openreview.net/forum?id=gfI9v7AbFg)]
    + See Section 6: LLM Inference + Search Beyond Sequential Decision Making
- **AFlow: Automating Agentic Workflow Generation**, ICLR 2025 [[paper](https://openreview.net/forum?id=z5uVAKwmjf)]
    + See Section 6: LLM Inference + Search Beyond Sequential Decision Making
- **Planning in Natural Language Improves LLM Search for Code Generation**, ICLR 2025 [[paper](https://openreview.net/forum?id=48WAZhwHHw)]
    + See Section 6: LLM Inference + Search Beyond Sequential Decision Making
- **DeFT: Decoding with Flash Tree-attention for Efficient Tree-structured LLM Inference**, ICLR 2025 [[paper](https://openreview.net/forum?id=2c7pfOqu9k)]
    + See Section 7: Related Work 
- **Scaling Test-Time Compute Optimally Can be More Effective than Scaling LLM Parameters**, ICLR 2025 [[paper](https://openreview.net/forum?id=4FWAwZtd2n)]
    + See Section 8: Discussion
- **Searching for Optimal Solutions with LLMs via Bayesian Optimization**, ICLR 2025 [[paper](https://openreview.net/forum?id=aVfDrl7xDV)]
    + To be reviewed

## Other Venues or Preprint 2025
- **How Far are LLMs from Real Search? A Comprehensive Study on Efficiency, Completeness, and Inherent Capabilities**, arXiv 2025 [[paper](https://arxiv.org/abs/2502.18387)]
    + To be reviewed

## ICML/ICLR/NeuIPS 2024
- **Think-on-Graph: Deep and Responsible Reasoning of Large Language Model on Knowledge Graph**, ICLR 2024 [[paper](https://openreview.net/forum?id=nnVO1PvbTv)]
    + Search Algorithm: Beam Search
- **ToolChain*: Efficient Action Space Navigation in Large Language Models with A* Search**, ICLR 2024 [[paper](https://openreview.net/forum?id=B6pQxqUcT8)]
    + Search Algorithm: A*
- **Alphazero-like Tree-Search can guide large language model decoding and training**, ICML 2024 [[paper](https://arxiv.org/abs/2309.17179)]
    + Search Algorithm: MCTS
- **Language Agent Tree Search Unifies Reasoning, Acting, and Planning in Language Models**, ICML 2024 [[paper](https://openreview.net/forum?id=6LNTSrJjBe)]
    + Search Algorithm: MCTS
- **Tree-Planner: Efficient Close-loop Task Planning with Large Language Models**, ICLR 2024 [[paper](https://openreview.net/forum?id=Glcsog6zOe)]
    + See Section 7: Related Work

## *ACL 2024
- **When is Tree Search Useful for {LLM} Planning? It Depends on the Discriminator**, ACL 2024 [[paper](https://aclanthology.org/2024.acl-long.738/)]
    + Search Algorithm: MCTS
- **Everything of Thoughts: Defying the Law of Penrose Triangle for Thought Generation**, ACL findings 2024 [[paper](https://aclanthology.org/2024.findings-acl.95/)]
    + Search Algorithm: MCTS
- **Tree-of-Traversals: A Zero-Shot Reasoning Algorithm for Augmenting Black-box Language Models with Knowledge Graphs**, ACL 2024 [[paper](https://aclanthology.org/2024.acl-long.665/)]
    + Search Algorithm: BFS/DFS
- **LLM-A\*: Large Language Model Enhanced Incremental Heuristic Search on Path Planning**, EMNLP findings 2024 [[paper](https://arxiv.org/pdf/2407.02511)] | [[code]](https://github.com/SilinMeng0510/llm-astar/)
    + Search Algorithm: A*

## Other Venues or Preprint 2024
- **LLM Reasoners: New Evaluation, Library, and Analysis of Step-by-Step Reasoning with Large Language Models**, COLM2024 [[paper]](https://arxiv.org/abs/2404.05221) | [[code]](https://github.com/maitrix-org/llm-reasoners)
- **Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models**, arXiv.2310.04406 [[paper](https://doi.org/10.48550/arXiv.2310.04406)] 💡
- **Large Language Model Guided Tree-of-Thought**, arXiv.2305.08291 [[paper](https://doi.org/10.48550/arXiv.2305.08291)]💡
- **Tree Search for Language Model Agents**, Under Review [[paper](https://openreview.net/forum?id=kpL66Mvd2a)]💡
    + Search Algorithm: Best-First Search
- **Q\*: Improving multi-step reasoning for llms with deliberative planning**, Under Review [[paper](https://openreview.net/forum?id=F7QNwDYG6I)]💡
    + Search Algorithm: A*

## ICML/ICLR/NeuIPS 2023
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
- **Efficient Evolutionary Search Over Chemical Space with Large Language Models**, ICLR 2025 [[paper](https://openreview.net/forum?id=awWiNvQwf3)]
    + Search Algorithm: Evolutionary Search

## *ACL 2023
- **Plan, Verify and Switch: Integrated Reasoning with Diverse X-of-Thoughts**, EMNLP 2023 [[paper](https://doi.org/10.48550/arXiv.2310.14628)] 
- **RAP: Reasoning with Language Model is Planning with World Model**, EMNLP 2023 [[paper](https://api.semanticscholar.org/CorpusID:258865812)]
    + Search Algorithm: MCTS
- **Prompt-Based Monte-Carlo Tree Search for Goal-oriented Dialogue Policy Planning**, EMNLP 2023 [[paper](https://aclanthology.org/2023.emnlp-main.439/)]
    + Search Algorithm: MCTS
- **Monte Carlo Thought Search: Large Language Model Querying for Complex Scientific Reasoning in Catalyst Design**, EMNLP findings 2023 [[paper](https://aclanthology.org/2023.findings-emnlp.560/)]
    + Search Algorithm: MCTS

## Other Venues or Preprint 2023
- **Agent q: Advanced reasoning and learning for autonomous ai agents**, arXiv.2309.10814 [[paper](https://arxiv.org/abs/2408.07199)] 💡
    + Search Algorithm: MCTS
- **Graph of Thoughts: Solving Elaborate Problems with Large Language Models**, AAAI 2024 [[paper](https://doi.org/10.48550/arXiv.2308.09687)]
    + See Section 7: Related Work
