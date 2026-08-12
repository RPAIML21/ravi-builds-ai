# Applied AI Portfolio

Six hands-on generative AI projects — agentic pipelines, RAG systems, and LLM-as-judge evaluation — built while getting into the mechanics of prompt engineering, LangChain/LangGraph orchestration, and retrieval-augmented generation.

I'm a Technical Program Manager / AI Product Manager by day, currently leading delivery on [Serv360AI](#), a GenAI-powered ITSM and observability platform. These projects are where I got hands-on with the build side myself — writing the prompts, wiring the agents, and designing the evaluation harnesses directly, rather than only directing engineers who own that layer. That distinction matters to me: I'd rather be precise about what I built myself than blur it with what I managed.

## Projects

| # | Project | What it demonstrates |
|---|---|---|
| 1 | [AI Email Assistant](./01-ai-email-assistant) | Inbox summarization, urgency classification, response drafting, LLM-as-judge evaluation |
| 2 | [Knowledge Base RAG Chatbot](./02-knowledge-base-rag-chatbot) | Embeddings + vector store, conversational retrieval, source citation, human-escalation fallback |
| 3 | [Research Proposal Automation Agent](./03-research-proposal-agent) | NOFO-aligned proposal drafting, FAISS semantic search, LLM-as-judge scoring against funder criteria, human-in-the-loop review |
| 4 | [News Discovery Agent](./04-news-discovery-agent) | Autonomous topic/keyword filtering, relevance & recency ranking, source-attributed digesting |
| 5 | [Competitive Analysis Agent](./05-competitive-analysis-agent) | Multi-source research automation, signal extraction, structured competitive-intelligence briefs |
| 6 | [AI Assistant with LangChain Agents](./06-langchain-multitool-assistant) | Tool-calling, memory, multi-step reasoning, agent orchestration across multi-turn tasks |

## Common threads across all six

- **Prompt engineering** as a first-class design activity, not an afterthought
- **RAG** (retrieval-augmented generation) for grounding outputs in real source material
- **Agent orchestration** via LangChain/LangGraph — tool use, multi-step reasoning, memory
- **LLM-as-judge evaluation** — every project includes a structured pass for scoring its own output against defined criteria, not just "does it run"
- **Honest scoping** — each README states clearly what's a course/self-directed build vs. production work, and what's fictional case-study data vs. real

## About me

I'm Ravi Pallepogu — 20+ years in enterprise technology delivery (Avaya, Cisco, Microsoft, cybersecurity operations), now focused on applied AI product and technical program management. Currently building Serv360AI, a RAG- and agent-based observability/ITSM platform, while getting hands-on with the underlying AI engineering through projects like these.

- LinkedIn: [linkedin.com/in/ravi-pallepogu-06a302b](https://linkedin.com/in/ravi-pallepogu-06a302b)
- Email: ravi.agc15@gmail.com
