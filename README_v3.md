<div align="left">
  <a href="https://github.com/outpost2026/outpost2026/blob/main/README_EN_v3.md">
    <img src="https://flagcdn.com/24x18/gb.png" alt="EN" height="18"> English
  </a>
</div>

# Outpost2026

### *Fyzická realita je jedinečná absolutní metrika pravdy. Digitální svět je jen její abstrakce*

[![Followers](https://img.shields.io/github/followers/outpost2026?label=followers&style=social)](https://github.com/outpost2026?tab=followers) [![Stars](https://img.shields.io/github/stars/outpost2026?label=stars)](https://github.com/outpost2026?tab=stars) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/ondrejsousek) [![Website](https://img.shields.io/badge/website-systeq.cz-000000)](https://systeq.cz/)

```
Off-grid, Praha  
2500 Wp FV · 16 kWh LiFePO4  
CNC · RE · Python · Modular · CI/CD · MCP
```

Stavím věci, které prošly fyzickou realitou dřív, než jsem je přepsal do kódu. 14 let off-grid DIY, CNC výroba, reverzní inženýrství proprietárních formátů — a k tomu posledních pár měsíců intenzivního převodu do digitální domény. Moje zkušenosti z off-gridu, dílny, počítačově řízeného obrábění, pobytů v cizině mě naučila že **realita je pro mne nejdůležitějším měřítkem**.

Nástroje, které tvořím s pomocí AI, slouží k pomyslnému hledání jehly v kupce sena = k datové analýze založené na filtraci vaty a všudypřítomného šumu. Věřím, že skutečná seniorita se měří úrovní abstrakce problému, který dokážete řešit, ne počtem let strávených u klávesnice.

---

## 🔥 Featured Project

### [linkedin-mcp-analyzer](https://github.com/outpost2026/linkedin-mcp-analyzer)

> **MCP server — automatizovaná EROI analýza uložených LinkedIn nabídek.**
>
> Ze 49 analyzovaných nabídek bylo pouze 12 % relevantních (SLEDOVAT) — tento nástroj vám řekne, které to jsou.
>
> `Python` `MCP` `Playwright` `LinkedIn API` `EROI scoring`

[![Python 3.12+](https://img.shields.io/badge/python-3.12%2B-blue)](https://www.python.org/downloads/)
[![MCP](https://img.shields.io/badge/MCP-server-purple)](https://modelcontextprotocol.io)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/outpost2026/linkedin-mcp-analyzer/pulls)
[![License: MIT](https://img.shields.io/badge/license-MIT-green)](https://github.com/outpost2026/linkedin-mcp-analyzer/blob/main/LICENSE)

```bash
git clone https://github.com/outpost2026/linkedin-mcp-analyzer.git
cd linkedin-mcp-analyzer
uv sync
.\linkedin-mcp.bat --login
.\linkedin-mcp.bat --status
```

📊 [Živá analýza 49 nabídek →](https://github.com/outpost2026/B2B-Knowledge-Base/blob/main/02_ANAL%C3%9DZY/00_linkedin/synteticky_report_analyza.md) · [EROI scoring model →](https://github.com/outpost2026/linkedin-mcp-analyzer#-eroi-scoring-model)

**Pipeline:** LinkedIn saved jobs → Patchright scraper (4-vrstvá extrakce) → EROI scoring (6 dimenzí) → strukturovaný report + git commit do knowledge base.

---

## Co umím

| Vrstva | Oblast | Důkaz |
| - | - | - |
| **[Reverse Engineering](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/RE_CASE_STUDY_VCUTWORKS_LIGHTBURN_revised_en.md)** | Binární formáty, IEEE 754 | RE Ruida VCF — 200 h bez dokumentace |
| **CNC & CAM** | Vodní paprsek, oscilační nůž, V-slot, DXF | Vlastní dílna, end-to-end |
| **Python & Modular engineering** | Modulární architektura, OOP, pytest, FastMCP | Deterministické moduly |
| **Deterministic engineering** | Golden master, regression, roundtrip | Validační sada v každém modulu |
| **RPA** | GUI automatizace VCutWorks | 33/33 = 100 % |
| **CI/CD & DevSecOps** | Actions, CodeQL, Dependabot | Cross-repo orchestrace |
| **MCP & agentic** | FastMCP, tool registry | Interní server + analyzer |
| **Cloud (GCP)** | Cloud Run, Storage, IAM | Live demo |

## Repozitáře

Všechny hlavní moduly řeší jeden řetězec = jak dostat z legacy nástrojů důležité informace, nyní řeším zejména jak dostat geometrii z CAD do CNC stroje přes proprietární binární formáty — deterministicky, testovatelně, s MCP nástroji.

### Core Engineering

| Repo | Oblast | Co dělá |
| - | - | - |
| [Vcutworks-vcf-parser](https://github.com/outpost2026/Vcutworks-vcf-parser) | VCF Engine | Produkční parser VCutWorks |
| [CNC\_2\_LLM](https://github.com/outpost2026/CNC_2_LLM) | DXF Engine | CAD → ML → CAM pipeline |
| [Vcf-compiler](https://github.com/outpost2026/Vcf-compiler) | VCF Compiler | Binární writer Ruida VCF |
| [vcf\_color\_service](https://github.com/outpost2026/vcf_color_service) | VCF Color Service | ACI mapování (LightBurn ↔ VCutWorks) |
| mcp-local-server *(lokální)* | MCP | FastMCP server pro CNC tooling |
| [linkedin-mcp-analyzer](https://github.com/outpost2026/linkedin-mcp-analyzer) | LinkedIn MCP | EROI scoring pracovních nabídek |

### Dokumentace, web & archiv

| Typ | Repozitáře |
| - | - |
| aktivní | [B2B-Knowledge-Base](https://github.com/outpost2026/B2B-Knowledge-Base) · [Systeq.cz\_dev](https://github.com/outpost2026/Systeq.cz_dev) · [Kazuistiky-LLM-sprint](https://github.com/outpost2026/Kazuistiky-LLM-sprint) |
| POC / archiv | [cad2llm](https://github.com/outpost2026/cad2llm) · [RAG-indexer](https://github.com/outpost2026/RAG-indexer) · [Outpost-security-perimeter](https://github.com/outpost2026/Outpost-security-perimeter) · [vcut-parser](https://github.com/outpost2026/vcut-parser) |

## Trajektorie

| Rok | Role | Poznámka |
| - | - | - |
| 2020 | Cestovatel | Pobyt v zahraničí (FR,ES,UK) |
| 2022–2024 | Off-grid stavitel | Outpost od základů vlastníma rukama |
| 2025-2026 | CNC operátor | Zakázková výroba vodní paprsek |
| 03/2026 | První commit na GitHub | 0 Python, 0 Git, 0 Cloud |
| 06/2026 | B2B jednání | První NDA, unikátní VCF parser (monolit) |
| 07/2026 | Modular engineering ecosystem | OOP refaktor · CI/CD · MCP |

### Manifest: Osel, geometrie a konsolidace

**[AI vám bere kreativitu. Ale ne tak, jak si myslíte](https://systeq.cz/docs/osel_geometrie_konsolidace_manifest.pdf)**  
Text shrnující mé chápání vztahu mezi lidskou kognicí, tělesnou zkušeností, konsolidací myšlení a limity LLM systémů.

## Výzkum a architektura myšlení (R&D)

Stavět efektivní systémy a pracovat s AI vyžaduje pochopit, jak vzniká samotná abstrakce. Během reverzního inženýrství a vývoje parserů jsem se začal zabývat tím, jak se biologická kognice překrývá s architekturou strojového učení — vedlejší větev, ne hlavní proud, ale důležitý kontext pro mé architektonické rozhodování.

🧠 Esej: [Proč váš mozek není počítač, ale geometrické GPU](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/brain_geometric_processor_summary_v2.1.md) 🎧 [Audio varianta](https://systeq.cz/docs/audio/Jak_komprese_reality_spojuje_mozek_a_CNC.mp3)

## Metodika reverse engineering ruida vcf

6-fázový proces RE pro proprietární binární formáty — QC, detekční taxonomie, validační framework s golden master testy.

📄 **[Methodology & Validation Framework](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/METHODOLOGY_VALIDATION_FRAMEWORK.md)**

## Jak vypadá střet s trhem (Případová studie)

Můj první IT pohovor — co fungovalo a proč se těžiště práce přesouvá od memorování syntaxe k systémovému myšlení.

👉 [Kariérní přechody v éře saturace AI (2026)](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/karierni_prechody_v_ere_saturace_AI_rok_2026_revidovano_v2.md) · [EN](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/career_transitions_in_the_era_of_AI_saturation_2026_en.md)

## Kontakt

Ondřej Soušek [LinkedIn](https://linkedin.com/in/ondrejsousek) | [systeq.cz](https://systeq.cz/) | [sousek@systeq.cz](mailto:sousek@systeq.cz)
