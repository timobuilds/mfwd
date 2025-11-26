# Agents

**Agents = llm + memory + planning skills + tool use X n loops**

<figure><img src="../.gitbook/assets/Screenshot 2025-11-25 at 21.55.33.png" alt=""><figcaption><p>how a human performs a task versus an agetn</p></figcaption></figure>

[Lilian Weng Agents](https://lilianweng.github.io/posts/2023-06-23-agent/) (dated but foundationally correct)



**Introduction to Agents** \
Lay the groundwork for building intelligent, autonomous systems:

* foundational concepts of AI agents
* defining characteristics
* agentic architectures vs. traditional LLM applications,&#x20;



**Agent Tools & Interoperability with MCP**\
Expore how agents can 'take action'

* via external functionalities and APIs
* using Model Context Protocol (MCP)<br>

**Context Engineering: Sessions & Memory**\
Build AI agents that can:

* remember past interactions and maintain context.&#x20;
* Implement short-term and long-term memory to create more robust agents capable of handling complex, multi-turn tasks.

**Agent Quality**\
Build robust and reliable AI agents:

* master the critical disciplines of evaluating and improving agents
* observability, logging, and tracing to provide visibility
* key metrics and evaluation strategies to optimize performance

**Production** \
Deploy and scale AI agents for real-world use.&#x20;

* Best practices for deploying your agents in product&#x20;
* multi-agent systems with the Agent2Agent (A2A) Protocol.





* Multi-agent system, including any combination of:
  * Agent powered by an LLM
  * Parallel agents
  * Sequential agents
  * Loop agents
* Tools, including:
  * MCP
  * Custom tools
  * Built-in tools, such as Google Search or Code Execution
  * OpenAPI tools
  * Long-running operations (pause/resume agents)
* Sessions & Memory
  * Sessions & state management (e.g., InMemorySessionService)
  * Long-term memory (e.g., Memory Bank)
* Context engineering (e.g., context compaction)
* Observability: Logging, Tracing, Metrics
* Agent evaluation
* A2A Protocol
* Agent deployment
