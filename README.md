⭐ If you find this repository helpful, please consider giving it a ⭐ here on GitHub (click the star button in the top right corner) 
It's a quick way to show support for this openly available code. ⭐

![OReilly_logo_rgb.png](resources%2FOReilly_logo_rgb.png)

# AI Agents - The definitive Guide
This is the corresponding code for the book AI Agents - The Definitive Guide
the book can be found [here](oreillymedia.pxf.io/POEx4e) and on [Amazon](https://www.amazon.com/Agents-Definitive-Deployment-Evaluation-Production/dp/B0GTYKTZHG/ref=sr_1_1?crid=3IKPXNW1IGD7V&dib=eyJ2IjoiMSJ9.n6XdCRmcIshseCli02TdjNbRQDKjQdxsP1qL6u931_bI2BtpzIRu5R9-o2YkOb_vzPUHPjhf4OoJU0trC-J3JmVQq6-SPw_ESya-oNpS-KR_8Z9BT3OiAZtJrwvA-MietSkrVBlK-0fs_pKJ5lgNNlF_oAxQYPzMOHeovQXa2dXt5D3LlnrVrZp_ZOQSQpMBJMGXrVKT4FSwOqW4ioOEhymB94LPQi3W15wVpSjkftM.tvvAb5_XOOez9Drd930kMnl_WBhjvEhzEp1C9miRRSc&dib_tag=se&keywords=ai+agents+the+definitive+guide&qid=1782032850&sprefix=ai+agents+the%2Caps%2C232&sr=8-1). The book has an [accompanying website](https://ai-agents-the-definitive-guide.com/) with quizzes and additional material, as well as a [Discord channel](https://discord.gg/pqeHTvzdhJ). 

## TOC
- Chapter 1 From LLMs to Agents: The Foundational Blueprint
- Chapter 2 Architectures and Patterns: Planning, Reactivity, and Multi-Agent-Systems
- Chapter 3 Advanced Planning, Reasoning, and Scalable Execution in Agents
- Chapter 4 Models Behind the Agents: Capabilities and Optimization
- Chapter 5 From Prototypes to Production: Contracts, Tools, and Reliable Execution
- Chapter 6 Secure Execution and Tool Governance 
- Chapter 7 Deploying Agents in Real Products 
- Chapter 8 Foundational Evaluation and Operational Observation of Agentic Systems
- Chapter 9 Customized and Advanced Evaluation of Agentic Systems 
- Chapter 10 Agent Memory: How Persistence Turns Agents Into Evolving Systems
- Chapter 11 From Compute to Cost: Designing Efficient Agentic Systems
- Chapter 12 Threat Modeling for AI Agents

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with `CH` followed by the chapter number. For example, CH01.
The notebooks are then organized as follows: `ch01_attention_mechanism_variations.ipynb`, where `ch01` indicates the chapter
and `attention_mechanism_variations` what is done in the notebook. 


## Repo structure

```
├── LICENSE
├── README.md             <- The top-level README for developers using this project.
├── CH01                  <- Per chapter folder with Jupyter notebooks.
    ├── [name].ipynb      <- Jupyter notebooks with naming as mentioned above.
├── CH02                  <- Per chapter folder with Jupyter notebooks.
...                       <- Same structure for all chapters.
├── utils                 <- Custom classes and functions and utility functions.
├── resources             <- Some miscellaneous resources.

```


## Running the Notebooks

Every notebook can be opened and run on Google Colab directly from the links below. Just click the **Open In Colab** badge next to the notebook you want to run.

### Chapter 1 — From LLMs to Agents: The Foundational Blueprint
| Notebook | Colab |
|---|---|
| Code Examples | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/CH01/ch01_code_examples.ipynb) |

### Chapter 2 — Architectures and Patterns: Planning, Reactivity, and Multi-Agent-Systems
| Notebook | Colab |
|---|---|
| Chain-of-Thought (CoT) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/CH02/ch02_CoT.ipynb) |
| Tree-of-Thought (ToT) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/CH02/ch02_ToT.ipynb) |
| ReAct | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/CH02/ch02_react.ipynb) |
| Human-in-the-Loop (HITL) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/CH02/ch02_HITL.ipynb) |
| Hierarchical Agent Teams | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/CH02/ch02_hierarchical_agent_teams.ipynb) |
| Swarms | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/CH02/ch02_swarms.ipynb) |

