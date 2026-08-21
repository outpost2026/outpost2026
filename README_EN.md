<div align="left">
  <a href="https://github.com/outpost2026/outpost2026/blob/main/README.md">
    <img src="https://flagcdn.com/24x18/cz.png" alt="CZ" height="18"> Česky
  </a>
</div>

# Outpost2026

### *Physical reality is the unique absolute metric of truth. The digital world is merely its abstraction*

[![Followers](https://img.shields.io/github/followers/outpost2026?label=followers&style=social)](https://github.com/outpost2026?tab=followers) [![Stars](https://img.shields.io/github/stars/outpost2026?label=stars)](https://github.com/outpost2026?tab=stars) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/ondrejsousek) [![Website](https://img.shields.io/badge/website-systeq.cz-000000)](https://systeq.cz/)

```text
Automation & Integration · Prague
Python · ETL · SQL/PostgreSQL · MCP/LLM · CI
CNC/CAM · Reverse engineering · Docker/GCP
```

I build deterministic automation and data systems for real-world, messy, and proprietary processes. I use Python for ingestion, transformations, and tooling; SQL/PostgreSQL for persistent data; MCP/LLM for AI-facing interfaces and decision workflows.

Physical systems, CNC/CAM, and reverse engineering are my original engineering environment. This is why I design software with emphasis on real-world constraints, validation, reproducibility, and measurable outputs.

## Featured Projects

### [MCP-Jobs](https://github.com/outpost2026/MCP-Jobs) — multi-provider market intelligence

> **Python MCP server for working with Czech job portals: provider ingestion, boolean matching, URL/fuzzy deduplication, PostgreSQL persistence, CLI and MCP interface.**

> `Python` `ETL` `SQL/PostgreSQL` `FastMCP` `CLI` `pytest` `CI`

Six providers, structured logging, asynchronous jobs, and 189 public test functions. This project connects data ingestion, normalization, persistence, and AI-facing interface into a single reproducible workflow.

[Repo ->](https://github.com/outpost2026/MCP-Jobs)

### [LinkedIn MCP Analyzer](https://github.com/outpost2026/linkedin-mcp-analyzer) — decision support for job offers

> **MCP workflow for structured analysis of saved LinkedIn job offers against deterministic EROI/FIT/GAP criteria relative to your CV and current stack.**

> `Python` `MCP` `Patchright` `EROI scoring` `Knowledge base`

Of 49 analyzed offers, only 12% were worth following up on. The pipeline converts saved offers through multi-layer extraction and six-dimensional scoring into a structured report and knowledge base write-back.

[Live analysis of 49 offers ->](https://github.com/outpost2026/B2B-Knowledge-Base/blob/main/02_ANALYZY/00_linkedin/synteticky_report_analyza.md) · [EROI scoring model ->](https://github.com/outpost2026/linkedin-mcp-analyzer#-eroi-scoring-model)

## What I Do

| Layer | Area | Evidence |
| - | - | - |
| **[Reverse Engineering](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/RE_CASE_STUDY_VCUTWORKS_LIGHTBURN_revised_en.md)** | Binary formats, IEEE 754, serialization | Ruida VCF: research, parser, compiler, and validation artifacts |
| **Industrial systems** | CNC/CAM, DXF, G-code, real-world constraints | Waterjet, CAD/CAM workflow, VCF/DXF tooling |
| **Python & modular engineering** | OOP, CLI, configuration, pytest | Modular tools and testable pipelines |
| **Data / ETL** | Ingestion, normalization, matching, deduplication, reporting | MCP-Jobs, RAG, and manufacturing-data workflows |
| **SQL / PostgreSQL** | Relational schema, queries, persistence, upsert | PostgreSQL layer and test database in MCP-Jobs |
| **MCP & AI integration** | FastMCP tools/resources/prompts, deterministic workflows | MCP-Jobs, LinkedIn and Lichess analyzers |
| **Quality & delivery** | Regression, golden master, linting, CI, logging | pytest, Ruff, GitHub Actions, CodeQL, structured logging |
| **Project infrastructure** | Docker and GCP Cloud Run | Project deployments and operational tooling |

## Repositories

The core modules cover a single chain: from legacy or proprietary systems through structured data and deterministic processing to automation, MCP/AI interfaces, and decision support.

### Core Engineering

| Repo | Domain | What it does |
| - | - | - |
| [MCP-Jobs](https://github.com/outpost2026/MCP-Jobs) | Market intelligence ETL | Multi-provider ingestion, matching, deduplication, PostgreSQL persistence, MCP and CLI |
| [linkedin-mcp-analyzer](https://github.com/outpost2026/linkedin-mcp-analyzer) | Career intelligence MCP | EROI/FIT/GAP scoring, structured reports and knowledge base integration |
| [Vcutworks-vcf-parser](https://github.com/outpost2026/Vcutworks-vcf-parser) | VCF Engine | Production VCutWorks parser |
| [CNC_2_LLM](https://github.com/outpost2026/CNC_2_LLM) | DXF Engine | CAD -> ML -> CAM pipeline |
| [Vcf-compiler](https://github.com/outpost2026/Vcf-compiler) | VCF Compiler | Binary writer for Ruida VCF |
| [vcf_color_service](https://github.com/outpost2026/vcf_color_service) | VCF Color Service | ACI mapping between LightBurn and VCutWorks |
| mcp-local-server *(local)* | MCP | FastMCP server for CNC tooling |
| [lichess-mcp-analyzer](https://github.com/outpost2026/lichess-mcp-analyzer) | Chess MCP | Pattern detection, validation, and LLM reasoning as R&D lab |

### Documentation, web & archive

| Type | Repositories |
| - | - |
| active | [B2B-Knowledge-Base](https://github.com/outpost2026/B2B-Knowledge-Base) · [Systeq.cz_dev](https://github.com/outpost2026/Systeq.cz_dev) · [Kazuistiky-LLM-sprint](https://github.com/outpost2026/Kazuistiky-LLM-sprint) |
| POC / archive | [cad2llm](https://github.com/outpost2026/cad2llm) · [RAG-indexer](https://github.com/outpost2026/RAG-indexer) · [Outpost-security-perimeter](https://github.com/outpost2026/Outpost-security-perimeter) · [vcut-parser](https://github.com/outpost2026/vcut-parser) |

### Projects & Consulting

| Repo | Domain | What it does |
| - | - | - |
| [van-peugeot-offgrid](https://github.com/outpost2026/van-peugeot-offgrid) | Off-grid 12V/230V | Victron island system for Peugeot Boxer — design, documentation, wiring diagram, and IoT research |

## Trajectory

| Year | Role | Note |
| - | - | - |
| 2020 | Traveler | Living abroad: FR, ES, UK |
| 2022–2024 | Off-grid builder | Outpost built from scratch by hand |
| 2025–2026 | CNC operator | Custom waterjet manufacturing |
| 03/2026 | First GitHub commit | Beginning of systematic software development |
| 06/2026 | B2B negotiations | First NDA, unique VCF parser as monolith |
| 07/2026 | Modular engineering ecosystem | OOP refactor, CI/CD, and MCP |
| 08/2026 | Data & automation systems | Multi-provider ETL, PostgreSQL persistence, direct CLI, MCP workflow, and decision support |

### Manifesto: The Donkey, Geometry, and Consolidation

**[AI is taking your creativity. But not the way you think.](https://systeq.cz/docs/osel_geometrie_konsolidace_manifest.pdf)**  
A text summarizing my understanding of the relationship between human cognition, bodily experience, consolidation of thought, and the limits of LLM systems.

## Research & Architecture of Thinking (R&D)

Building effective systems and working with AI requires understanding how abstraction itself arises. During reverse engineering and parser development, I began exploring how biological cognition overlaps with machine learning architecture — a side branch, not the main focus, but an important context for my architectural decisions.

Essay: [Why Your Brain Is Not a Computer But a Geometric GPU](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/brain_geometric_processor_summary_v2.1.md) · [Audio version](https://systeq.cz/docs/audio/Jak_komprese_reality_spojuje_mozek_a_CNC.mp3)

## Methodology — Reverse Engineering Ruida VCF

A six-phase process for working with proprietary binary formats: QC, detection taxonomy, and validation framework with golden-master tests.

**[Methodology & Validation Framework](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/METHODOLOGY_VALIDATION_FRAMEWORK.md)**

## How the Market Collision Looks — Case Study

My first IT interview: what worked and why the center of gravity is shifting from syntax memorization to systems thinking.

[Career Transitions in the Era of AI Saturation (2026)](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/career_transitions_in_the_era_of_AI_saturation_2026_en.md) · [CZ](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/karierni_prechody_v_ere_saturace_AI_rok_2026_revidovano_v2.md)

## Contact

Ondřej Soušek · [LinkedIn](https://linkedin.com/in/ondrejsousek) · [systeq.cz](https://systeq.cz/) · [sousek@systeq.cz](mailto:sousek@systeq.cz)
