# Dataset Citation Ranking

Citation counts of each dataset's reference paper, used to select the Core Datasets in the [README](../README.md#core-datasets). Counts were retrieved from [OpenAlex](https://openalex.org) on 26 September 2026.

* **Per year** = citations ÷ years since publication (counting the publication year). It is used for ranking so that recent datasets are not penalized only for being new.
* **Reference type:** *official* = the paper the dataset authors ask users to cite, or the dataset's data paper; *proxy* = a commonly used stand-in where no official paper exists.
* **Core rule:** 10 or more citations per year, plus MFPT, MAFAULDA, and PHM09 by convention. The Paderborn and KAIST run-to-failure datasets are listed alongside their groups' core datasets.
* **Why counts differ from other sites:** citation counts depend on the database. Publisher pages (e.g., IEEE Xplore, ScienceDirect), Crossref, Semantic Scholar, and Google Scholar each index a different set of citing documents and match references differently, so their numbers will not match this table. For example, the SEU paper has 1648 citations in OpenAlex, 1577 in Crossref, and 1427 in Semantic Scholar. Google Scholar is usually highest. This table uses OpenAlex for every dataset so the ranking is consistent; the OpenAlex column links to the exact record used. Counts keep changing after the snapshot date.
* **Caveats:** for some datasets the reference is a method paper that used the data (e.g., HUST Huazhong, Siemens 2 MW SCADA, URMA-CRTI, Lenze-MB), so its count reflects the method as much as the dataset. Counts for 2025–2026 datasets are naturally low. Datasets described in the same paper (e.g., KAIST varying load and varying speed) share one count.

## Ranked Datasets

