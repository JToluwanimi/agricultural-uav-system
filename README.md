# Agricultural UAV System — Assembly & Operations

> **Status:** Assembled / Operated
> **Author:** Toluwanimi Jesusina (Team Member)
> **Context:** Engineer, ULTRAPIC (2025); SIWES 2022, Federal Polytechnic Ilaro

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Completed-green)]()

---

## 1. What is this?

A practical UAV engineering project involving the assembly, configuration, and flight operation of a heavy-lift agricultural drone. The system was used for precision agriculture applications including irrigation, seeding, and spraying.

---

## 2. Why was it built?

To gain hands-on experience with professional-grade agricultural UAVs and to understand the practical challenges of deploying drone technology in precision agriculture.

---

## 3. Objectives

| # | Objective | Status |
|---|-----------|--------|
| 1 | Assemble heavy-lift agricultural drone | ✅ Completed |
| 2 | Configure flight controller and telemetry | ✅ Completed |
| 3 | Operate drone for spraying/seeding | ✅ Completed |
| 4 | Document agricultural applications | ✅ Completed |

---

## 4. System Architecture

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    AGRICULTURAL UAV SYSTEM                                  │
│                                                                             │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐     │
│  │  GPS         │  │  Flight      │  │  Telemetry   │  │  Spray       │     │
│  │  Module      │  │  Controller  │  │  (915 MHz)   │  │  Tank        │     │
│  └──────────────┘  └──────┬───────┘  └──────────────┘  └──────────────┘     │
│                           │                                                 │
│         ┌─────────────────┼─────────────────┐                               │
│         │                 │                 │                               │
│         ▼                 ▼                 ▼                               │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐                       │
│  │  6x Motors   │  │  6x ESCs     │  │  Pump        │                       │
│  │  (Heavy Lift)│  │  (High Power)│  │  (Sprayer)   │                       │
│  └──────────────┘  └──────────────┘  └──────────────┘                       │
│                                                                             │
│  Power: High-Capacity LiPo Battery Pack                                     │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## 5. Hardware

| Component | Specification |
|-----------|--------------|
| Frame | Heavy-lift hexacopter |
| Motors | X11 Plus (or equivalent) |
| ESCs | High-power (80A+) |
| Battery | High-capacity LiPo |
| Flight Controller | Pixhawk / DJI A3 |
| Payload | Spray tank + pump |
| GPS | RTK-capable |

---

## 6. Implementation

1. Assembled frame and arms
2. Mounted motors and ESCs
3. Installed flight controller and GPS
4. Configured telemetry and RC
5. Mounted spray tank and pump
6. Calibrated ESCs and IMU
7. Test flights and operational runs

---

## 7. Applications

| Application | Description |
|-------------|-------------|
| Irrigation | Aerial water distribution |
| Seeding | Precision seed dispersal |
| Spraying | Agrochemical application |
| Crop Monitoring | Aerial imaging (if equipped) |

---

## 8. Limitations

1. **Team Effort** — This was a team project; I contributed to assembly and operation, not design.
2. **No Custom Firmware** — Used manufacturer firmware.
3. **Weather Dependent** — Operations limited by wind and rain.

---

## 9. Lessons Learned

1. **Heavy-Lift Safety** — Large drones require strict safety protocols and pre-flight checklists.
2. **Team Coordination** — Agricultural operations require coordinated ground and air teams.
3. **Payload Balance** — Spray tank levels affect center of gravity and flight characteristics.

---

## 10. Media

*[Insert assembly photos, flight operation photos]*

---

## 11. Repository Structure

```
agricultural-uav-system/
├── README.md
├── LICENSE
├── docs/
│   ├── Assembly_Guide.md
│   ├── Operational_Checklist.md
│   └── Applications.md
├── hardware/
│   ├── motor_specs.md
│   └── esc_specs.md
└── media/
    ├── assembly_photos/
    └── operation_photos/
```

---

## 12. License

MIT License — see [LICENSE](LICENSE) for details.

---

## 13. Contact

**Toluwanimi Jesusina**
- Email: [jesusinatoluwanimi@gmail.com](mailto:jesusinatoluwanimi@gmail.com)
- LinkedIn: [linkedin.com/in/toluwanimi-jesusina](https://linkedin.com/in/your-profile)
```