### Chapter 3 — Advanced Planning, Reasoning, and Scalable Execution in Agents
| Notebook | Colab |
|---|---|
| ART + RULER | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/CH03/ch03_ART_RULER.ipynb) |
| RULER Cat Poems | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/CH03/ch03_RULER_cat_poems.ipynb) |
| TreeQuest (AB-MCTS) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/CH03/ch03_TreeQuest.ipynb) |

### Chapter 4 — Models Behind the Agents: Capabilities and Optimization
| Notebook | Colab |
|---|---|
| Supervisor Agent Team | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/CH04/ch04_supervisor_agent_team.ipynb) |

### Chapter 5 — From Prototypes to Production: Contracts, Tools, and Reliable Execution
| Notebook | Colab |
|---|---|
| Deep Agents | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/CH05/ch05_deep_agents.ipynb) |
| MCP with LangGraph | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/CH05/ch05_mcp_langgraph.ipynb) |
| Product Reliability Rule | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/CH05/ch05_product_reliability_rule.ipynb) |
| Pydantic Agent Consistency | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/CH05/ch05_pydantic_agent_consistency.ipynb) |

### Chapter 6 — Secure Execution and Tool Governance
| Notebook | Colab |
|---|---|
| A2A + MCP Governed | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch06/ch06_A2A_MCP_Governed.ipynb) |
| MCP Server with Composio | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch06/ch06_MCP_server_composio.ipynb) |
| LangGraph + E2B Sandbox | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch06/ch06_langgraph_E2B.ipynb) |
| Programmatic Tool Calling (Monty) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch06/ch06_programmatic_tool_calling_monty.ipynb) |

### Chapter 7 — Deploying Agents in Real Products
| Notebook | Colab |
|---|---|
| Hardening Backbone | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch07/ch07_hardening_backbone.ipynb) |
| Inference Backends | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch07/ch07_inference_backends.ipynb) |
| Model Fallback | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch07/ch07_model_fallback.ipynb) |

### Chapter 8 — Foundational Evaluation and Operational Observation of Agentic Systems
| Notebook | Colab |
|---|---|
| OWASP ASI 2026 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch08/ch08_OWASP_ASI_2026.ipynb) |
| Evaluation Harness | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch08/ch08_eval_harness.ipynb) |

### Chapter 9 — Customized and Advanced Evaluation of Agentic Systems
| Notebook | Colab |
|---|---|
| AgentVista | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch09/ch09_agentvista.ipynb) |
| External Evaluation Pipelines (Langfuse) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch09/ch09_example_external_evaluation_pipelines_Langfuse.ipynb) |
| External Evaluation Pipelines (LangSmith) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch09/ch09_example_external_evaluation_pipelines_langsmith.ipynb) |
| RULER Trace Answer Ranking (LangSmith) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch09/ch09_ruler_trace_answer_ranking_langsmith.ipynb) |

### Chapter 10 — Agent Memory: How Persistence Turns Agents Into Evolving Systems
| Notebook | Colab |
|---|---|
| Agent Memory with LangGraph | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch10/ch10_agent_memory_langgraph.ipynb) |
| Memory vs. No Memory | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch10/ch10_memory_no_memory.ipynb) |
| Memory Topologies | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch10/ch10_memory_topologies.ipynb) |

### Chapter 11 — From Compute to Cost: Designing Efficient Agentic Systems
| Notebook | Colab |
|---|---|
| Agent Cost Estimator by Topology | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch11/ch11_agent_cost_estimator_based_on_topology.ipynb) |
| Memoizing Swarm Research Engine | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch11/ch11_memoizing_swarm_research_engine.ipynb) |
| Memory Footprint, Throughput & GPU Requirements | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch11/ch11_memory_footprint_throughput_and_GPU_requirements.ipynb) |

### Chapter 12 — Threat Modeling for AI Agents
| Notebook | Colab |
|---|---|
| LlamaFirewall | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/ai-agents-the-definitive-guide/blob/main/ch12/ch12_LlamaFirewall.ipynb) |


