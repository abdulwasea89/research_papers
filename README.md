# Research Papers & Publications

### Abdul Wasea
**Independent Researcher | Artificial Intelligence · Software Engineering · Economics of Automation**

*Exploring how intelligent software systems can reason, remember, adapt, and operate reliably as their environments change.*

[![Research](https://img.shields.io/badge/Focus-Agentic%20AI-2563eb?style=flat-square)](#research-areas)
[![Publications](https://img.shields.io/badge/Publications-Research%20Manuscripts-0f766e?style=flat-square)](#publications)
[![SSRN](https://img.shields.io/badge/SSRN-Research%20Profile-334155?style=flat-square)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7644118)


---

## About this repository

This repository is a central index of my research papers, preprints, technical investigations, and supporting research artifacts. My research explores **reliable artificial intelligence systems** and the **economic implications of automation**, from long-horizon coding-agent memory and software verification to AI-driven changes in human tasks, employment, and productivity.

Each entry identifies its publication or manuscript status. A publicly available preprint is **not necessarily peer-reviewed**; proposed architectures and planned experiments are distinguished from validated experimental results.

## Research areas

- **Agentic AI and autonomous software engineering** — long-running coding tasks, multi-agent collaboration, and dependable actions.
- **Memory and context engineering** — persistent memory, provenance, temporal validity, and context handoffs.
- **Software correctness and verification** — dependency tracking, change-impact analysis, proof obligations, and evidence-based decisions.
- **Uncertainty-aware systems** — partial observability, risk-sensitive verification, and bounded computation.
- **AI, work, and economic change** — task automation, labor displacement and reinstatement, productivity, and policy.
- **Reproducible AI research** — benchmark design, controlled experiments, and transparent limitations.

## Publications

### 01 · Causally Sound Memory Invalidation for Long-Horizon Software Engineering Agents

**Subtitle:** *Transitive Constraints, Partial Observability, and Verification Budgets*  
**Author:** Abdul Wasea  
**Affiliation:** Independent Researcher  
**Type:** Research manuscript / preprint  
**Status:** Publicly available on SSRN; experimental validation proposed, not yet reported in the manuscript

[**Read on SSRN →**](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7644118)

Long-horizon coding agents can preserve past observations, design constraints, and decisions even while a codebase continues to change. A memory can be *historically accurate* yet no longer *safe to rely on*. This paper studies how to identify engineering decisions that need revalidation following upstream changes, without unnecessarily invalidating everything.

The paper introduces **CAVI (Causal Assumption Verification and Invalidation)**, a proposed research architecture using a time-indexed, provenance-annotated **justification hypergraph**. It combines repository change-impact analysis, transitive dependency propagation, uncertainty-aware verification, and guarded handoff between agents.

**Key elements**

- Separates historical observation truth, current applicability, justification validity, and action admissibility.
- Models decisions with conjunctive and alternative sets of supporting premises.
- Gives a *conditional* invalidation-soundness proposition under complete dependency information and other explicit assumptions.
- Discusses missing or latent dependencies and why unconditional open-world guarantees are not established.
- Frames verification selection as a resource-constrained decision problem.
- Proposes **TIDE-Bench** (*Transitive Invalidation of Development Evidence*) for controlled repository-mutation experiments.

> **Research status:** CAVI is proposed as a formal and experimental research agenda. The paper's charts are synthetic illustrations; they are not empirical performance results. The manuscript does not claim that CAVI has been demonstrated to outperform existing systems.

**Suggested citation**

```bibtex
@misc{wasea_cavi_2026,
  author       = {Wasea, Abdul},
  title        = {Causally Sound Memory Invalidation for Long-Horizon Software Engineering Agents: Transitive Constraints, Partial Observability, and Verification Budgets},
  year         = {2026},
  howpublished = {SSRN preprint},
  url          = {https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7644118},
  note         = {SSRN Abstract ID: 7644118}
}
```

### 02 · Can Humans Compete with Artificial Intelligence? The Future of Work and Task Automation

**Author:** Abdul Wasea  
**Affiliation:** Independent Researcher  
**Date written:** July 28, 2026  
**Posted on SSRN:** August 7, 2026  
**Length:** 10 pages  
**Type:** Research manuscript / SSRN preprint  
**DOI:** [10.2139/ssrn.7202438](https://doi.org/10.2139/ssrn.7202438)

[**Read on SSRN →**](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7202438)

This paper examines whether advances in artificial intelligence will replace human labor or reshape the tasks people perform. Drawing on **Acemoglu and Restrepo's displacement–reinstatement framework**, the **Anthropic Economic Index**, and evidence from **US industrial robot adoption**, it analyzes the distinction between jobs and tasks, the balance between displacement and new-task creation, gaps between AI capability and observed use, cognitive versus physical automation, and policy responses such as universal basic income and AI taxation.

The paper reports **no evidence supporting near-term mass unemployment** in the evidence it surveys, but identifies the possibility of **“so-so automation”**: displacement of labor-intensive tasks without commensurate productivity improvements or creation of new tasks. It emphasizes the role of innovation choices and institutions in shaping employment outcomes.

> **Research status:** SSRN-hosted manuscript. This repository does not characterize it as a peer-reviewed publication or claim new causal estimates beyond the sources analyzed in the paper.

**Suggested citation**

```bibtex
@misc{wasea_future_work_2026,
  author       = {Wasea, Abdul},
  title        = {Can Humans Compete with Artificial Intelligence? The Future of Work and Task Automation},
  year         = {2026},
  month        = jul,
  howpublished = {SSRN preprint},
  doi          = {10.2139/ssrn.7202438},
  url          = {https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7202438},
  note         = {Written July 28, 2026; posted August 7, 2026}
}
```

## Contact

For research discussion, technical feedback, or collaboration:

**Abdul Wasea** · Independent Researcher  
**Email:** [abdulwasea5678@gmail.com](mailto:abdulwasea5678@gmail.com)

---

*Research with explicit assumptions, transparent limitations, and reproducible goals.*