| # | Dataset | Citations | Year | Per Year | Reference Type | Reference Paper | OpenAlex |
| ---: | :--- | ---: | ---: | ---: | :--- | :--- | :--- |
| 1 | [Case Western Reserve University (CWRU)](datasets.md#case-western-reserve-university-cwru) | 2715 | 2015 | 226.2 | proxy | [10.1016/j.ymssp.2015.04.021](https://doi.org/10.1016/j.ymssp.2015.04.021) | [W243674440](https://openalex.org/W243674440) |
| 2 | [Xi'an Jiaotong University (XJTU-SY)](datasets.md#xian-jiaotong-university-xjtu-sy) | 1904 | 2018 | 211.6 | official | [10.1109/TR.2018.2882682](https://doi.org/10.1109/TR.2018.2882682) | [W2904460913](https://openalex.org/W2904460913) |
| 3 | [Southeast University (SEU)](datasets.md#southeast-university-seu) | 1648 | 2018 | 183.1 | official | [10.1109/TII.2018.2864759](https://doi.org/10.1109/TII.2018.2864759) | [W2887782657](https://openalex.org/W2887782657) |
| 4 | [HUST (Huazhong University of Science and Technology)](datasets.md#hust-huazhong-university-of-science-and-technology) | 513 | 2024 | 171.0 | official | [10.1016/j.ress.2024.109964](https://doi.org/10.1016/j.ress.2024.109964) | [W4391247724](https://openalex.org/W4391247724) |
| 5 | [Paderborn University (PU)](datasets.md#paderborn-university-pu) | 1265 | 2016 | 115.0 | official | [10.36001/phme.2016.v3i1.1577](https://doi.org/10.36001/phme.2016.v3i1.1577) | [W2530133016](https://openalex.org/W2530133016) |
| 6 | [NASA IMS](datasets.md#nasa-ims) | 1481 | 2005 | 67.3 | official | [10.1016/j.jsv.2005.03.007](https://doi.org/10.1016/j.jsv.2005.03.007) | [W2019505419](https://openalex.org/W2019505419) |
| 7 | [University of Ottawa Time-Varying Speed (2018)](datasets.md#university-of-ottawa-time-varying-speed-2018) | 506 | 2018 | 56.2 | official | [10.1016/j.dib.2018.11.019](https://doi.org/10.1016/j.dib.2018.11.019) | [W2900367617](https://openalex.org/W2900367617) |
| 8 | [KAIST Varying Load (Multi-Sensor)](datasets.md#kaist-varying-load-multi-sensor) | 197 | 2023 | 49.2 | official | [10.1016/j.dib.2023.109049](https://doi.org/10.1016/j.dib.2023.109049) | [W4323664477](https://openalex.org/W4323664477) |
| 9 | [KAIST Varying Speed](datasets.md#kaist-varying-speed) | 197 | 2023 | 49.2 | official | [10.1016/j.dib.2023.109049](https://doi.org/10.1016/j.dib.2023.109049) | [W4323664477](https://openalex.org/W4323664477) |
| 10 | [FEMTO-ST (PRONOSTIA)](datasets.md#femto-st-pronostia) | 693 | 2012 | 46.2 | official | No DOI ([HAL](https://hal.science/hal-00719503)) | [W2603225712](https://openalex.org/W2603225712) |
| 11 | [HUST (Hanoi University of Science and Technology)](datasets.md#hust-hanoi-university-of-science-and-technology) | 136 | 2023 | 34.0 | official | [10.1186/s13104-023-06400-4](https://doi.org/10.1186/s13104-023-06400-4) | [W4383371431](https://openalex.org/W4383371431) |
| 12 | [Politecnico di Torino (DIRG)](datasets.md#politecnico-di-torino-dirg) | 254 | 2018 | 28.2 | official | [10.1016/j.ymssp.2018.10.010](https://doi.org/10.1016/j.ymssp.2018.10.010) | [W2899318073](https://openalex.org/W2899318073) |
| 13 | [Siemens 2 MW Wind Turbine SCADA](datasets.md#siemens-2-mw-wind-turbine-scada) | 218 | 2017 | 21.8 | official | [10.1016/j.renene.2017.06.089](https://doi.org/10.1016/j.renene.2017.06.089) | [W2653623715](https://openalex.org/W2653623715) |
| 14 | [Jiangnan University (JNU)](datasets.md#jiangnan-university-jnu) | 293 | 2013 | 20.9 | official | [10.3390/s130608013](https://doi.org/10.3390/s130608013) | [W2010619950](https://openalex.org/W2010619950) |
| 15 | [UOEMD-VAFCVS](datasets.md#uoemd-vafcvs) | 49 | 2024 | 16.3 | official | [10.1016/j.dib.2024.110144](https://doi.org/10.1016/j.dib.2024.110144) | [W4391469864](https://openalex.org/W4391469864) |
| 16 | [UORED-VAFCLS (University of Ottawa, 2023)](datasets.md#uored-vafcls-university-of-ottawa-2023) | 63 | 2023 | 15.8 | official | [10.1016/j.dib.2023.109327](https://doi.org/10.1016/j.dib.2023.109327) | [W4381112601](https://openalex.org/W4381112601) |
| 17 | [URMA-CRTI](datasets.md#urma-crti) | 105 | 2019 | 13.1 | official | [10.1007/s00170-019-04726-7](https://doi.org/10.1007/s00170-019-04726-7) | [W2994887188](https://openalex.org/W2994887188) |
| 18 | [Lenze-MB](datasets.md#lenze-mb) | 50 | 2023 | 12.5 | official | [10.1016/j.engappai.2023.106834](https://doi.org/10.1016/j.engappai.2023.106834) | [W4385493032](https://openalex.org/W4385493032) |
| 19 | [University of New South Wales (UNSW)](datasets.md#university-of-new-south-wales-unsw) | 55 | 2022 | 11.0 | official | [10.1016/j.ymssp.2021.108466](https://doi.org/10.1016/j.ymssp.2021.108466) | [W3201953627](https://openalex.org/W3201953627) |
| 20 | [SDOL (Korea Aerospace University)](datasets.md#sdol-korea-aerospace-university) | 75 | 2020 | 10.7 | official | [10.3390/app10207302](https://doi.org/10.3390/app10207302) | [W3094325960](https://openalex.org/W3094325960) |
| 21 | [CARE to Compare](datasets.md#care-to-compare) | 28 | 2024 | 9.3 | official | [10.3390/data9120138](https://doi.org/10.3390/data9120138) | [W4404700659](https://openalex.org/W4404700659) |
| 22 | [Politecnico di Torino (ISED)](datasets.md#politecnico-di-torino-ised) | 40 | 2022 | 8.0 | proxy | [10.3390/s23010211](https://doi.org/10.3390/s23010211) | [W4313259654](https://openalex.org/W4313259654) |
| 23 | [Politecnico di Torino (ISED) Multiple Defects](datasets.md#politecnico-di-torino-ised-multiple-defects) | 40 | 2022 | 8.0 | official | [10.3390/s23010211](https://doi.org/10.3390/s23010211) | [W4313259654](https://openalex.org/W4313259654) |
| 24 | [BJTU-RAO Bogie Dataset](datasets.md#bjtu-rao-bogie-dataset) | 14 | 2025 | 7.0 | official | [10.1109/ACCESS.2025.3551603](https://doi.org/10.1109/ACCESS.2025.3551603) | [W4408609531](https://openalex.org/W4408609531) |
| 25 | [ISAC Lab Bearing and Unbalance](datasets.md#isac-lab-bearing-and-unbalance) | 13 | 2025 | 6.5 | official | [10.1080/23307706.2025.2567006](https://doi.org/10.1080/23307706.2025.2567006) | [W4416358489](https://openalex.org/W4416358489) |
| 26 | [Fraunhofer LBF Wind Turbine](datasets.md#fraunhofer-lbf-wind-turbine) | 19 | 2024 | 6.3 | official | [10.1038/s41597-024-03934-5](https://doi.org/10.1038/s41597-024-03934-5) | [W4403243077](https://openalex.org/W4403243077) |
| 27 | [SUBF v2.0 Dataset: Bearing Faults Sound Data](datasets.md#subf-v20-dataset-bearing-faults-sound-data) | 19 | 2024 | 6.3 | official | [10.1016/j.dsp.2024.104776](https://doi.org/10.1016/j.dsp.2024.104776) | [W4402468366](https://openalex.org/W4402468366) |
| 28 | [MCC5-THU Motor](datasets.md#mcc5-thu-motor) | 6 | 2026 | 6.0 | official | [10.1016/j.dib.2026.112583](https://doi.org/10.1016/j.dib.2026.112583) | [W7128774856](https://openalex.org/W7128774856) |
| 29 | [UPM CITEF Rolling Element Faults (2020)](datasets.md#upm-citef-rolling-element-faults-2020) | 41 | 2020 | 5.9 | official | [10.3390/s20123493](https://doi.org/10.3390/s20123493) | [W3036655301](https://openalex.org/W3036655301) |
| 30 | [AITHE Bearing Dataset](datasets.md#aithe-bearing-dataset) | 33 | 2021 | 5.5 | official | [10.1007/s00500-021-06307-x](https://doi.org/10.1007/s00500-021-06307-x) | [W3202170162](https://openalex.org/W3202170162) |
| 31 | [DCASE Challenge Task 2 — Bearing](datasets.md#dcase-challenge-task-2--bearing) | 22 | 2022 | 4.4 | official | [10.48550/arXiv.2205.13879](https://doi.org/10.48550/arXiv.2205.13879) | [W4281719388](https://openalex.org/W4281719388) |
| 32 | [University of Seoul (UOS) Multi-Domain Compound Faults](datasets.md#university-of-seoul-uos-multi-domain-compound-faults) | 13 | 2024 | 4.3 | official | [10.1016/j.dib.2024.110940](https://doi.org/10.1016/j.dib.2024.110940) | [W4402536317](https://openalex.org/W4402536317) |
| 33 | [Wind Turbine High-Speed Shaft Bearing](datasets.md#wind-turbine-high-speed-shaft-bearing) | 58 | 2013 | 4.1 | official | [10.36001/phmconf.2013.v5i1.2220](https://doi.org/10.36001/phmconf.2013.v5i1.2220) | [W2606377831](https://openalex.org/W2606377831) |
| 34 | [SCA Bearing Dataset](datasets.md#sca-bearing-dataset) | 15 | 2023 | 3.8 | official | [10.3390/data8070115](https://doi.org/10.3390/data8070115) | [W4382584507](https://openalex.org/W4382584507) |
| 35 | [MAFAULDA (Machinery Fault Database)](datasets.md#mafaulda-machinery-fault-database) | 36 | 2017 | 3.6 | proxy | [10.14209/sbrt.2017.133](https://doi.org/10.14209/sbrt.2017.133) | [W2976936892](https://openalex.org/W2976936892) |
| 36 | [KAIST Run-to-Failure](datasets.md#kaist-run-to-failure) | 10 | 2024 | 3.3 | official | [10.1016/j.dib.2024.110403](https://doi.org/10.1016/j.dib.2024.110403) | [W4394685279](https://openalex.org/W4394685279) |
| 37 | [University of Ferrara](datasets.md#university-of-ferrara) | 10 | 2024 | 3.3 | official | [10.1016/j.dib.2024.110620](https://doi.org/10.1016/j.dib.2024.110620) | [W4399925440](https://openalex.org/W4399925440) |
| 38 | [Harbin Institute of Technology (HIT-SM)](datasets.md#harbin-institute-of-technology-hit-sm) | 16 | 2022 | 3.2 | official | [10.1088/1361-6501/ac7941](https://doi.org/10.1088/1361-6501/ac7941) | [W4282983125](https://openalex.org/W4282983125) |
| 39 | [University of Adelaide Defect Slope Series](datasets.md#university-of-adelaide-defect-slope-series) | 22 | 2020 | 3.1 | official | [10.1177/1475921720938296](https://doi.org/10.1177/1475921720938296) | [W3048055158](https://openalex.org/W3048055158) |
| 40 | [MOIRA-UNIMORE Independent Cart System](datasets.md#moira-unimore-independent-cart-system) | 6 | 2025 | 3.0 | official | [10.3390/app15073691](https://doi.org/10.3390/app15073691) | [W4408924713](https://openalex.org/W4408924713) |
| 41 | [NOVIC+ Motor Compound Fault](datasets.md#novic-motor-compound-fault) | 6 | 2025 | 3.0 | official | [10.1016/j.ymssp.2025.113786](https://doi.org/10.1016/j.ymssp.2025.113786) | [W4414855970](https://openalex.org/W4414855970) |
| 42 | [Vishwakarma Institute of Technology (VIT)](datasets.md#vishwakarma-institute-of-technology-vit) | 5 | 2025 | 2.5 | official | [10.1016/j.dib.2025.111455](https://doi.org/10.1016/j.dib.2025.111455) | [W4408394410](https://openalex.org/W4408394410) |
| 43 | [University of Arkansas (Single & Double Faults)](datasets.md#university-of-arkansas-single--double-faults) | 10 | 2023 | 2.5 | official | [10.1016/j.dib.2023.109358](https://doi.org/10.1016/j.dib.2023.109358) | [W4382929685](https://openalex.org/W4382929685) |
| 44 | [VIT Vellore SpectraQuest Ball Bearing](datasets.md#vit-vellore-spectraquest-ball-bearing) | 5 | 2025 | 2.5 | official | [10.1038/s41598-025-01780-y](https://doi.org/10.1038/s41598-025-01780-y) | [W4410726974](https://openalex.org/W4410726974) |
| 45 | [CUMTB Wind Turbine Pitch Bearing](datasets.md#cumtb-wind-turbine-pitch-bearing) | 5 | 2025 | 2.5 | official | [10.1016/j.dib.2025.111876](https://doi.org/10.1016/j.dib.2025.111876) | [W4412870979](https://openalex.org/W4412870979) |
| 46 | [German Aerospace Center (DLR)](datasets.md#german-aerospace-center-dlr) | 9 | 2023 | 2.2 | official | [10.1016/j.dib.2023.109019](https://doi.org/10.1016/j.dib.2023.109019) | [W4322621256](https://openalex.org/W4322621256) |
| 47 | [Paderborn University (Time-Varying Run-to-Failure)](datasets.md#paderborn-university-time-varying-run-to-failure) | 6 | 2024 | 2.0 | official | [10.36001/phme.2024.v8i1.4101](https://doi.org/10.36001/phme.2024.v8i1.4101) | [W4400101200](https://openalex.org/W4400101200) |
| 48 | [Army Engineering University of PLA, Mixed Bearing–Gearbox](datasets.md#army-engineering-university-of-pla-mixed-bearinggearbox) | 4 | 2025 | 2.0 | official | [10.1016/j.dib.2025.112187](https://doi.org/10.1016/j.dib.2025.112187) | [W4415328257](https://openalex.org/W4415328257) |
| 49 | [NUST ICE Journal Bearing](datasets.md#nust-ice-journal-bearing) | 5 | 2024 | 1.7 | official | [10.1016/j.dib.2024.111214](https://doi.org/10.1016/j.dib.2024.111214) | [W4405131180](https://openalex.org/W4405131180) |
| 50 | [University of Adelaide Defect Length Series](datasets.md#university-of-adelaide-defect-length-series) | 13 | 2018 | 1.4 | official | [10.1177/1475921718808805](https://doi.org/10.1177/1475921718808805) | [W2898344073](https://openalex.org/W2898344073) |
| 51 | [UPM CITEF Combined Faults (2021)](datasets.md#upm-citef-combined-faults-2021) | 7 | 2021 | 1.2 | official | [10.3390/app11146452](https://doi.org/10.3390/app11146452) | [W3179780895](https://openalex.org/W3179780895) |
| 52 | [EJUST-PdM-1 (Video)](datasets.md#ejust-pdm-1-video) | 1 | 2025 | 0.5 | official | [10.5220/0013715900003982](https://doi.org/10.5220/0013715900003982) | [W4415591971](https://openalex.org/W4415591971) |
| 53 | [Saarland University Cylindrical Roller IR Damage](datasets.md#saarland-university-cylindrical-roller-ir-damage) | 0 | 2025 | 0.0 | official | [10.3390/data10050077](https://doi.org/10.3390/data10050077) | [W4410442321](https://openalex.org/W4410442321) |
| 54 | [IFSP Bronze Plain-Bearing Bushing](datasets.md#ifsp-bronze-plain-bearing-bushing) | 0 | 2026 | 0.0 | official | [10.1109/OJIM.2026.3720860](https://doi.org/10.1109/OJIM.2026.3720860) | [W7196948392](https://openalex.org/W7196948392) |
| 55 | [GUET Multi-Condition Acoustic Ball Bearing](datasets.md#guet-multi-condition-acoustic-ball-bearing) | 0 | 2026 | 0.0 | official | [10.1016/j.dib.2026.112919](https://doi.org/10.1016/j.dib.2026.112919) | [W7163578371](https://openalex.org/W7163578371) |
| 56 | [HB-Bearing (Real Background Noise)](datasets.md#hb-bearing-real-background-noise) | 0 | 2026 | 0.0 | official | [10.1109/TASLPRO.2026.3685908](https://doi.org/10.1109/TASLPRO.2026.3685908) | [W7155512343](https://openalex.org/W7155512343) |
| 57 | [IM-VACD (Smartphone)](datasets.md#im-vacd-smartphone) | 0 | 2026 | 0.0 | official | [10.1016/j.ymssp.2026.114922](https://doi.org/10.1016/j.ymssp.2026.114922) | [W7207659323](https://openalex.org/W7207659323) |
| 58 | [KIMM PMSM Multi-Location](datasets.md#kimm-pmsm-multi-location) | 0 | 2026 | 0.0 | official | [10.1038/s41598-026-73197-0](https://doi.org/10.1038/s41598-026-73197-0) | [W7214298413](https://openalex.org/W7214298413) |
| 59 | [FSTF Mechanical Laboratory](datasets.md#fstf-mechanical-laboratory) | 0 | 2023 | 0.0 | none | – | [W6925745250](https://openalex.org/W6925745250) |
| 60 | [UPM CITEF Isolated Faults (2023)](datasets.md#upm-citef-isolated-faults-2023) | 0 | 2023 | 0.0 | official | [10.3390/math11163498](https://doi.org/10.3390/math11163498) | [W4385812855](https://openalex.org/W4385812855) |

## Datasets Without a Citable Paper

These datasets have no reference paper with a citation count (no paper found, or the paper is not indexed).

| Dataset | Note |
| :--- | :--- |
| [HAUST-LDV](datasets.md#haust-ldv) | No associated paper found |
| [Tecnalia Bearing, Variable Conditions](datasets.md#tecnalia-bearing-variable-conditions) | No associated paper found |
| [Tecnalia Gearbox, Variable Conditions](datasets.md#tecnalia-gearbox-variable-conditions) | No associated paper found |
| [UC204 Outer Race Fault, Variable Load](datasets.md#uc204-outer-race-fault-variable-load) | No associated paper found |
| [JUST Slewing Bearing](datasets.md#just-slewing-bearing) | Reference paper not indexed in OpenAlex |
| [Bearing 6213 Healthy vs. Compound Fault](datasets.md#bearing-6213-healthy-vs-compound-fault) | No associated paper found |
| [VIT Vellore Taper Roller Bearing (Set 1)](datasets.md#vit-vellore-taper-roller-bearing-set-1) | No associated paper found |
| [AHU Parabolic Acoustic Mirror](datasets.md#ahu-parabolic-acoustic-mirror) | No associated paper found |
| [Wind Turbine Bearings with White Etching Cracks](datasets.md#wind-turbine-bearings-with-white-etching-cracks) | No associated paper found |
| [Mehran UET Motor Current](datasets.md#mehran-uet-motor-current) | No associated paper found |
| [ESTOGU](datasets.md#estogu) | No associated paper found |
| [DLR Oscillating Needle Bearing Endurance](datasets.md#dlr-oscillating-needle-bearing-endurance) | No associated paper found |
| [Machinery Failure Prevention Technology (MFPT)](datasets.md#machinery-failure-prevention-technology-mfpt) | No associated paper found |
| [PHM09 Gearbox](datasets.md#phm09-gearbox) | No associated paper found |
| [VIT Vellore Taper Roller Bearing (Set 2)](datasets.md#vit-vellore-taper-roller-bearing-set-2) | No associated paper found |

[Back to the summary](../README.md#summary-of-datasets)
