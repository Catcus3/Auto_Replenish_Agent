# Auto_Replenish_Agent

This is an agent built with Bedrock and the Langchain Framwork,  using the model Claude Sonnet 3.  
The agent assists in stock replenishment in retail and aims to reduce stockouts, overstocks and backorders. 

The agent's tools: 
- retriever 
- datetime
- Tavily
- Wikipedia
- maths - Python REPL

We attempted several extensions including: 
- memory (created a chain with a runnable) 
- multi-agent systems
- sending emails (instead of just drafting them)
- UI using Gradio
- guardrails 
