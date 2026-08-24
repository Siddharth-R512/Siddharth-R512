# hey, I'm Siddharth 👋

I'm an AI engineer. I build agent systems that drive real API surfaces through typed tools, and retrieval systems that stay grounded in real data.

The part I care most about is measurement. Most LLM work has no ground truth, so it's easy to ship something that feels good and impossible to say whether it's right. I spend a disproportionate amount of time on eval harnesses strict enough to catch a result that looks like an improvement but isn't -- including my own.

## : what I work on

- 🧩 **MCP & agent orchestration** -- exposing existing APIs as typed tools, scoped tool catalogs, one-agent-per-domain routing to keep selection accuracy stable as coverage grows
- 🔍 **Retrieval** -- structural chunking, hybrid BM25 + RRF, version-aware filtering
- 📏 **Evaluation** -- frozen golden sets, deterministic LLM-free scoring, pre-registered predictions, per-question analysis instead of aggregate-only reporting
- 🔒 **Structured output** -- schema validation in JSON mode, retry on violation, pinned seeds for reproducible runs

I build directly against SDKs rather than reaching for a framework, mostly so I can see what's actually happening in the retrieval and tool-call paths.

## : stack

Python · FastAPI · Pydantic · MCP (FastMCP) · Qdrant · OpenAI / Azure OpenAI · SQL · Git

## : connect

Happy to talk about retrieval, agent design, or how you're evaluating any of it.

- 📧 siddharth.rajendranps@gmail.com
- 💼 LinkedIn: [@siddharth-rajendranps](https://linkedin.com/in/siddharth-rajendranps)
