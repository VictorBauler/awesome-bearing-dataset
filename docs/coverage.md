# Coverage of This List

This page records where datasets were searched for and which notable candidates were left out, so contributors can see what has already been checked. Last updated: 26 September 2026.

## Inclusion Standard

A dataset is listed only if it is original, publicly available experimental or field data in which bearing condition is labelled or documented (for field data, bearing failures with dates stated in the record or paper are accepted), and if every summary-table column and a short description can be filled from its repository record or paper. Mirrors, feature extractions, simulations, and code-only records are not listed.

## Sources Searched

### Repository Sweeps (September 2026)

DataCite searches by DOI prefix, with abstract-level screening:

* **Mendeley Data** (10.17632): bearing fault/vibration/diagnosis queries; "rolling element" and "rotating machinery" records without "bearing" in the title; bearing records without fault or vibration terms (degradation, lubrication, wear, acoustic, current, temperature, run-to-failure); spindle, axlebox, slewing, wheelset, and journal/plain bearing terms; non-English terms (rolamento, rodamiento, roulement, cuscinetto, rulman, Wälzlager, подшипник, 轴承, łożysko, ložisko, laakeri, rulment).
* **Zenodo** (10.5281): title queries for bearing with vibration/fault/diagnosis and with prognostics terms; bearing fault records without "bearing" in the title (motor, spindle, centrifuge, mill); acoustic, current, acoustic emission, ultrasound, and thermal terms; DCASE/MIMII.
* **figshare** (10.6084), **IEEE DataPort** (10.21227), **Science Data Bank** (10.57760), **4TU.ResearchData** (10.4121), and **Harvard Dataverse** (10.7910).

### Literature and Community Sources (September 2026)

* **Data papers:** Data in Brief, Scientific Data, MDPI *Data*, and *Measurement: Sensors*, for bearing, rolling element, rotating machinery, motor, and gearbox titles, ranked by citations; plus bearing dataset, benchmark, and test-rig papers in any venue with 30 or more citations.
* **Review papers:** six reviews and benchmarks that tabulate public datasets (arXiv 2403.13694, 2504.01373, 2312.16810, 2003.03315, 2206.14153, 2509.22267).
* **Curated lists:** [hustcxl/Rotating-machine-fault-data-set](https://github.com/hustcxl/Rotating-machine-fault-data-set), [dasolma/phmd](https://github.com/dasolma/phmd), CHAOZHAO-1/Machine-Fault-Dataset, and about 15 other GitHub dataset lists; the NASA PCoE data repository; PHM Society, PHME, and PHMAP data challenges.
* **GitHub and Kaggle:** repository searches for bearing dataset terms (about 330 repositories screened), Kaggle dataset searches (about 120 datasets screened), and web searches for lab-hosted datasets.

The searches were systematic but not exhaustive; datasets without a DOI or a public listing may have been missed.

## Notable Candidates Not Listed

Candidates that were cited in the literature or named by several sources, but did not meet the inclusion standard when checked. Status as of 26 September 2026; availability may have changed since. Authors can request a re-check through an issue.

| Candidate | Reason |
| :--- | :--- |
| Fuhrländer FL2500 wind farm SCADA ([figshare](https://doi.org/10.6084/m9.figshare.25201631)) | Bearing information consists of temperature threshold alarms; no bearing failure is documented |
| University of Macau gearbox | Available through a login-protected NAS or Baidu Netdisk; no licence stated; bearing model and defect sizes not stated |
| KAIST AC motor testbed (Data in Brief, 2025) | 6 of the 7 Mendeley parts cited in the paper returned HTTP 404; re-deposited parts are under embargo until 15 February 2027 |
| AMPERE motor dataset (UBFC) | One bearing state (electrically eroded); bearing model, position, and damage extent not stated |
| HUSTmotor multimodal | Bearing fault described as preset by the manufacturer; fault type and size not stated |
| CFD compound-fault dataset (Tsinghua) | Sampling rate, bearing type, fault generation method, and operating conditions not stated in the repository |
| IIT Roorkee run-to-failure (Mendeley mxxphphny4) | Bearing type, speed, and load not stated in the record; the paper is not open access |
| KAIST vertical motor-pump journal bearing (Mendeley x2hrn4vfrt) | Data paper not yet published; institution and units not stated |
| Roller fault signals (Mendeley 7w5cstbz3c) | Contains two roller-fault signals and no healthy recording |
| Shandong Normal University cross-speed (Zenodo 22170309) | No paper; rig, bearing, and fault method not stated |
| St Petersburg motor startup modes (Zenodo 21325944) | Record restricted, no public files |
| GPNU (IEEE DataPort) | No data files available on the record |
| QIT-Bearing, SLIET NU205E, BEED (IEEE DataPort) | QIT-Bearing: partial release, subscription required; SLIET NU205E: page returned "Access denied"; BEED: partial release |
| SUDA, SJTU, SCP pump, Donghua spinning frame, iFLYTEK challenge | No public copy of the data found |

Suggestions for datasets that are missing, or that now meet the standard, are welcome through an issue or pull request.

[Back to the summary](../README.md#summary-of-datasets)
