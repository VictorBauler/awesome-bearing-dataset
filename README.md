# Awesome Bearing Datasets for Diagnostics and Prognostics

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated collection of public datasets for bearing fault diagnosis and prognostics, intended for researchers and engineers in condition monitoring and predictive maintenance.

---

## Summary of Datasets

Each dataset name links to its description in [docs/datasets.md](docs/datasets.md).

### Core Datasets

The most widely used benchmarks, ordered by citations per year of their reference paper (OpenAlex, September 2026). MFPT, MAFAULDA, and PHM09 are included by convention (no official reference paper), and the Paderborn and KAIST run-to-failure datasets are listed alongside their groups' core datasets. See [docs/citations.md](docs/citations.md) for the full ranking.

| Dataset | Originating Institution(s) | Year | Primary Task | Fault Generation | Key Signals |
| :--- | :--- | :--- | :--- | :--- | :--- |
| [Case Western Reserve University (CWRU)](docs/datasets.md#case-western-reserve-university-cwru) | Case Western Reserve University | ~1999 | Diagnosis | Artificial (EDM) | Vibration (DE, FE) |
| [Xi'an Jiaotong University (XJTU-SY)](docs/datasets.md#xian-jiaotong-university-xjtu-sy) | Xi'an Jiaotong University & Sumyoung Tech. | 2019 | Prognostics | Natural (Accelerated) | Vibration |
| [Southeast University (SEU)](docs/datasets.md#southeast-university-seu) | Southeast University | ~2016 | Diagnosis | Artificial | Vibration, Torque |
| [HUST (Huazhong University of Science and Technology)](docs/datasets.md#hust-huazhong-university-of-science-and-technology) | Huazhong University of Science and Technology | ~2023 | Diagnosis | Artificial | Vibration |
| [Paderborn University (PU)](docs/datasets.md#paderborn-university-pu) | Paderborn University | 2016 | Diagnosis | Artificial & Natural | Vibration, Motor Current |
| [Paderborn University (Time-Varying Run-to-Failure)](docs/datasets.md#paderborn-university-time-varying-run-to-failure) | Paderborn University | 2024 | Prognostics | Natural (Accelerated) | Vibration, Temperature |
| [KAIST Run-to-Failure](docs/datasets.md#kaist-run-to-failure) | KAIST | 2024 | Prognostics | Natural (Accelerated) | Vibration, Temperature |
| [NASA IMS](docs/datasets.md#nasa-ims) | IMS, University of Cincinnati / NASA | ~2004 | Prognostics | Natural (Accelerated) | Vibration |
| [University of Ottawa Time-Varying Speed (2018)](docs/datasets.md#university-of-ottawa-time-varying-speed-2018) | University of Ottawa | 2018 | Diagnosis | Artificial (method not stated) | Vibration, Speed |
| [KAIST Varying Load (Multi-Sensor)](docs/datasets.md#kaist-varying-load-multi-sensor) | KAIST | 2023 | Diagnosis | Artificial (method not stated) | Vibration, Acoustic, Temperature, Current |
| [KAIST Varying Speed](docs/datasets.md#kaist-varying-speed) | KAIST | 2023 | Diagnosis | Artificial (method not stated) | Vibration, Current, Speed |
| [FEMTO-ST (PRONOSTIA)](docs/datasets.md#femto-st-pronostia) | FEMTO-ST Institute | 2012 | Prognostics | Natural (Accelerated) | Vibration, Temperature |
| [HUST (Hanoi University of Science and Technology)](docs/datasets.md#hust-hanoi-university-of-science-and-technology) | Hanoi University of Science and Technology | 2023 | Diagnosis | Artificial (Cracks) | Vibration |
| [Politecnico di Torino (DIRG)](docs/datasets.md#politecnico-di-torino-dirg) | Politecnico di Torino | 2019 | Diagnosis/ Prognostics | Artificial (Indentations) & Natural | Vibration |
| [Jiangnan University (JNU)](docs/datasets.md#jiangnan-university-jnu) | Jiangnan University | ~2023 | Diagnosis | Artificial (Dents) | Vibration |
| [UORED-VAFCLS (University of Ottawa, 2023)](docs/datasets.md#uored-vafcls-university-of-ottawa-2023) | University of Ottawa | 2023 | Diagnosis | Not stated | Vibration, Acoustic, Load, Speed, Temperature |
| [University of New South Wales (UNSW)](docs/datasets.md#university-of-new-south-wales-unsw) | University of New South Wales | 2022 | Prognostics | Natural (Accelerated) | Vibration |
| [SDOL (Korea Aerospace University)](docs/datasets.md#sdol-korea-aerospace-university) | Korea Aerospace University | ~2021 | Diagnosis | Artificial | Vibration |
| [Machinery Failure Prevention Technology (MFPT)](docs/datasets.md#machinery-failure-prevention-technology-mfpt) | Machinery Failure Prevention Technology | ~2000s | Diagnosis | Artificial & Natural | Vibration |
| [MAFAULDA (Machinery Fault Database)](docs/datasets.md#mafaulda-machinery-fault-database) | UFRJ | ~2018 | Diagnosis | Artificial | Vibration, Acoustic |
| [PHM09 Gearbox](docs/datasets.md#phm09-gearbox) | PHM Society | 2009 | Diagnosis | Artificial | Vibration |

### Diagnosis — Vibration (Laboratory)

| Dataset | Originating Institution(s) | Year | Primary Task | Fault Generation | Key Signals |
| :--- | :--- | :--- | :--- | :--- | :--- |
| [Politecnico di Torino (ISED)](docs/datasets.md#politecnico-di-torino-ised) | Politecnico di Torino | 2024 | Diagnosis | Artificial | Vibration, Temperature, Speed |
| [Politecnico di Torino (ISED) Multiple Defects](docs/datasets.md#politecnico-di-torino-ised-multiple-defects) | Politecnico di Torino | 2025 | Diagnosis | Artificial (Compound) | Vibration, Temperature, Speed |
| [German Aerospace Center (DLR)](docs/datasets.md#german-aerospace-center-dlr) | German Aerospace Center | 2023 | Diagnosis | Artificial (Spalls) | Vibration |
| [University of Seoul (UOS) Multi-Domain Compound Faults](docs/datasets.md#university-of-seoul-uos-multi-domain-compound-faults) | University of Seoul | 2024 | Diagnosis | Artificial | Vibration |
| [Harbin Institute of Technology (HIT-SM)](docs/datasets.md#harbin-institute-of-technology-hit-sm) | Harbin Institute of Technology | ~2022 | Diagnosis | Artificial | Vibration |
| [Vishwakarma Institute of Technology (VIT)](docs/datasets.md#vishwakarma-institute-of-technology-vit) | Vishwakarma Institute of Technology | 2024 | Diagnosis | Artificial | Vibration |
| [University of Arkansas (Single & Double Faults)](docs/datasets.md#university-of-arkansas-single--double-faults) | University of Arkansas | 2023 | Diagnosis | Artificial | Vibration |
| [NUST ICE Journal Bearing](docs/datasets.md#nust-ice-journal-bearing) | NUST, Pakistan | 2024 | Diagnosis | Natural (Wear) | Vibration |
| [BJTU-RAO Bogie Dataset](docs/datasets.md#bjtu-rao-bogie-dataset) | Beijing Jiaotong University | 2024 | Diagnosis | Artificial (Simulation) | Vibration, Acoustic, Current |
| [HAUST-LDV](docs/datasets.md#haust-ldv) | Henan University of Science and Technology | 2026 | Diagnosis | Artificial (Pitting) | Vibration (Laser Doppler) |
| [AITHE Bearing Dataset](docs/datasets.md#aithe-bearing-dataset) | Ahrar Institute of Technology and Higher Education | 2021 | Diagnosis | Artificial (method not stated) | Vibration |
| [Tecnalia Bearing, Variable Conditions](docs/datasets.md#tecnalia-bearing-variable-conditions) | Tecnalia | 2026 | Diagnosis | Artificial (method not stated) | Vibration, Tachometer |
| [Tecnalia Gearbox, Variable Conditions](docs/datasets.md#tecnalia-gearbox-variable-conditions) | Tecnalia | 2025 | Diagnosis | Artificial (method not stated) | Vibration, Torque, Current |
| [UC204 Outer Race Fault, Variable Load](docs/datasets.md#uc204-outer-race-fault-variable-load) | Universidade Federal da Paraíba | 2026 | Diagnosis | Artificial (Grooves) | Vibration |
| [JUST Slewing Bearing](docs/datasets.md#just-slewing-bearing) | Jiangsu University of Science and Technology | 2023 | Diagnosis | Artificial (method not stated) | Vibration, Acoustic |
| [Bearing 6213 Healthy vs. Compound Fault](docs/datasets.md#bearing-6213-healthy-vs-compound-fault) | VibroBox (Minsk) | 2020 | Diagnosis | Not stated | Vibration |
| [Army Engineering University of PLA, Mixed Bearing–Gearbox](docs/datasets.md#army-engineering-university-of-pla-mixed-bearinggearbox) | Army Engineering University of PLA | 2025 | Diagnosis | Artificial (Cracks, Laser Etching) | Vibration (Triaxial) |
| [Saarland University Cylindrical Roller IR Damage](docs/datasets.md#saarland-university-cylindrical-roller-ir-damage) | Saarland University / ZeMA | 2025 | Diagnosis | Artificial (Milled) | Vibration (3-axis), Force |
| [MOIRA-UNIMORE Independent Cart System](docs/datasets.md#moira-unimore-independent-cart-system) | University of Modena and Reggio Emilia | 2025 | Diagnosis | Artificial (Laser) | Vibration, Position, Speed, Current |
| [NOVIC+ Motor Compound Fault](docs/datasets.md#novic-motor-compound-fault) | KAIST | 2025 | Diagnosis | Artificial (Cracks) | Vibration, Temperature, Torque, Speed |
| [UPM CITEF Rolling Element Faults (2020)](docs/datasets.md#upm-citef-rolling-element-faults-2020) | Universidad Politécnica de Madrid | 2020 | Diagnosis | Artificial (Milled) | Vibration |
| [UPM CITEF Combined Faults (2021)](docs/datasets.md#upm-citef-combined-faults-2021) | Universidad Politécnica de Madrid | 2021 | Diagnosis | Artificial (Milled) | Vibration |
| [UPM CITEF Isolated Faults (2023)](docs/datasets.md#upm-citef-isolated-faults-2023) | Universidad Politécnica de Madrid | 2023 | Diagnosis | Artificial (Milled) | Vibration |
| [URMA-CRTI](docs/datasets.md#urma-crti) | CRTI (Annaba, Algeria) | 2026 | Diagnosis | Artificial (method not stated) | Vibration |
| [ISAC Lab Bearing and Unbalance](docs/datasets.md#isac-lab-bearing-and-unbalance) | University of Guilan | 2025 | Diagnosis | Artificial (method not stated) | Vibration |
| [VIT Vellore Taper Roller Bearing (Set 1)](docs/datasets.md#vit-vellore-taper-roller-bearing-set-1) | Vellore Institute of Technology | 2026 | Diagnosis | Artificial (Wire-cut EDM) | Vibration |
| [VIT Vellore Taper Roller Bearing (Set 2)](docs/datasets.md#vit-vellore-taper-roller-bearing-set-2) | Vellore Institute of Technology | 2026 | Diagnosis | Artificial (EDM) | Vibration |
| [VIT Vellore SpectraQuest Ball Bearing](docs/datasets.md#vit-vellore-spectraquest-ball-bearing) | Vellore Institute of Technology | 2026 | Diagnosis | Artificial (Ground) | Vibration |
| [University of Adelaide Defect Slope Series](docs/datasets.md#university-of-adelaide-defect-slope-series) | University of Adelaide | 2016 | Diagnosis | Artificial (EDM) | Vibration, Displacement, Acoustic, Load |
| [University of Adelaide Defect Length Series](docs/datasets.md#university-of-adelaide-defect-length-series) | University of Adelaide | 2017 | Diagnosis | Artificial (method not stated) | Vibration, Displacement, Acoustic, Load |
| [IFSP Bronze Plain-Bearing Bushing](docs/datasets.md#ifsp-bronze-plain-bearing-bushing) | Federal Institute of São Paulo (IFSP) | 2026 | Diagnosis | Artificial (Clearance, Eccentricity) | Vibration (MEMS) |
| [CUMTB Wind Turbine Pitch Bearing](docs/datasets.md#cumtb-wind-turbine-pitch-bearing) | China University of Mining and Technology (Beijing) | 2025 | Diagnosis | Artificial (EDM) | Vibration, Acoustic |

### Diagnosis — Acoustic and Non-Contact

| Dataset | Originating Institution(s) | Year | Primary Task | Fault Generation | Key Signals |
| :--- | :--- | :--- | :--- | :--- | :--- |
| [SUBF v2.0 Dataset: Bearing Faults Sound Data](docs/datasets.md#subf-v20-dataset-bearing-faults-sound-data) | University of Engineering and Technology Taxila | 2025 | Diagnosis | Artificial | Acoustic |
| [FSTF Mechanical Laboratory](docs/datasets.md#fstf-mechanical-laboratory) | FSTF Mechanical Laboratory at Sidi Mohamed Ben Abdellah University | 2023 | Diagnosis | Artificial & Natural | Acoustic |
| [GUET Multi-Condition Acoustic Ball Bearing](docs/datasets.md#guet-multi-condition-acoustic-ball-bearing) | Guilin University of Electronic Technology | 2026 | Diagnosis | Artificial (EDM, Wire Cutting, Fatigue) | Acoustic (3 microphones) |
| [AHU Parabolic Acoustic Mirror](docs/datasets.md#ahu-parabolic-acoustic-mirror) | Anhui University | 2026 | Diagnosis | Artificial (method not stated) | Acoustic |
| [HB-Bearing (Real Background Noise)](docs/datasets.md#hb-bearing-real-background-noise) | Yanshan University | 2025 | Diagnosis | Artificial (method not stated) | Acoustic |
| [EJUST-PdM-1 (Video)](docs/datasets.md#ejust-pdm-1-video) | Egypt-Japan University of Science and Technology | 2026 | Diagnosis | Artificial (method not stated) | Video (4K, 60 fps) |
| [DCASE Challenge Task 2 — Bearing](docs/datasets.md#dcase-challenge-task-2--bearing) | Hitachi / NTT | 2022 | Anomaly Detection | Artificial (Damaged Machine) | Acoustic |

### Motor-Level and Drive-Signal Datasets

| Dataset | Originating Institution(s) | Year | Primary Task | Fault Generation | Key Signals |
| :--- | :--- | :--- | :--- | :--- | :--- |
| [Mehran UET Motor Current](docs/datasets.md#mehran-uet-motor-current) | Mehran University of Engineering and Technology | 2022 | Diagnosis | Artificial (method not stated) | Current |
| [MCC5-THU Motor](docs/datasets.md#mcc5-thu-motor) | Tsinghua University / MCC5 Group | 2026 | Diagnosis | Artificial (Laser Etched) | Vibration, Current, Torque, Speed |
| [UOEMD-VAFCVS](docs/datasets.md#uoemd-vafcvs) | University of Ottawa | 2023 | Diagnosis | Artificial (Built into Motors) | Vibration, Acoustic, Temperature |
| [IM-VACD (Smartphone)](docs/datasets.md#im-vacd-smartphone) | University of Ottawa | 2026 | Diagnosis | Artificial (Built into Motors) | Vibration, Acoustic (Smartphone) |
| [Lenze-MB](docs/datasets.md#lenze-mb) | Lenze SE | 2025 | Diagnosis | Artificial (Pitting) | Drive Signals (Current, Voltage, Encoder) |
| [ESTOGU](docs/datasets.md#estogu) | Eskişehir Technical University | 2026 | Diagnosis | Not confirmed (see caveat) | Vibration, Current, Voltage |
| [KIMM PMSM Multi-Location](docs/datasets.md#kimm-pmsm-multi-location) | Korea Institute of Machinery & Materials | 2026 | Diagnosis | Artificial (Balls Removed) | Vibration (MEMS) |

### Prognostics (Run-to-Failure)

| Dataset | Originating Institution(s) | Year | Primary Task | Fault Generation | Key Signals |
| :--- | :--- | :--- | :--- | :--- | :--- |
| [University of Ferrara](docs/datasets.md#university-of-ferrara) | University of Ferrara | 2024 | Prognostics | Natural (Accelerated) | Vibration |
| [DLR Oscillating Needle Bearing Endurance](docs/datasets.md#dlr-oscillating-needle-bearing-endurance) | German Aerospace Center (DLR) | 2026 | Prognostics | Natural (Accelerated) | Vibration, Displacement, Torque, Temperature |
| [Wind Turbine High-Speed Shaft Bearing](docs/datasets.md#wind-turbine-high-speed-shaft-bearing) | Green Power Monitoring Systems | 2018 | Prognostics | Natural (Field) | Vibration, Tachometer |

### Field and SCADA Data

| Dataset | Originating Institution(s) | Year | Primary Task | Fault Generation | Key Signals |
| :--- | :--- | :--- | :--- | :--- | :--- |
| [SCA Bearing Dataset](docs/datasets.md#sca-bearing-dataset) | Mittuniversitetet | 2024 | Diagnosis | Natural (Industrial) | Vibration |
| [Fraunhofer LBF Wind Turbine](docs/datasets.md#fraunhofer-lbf-wind-turbine) | Fraunhofer LBF / TU Darmstadt | 2024 | Diagnosis | Artificial (Etched) | Vibration, Temperature, Wind |
| [Siemens 2 MW Wind Turbine SCADA](docs/datasets.md#siemens-2-mw-wind-turbine-scada) | AGH University of Krakow | 2026 | Anomaly Detection | Natural (Field) | SCADA |
| [CARE to Compare](docs/datasets.md#care-to-compare) | Fraunhofer IEE | 2024 | Anomaly Detection | Natural (Field) | SCADA |

### Other Modalities

| Dataset | Originating Institution(s) | Year | Primary Task | Fault Generation | Key Signals |
| :--- | :--- | :--- | :--- | :--- | :--- |
| [Wind Turbine Bearings with White Etching Cracks](docs/datasets.md#wind-turbine-bearings-with-white-etching-cracks) | DTU Wind Energy / NTNU | 2018 | Diagnosis | Natural (Accelerated) | Ultrasound Images |

---

## 🤝 How to Contribute

This document is intended to be a living resource. Contributions are welcome to ensure it remains accurate, comprehensive, and up-to-date.

* **Open an Issue:** For any proposed changes or additions, please open a new issue in the repository's issue tracker.
* **Provide Details:** In the issue, clearly describe the proposed change. If suggesting a new dataset, please provide a link to its official source, a reference to a primary publication, and a summary of its key characteristics.
* **Submit a Pull Request (Optional):** For those comfortable with Markdown and Git, you can fork the repository, make your changes directly, and submit a pull request for review.

## Inspiration

This list was inspired by the work of repositories like [hustcxl/Rotating-machine-fault-data-set](https://github.com/hustcxl/Rotating-machine-fault-data-set/tree/master).

## License

This project is licensed under the [MIT License](LICENSE).
