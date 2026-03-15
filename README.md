<div align="center">

# ☀️ Solar Flare & Sunspot Cycle Activity
### Autonomous Space Weather & Ionospheric Telemetry System (NOAA SWPC Data)

[![Solar Cycle 25: Active](https://img.shields.io/badge/Solar%20Cycle-Cycle%2025%20(Maximum%20Phase)-E65100?style=for-the-badge&logo=nasa&logoColor=white)](https://www.swpc.noaa.gov)
[![NOAA SWPC Feed](https://img.shields.io/badge/Data%20Source-NOAA%20SWPC%20Telemetry-0277BD?style=for-the-badge&logo=satellite&logoColor=white)](https://services.swpc.noaa.gov)
[![Geomagnetic Status](https://img.shields.io/badge/Geomagnetic%20Activity-🟢%20Quiet-brightgreen?style=for-the-badge&logo=speedtest&logoColor=white)](https://www.swpc.noaa.gov/products/planetary-k-index)
[![Daily Automated Sync](https://img.shields.io/badge/Automated%20Telemetry-Operational-2E7D32?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/DimasAdiNugroho-dryTundra)

<p align="center">
  <b>Near-real-time and historical monitoring of Solar Cycle 25 activity: sunspot numbers (SSN), 10.7cm solar radio flux (F10.7), planetary geomagnetic Kp-index, and GOES X-ray solar flare classifications.</b>
</p>

---

</div>

## 📡 Live Solar Observational Dashboard

> **Telemetry Status:** Updated autonomously by GitHub Actions via NOAA Space Weather Prediction Center (SWPC) daily feeds.

| Space Weather Metric | Observation Value | Visual Intensity Gauge | Operational Status / Assessment |
| :--- | :---: | :---: | :--- |
| **Daily Sunspot Number (SSN)** | **`142`** | `[▰▰▰▰▰▰▱▱▱▱]` | Active solar disk complex; multiple bipoles |
| **10.7 cm Solar Radio Flux** | **`166.9 sfu`** | `[▰▰▰▰▰▰▱▱▱▱]` | Ionospheric F2-layer ionization baseline |
| **Planetary Kp-Index (3h Max)** | **`1.94`** | `[▰▰▱▱▱▱▱▱▱▱]` | **G0 (Quiet)** — Minimal magnetospheric disturbance |
| **24h Solar Flare Activity** | **`C7.2 @ 07:39 UTC`** | `C:5  M:0  X:0` | **🟢 NORMAL / PRODUCTIVE** |
| **Solar Wind / IMF Condition** | **`Nominal (Estimated)`** | `~420 km/s &#124; Bz: ~-1.8 nT` | Coupled interplanetary magnetic field |

---

## 📊 Solar Cycle Comparison: Cycle 25 vs Historical Baselines

A comparative scientific benchmark of **Solar Cycle 25** against the moderate **Solar Cycle 24** (2008–2019) and the record-setting **Solar Cycle 19** (1954–1964):

| Solar Cycle | Epoch / Duration | Peak Sunspot Number (SSN) | Peak 10.7cm Flux | Major Flares (M/X Class) | Terrestrial & Space Impact |
| :--- | :---: | :---: | :---: | :---: | :--- |
| **Cycle 25 (Current)** | **2019 – Present** | **~160 – 215 (Peak Plateau)** | **~190 – 250 sfu** | **Frequent M & X Eruptions** | **Significant satellite orbital drag, frequent aurora, HF disruptions** |
| **Cycle 24** | 2008 – 2019 | 146.4 (Apr 2014) | 179.0 sfu | Moderate (rare X-class) | Mild geomagnetic storming; lowest peak in a century |
| **Cycle 19** | 1954 – 1964 | 285.0 (Mar 1958) | 315.0 sfu | Extreme Super-Flares | Historic March 1958 geomagnetic storm; mid-latitude power surges |

> [!NOTE]
> Solar Cycle 25 has substantially outperformed early consensus forecasts, exhibiting elevated peak sunspot activity and pronounced solar radio emission typical of strong historical solar cycles.

---

## 🗓️ 7-Day Moving Telemetry Log

Moving observation window capturing the last 7 days leading to the current telemetry snapshot:

| Date (UTC) | Sunspot (SSN) | Radio Flux (10.7cm) | Max Kp | Geomagnetic Status | Flares (C / M / X) | Peak Flare Class |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| `2026-03-09` | **142** | 169.9 sfu | Kp 1.81 | 🟢 Quiet | `C:8 M:2 X:0` | `M3.6` |
| `2026-03-10` | **157** | 176.9 sfu | Kp 1.47 | 🟢 Quiet | `C:6 M:0 X:0` | `C1.3` |
| `2026-03-11` | **154** | 188.1 sfu | Kp 0.91 | 🟢 Quiet | `C:6 M:2 X:0` | `M7.4` |
| `2026-03-12` | **158** | 185.7 sfu | Kp 2.78 | 🟢 Nominal | `C:7 M:0 X:0` | `C2.0` |
| `2026-03-13` | **165** | 192.4 sfu | Kp 5.84 | 🟠 G1 Minor | `C:9 M:0 X:0` | `C4.4` |
| `2026-03-14` | **147** | 175.9 sfu | Kp 1.62 | 🟢 Quiet | `C:6 M:0 X:0` | `C8.0` |
| `2026-03-15` | **142** | 166.9 sfu | Kp 1.94 | 🟢 Quiet | `C:5 M:0 X:0` | `C7.2` |

---

## 🛰️ Space Weather Impact & NOAA Scale Reference

<details>
<summary><b>🔍 Click to expand: NOAA Space Weather Scales (R, G, S) Technical Breakdown</b></summary>

<br>

### 1. Radio Blackouts (R-Scale) — Driven by GOES Solar X-Ray Flares
- **R1 (Minor - M1 Flare):** Weak degradation of HF radio communication on sunlit side; occasional loss of radio contact.
- **R2 (Moderate - M5 Flare):** Limited blackout of HF radio communication for tens of minutes; loss of low-frequency navigation signals.
- **R3 (Strong - X1 Flare):** Wide area blackout of HF radio communications for about an hour.
- **R4 (Severe - X10 Flare):** HF radio blackout across most of the sunlit hemisphere lasting one to two hours.
- **R5 (Extreme - X20+ Flare):** Complete HF radio blackout throughout the entire sunlit side of Earth.

### 2. Geomagnetic Storms (G-Scale) — Driven by CME & Coronal Hole High-Speed Streams (Kp Index)
- **G1 (Minor / Kp = 5):** Weak power grid fluctuations; aurora visible at high latitudes (e.g., northern US, Scandinavia).
- **G2 (Moderate / Kp = 6):** High-latitude power systems experience voltage alarms; satellite orientation adjustments required.
- **G3 (Strong / Kp = 7):** Voltage corrections required; false alarms triggered on protection devices; satellite drag increases.
- **G4 (Severe / Kp = 8):** Voltage control problems; induced pipeline currents; degradation of GPS and satellite navigation.
- **G5 (Extreme / Kp = 9):** Widespread voltage control problems and protective system collapse; transformer damage possible.

### 3. Solar Radiation Storms (S-Scale) — Driven by Energetic Protons (>10 MeV)
- **S1–S2 (Minor to Moderate):** Elevated radiation levels for passengers and crew in high-altitude polar aircraft; minor satellite single-event upsets.
- **S3–S5 (Strong to Extreme):** Bio-hazard risk to astronauts on EVA; solar array degradation; high-latitude HF communication impossible.

</details>

---

## ⚙️ Repository Automation Architecture

```
                       ┌────────────────────────────────────────┐
                       │  NOAA Space Weather Prediction Center  │
                       │     (SWPC REST APIs & Telemetry)       │
                       └───────────────────┬────────────────────┘
                                           │ Daily Cron (00:00 UTC)
                                           ▼
                       ┌────────────────────────────────────────┐
                       │       GitHub Actions Automated CI      │
                       │     (.github/workflows/update.yml)     │
                       └───────────────────┬────────────────────┘
                                           │ Runs fetch_solar.py
                                           ▼
                       ┌────────────────────────────────────────┐
                       │      Autonomous Telemetry Engine       │
                       │     - Ingests SSN & F10.7 cm Flux      │
                       │     - Ingests Geomagnetic Kp Indices   │
                       │     - Evaluates 24h Flare Alerts       │
                       │     - Renders Production README.md     │
                       └───────────────────┬────────────────────┘
                                           │ Git Commit & Push
                                           ▼
                       ┌────────────────────────────────────────┐
                       │   Updated Public Scientific Dashboard  │
                       │    (README.md on GitHub Main Branch)   │
                       └────────────────────────────────────────┘
```

---

<div align="center">

### ⏱️ Last Automated Telemetry Sync
`2026-03-15 14:55:16 UTC`

**Data Telemetry Source:** [NOAA SWPC](https://www.swpc.noaa.gov/) & [SILSO Royal Observatory of Belgium](https://www.sidc.be/silso/)  
**Maintained by:** [DimasAdiNugroho-dryTundra](https://github.com/DimasAdiNugroho-dryTundra) • *Autonomous Solar Data Pipeline*

</div>
