# Outpost2026

```
Off-grid, Praha    
2500 Wp FV · 16 kWh LiFePO4    
CNC · Python · GCP · RE · LLM augmentace
```

Stavím věci, které prošly fyzickou realitou dřív, než jsem je přepsal do kódu. 14 let off-grid DIY, CNC výroba, reverzní inženýrství proprietárních formátů — a k tomu posledních pár měsíců intenzivního převodu do digitální domény.
Moje zkušenosti z off-gridu, dílny, počítačově řízeného obrábění, pobytů v cizině mě naučila že **realita je pro mne nejdůležitějším měřítkem**. 

Nástroje, které tvořím s pomocí AI, slouží k pomyslnému hledání jehly v kupce sena, nyní k datové analýze založené na filtraci vaty a všudepřítomného šumu.

*První open-source parser proprietárního formátu .VCF (Ruida/VCutWorks). Žádná známá konkurence.* **[Online konverze VCF na cloudu GCP](https://vcf-parser-demo-537446704644.europe-west1.run.app/)**

## Co umím

| Vrstva | Oblast | Důkaz |
| - | - | - |
| **[Reverse Engineering](https://github.com/outpost2026/Kazuistiky-LLM-sprint/edit/main/RE_CASE_STUDY_VCUTWORKS_LIGHTBURN_v2.md)** | Binární formáty, IEEE 754, bitová maskování | 74B segmenty .VCF dekódovány bez dokumentace (184 h) |
| **Python** | Streamlit, pandas, RPA, ETL | 7 repozitářů, 2 produkční parsery |
| **Cloud** | GCP (Cloud Run, Scheduler, Storage, IAM, Artifact Registry) | Docker → Cloud Run deploy |
| **RPA** | GUI automatizace VCutWorks | 33/33 souborů = 100% úspěšnost |
| **Testování** | Golden master regression, determinism, smoke | 11 testů, baseline JSONy v repu |
| **Off-grid systémy** | FV, LiFePO4 BMS, ESP32/8266 IoT | Outpost-security-perimeter |
| **CNC technologie** | Vodní paprsek, oscilační nůž, V-slot | CAM workflow od DXF po hotový díl |


## Repozitáře

| Repo | Vznik | Co dělá |
| - | - | - |
| [🔒Vcut-parser](https://github.com/outpost2026/Kazuistiky-LLM-sprint/edit/main/RE_CASE_STUDY_VCUTWORKS_LIGHTBURN_v2.md) (private)| 2026-06 | **Cracknutí a tvorba datové pipeline pro CNC software Vcutwork** — reverzní inženýrství hexadecimální binárky Ruida/VCutWorks |
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

## Jak vypadá střet s trhem (Případová studie)
Teorie a repozitáře jsou jedna věc, ale jak to funguje, když s tímto přístupem a arzenálem přijdete z výroby rovnou na reálný IT pohovor? Sepsal jsem detailní analytickou kazuistiku mého úplně prvního pohovoru v životě. Zdokumentoval jsem v ní, co v praxi zafungovalo, na jaká rizika si dát pozor a proč si myslím, že v nastupující éře se těžiště práce přesouvá od pouhého memorování syntaxe k systémovému myšlení a pragmatickému řízení AI.

👉 Přečíst dokument: [Kariérní přechody v éře saturace AI (2026)](https://github.com/outpost2026/Kazuistiky-LLM-sprint/blob/main/karierni_prechody_v_ere_saturace_AI_rok_2026_revidovano_v2.md)

## Kontakt

```
Ondřej Soušek    
sousek@systeq.cz    
www.systeq.cz    
Praha, ČR
```

*Hledám funkční řešení v balastu.*

