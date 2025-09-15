# basicllm — Local LLM (Retrospective, May 2025)

**Summary:** In **May 2025** I ran a small **local language model** on my personal machine and used a simple **Streamlit** chat UI to test prompts for summaries and Q&A.

## Reproduce (now)
```bash
# Quick local run with Ollama
ollama pull mistral
ollama run mistral
# (optional UI later: a tiny Streamlit app will be added under /app)
