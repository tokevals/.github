# TokEvals

TokEvals is an open-source research and engineering project for measuring,
explaining, visualizing, and reducing multilingual LLM tokenization
inefficiency. Korean is the first optimization case, English is the initial
baseline, and the framework is designed to support additional languages
through configuration rather than language-specific assumptions.

Our central question is whether language-aware tokenization and model
adaptation can lower cost per successfully completed task while preserving
quality and capabilities across languages. Token count, model quality,
latency, memory, energy, and monetary cost remain separate measurements.

| Repository | Purpose |
| --- | --- |
| [TokEvals](https://github.com/tokevals/tokevals) | Reusable Python library for multilingual tokenizer evaluation. |
| [TokEvals Explorer](https://github.com/tokevals/tokevals-dashboard) | Public byte-safe token comparison dashboard and hosted-count Worker. |
| [TokEvals Research](https://github.com/tokevals/tokevals-research) | Research scope, experiment configurations, reproducible results, and writeups. |

Explore the live tokenizer comparison at [tokeval.dev](https://tokeval.dev)
and find model weights and model cards at
[huggingface.co/tokevals](https://huggingface.co/tokevals).

A [Tanager Labs](https://github.com/tanagerlabs) project.
