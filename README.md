# Africa-FMG-Map

Queried data from the [UNICEF Data Warehouse](https://data.unicef.org/dv_index/), [specifically](https://data.unicef.org/resources/data_explorer/unicef_f/?ag=UNICEF&df=GLOBAL_DATAFLOW&ver=1.0&dq=.PT_F_15-49_FGM..&startPeriod=2016&endPeriod=2023&lastnobservations=1) the latest data recorded for the indicator "Percentage of girls and women (aged 15-49 years) who have undergone female genital mutilation (FGM)" in African countries. Used Pandas/GeoPandas, Altair and RegEx to develop a mp where prevalence of indicator in a specific country is denoted by yellow monochromatic gradient shade (e.g., lower % = lighter shade, etc.)

Text labels are included for FMG countries. Tooltip for FMG countries contains FMG indicator prevalence and year reported, as well as country population and the [UNICEF indicator for child marriage](https://data.unicef.org/resources/data_explorer/unicef_f/?ag=UNICEF&df=GLOBAL_DATAFLOW&ver=1.0&dq=.PT_F_20-24_MRD_U15..&startPeriod=2016&endPeriod=2023&lastnobservations=1), specifically the latest data for women aged 20 to 24 who were married before age 15. Note: child marriage data reflects the latest statistics for each country and may not align with the reported year for FMG data that's included in the tooltip (see label: "Year Reported").

Tooltip for countries without record of FMG prevalence shows country name only.
