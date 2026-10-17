## Welcome to AI999X Labs 👋

**AI999X builds verifiable AI**: models and engines whose answers are checked before you see them. We are building a
**model factory** that produces compact, open models across the whole range of AI tasks — language, vision, audio,
multimodal, tabular and time series, reinforcement learning and robotics, graphs, and science and mathematics — each
with measured accuracy, honest limits and a small, fast deployment (ONNX on any CPU, Safetensors for training).

**How we work:** a teacher model writes candidate data; deterministic engines, libraries and test suites check every
record; only what passes becomes a dataset, a model or a capability. Every release ships with its evaluation —
including how often it is wrong — and refuses rather than guesses where it cannot verify an answer.

### First releases (Apache-2.0)

| Release | What it does |
|---|---|
| [physics-ai999x](https://github.com/AI999X/physics-ai999x) · [🤗](https://huggingface.co/AI999X/physics-ai999x) | Offline, verified physics solver: 148 certified capabilities, step-by-step answers with units and LaTeX, 365 exact ONNX formula graphs, and a 33M-parameter ONNX decision model that answers free-form questions only through a verification gate (0 wrong on held-out questions) |
| [algebra-ai999x](https://github.com/AI999X/algebra-ai999x) · [🤗](https://huggingface.co/AI999X/algebra-ai999x) | Equations up to quartics, systems, inequalities, logarithms, sequences, matrices and proofs, plus a 33M-parameter ONNX decision model that reads free-form questions (0 wrong on 364 held-out answers) |

`pip install physics-ai999x algebra-ai999x`

### Roadmap

Mathematics (geometry to calculus, statistics and linear algebra) · chemistry and the other sciences · text
classification, token classification, question answering, summarization, translation and sentence similarity ·
image classification, object detection, segmentation and OCR · speech recognition and audio classification ·
document and visual question answering · tabular classification, regression and time-series forecasting ·
reinforcement learning and robotics · graph machine learning. Each arrives when it measures up, with its numbers.

Created and engineered by **Ibnul Jaif Farabi** · [ai999x.com](https://ai999x.com) · [Hugging Face](https://huggingface.co/AI999X) ·
[ibnuljaiffarabi@ai999x.com](mailto:ibnuljaiffarabi@ai999x.com) ·
[Support the work on Buy Me a Coffee ☕](https://buymeacoffee.com/ibnuljaiffarabi)
