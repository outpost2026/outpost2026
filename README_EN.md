<div align="left">
  <a href="https://github.com/outpost2026/outpost2026/blob/main/README_EN_v3.md">
    <img src="https://flagcdn.com/24x18/gb.png" alt="EN" height="18"> English
  </a>
  ·
  <a href="README.md">
    <img src="https://flagcdn.com/24x18/cz.png" alt="CS" height="18"> Česky
  </a>
</div>

# Outpost2026

### *Physical reality is the one absolute metric of truth. The digital world is merely its abstraction*

[![Followers](https://img.shields.io/github/followers/outpost2026?label=followers&style=social)](https://github.com/outpost2026?tab=followers) [![Stars](https://img.shields.io/github/stars/outpost2026?label=stars)](https://github.com/outpost2026?tab=stars) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/ondrejsousek) [![Website](https://img.shields.io/badge/website-systeq.cz-000000)](https://systeq.cz/)

```
Off-grid, Prague    
2500 Wp PV · 16 kWh LiFePO4    
CNC · RE · Python · Modular · CI/CD · MCP
```

I build things that passed through physical reality before I transcribed them into code. 14 years of off-grid DIY, CNC manufacturing, reverse engineering proprietary formats — and in the last few months, an intensive transfer into the digital domain. My experience from off-grid living, the workshop, computer-controlled machining, and stays abroad has taught me that **reality is the most important metric for me**.

The tools I create with the help of AI serve as a metaphorical needle-in-a-haystack search = data analysis based on filtering out fluff and ubiquitous noise. I believe that true seniority is measured by the level of abstraction of the problem you can solve, not by the number of years spent at a keyboard.


## 🔥 Featured Project

### [LinkedIn Job Analyzer — No need to waste time deciphering every job posting](https://github.com/outpost2026/linkedin-mcp-analyzer) 

> **MCP server — automated analysis of saved LinkedIn job listings based on clear deterministic criteria (EROI/FIT/GAP) against your CV and overall stack. Outputs a weighted report in 6 clear categories with emphasis on facts and a clear call to action => i.e., respond, don't respond, consider, etc., upskill.**

> Out of 49 analyzed job postings, only 12 % were relevant (Follow) — this tool tells you which ones they are.

> `Python` `MCP` `Playwright` `LinkedIn API` `EROI scoring`

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/outpost2026/linkedin-mcp-analyzer/pulls)
[Live analysis of 49 listings →](https://github.com/outpost2026/B2B-Knowledge-Base/blob/main/02_ANAL%C3%9DZY/00_linkedin/synteticky_report_analyza.md) · [EROI scoring model →](https://github.com/outpost2026/linkedin-mcp-analyzer#-eroi-scoring-model)

**Pipeline:** LinkedIn saved jobs → Patchright scraper (4-layer extraction) → EROI scoring (6 dimensions) → structured report + git commit to knowledge base.


## What I do

| Layer | Area | Proof |
| - | - | - |
| **[Reverse Engineering](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/RE_CASE_STUDY_VCUTWORKS_LIGHTBURN_revised_en.md)** | Binary formats, IEEE 754 | RE Ruida VCF — 200 h without documentation |
| **CNC & CAM** | Waterjet, oscillating knife, V-slot, DXF | Own workshop, end-to-end |
| **Python & Modular engineering** | Modular architecture, OOP, pytest, FastMCP | Deterministic modules |
| **Deterministic engineering** | Golden master, regression, roundtrip | Validation suite in every module |
| **RPA** | GUI automation VCutWorks | 33/33 = 100 % |
| **CI/CD & DevSecOps** | Actions, CodeQL, Dependabot | Cross-repo orchestration |
| **MCP & agentic** | FastMCP, tool registry | Internal server + analyzer |
| **Cloud (GCP)** | Cloud Run, Storage, IAM | Live demo |


## Repositories

All main modules solve one chain = how to get important information out of legacy tools, currently I'm mainly solving how to get geometry from CAD to a CNC machine through proprietary binary formats — deterministically, testably, with MCP tools.

### Core Engineering

| Repo | Area | What it does |
| - | - | - |
| [Vcutworks-vcf-parser](https://github.com/outpost2026/Vcutworks-vcf-parser) | VCF Engine | Production parser VCutWorks |
| [CNC\_2\_LLM](https://github.com/outpost2026/CNC_2_LLM) | DXF Engine | CAD → ML → CAM pipeline |
| [Vcf-compiler](https://github.com/outpost2026/Vcf-compiler) | VCF Compiler | Binary writer Ruida VCF |
| [vcf\_color\_service](https://github.com/outpost2026/vcf_color_service) | VCF Color Service | ACI mapping (LightBurn ↔ VCutWorks) |
| mcp-local-server *(local)* | MCP | FastMCP server for CNC tooling |
| [linkedin-mcp-analyzer](https://github.com/outpost2026/linkedin-mcp-analyzer) | LinkedIn MCP | EROI scoring of job listings |


### Documentation, web & archive

| Type | Repositories |
| - | - |
| active | [B2B-Knowledge-Base](https://github.com/outpost2026/B2B-Knowledge-Base) · [Systeq.cz\_dev](https://github.com/outpost2026/Systeq.cz_dev) · [Kazuistiky-LLM-sprint](https://github.com/outpost2026/Kazuistiky-LLM-sprint) |
| POC / archive | [cad2llm](https://github.com/outpost2026/cad2llm) · [RAG-indexer](https://github.com/outpost2026/RAG-indexer) · [Outpost-security-perimeter](https://github.com/outpost2026/Outpost-security-perimeter) · [vcut-parser](https://github.com/outpost2026/vcut-parser) |


## Trajectory

| Year | Role | Note |
| - | - | - |
| 2020 | Traveler | Stay abroad (FR, ES, UK) |
| 2022–2024 | Off-grid builder | Outpost from the ground up with own hands |
| 2025-2026 | CNC operator | Custom waterjet manufacturing |
| 03/2026 | First commit on GitHub | 0 Python, 0 Git, 0 Cloud |
| 06/2026 | B2B negotiations | First NDA, unique VCF parser (monolith) |
| 07/2026 | Modular engineering ecosystem | OOP refactor · CI/CD · MCP |


### Manifesto: The donkey, geometry and consolidation

**[AI takes away your creativity. But not the way you think](https://systeq.cz/docs/osel_geometrie_konsolidace_manifest.pdf)**  
A text summarizing my understanding of the relationship between human cognition, bodily experience, thought consolidation, and the limits of LLM systems.

## Research & architecture of thought (R&D)

Building effective systems and working with AI requires understanding how abstraction itself arises. During reverse engineering and parser development, I started exploring how biological cognition overlaps with machine learning architecture — a side branch, not the mainstream, but an important context for my architectural decisions.

🧠 Essay: [Why your brain is not a computer, but a geometric GPU](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/brain_geometric_processor_summary_v2.1.md) 🎧 [Audio version](https://systeq.cz/docs/audio/Jak_komprese_reality_spojuje_mozek_a_CNC.mp3)

## Reverse engineering Ruida VCF methodology

6-phase RE process for proprietary binary formats — QC, detection taxonomy, validation framework with golden master tests.

📄 **[Methodology & Validation Framework](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/METHODOLOGY_VALIDATION_FRAMEWORK.md)**

## What a clash with the market looks like (Case Study)

My first IT interview — what worked and why the center of work is shifting from syntax memorization to systems thinking.

👉 [Career transitions in the era of AI saturation (2026)](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/karierni_prechody_v_ere_saturace_AI_rok_2026_revidovano_v2.md) · [EN](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/career_transitions_in_the_era_of_AI_saturation_2026_en.md)

## Contact

Ondřej Soušek [LinkedIn](https://linkedin.com/in/ondrejsousek) | [systeq.cz](https://systeq.cz/) | [sousek@systeq.cz](mailto:sousek@systeq.cz)
