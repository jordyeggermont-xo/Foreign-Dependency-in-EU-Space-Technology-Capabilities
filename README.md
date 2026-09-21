# Foreign Dependency in EU Space Technology Capabilities

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Data Source: OpenTender.eu](https://img.shields.io/badge/Data-OpenTender.eu-blue)](https://opentender.eu/)
[![Data Source: Orbis](https://img.shields.io/badge/Data-Orbis-blue)](https://www.moodys.com/web/en/us/capabilities/company-reference-data/orbis.html)
[![Data Source: ESA](https://img.shields.io/badge/Data-ESA-blue)](https://www.esa.int/Applications/Observing_the_Earth/Copernicus/Space_Component_tenders_and_contracts)

A case study as part of my Master's thesis analyzing the extent to which the European Union's space capabilities rely on non-EU actors across three critical strategic dimensions: corporate ownership, public procurement, and program supply chains.

---

## General information
This repository contains the data, methodology, and detailed written out report of a case study investigating the foreign dependency of the European Union’s space capabilities. Achieving strategic autonomy requires ensuring that the EU can design, develop, procure, and operate space infrastructure without critical vulnerabilities to external actors. To evaluate the extent of these dependencies, this research examines three strategic dimensions: non-EU ownership of European spacecraft manufacturing firms, non-EU success in European space technology tenders, and non-EU participation in the supply chains of flagship EU space programmes.

## Executive Summary

* **Dimension 1: Corporate Ownership (EU Space Industry)**
  * **Direct vs. Indirect Ownership:** Direct non-EU ownership of Eurospace member firms stands at **8.22%**, but jumps to **27.26%** when incorporating indirect ownership structures.
  * **Geopolitical Profile:** Foreign ownership is heavily concentrated in allied nations (USA, Canada, UK, Switzerland, Norway). Ownership by geopolitical rivals (e.g., Russia, China) is **<0.03%**.
  * **Firm Type Variations:** Publicly traded space manufacturers exhibit significant foreign ownership, whereas state- or family-owned firms remain predominantly EU-owned.

* **Dimension 2: Public Procurement Tenders (2013–2022)**
  * **Foreign Success Rate:** Non-EU companies won **18.66%** of all EU space technology tenders (170 of 911 valid cases), with US firms taking the primary share (**14.16%**).
  * **Temporal Trend:** Foreign tender success surged from **2017 onward**, consistently exceeding **30% annually** and peaking at **60.32% in 2021**.
  * **Price & Competition Dynamics:** Tenders awarded to non-EU suppliers received **more bids per tender (5.94 average)** and lower average bid prices (€1.4M vs. €4.07M for EU firms), indicating price competition rather than purely an EU capacity deficit.

* **Dimension 3: Copernicus Programme Supply Chain**
  * **Public Procurement:** Foreign entities secured **5.70%** (73 of 1,281) of Copernicus contracts between 2014 and 2022, led by Switzerland (1.72%), Norway (1.72%), and the UK (1.17%).
  * **Sentinel Satellite Hardware:** Non-EU involvement in the Sentinel industrial consortium reaches **11.05%** of all components, with the highest foreign reliance in **Sentinel-1 (18.52%)** and **Sentinel-2 (13.16%)**.

---

## Detailed Findings & Tables

<details>
<summary><b>Dimension 1: Non-EU Ownership Breakdown (Table 1)</b></summary>

Direct foreign shareholding in the EU space industry exceeds **8%**, but total foreign control increases to over **27%** when indirect ownership is included. Publicly traded space companies display widespread foreign ownership, whereas state- or family-owned firms remain predominantly EU-controlled.

| Nationality of Non-EU Owners | % Direct Ownership | % Indirect Ownership |
| :--- | :---: | :---: |
| **USA** | 5.94 | 16.43 |
| **UK** | 1.13 | 2.72 |
| **Canada** | 0.45 | 2.06 |
| **Norway** | 0.37 | 1.52 |
| **Switzerland** | 0.07 | 1.05 |
| **China** | 0.00 | 0.03 |
| **Total Non-EU Ownership of Industry** | **8.22** | **27.26** |
| **Average Shareholding of Non-EU Owners** | **5.27** | **2.61** |

*Source: Own analysis based on Orbis database, Bureau van Dijk, 2023.*
</details>

<details>
<summary><b>Dimension 2: Public Procurement & Tender Success (Tables 2–4 + Graph 1)</b></summary>

Over 18% of space technology tenders between 2013 and 2022 were awarded to non-EU firms (US firms taking 14.16%). Except for 3 cases won by Israeli firms, all non-EU suppliers belong to allied agreements (EEA/NATO). Zero tenders were awarded to Russian or Chinese suppliers.

#### Table 2: Non-EU Success in EU Space Technology Tenders

| Nationality Non-EU Tender Supplier | # Tenders Won | Share of Total # Tenders (%) |
| :--- | :---: | :---: |
| **USA** | 129 | 14.16 |
| **UK** | 31 | 3.40 |
| **Canada** | 6 | 0.66 |
| **Israel** | 3 | 0.33 |
| **Switzerland** | 1 | 0.11 |
| **Total** | **170** | **18.66** |

*Source: Own analysis based on data retrieved from OpenTender.eu, 2023.*

#### Table 3: Non-EU Success in EU Space Technology Tenders

| Nationality non-EU tender supplier | #tenders won | Share of total #tenders (in %) |
| :--- | :--- | :---: |
| USA | 129 | 14,16 |
| UK | 31 | 3,4 |
| Canada | 6 | 0,66 |
| Israel | 3 | 0,33 |
| Switzerland | 1 | 0,11 |
| **Total** | **170** | **18,66** |


**Graph 1: Share of EU27 Space Technology Tenders Awarded to Non-EU Bidders (2013–2022)**

```mermaid
xychart-beta
    title "Share of EU27 Space Technology Tenders Awarded to Non-EU Bidders (%)"
    x-axis ["2013", "2014", "2015", "2016", "2017", "2018", "2019", "2020", "2021", "2022"]
    y-axis "Share (%)" 0 --> 70
    bar [3.08, 11.38, 4.12, 1.41, 37.04, 42.39, 32.14, 33.33, 60.32, 32.00]
