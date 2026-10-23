# tokevals

tokevals is an open-source research and engineering project for measuring,
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
| [tokevals](https://github.com/tokevals/tokevals) | Reusable Python library for multilingual tokenizer evaluation. |
| [tokevals-lib](https://github.com/tokevals/tokevals-lib) | Public model catalog and validation tools. |
| [tokevals-research](https://github.com/tokevals/tokevals-research) | Research scope, experiment configurations, reproducible results, and writeups. |

Explore the hosted tokenizer comparison at [tokevals.dev](https://tokevals.dev)
(the dashboard implementation is private), and find model weights and model cards at
[huggingface.co/tokevals](https://huggingface.co/tokevals).

A [Tanager Labs](https://github.com/tanagerlabs) project.
