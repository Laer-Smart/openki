This is a living document that will be updated over time.

This project is focused on **building tools** to support the training of **multimodal AI systems**—models that learn not only from text but also from vision, audio, interaction, and other sensorimotor input. Inspired by the ideas of LeCun, Hinton, and Bengio, we recognize that true intelligence cannot be learned from language alone. This roadmap outlines how we will build an extensible toolchain to support this broader, richer training paradigm.

In AI, **training** is the process of teaching a model by exposing it to data and adjusting its parameters to learn patterns and relationships. **Inference** is using that trained model to make predictions. This project focuses entirely on the **training phase**—where learning happens, and where joint representations from different modalities are formed.

Legend:

* 🟢 = Implemented
* 🟡 = Ongoing work
* 🔴 = Not started

---

## 🧱 Phase 1 (🔴): Foundations (Now – Q4 2025)

Establish design for tools that support multimodal learning pipelines.

* \[🔴] Define requirements and modular architecture for training tools
* \[🔴] Research data formats and conversion specs for vision, text, and audio
* \[🔴] Draft schema for multimodal training configurations (YAML/JSON)
* \[🔴] Plan minimal energy-based training loop (joint embeddings, contrastive loss)
* \[🔴] Design logging and evaluation strategy for multiple input/output types

---

## 🚀 Phase 2 (🔴): Systems Integration (Q1–Q2 2026)

Develop end-to-end training system for rich, multimodal interactions.

* \[🔴] Implement multimodal training orchestrator (text, images, audio)
* \[🔴] Build plugin system for custom preprocessing and augmentation pipelines
* \[🔴] Create synthetic environment simulator for grounded learning (toy tasks)
* \[🔴] Draft interactive UI for visualizing learning dynamics across modalities

---

## 🌐 Phase 3 (🔴): Collaborative Intelligence (Q3–Q4 2026)

Support reproducibility, sharing, and team-based model development.

* \[🔴] Build pipeline composer UI for chaining multimodal modules
* \[🔴] Integrate versioning, checkpoint tracking, and experiment resumption
* \[🔴] Add support for declarative experiment setup via natural language
* \[🔴] Enable multi-user access and sharing of training runs and results
* \[🔴] Real-time collaboration tools (WebSockets, notebooks, shared state)

---

## 🧹 Long-Term Vision (2027+)

Build the standard open platform for training sensorimotor and world models.

* \[🔴] Fully open-source training toolchain with reproducible runs
* \[🔴] Support for embodied learning and interaction data
* \[🔴] Marketplace for multimodal datasets, configs, and training agents
* \[🔴] Offline-first, privacy-safe support for training local world models

---

Pull requests, ideas, and experiments are welcome at every phase.
