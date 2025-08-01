# FG-EVQA: Fine-Grained Explainable Visual Question Answering

FG-EVQA is designed to evaluate and improve fine-grained, explainable reasoning in Visual Question Answering (VQA). Unlike traditional VQA benchmarks that compress complex cognition into a single-step process, FG-EVQA decomposes visual reasoning into a multi-step pipeline — **localization, attribute extraction, and logical reasoning** — better reflecting human-like understanding.

## Key Features

- **Novel Task Design**: FG-EVQA introduces a fine-grained explainable VQA task with sub-questions for each reasoning stage, enhancing interpretability and error traceability.
- **Large-Scale Dataset**: The dataset contains **319,624 high-quality QA pairs**, covering **9,667 real-world images** with around **8 questions per image**.
- **Comprehensive Evaluation**: Extensive benchmarking of popular Large Vision-Language Models (LVLMs) reveals their current limitations in fine-grained reasoning and explanation credibility.

FG-EVQA offers a new path for developing VQA systems with better transparency, diagnostic feedback, and human-aligned reasoning structures.

**Note**: We currently provide `FG-EVQA-subset.json`, a publicly available **subset of 15,802 samples** for early research and development.
