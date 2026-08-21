<div align="left">
  <a href="https://github.com/outpost2026/outpost2026/blob/main/README_EN.md">
    <img src="https://flagcdn.com/24x18/gb.png" alt="EN" height="18"> English
  </a>
</div>


# Outpost2026

### *Fyzická realita je jedinečná absolutní metrika pravdy. Digitální svět je jen její abstrakce*

[![Followers](https://img.shields.io/github/followers/outpost2026?label=followers&style=social)](https://github.com/outpost2026?tab=followers) [![Stars](https://img.shields.io/github/stars/outpost2026?label=stars)](https://github.com/outpost2026?tab=stars) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/ondrejsousek) [![Website](https://img.shields.io/badge/website-systeq.cz-000000)](https://systeq.cz/)

```
Automation & Integration · Praha  
Python · ETL · SQL/PostgreSQL · MCP/LLM · CI  
CNC/CAM · Reverse engineering · Docker/GCP
```

Stavím deterministické automatizační a datové systémy pro reálné nestrukturované a proprietární procesy. Prostě: bordel → řád.   
Python používám pro ingestion, transformace a tooling; SQL/PostgreSQL pro persistentní data; MCP/LLM pro AI-facing rozhraní a rozhodovací workflow.

Fyzické systémy, CNC/CAM a reverse engineering jsou moje původní engineering prostředí. Díky tomu navrhuji software s důrazem na real-world constraints, validaci, reprodukovatelnost a měřitelné výstupy.

## 🔥 Featured Projects

### [MCP-Jobs](https://github.com/outpost2026/MCP-Jobs) — multi-provider market intelligence

> **Pythonový MCP server pro práci s českými pracovními portály: provider ingestion, boolean matching, URL/fuzzy deduplikace, PostgreSQL persistence, CLI a MCP interface.**

> `Python` `ETL` `SQL/PostgreSQL` `FastMCP` `CLI` `pytest` `CI`

Šest providerů, strukturované logování, asynchronní joby a 189 veřejných testovacích funkcí. Tento projekt propojuje data ingestion, normalizaci, persistenci a AI-facing rozhraní do jednoho reprodukovatelného workflow.

[Repo →](https://github.com/outpost2026/MCP-Jobs)

### [LinkedIn MCP Analyzer](https://github.com/outpost2026/linkedin-mcp-analyzer) — rozhodovací podpora nad pracovními nabídkami

> **MCP workflow pro strukturovanou analýzu uložených LinkedIn pracovních nabídek podle deterministických kritérií EROI/FIT/GAP vůči CV a aktuálnímu stacku.**

> `Python` `MCP` `Patchright` `EROI scoring` `Knowledge base`

Z 49 analyzovaných nabídek bylo pouze 12 % relevantních pro další sledování. Pipeline převádí uložené nabídky přes vícevrstvou extrakci a šestidimenzionální scoring na strukturovaný report a zápis do knowledge base.

[Živá analýza 49 nabídek →](https://github.com/outpost2026/B2B-Knowledge-Base/blob/main/02_ANALYZY/00_linkedin/synteticky_report_analyza.md) · [EROI scoring model →](https://github.com/outpost2026/linkedin-mcp-analyzer#-eroi-scoring-model)

## Co umím

| Vrstva | Oblast | Důkaz |
| - | - | - |
| **[Reverse Engineering**](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/RE_CASE_STUDY_VCUTWORKS_LIGHTBURN_revised_en.md) | Binární formáty, IEEE 754, serializace | Ruida VCF: výzkum, parser, compiler a validační artefakty |
| **Industrial systems** | CNC/CAM, DXF, G-kód, real-world constraints | Vodní paprsek, CAD/CAM workflow, VCF/DXF tooling |
| **Python & modular engineering** | OOP, CLI, konfigurace, pytest | Modulární nástroje a testovatelné pipeline |
| **Data / ETL** | Ingestion, normalizace, matching, deduplikace, reporting | MCP-Jobs, RAG a manufacturing-data workflow |
| **SQL / PostgreSQL** | Relační schéma, dotazy, persistence, upsert | PostgreSQL vrstva a testovací DB v MCP-Jobs |
| **MCP & AI integration** | FastMCP tools/resources/prompts, deterministické workflow | MCP-Jobs, LinkedIn a Lichess analyzery |
| **Quality & delivery** | Regrese, golden master, linting, CI, logging | pytest, Ruff, GitHub Actions, CodeQL, strukturované logování |
| **Project infrastructure** | Docker a GCP Cloud Run | Projektové deploymenty a provozní tooling |


## Repozitáře

Hlavní moduly pokrývají jeden řetězec: od legacy nebo proprietárních systémů přes strukturovaná data a deterministické zpracování až po automatizaci, MCP/AI rozhraní a rozhodovací podporu.

### Core Engineering

| Repo | Oblast | Co dělá |
| - | - | - |
| [MCP-Jobs](https://github.com/outpost2026/MCP-Jobs) | Market intelligence ETL | Multi-provider ingestion, matching, deduplikace, PostgreSQL persistence, MCP a CLI |
| [linkedin-mcp-analyzer](https://github.com/outpost2026/linkedin-mcp-analyzer) | Career intelligence MCP | EROI/FIT/GAP scoring, strukturované reporty a knowledge-base integrace |
| [Vcutworks-vcf-parser](https://github.com/outpost2026/Vcutworks-vcf-parser) | VCF Engine | Produkční parser VCutWorks |
| [CNC\_2\_LLM](https://github.com/outpost2026/CNC_2_LLM) | DXF Engine | CAD → ML → CAM pipeline |
| [Vcf-compiler](https://github.com/outpost2026/Vcf-compiler) | VCF Compiler | Binární writer Ruida VCF |
| [vcf\_color\_service](https://github.com/outpost2026/vcf_color_service) | VCF Color Service | ACI mapování mezi LightBurn a VCutWorks |
| mcp-local-server *(lokální)* | MCP | FastMCP server pro CNC tooling |
| [lichess-mcp-analyzer](https://github.com/outpost2026/lichess-mcp-analyzer) | Chess MCP | Pattern detection, validace a LLM reasoning jako R&D laboratoř |


### Dokumentace, web & archiv

| Typ | Repozitáře |
| - | - |
| aktivní | [B2B-Knowledge-Base](https://github.com/outpost2026/B2B-Knowledge-Base) · [Systeq.cz\_dev](https://github.com/outpost2026/Systeq.cz_dev) · [Kazuistiky-LLM-sprint](https://github.com/outpost2026/Kazuistiky-LLM-sprint) |
| POC / archiv | [cad2llm](https://github.com/outpost2026/cad2llm) · [RAG-indexer](https://github.com/outpost2026/RAG-indexer) · [Outpost-security-perimeter](https://github.com/outpost2026/Outpost-security-perimeter) · [vcut-parser](https://github.com/outpost2026/vcut-parser) |


### Projekty & Konzultace

| Repo | Oblast | Co dělá |
| - | - | - |
| [van-peugeot-offgrid](https://github.com/outpost2026/van-peugeot-offgrid) | Off-grid 12V/230V | Victron ostrovní systém pro Peugeot Boxer — návrh, dokumentace, schéma a IoT rešerše |


## Trajektorie

| Rok | Role | Poznámka |
| - | - | - |
| 2020 | Cestovatel | Pobyt v zahraničí: FR, ES, UK |
| 2022–2024 | Off-grid stavitel | Outpost od základů vlastníma rukama |
| 2025–2026 | CNC operátor | Zakázková výroba na vodním paprsku |
| 03/2026 | První commit na GitHub | Začátek systematického software vývoje |
| 06/2026 | B2B jednání | První NDA, unikátní VCF parser jako monolit |
| 07/2026 | Modular engineering ecosystem | OOP refaktor, CI/CD a MCP |
| 08/2026 | Data & automation systems | Multi-provider ETL, PostgreSQL persistence, direct CLI, MCP workflow a decision support |


### Manifest: Osel, geometrie a konsolidace

**[AI vám bere kreativitu. Ale ne tak, jak si myslíte**](https://systeq.cz/docs/osel_geometrie_konsolidace_manifest.pdf)  
Text shrnující mé chápání vztahu mezi lidskou kognicí, tělesnou zkušeností, konsolidací myšlení a limity LLM systémů.

## Výzkum a architektura myšlení (R&D)

Stavět efektivní systémy a pracovat s AI vyžaduje pochopit, jak vzniká samotná abstrakce. Během reverse engineeringu a vývoje parserů se zabývám tím, jak se biologická kognice překrývá s architekturou strojového učení. Jde o vedlejší, metodickou větev — nikoli o hlavní produktový proud — která však ovlivňuje architektonická rozhodování.

🧠 Esej: [Proč váš mozek není počítač, ale geometrické GPU](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/brain_geometric_processor_summary_v2.1.md) · 🎧 [Audio varianta](https://systeq.cz/docs/audio/Jak_komprese_reality_spojuje_mozek_a_CNC.mp3)

## Metodika reverse engineeringu Ruida VCF

Šestifázový proces pro práci s proprietárními binárními formáty: QC, detekční taxonomie a validační framework s golden-master testy.

📄 **[Methodology & Validation Framework**](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/METHODOLOGY_VALIDATION_FRAMEWORK.md)

## Jak vypadá střet s trhem — případová studie

Můj první IT pohovor: co fungovalo a proč se těžiště práce přesouvá od memorování syntaxe k systémovému myšlení.

👉 [Kariérní přechody v éře saturace AI (2026)](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/karierni_prechody_v_ere_saturace_AI_rok_2026_revidovano_v2.md) · [EN](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/career_transitions_in_the_era_of_AI_saturation_2026_en.md)

## Kontakt

Ondřej Soušek · [LinkedIn](https://linkedin.com/in/ondrejsousek) · [systeq.cz](https://systeq.cz/) · [sousek@systeq.cz](mailto:sousek@systeq.cz)

