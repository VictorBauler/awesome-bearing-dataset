# Dataset Citation Ranking

Citation counts of each dataset's reference paper, used to select the Core Datasets in the [README](../README.md#core-datasets). Counts were retrieved from [OpenAlex](https://openalex.org) on 26 September 2026.

* **Per year** = citations ÷ years since publication (counting the publication year). It is used for ranking so that recent datasets are not penalized only for being new.
* **Reference type:** *official* = the paper the dataset authors ask users to cite, or the dataset's data paper; *proxy* = a commonly used stand-in where no official paper exists.
* **Core rule:** 10 or more citations per year, plus MFPT, MAFAULDA, and PHM09 by convention. The Paderborn and KAIST run-to-failure datasets are listed alongside their groups' core datasets.
* **Why counts differ from other sites:** citation counts depend on the database. Publisher pages (e.g., IEEE Xplore, ScienceDirect), Crossref, Semantic Scholar, and Google Scholar each index a different set of citing documents and match references differently, so their numbers will not match this table. For example, the SEU paper has 1648 citations in OpenAlex, 1577 in Crossref, and 1427 in Semantic Scholar. Google Scholar is usually highest. This table uses OpenAlex for every dataset so the ranking is consistent; the OpenAlex column links to the exact record used. Counts keep changing after the snapshot date.
* **Caveats:** for some datasets the reference is a method paper that used the data (e.g., HUST Huazhong, SDUST, NEEPU, SUSU, Siemens 2 MW SCADA, URMA-CRTI, Lenze-MB), so its count reflects the method as much as the dataset. Counts for 2025–2026 datasets are naturally low. Datasets described in the same paper (e.g., KAIST varying load and varying speed) share one count.

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
| 11 | [HIT Inter-Shaft Bearing (Aero-Engine)](datasets.md#hit-inter-shaft-bearing-aero-engine) | 169 | 2023 | 42.2 | official | [10.37965/jdmd.2023.314](https://doi.org/10.37965/jdmd.2023.314) | [W4385548165](https://openalex.org/W4385548165) |
| 12 | [MCC5-THU Gearbox](datasets.md#mcc5-thu-gearbox) | 124 | 2024 | 41.3 | official | [10.1016/j.dib.2024.110453](https://doi.org/10.1016/j.dib.2024.110453) | [W4394912981](https://openalex.org/W4394912981) |
| 13 | [SUSU Shaft-Mounted Wireless Sensor](datasets.md#susu-shaft-mounted-wireless-sensor) | 177 | 2022 | 35.4 | official | [10.1016/j.ymssp.2022.109454](https://doi.org/10.1016/j.ymssp.2022.109454) | [W4225815954](https://openalex.org/W4225815954) |
| 14 | [HUST (Hanoi University of Science and Technology)](datasets.md#hust-hanoi-university-of-science-and-technology) | 136 | 2023 | 34.0 | official | [10.1186/s13104-023-06400-4](https://doi.org/10.1186/s13104-023-06400-4) | [W4383371431](https://openalex.org/W4383371431) |
| 15 | [SDUST Bearing and Gear](datasets.md#sdust-bearing-and-gear) | 131 | 2023 | 32.8 | official | [10.1016/j.knosys.2023.111285](https://doi.org/10.1016/j.knosys.2023.111285) | [W4389410654](https://openalex.org/W4389410654) |
| 16 | [Politecnico di Torino (DIRG)](datasets.md#politecnico-di-torino-dirg) | 254 | 2018 | 28.2 | official | [10.1016/j.ymssp.2018.10.010](https://doi.org/10.1016/j.ymssp.2018.10.010) | [W2899318073](https://openalex.org/W2899318073) |
| 17 | [NEEPU Bearing Dataset](datasets.md#neepu-bearing-dataset) | 106 | 2023 | 26.5 | official | [10.1016/j.aei.2023.101890](https://doi.org/10.1016/j.aei.2023.101890) | [W4319986927](https://openalex.org/W4319986927) |
| 18 | [Siemens 2 MW Wind Turbine SCADA](datasets.md#siemens-2-mw-wind-turbine-scada) | 218 | 2017 | 21.8 | official | [10.1016/j.renene.2017.06.089](https://doi.org/10.1016/j.renene.2017.06.089) | [W2653623715](https://openalex.org/W2653623715) |
| 19 | [Jiangnan University (JNU)](datasets.md#jiangnan-university-jnu) | 293 | 2013 | 20.9 | official | [10.3390/s130608013](https://doi.org/10.3390/s130608013) | [W2010619950](https://openalex.org/W2010619950) |
| 20 | [SQ Variable-Speed Bearing (SQV)](datasets.md#sq-variable-speed-bearing-sqv) | 84 | 2022 | 16.8 | official | [10.1016/j.ymssp.2022.110071](https://doi.org/10.1016/j.ymssp.2022.110071) | [W4313397280](https://openalex.org/W4313397280) |
| 21 | [UOEMD-VAFCVS](datasets.md#uoemd-vafcvs) | 49 | 2024 | 16.3 | official | [10.1016/j.dib.2024.110144](https://doi.org/10.1016/j.dib.2024.110144) | [W4391469864](https://openalex.org/W4391469864) |
| 22 | [UORED-VAFCLS (University of Ottawa, 2023)](datasets.md#uored-vafcls-university-of-ottawa-2023) | 63 | 2023 | 15.8 | official | [10.1016/j.dib.2023.109327](https://doi.org/10.1016/j.dib.2023.109327) | [W4381112601](https://openalex.org/W4381112601) |
| 23 | [URMA-CRTI](datasets.md#urma-crti) | 105 | 2019 | 13.1 | official | [10.1007/s00170-019-04726-7](https://doi.org/10.1007/s00170-019-04726-7) | [W2994887188](https://openalex.org/W2994887188) |
| 24 | [Lenze-MB](datasets.md#lenze-mb) | 50 | 2023 | 12.5 | official | [10.1016/j.engappai.2023.106834](https://doi.org/10.1016/j.engappai.2023.106834) | [W4385493032](https://openalex.org/W4385493032) |
| 25 | [University of New South Wales (UNSW)](datasets.md#university-of-new-south-wales-unsw) | 55 | 2022 | 11.0 | official | [10.1016/j.ymssp.2021.108466](https://doi.org/10.1016/j.ymssp.2021.108466) | [W3201953627](https://openalex.org/W3201953627) |
| 26 | [SDOL (Korea Aerospace University)](datasets.md#sdol-korea-aerospace-university) | 75 | 2020 | 10.7 | official | [10.3390/app10207302](https://doi.org/10.3390/app10207302) | [W3094325960](https://openalex.org/W3094325960) |
| 27 | [NLN-EMP Navy E-Motor Pump](datasets.md#nln-emp-navy-e-motor-pump) | 40 | 2023 | 10.0 | official | [10.1016/j.dib.2023.109987](https://doi.org/10.1016/j.dib.2023.109987) | [W4389841697](https://openalex.org/W4389841697) |
| 28 | [CARE to Compare](datasets.md#care-to-compare) | 28 | 2024 | 9.3 | official | [10.3390/data9120138](https://doi.org/10.3390/data9120138) | [W4404700659](https://openalex.org/W4404700659) |
| 29 | [Mehran UET Motor Bearing (Vibration & Current)](datasets.md#mehran-uet-motor-bearing-vibration--current) | 46 | 2022 | 9.2 | official | [10.1016/j.dib.2022.108315](https://doi.org/10.1016/j.dib.2022.108315) | [W4281395108](https://openalex.org/W4281395108) |
| 30 | [Politecnico di Torino (ISED)](datasets.md#politecnico-di-torino-ised) | 40 | 2022 | 8.0 | proxy | [10.3390/s23010211](https://doi.org/10.3390/s23010211) | [W4313259654](https://openalex.org/W4313259654) |
| 31 | [SUBF v1.0: Bearing Fault Vibration Data](datasets.md#subf-v10-bearing-fault-vibration-data) | 30 | 2023 | 7.5 | official | [10.1016/j.measurement.2023.112871](https://doi.org/10.1016/j.measurement.2023.112871) | [W4365511600](https://openalex.org/W4365511600) |
| 32 | [BJTU-RAO Bogie Dataset](datasets.md#bjtu-rao-bogie-dataset) | 14 | 2025 | 7.0 | official | [10.1109/ACCESS.2025.3551603](https://doi.org/10.1109/ACCESS.2025.3551603) | [W4408609531](https://openalex.org/W4408609531) |
| 33 | [VBL-VA001](datasets.md#vbl-va001) | 27 | 2023 | 6.8 | official | [10.1007/s42417-023-00959-9](https://doi.org/10.1007/s42417-023-00959-9) | [W4378549149](https://openalex.org/W4378549149) |
| 34 | [ISAC Lab Bearing and Unbalance](datasets.md#isac-lab-bearing-and-unbalance) | 13 | 2025 | 6.5 | official | [10.1080/23307706.2025.2567006](https://doi.org/10.1080/23307706.2025.2567006) | [W4416358489](https://openalex.org/W4416358489) |
| 35 | [Fraunhofer LBF Wind Turbine](datasets.md#fraunhofer-lbf-wind-turbine) | 19 | 2024 | 6.3 | official | [10.1038/s41597-024-03934-5](https://doi.org/10.1038/s41597-024-03934-5) | [W4403243077](https://openalex.org/W4403243077) |
| 36 | [SUBF v2.0 Dataset: Bearing Faults Sound Data](datasets.md#subf-v20-dataset-bearing-faults-sound-data) | 19 | 2024 | 6.3 | official | [10.1016/j.dsp.2024.104776](https://doi.org/10.1016/j.dsp.2024.104776) | [W4402468366](https://openalex.org/W4402468366) |
| 37 | [HDU PT500 Compound Faults](datasets.md#hdu-pt500-compound-faults) | 19 | 2024 | 6.3 | official | [10.1109/TIM.2024.3470961](https://doi.org/10.1109/TIM.2024.3470961) | [W4402979658](https://openalex.org/W4402979658) |
| 38 | [MCC5-THU Motor](datasets.md#mcc5-thu-motor) | 6 | 2026 | 6.0 | official | [10.1016/j.dib.2026.112583](https://doi.org/10.1016/j.dib.2026.112583) | [W7128774856](https://openalex.org/W7128774856) |
| 39 | [UPM CITEF Rolling Element Faults (2020)](datasets.md#upm-citef-rolling-element-faults-2020) | 41 | 2020 | 5.9 | official | [10.3390/s20123493](https://doi.org/10.3390/s20123493) | [W3036655301](https://openalex.org/W3036655301) |
| 40 | [AITHE Bearing Dataset](datasets.md#aithe-bearing-dataset) | 33 | 2021 | 5.5 | official | [10.1007/s00500-021-06307-x](https://doi.org/10.1007/s00500-021-06307-x) | [W3202170162](https://openalex.org/W3202170162) |
| 41 | [DCASE Challenge Task 2 — Bearing](datasets.md#dcase-challenge-task-2--bearing) | 22 | 2022 | 4.4 | official | [10.48550/arXiv.2205.13879](https://doi.org/10.48550/arXiv.2205.13879) | [W4281719388](https://openalex.org/W4281719388) |
| 42 | [University of Seoul (UOS) Multi-Domain Compound Faults](datasets.md#university-of-seoul-uos-multi-domain-compound-faults) | 13 | 2024 | 4.3 | official | [10.1016/j.dib.2024.110940](https://doi.org/10.1016/j.dib.2024.110940) | [W4402536317](https://openalex.org/W4402536317) |
| 43 | [Wind Turbine High-Speed Shaft Bearing](datasets.md#wind-turbine-high-speed-shaft-bearing) | 58 | 2013 | 4.1 | official | [10.36001/phmconf.2013.v5i1.2220](https://doi.org/10.36001/phmconf.2013.v5i1.2220) | [W2606377831](https://openalex.org/W2606377831) |
| 44 | [SCA Bearing Dataset](datasets.md#sca-bearing-dataset) | 15 | 2023 | 3.8 | official | [10.3390/data8070115](https://doi.org/10.3390/data8070115) | [W4382584507](https://openalex.org/W4382584507) |
| 45 | [MAFAULDA (Machinery Fault Database)](datasets.md#mafaulda-machinery-fault-database) | 36 | 2017 | 3.6 | proxy | [10.14209/sbrt.2017.133](https://doi.org/10.14209/sbrt.2017.133) | [W2976936892](https://openalex.org/W2976936892) |
| 46 | [KAIST Run-to-Failure](datasets.md#kaist-run-to-failure) | 10 | 2024 | 3.3 | official | [10.1016/j.dib.2024.110403](https://doi.org/10.1016/j.dib.2024.110403) | [W4394685279](https://openalex.org/W4394685279) |
| 47 | [University of Ferrara](datasets.md#university-of-ferrara) | 10 | 2024 | 3.3 | official | [10.1016/j.dib.2024.110620](https://doi.org/10.1016/j.dib.2024.110620) | [W4399925440](https://openalex.org/W4399925440) |
| 48 | [Harbin Institute of Technology (HIT-SM)](datasets.md#harbin-institute-of-technology-hit-sm) | 16 | 2022 | 3.2 | official | [10.1088/1361-6501/ac7941](https://doi.org/10.1088/1361-6501/ac7941) | [W4282983125](https://openalex.org/W4282983125) |
| 49 | [University of Adelaide Defect Slope Series](datasets.md#university-of-adelaide-defect-slope-series) | 22 | 2020 | 3.1 | official | [10.1177/1475921720938296](https://doi.org/10.1177/1475921720938296) | [W3048055158](https://openalex.org/W3048055158) |
| 50 | [MOIRA-UNIMORE Independent Cart System](datasets.md#moira-unimore-independent-cart-system) | 6 | 2025 | 3.0 | official | [10.3390/app15073691](https://doi.org/10.3390/app15073691) | [W4408924713](https://openalex.org/W4408924713) |
| 51 | [NOVIC+ Motor Compound Fault](datasets.md#novic-motor-compound-fault) | 6 | 2025 | 3.0 | official | [10.1016/j.ymssp.2025.113786](https://doi.org/10.1016/j.ymssp.2025.113786) | [W4414855970](https://openalex.org/W4414855970) |
| 52 | [HUST Transmission System](datasets.md#hust-transmission-system) | 6 | 2025 | 3.0 | official | [10.1016/j.eswa.2025.130962](https://doi.org/10.1016/j.eswa.2025.130962) | [W7117159164](https://openalex.org/W7117159164) |
| 53 | [Luleå Wind Turbine Drivetrain Vibration](datasets.md#luleå-wind-turbine-drivetrain-vibration) | 21 | 2020 | 3.0 | official | [10.2991/ijcis.d.201105.001](https://doi.org/10.2991/ijcis.d.201105.001) | [W2908889295](https://openalex.org/W2908889295) |
| 54 | [University of Ferrara Outer-Ring Defects](datasets.md#university-of-ferrara-outer-ring-defects) | 13 | 2022 | 2.6 | official | [10.1016/j.ymssp.2022.109783](https://doi.org/10.1016/j.ymssp.2022.109783) | [W4297510845](https://openalex.org/W4297510845) |
| 55 | [Vishwakarma Institute of Technology (VIT)](datasets.md#vishwakarma-institute-of-technology-vit) | 5 | 2025 | 2.5 | official | [10.1016/j.dib.2025.111455](https://doi.org/10.1016/j.dib.2025.111455) | [W4408394410](https://openalex.org/W4408394410) |
| 56 | [University of Arkansas (Single & Double Faults)](datasets.md#university-of-arkansas-single--double-faults) | 10 | 2023 | 2.5 | official | [10.1016/j.dib.2023.109358](https://doi.org/10.1016/j.dib.2023.109358) | [W4382929685](https://openalex.org/W4382929685) |
| 57 | [VIT Vellore SpectraQuest Ball Bearing](datasets.md#vit-vellore-spectraquest-ball-bearing) | 5 | 2025 | 2.5 | official | [10.1038/s41598-025-01780-y](https://doi.org/10.1038/s41598-025-01780-y) | [W4410726974](https://openalex.org/W4410726974) |
| 58 | [CUMTB Wind Turbine Pitch Bearing](datasets.md#cumtb-wind-turbine-pitch-bearing) | 5 | 2025 | 2.5 | official | [10.1016/j.dib.2025.111876](https://doi.org/10.1016/j.dib.2025.111876) | [W4412870979](https://openalex.org/W4412870979) |
| 59 | [German Aerospace Center (DLR)](datasets.md#german-aerospace-center-dlr) | 9 | 2023 | 2.2 | official | [10.1016/j.dib.2023.109019](https://doi.org/10.1016/j.dib.2023.109019) | [W4322621256](https://openalex.org/W4322621256) |
| 60 | [Paderborn University (Time-Varying Run-to-Failure)](datasets.md#paderborn-university-time-varying-run-to-failure) | 6 | 2024 | 2.0 | official | [10.36001/phme.2024.v8i1.4101](https://doi.org/10.36001/phme.2024.v8i1.4101) | [W4400101200](https://openalex.org/W4400101200) |
| 61 | [Army Engineering University of PLA, Mixed Bearing–Gearbox](datasets.md#army-engineering-university-of-pla-mixed-bearinggearbox) | 4 | 2025 | 2.0 | official | [10.1016/j.dib.2025.112187](https://doi.org/10.1016/j.dib.2025.112187) | [W4415328257](https://openalex.org/W4415328257) |
| 62 | [LASPI Gearbox](datasets.md#laspi-gearbox) | 7 | 2023 | 1.8 | official | [10.36001/ijphm.2023.v14i2.3497](https://doi.org/10.36001/ijphm.2023.v14i2.3497) | [W4386158069](https://openalex.org/W4386158069) |
| 63 | [NUST ICE Journal Bearing](datasets.md#nust-ice-journal-bearing) | 5 | 2024 | 1.7 | official | [10.1016/j.dib.2024.111214](https://doi.org/10.1016/j.dib.2024.111214) | [W4405131180](https://openalex.org/W4405131180) |
| 64 | [University of Adelaide Defect Length Series](datasets.md#university-of-adelaide-defect-length-series) | 13 | 2018 | 1.4 | official | [10.1177/1475921718808805](https://doi.org/10.1177/1475921718808805) | [W2898344073](https://openalex.org/W2898344073) |
| 65 | [UPM CITEF Combined Faults (2021)](datasets.md#upm-citef-combined-faults-2021) | 7 | 2021 | 1.2 | official | [10.3390/app11146452](https://doi.org/10.3390/app11146452) | [W3179780895](https://openalex.org/W3179780895) |
| 66 | [UAQ / UPC Rotating Electromechanical System](datasets.md#uaq--upc-rotating-electromechanical-system) | 1 | 2026 | 1.0 | official | [10.1038/s41597-026-07224-0](https://doi.org/10.1038/s41597-026-07224-0) | [W7154477635](https://openalex.org/W7154477635) |
| 67 | [Selçuk University Radar Bearing](datasets.md#selçuk-university-radar-bearing) | 2 | 2025 | 1.0 | official | [10.34248/bsengineering.1673237](https://doi.org/10.34248/bsengineering.1673237) | [W4412124763](https://openalex.org/W4412124763) |
| 68 | [EJUST-PdM-1 (Video)](datasets.md#ejust-pdm-1-video) | 1 | 2025 | 0.5 | official | [10.5220/0013715900003982](https://doi.org/10.5220/0013715900003982) | [W4415591971](https://openalex.org/W4415591971) |
| 69 | [Saarland University Cylindrical Roller IR Damage](datasets.md#saarland-university-cylindrical-roller-ir-damage) | 0 | 2025 | 0.0 | official | [10.3390/data10050077](https://doi.org/10.3390/data10050077) | [W4410442321](https://openalex.org/W4410442321) |
| 70 | [IFSP Bronze Plain-Bearing Bushing](datasets.md#ifsp-bronze-plain-bearing-bushing) | 0 | 2026 | 0.0 | official | [10.1109/OJIM.2026.3720860](https://doi.org/10.1109/OJIM.2026.3720860) | [W7196948392](https://openalex.org/W7196948392) |
| 71 | [GUET Multi-Condition Acoustic Ball Bearing](datasets.md#guet-multi-condition-acoustic-ball-bearing) | 0 | 2026 | 0.0 | official | [10.1016/j.dib.2026.112919](https://doi.org/10.1016/j.dib.2026.112919) | [W7163578371](https://openalex.org/W7163578371) |
| 72 | [HB-Bearing (Real Background Noise)](datasets.md#hb-bearing-real-background-noise) | 0 | 2026 | 0.0 | official | [10.1109/TASLPRO.2026.3685908](https://doi.org/10.1109/TASLPRO.2026.3685908) | [W7155512343](https://openalex.org/W7155512343) |
| 73 | [IM-VACD (Smartphone)](datasets.md#im-vacd-smartphone) | 0 | 2026 | 0.0 | official | [10.1016/j.ymssp.2026.114922](https://doi.org/10.1016/j.ymssp.2026.114922) | [W7207659323](https://openalex.org/W7207659323) |
| 74 | [KIMM PMSM Multi-Location](datasets.md#kimm-pmsm-multi-location) | 0 | 2026 | 0.0 | official | [10.1038/s41598-026-73197-0](https://doi.org/10.1038/s41598-026-73197-0) | [W7214298413](https://openalex.org/W7214298413) |
| 75 | [UPM CITEF Isolated Faults (2023)](datasets.md#upm-citef-isolated-faults-2023) | 0 | 2023 | 0.0 | official | [10.3390/math11163498](https://doi.org/10.3390/math11163498) | [W4385812855](https://openalex.org/W4385812855) |
| 76 | [UESTC Bearing Dataset](datasets.md#uestc-bearing-dataset) | 0 | 2025 | 0.0 | official | [10.1109/JSEN.2025.3635217](https://doi.org/10.1109/JSEN.2025.3635217) | [W4416707098](https://openalex.org/W4416707098) |
| 77 | [HSE Similar System](datasets.md#hse-similar-system) | 0 | 2025 | 0.0 | official | [10.1109/ACCESS.2025.3576435](https://doi.org/10.1109/ACCESS.2025.3576435) | [W4411019604](https://openalex.org/W4411019604) |

## Datasets Without a Citable Paper

These datasets have no reference paper with a citation count (no paper found, or the paper is not indexed).

| Dataset | Note |
| :--- | :--- |
| [Politecnico di Torino (ISED) Multiple Defects](datasets.md#politecnico-di-torino-ised-multiple-defects) | Reference papers describe the earlier ISED release, not this one |
| [FSTF Mechanical Laboratory](datasets.md#fstf-mechanical-laboratory) | No associated paper found |
| [HAUST-LDV](datasets.md#haust-ldv) | No associated paper found |
| [Tecnalia Bearing, Variable Conditions](datasets.md#tecnalia-bearing-variable-conditions) | No associated paper found |
| [Tecnalia Gearbox, Variable Conditions](datasets.md#tecnalia-gearbox-variable-conditions) | No associated paper found |
| [UC204 Outer Race Fault, Variable Load](datasets.md#uc204-outer-race-fault-variable-load) | No associated paper found |
| [JUST Slewing Bearing](datasets.md#just-slewing-bearing) | Reference paper not indexed in OpenAlex |
| [VibroBox Bearing Datasets](datasets.md#vibrobox-bearing-datasets) | No associated paper found |
| [VIT Vellore Taper Roller Bearing (Set 1)](datasets.md#vit-vellore-taper-roller-bearing-set-1) | No associated paper found |
| [AHU Parabolic Acoustic Mirror](datasets.md#ahu-parabolic-acoustic-mirror) | No associated paper found |
| [Wind Turbine Bearings with White Etching Cracks](datasets.md#wind-turbine-bearings-with-white-etching-cracks) | No associated paper found |
| [ESTOGU](datasets.md#estogu) | No associated paper found |
| [DLR Oscillating Needle Bearing Endurance](datasets.md#dlr-oscillating-needle-bearing-endurance) | No associated paper found |
| [Machinery Failure Prevention Technology (MFPT)](datasets.md#machinery-failure-prevention-technology-mfpt) | No associated paper found |
| [PHM09 Gearbox](datasets.md#phm09-gearbox) | No associated paper found |
| [VIT Vellore Taper Roller Bearing (Set 2)](datasets.md#vit-vellore-taper-roller-bearing-set-2) | No associated paper found |

[Back to the summary](../README.md#summary-of-datasets)
