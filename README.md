# Machine learning systems that trade

Execution algorithms, commodity signals, and macro forecasting across
capital markets and private investment. Based in Geneva.
Background and contact on [LinkedIn](https://www.linkedin.com/in/carlbarrelet).

## Current work

**[oil-agent-bench](https://github.com/Barrelet/oil-agent-bench)** — The same game played
on one market: front-month WTI crude oil, one decision a day, long, short or flat, over a
full year replayed. Three kinds of player take the seat: a small open LLM on a laptop
(Qwen3 8B), a frontier LLM through the API (GPT-5.1), and a time-series foundation model
(TimesFM 2.5). Each LLM plays with three prompts, and every run is scored against doing
nothing, holding oil and 1,000 random traders under the same rules and costs, so it only
gets credit for beating chance. Each player also states a daily probability that oil
closes higher, scored on its own. Results are cached, so every run is reproducible.
A research experiment on a paper account: not investment advice, and no result here is a
reason to trade anything.

**[agent-alpha-bench](https://github.com/Barrelet/agent-alpha-bench)** — An evaluation
harness that puts LLMs in the seat of a medium-term US-equity investor. Every model faces
the same 50 names, rules and costs in a paper-trading replay, and is scored against
rule-based agents and 1,000 random traders, so that it only gets credit for beating what
chance and simple rules already achieve. Local models via Ollama; any OpenAI-compatible
API otherwise. Results are cached, so every run is reproducible.


