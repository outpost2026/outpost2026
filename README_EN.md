<div align="left">
  <a href="https://github.com/outpost2026/outpost2026/blob/main/README.md">
    <img src="https://flagcdn.com/24x18/cz.png" alt="CZ" height="18"> Česky
  </a>
</div>

# Outpost2026
### *Physical reality is the only absolute metric of truth. The digital world is merely its abstraction*
```
Off-grid, Prague    
2500 Wp PV · 16 kWh LiFePO4    
CNC · Python · GCP · RE · LLM augmentation
```

I build things that passed through physical reality before I translated them into code. 14 years of off-grid DIY, CNC manufacturing, reverse engineering of proprietary formats — and in the last few months, an intensive transfer into the digital domain.
My experience from off-grid living, the workshop, computer-controlled machining, and time abroad has taught me that **reality is the most important metric for me**.

The tools I create with AI assistance serve a single purpose: finding the proverbial needle in a haystack — data analysis based on filtering out noise and the ever-present static.
I believe that true seniority is measured by the level of abstraction of the problem you can solve, not by the number of years spent at a keyboard.

## What I Do

| Layer | Area | Proof |
| - | - | - |
| **[Reverse Engineering](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/RE_CASE_STUDY_VCUTWORKS_LIGHTBURN_v2.md)** | Binary formats, IEEE 754, bit masking | 74B segments of .VCF decoded without documentation (200 h) |
| **Python** | Streamlit, pandas, RPA, ETL | 7 repositories, 2 production parsers |
| **Cloud** | GCP (Cloud Run, Scheduler, Storage, IAM, Artifact Registry) | Docker → Cloud Run deploy |
| **RPA** | GUI automation of VCutWorks | 33/33 files = 100% success rate |
| **Testing** | Golden master regression, determinism, smoke | 11 tests, baseline JSONs in repo |
| **Off-grid systems** | PV, LiFePO4 BMS, ESP32/8266 IoT | Outpost-security-perimeter |
| **CNC technology** | Waterjet, oscillating knife, V-slot | CAM workflow from DXF to finished part |
| **[RE Case Study: Ruida VCF & LightBurn DXF](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/RE_CASE_STUDY_VCUTWORKS_LIGHTBURN_revised_en.md)** | VCF files RE intelligence, methodology, golden master, 7 chapters, 23 defects, 8/8 PASS | VCF parsing tool for VcutWork CAM files

---
### Manifesto: The Donkey, Geometry, and Consolidation

**[AI is taking your creativity. But not the way you think.](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/osel_geometrie_konsolidace_manifest_EN.md)** ([CZ PDF](https://systeq.cz/docs/osel_geometrie_konsolidace_manifest.pdf))

A text summarizing my understanding of the relationship between human cognition, bodily experience, consolidation of thought, and the limits of LLM systems.

---
## Repositories

| Repo | Created | What it does |
| - | - | - |
| 🔒VCF Ruida Parser(**[Online VCF conversion on GCP Cloud](https://vcf-parser-demo-537446704644.europe-west1.run.app/)**| 2026-06 |**Cracking and building a data pipeline for VcutWorks CNC software** — 1st complete reverse engineering of Ruida/VCutWorks VCF files |
| [🔒CNC\_2\_LLM](https://github.com/outpost2026/CNC_2_LLM) (private) | 2026-06 | Pipeline from CAD data for ML, ERP integration, and production automation |
| [cad2llm](https://github.com/outpost2026/cad2llm) | 2026-03 | Deterministic SketchUp → JSON parser (0 % hallucinations) |
| [Kazuistiky-LLM-sprint](https://github.com/outpost2026/Kazuistiky-LLM-sprint) | 2026-03 | Learning methodology with LLMs, case studies, transfer learning |
| [RAG-indexer](https://github.com/outpost2026/RAG-indexer) | 2026-03 | Pre-processing unstructured data for vector databases |
| [Outpost-security-perimeter](https://github.com/outpost2026/Outpost-security-perimeter) | 2026-04 | IoT two-stage security (PIR+Doppler, ESP32) |


## Trajectory

| Year | Role | Note |
| - | - | - |
| 2020 | Traveler | Living abroad (FR, ES, UK) |
| 2022–2024 | Off-grid builder | Outpost built from scratch by hand |
| 2025-2026 | CNC operator | Custom waterjet manufacturing |
| 03/2026 | First GitHub commit | 0 Python, 0 Git, 0 Cloud |
| 06/2026 | B2B dev with a product | First meeting, NDA negotiations, unique parser |
---

## Research & Architecture of Thinking (R&D)
Building effective software systems and working with AI requires understanding how abstraction itself arises. During reverse engineering and parser development, I began intensely exploring how biological cognition overlaps with machine learning architecture.

I wrote a theoretical framework that deconstructs human cognition into pure mathematics and defines the brain as an **organic GPU**. The document explains why true intelligence is the ability to perform lossy compression and how intuition emerges through topology changes in neural networks. It is my epistemological kernel.

🧠 Read the research essay: [Why Your Brain Is Not a Computer But a Geometric GPU, the Ultimate Game Graphics](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/brain_geometric_processor_summary_v2.1.md)

- "I had AI synthesize, based on my technical notes, materials, and research created during software development, an [audio essay in mp3 about compression of reality](https://systeq.cz/docs/audio/Jak_komprese_reality_spojuje_mozek_a_CNC.mp3). It is a narrative — a guide — to the common aspect: **the relationship between the brain, geometry, and the learning machine**. It is based on the above essay 'Brain as a Geometric CPU'."

## Methodology & B2B Validation
A complete methodological framework for reverse engineering proprietary binary formats. 6-phase process, QC, detection taxonomy, validation framework with golden master tests.

📄 **[Methodology & Validation Framework](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/METHODOLOGY_VALIDATION_FRAMEWORK.md)**

---

## How the Market Collision Looks (Case Study)
Theory and repositories are one thing, but how does it work when you walk straight from manufacturing into a real IT interview with this approach and arsenal? I wrote a detailed analytical case study of my very first interview ever. I documented what actually worked in practice, what risks to watch out for, and why I believe that in the emerging era, the center of gravity shifts from mere syntax memorization to systems thinking and pragmatic AI orchestration.

👉 Read the document: [Career Transitions in the Era of AI Saturation (2026)](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/career_transitions_in_the_era_of_AI_saturation_2026_en.md)

## Contact

Ondřej Soušek    
[LinkedIn](https://linkedin.com/in/ondrejsousek) | [systeq.cz](https://systeq.cz) | sousek@systeq.cz
