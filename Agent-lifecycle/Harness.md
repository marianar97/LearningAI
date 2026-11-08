
[[What is a Harness?]]
A harness is software that provides an **environment** for an AI model to operate within. 
**Anatomy of the workflow harness** :
- system prompt
- tools
- framework of how the agent behaves
	- agentic loop

[[The Anatomy of an Agent Harness]]
Agent = Model + Harness. If you're not the model, you're the harness 
- System prompt
- Tools, skills, MCPs
- Bundled infrastructure (filesystem, sandbox, browser)
- Orchestration Layer (subagents, handoffs, model routing)
- Hooks for deterministic execution (compaction, tool calling)
![[Pasted image 20261108000440.png]]

