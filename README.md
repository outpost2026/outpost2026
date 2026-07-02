<div align="left">
  <a href="https://github.com/outpost2026/outpost2026/blob/main/README_EN.md">
    <img src="https://flagcdn.com/24x18/gb.png" alt="EN" height="18"> English
  </a>
</div>

# Outpost2026
### *Fyzická realita je jedinečná absolutní metrika pravdy. Digitální svět je jen její abstrakce* 

[![Followers](https://img.shields.io/github/followers/outpost2026?label=followers&style=social)](https://github.com/outpost2026?tab=followers)
[![Stars](https://img.shields.io/github/stars/outpost2026?label=stars)](https://github.com/outpost2026?tab=stars)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/ondrejsousek)
[![Website](https://img.shields.io/badge/website-systeq.cz-000000)](https://systeq.cz)


```
Off-grid, Praha    
2500 Wp FV · 16 kWh LiFePO4    
CNC · Python · GCP · RE · LLM augmentace
```

Stavím věci, které prošly fyzickou realitou dřív, než jsem je přepsal do kódu. 14 let off-grid DIY, CNC výroba, reverzní inženýrství proprietárních formátů — a k tomu posledních pár měsíců intenzivního převodu do digitální domény.
Moje zkušenosti z off-gridu, dílny, počítačově řízeného obrábění, pobytů v cizině mě naučila že **realita je pro mne nejdůležitějším měřítkem**. 

Nástroje, které tvořím s pomocí AI, slouží k pomyslnému hledání jehly v kupce sena = k datové analýze založené na filtraci vaty a všudepřítomného šumu. 
Věřím, že skutečná seniorita se měří úrovní abstrakce problému, který dokážete řešit, ne počtem let strávených u klávesnice.

## Co umím

| Vrstva | Oblast | Důkaz |
| - | - | - |
| **[Reverse Engineering](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/RE_CASE_STUDY_VCUTWORKS_LIGHTBURN_v2.md)** | Binární formáty, IEEE 754, bitová maskování | soubory vcf z vcutworks dekódovány bez dokumentace (200 h) |
| **Python** | Streamlit, pandas, RPA, ETL | 7 repozitářů, 2 produkční parsery |
| **Cloud** | GCP (Cloud Run, Scheduler, Storage, IAM, Artifact Registry) | Docker → Cloud Run deploy |
| **RPA** | GUI automatizace VCutWorks | 33/33 souborů = 100% úspěšnost |
| **Testování** | Golden master regression, determinism, smoke | 11 testů, baseline JSONy v repu |
| **Off-grid systémy** | FV, LiFePO4 BMS, ESP32/8266 IoT | Outpost-security-perimeter |
| **CNC technologie** | Vodní paprsek, oscilační nůž, V-slot | CAM workflow od DXF po hotový díl |
| **[RE Case Study: Ruida VCF & LightBurn DXF](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/RE_CASE_STUDY_VCUTWORKS_LIGHTBURN_revised_en.md)** | VCF files RE inteligence, metodika, golden master, 7 kapitol, 23 defektů, 8/8 PASS | VCF parsing tool for VcutWork CAM files

---
### Manifest: Osel, geometrie a konsolidace

**[AI vám bere kreativitu. Ale ne tak, jak si myslíte](https://systeq.cz/docs/osel_geometrie_konsolidace_manifest.pdf)**  

Text shrnující mé chápání vztahu mezi lidskou kognicí, tělesnou zkušeností, konsolidací myšlení a limity LLM systémů.

---
## Repozitáře

| Repo | Vznik | Co dělá |
| - | - | - |
| 🔒VCF Ruida Parser(**[Online konverze VCF na cloudu GCP](https://vcf-parser-demo-537446704644.europe-west1.run.app/)**| 2026-06 |**Cracknutí a tvorba datové pipeline pro CNC software Vcutworks** — 1. kompletní reverzní inženýrství souborů vcf Ruida/VCutWorks |
| [🔒CNC\_2\_LLM](https://github.com/outpost2026/CNC_2_LLM) (private) | 2026-06 | Pipeline z CAD dat pro ML, ERP integraci a automatizaci výroby |
| [cad2llm](https://github.com/outpost2026/cad2llm) | 2026-03 | Deterministický parser SketchUp → JSON (0 % halucinací) |
| [Kazuistiky-LLM-sprint](https://github.com/outpost2026/Kazuistiky-LLM-sprint) | 2026-03 | Metodologie učení s LLM, case studies, transfer learning |
| [RAG-indexer](https://github.com/outpost2026/RAG-indexer) | 2026-03 | Pre-processing nestrukturovaných dat pro vektorové DB |
| [Outpost-security-perimeter](https://github.com/outpost2026/Outpost-security-perimeter) | 2026-04 | IoT dvoustupňové zabezpečení (PIR+Doppler, ESP32) |


## Trajektorie

| Rok | Role | Poznámka |
| - | - | - |
| 2020 | Cestovatel | Pobyt v zahraničí (FR,ES,UK) |
| 2022–2024 | Off-grid stavitel | Outpost od základů vlastníma rukama |
| 2025-2026 | CNC operátor | Zakázková výroba vodní paprsek |
| 03/2026 | První commit na GitHub | 0 Python, 0 Git, 0 Cloud |
| 06/2026 | B2B dev s produktem | První schůzka, NDA jednání, unikátní parser |
---

## Výzkum a architektura myšlení (R&D)
Stavět efektivní softwarové systémy a pracovat s AI vyžaduje pochopit, jak vzniká samotná abstrakce. Během reverzního inženýrství a vývoje parserů jsem se začal intenzivně zabývat tím, jak se biologická kognice překrývá s architekturou strojového učení. 

Napsal jsem teoretický rámec, který dekonstruuje lidskou kognici na čistou matematiku a definuje mozek jako **organické GPU**. Dokument vysvětluje, proč je skutečná inteligence schopností ztrátové komprese a jak vzniká intuice skrze změny topologie v neuronových sítích. Je to můj epistemologický kernel.

🧠 Přečíst výzkumnou esej: [Proč váš mozek není počítač, ale geometrické GPU, ultimátní herní grafika](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/brain_geometric_processor_summary_v2.1.md)

- "Nechal jsem AI, aby na základě mých technických poznámek & materiálů & rešerší vzniklých během vývoje softwaru syntetizovala [Audio úvahu v mp3 o kompresi reality](https://systeq.cz/docs/audio/Jak_komprese_reality_spojuje_mozek_a_CNC.mp3). Je to vyprávění - průvodce - společným aspektem: **vztahem mezi mozkem, geometrií a učícím se strojem**. Vychází z výše uvedené eseje "**Mozek jako geometrické CPU**"

---

## Metodika reverse engineering ruida vcf
Kompletní metodologický rámec pro reverse engineering proprietárních binárních formátů. 6-fázový proces, QC, detekční taxonomie, validační framework s golden master testy.

📄 **[Methodology & Validation Framework](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/METHODOLOGY_VALIDATION_FRAMEWORK.md)**

---

## Jak vypadá střet s trhem (Případová studie)
Teorie a repozitáře jsou jedna věc, ale jak to funguje, když s tímto přístupem a arzenálem přijdete z výroby rovnou na reálný IT pohovor? Sepsal jsem detailní analytickou kazuistiku mého úplně prvního pohovoru v životě. Zdokumentoval jsem v ní, co v praxi zafungovalo, na jaká rizika si dát pozor a proč si myslím, že v nastupující éře se těžiště práce přesouvá od pouhého memorování syntaxe k systémovému myšlení a pragmatickému řízení AI.

👉 Přečíst dokument: [Kariérní přechody v éře saturace AI (2026)](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/karierni_prechody_v_ere_saturace_AI_rok_2026_revidovano_v2.md) [ENGLISH VER](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/career_transitions_in_the_era_of_AI_saturation_2026_en.md)

## Kontakt

Ondřej Soušek    
[LinkedIn](https://linkedin.com/in/ondrejsousek) | [systeq.cz](https://systeq.cz) | sousek@systeq.cz
