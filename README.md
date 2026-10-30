# Aviation Accident Analysis

## Project overview

This project analyzes aviation accident records from 1983 onward for professionally built airplanes. It compares fatal/serious injury fractions among reported occupants and the fraction of recorded accidents in which the aircraft was destroyed. The analysis separates small and large events using the reported occupant count, with 20 occupants as the threshold.

## Key findings

- **Small plane types:** The Diamond Aircraft DA 20 C1 had the lowest mean fatal/serious injury fraction among the displayed types with at least 10 usable records: 0.000 across 11 records.
- **Large plane types:** The Boeing 777 had the lowest displayed mean fraction: 0.001 across 31 usable records. These sample sizes are modest, so the results are preliminary comparisons.
- **Destruction by make:** Among small makes with at least 50 records of known damage, Grumman Acft Eng Cor-Schweizer had a 0.017 destruction fraction across 58 records; Luscombe and Stinson each had about 0.018 across 112 records. Among large makes, Boeing was 0.084 across 238 records and Airbus was 0.160 across 50.
- **Weather:** IMC records had a mean fatal/serious injury fraction of 0.636 (905 records) and destruction fraction of 0.371 (999 records). VMC records had corresponding fractions of 0.271 (14,304) and 0.077 (16,723).
- **Number of engines:** One-engine records had injury and destruction fractions of 0.301 (13,279) and 0.081 (15,603). Two-engine records had fractions of 0.282 (2,461) and 0.171 (2,455). Four-engine records had fractions of 0.160 (56) and 0.136 (66); this group is small.

## Interpretation and limitations

These are comparisons among recorded accident events, not estimates of accident or injury risk per flight. The injury fractions use reported occupants, which may include crew as well as passengers. Small/large groups are based on occupants reported for each event, not aircraft seating capacity. Missing injury and damage reports, differences between aircraft and operations, and small group sizes limit the conclusions. The results show associations and do not establish causes.

## Files

- [Cleaning notebook](Aviation_Accidents_Cleaning.ipynb)
- [Analysis notebook and visualizations](Aviation_Accidents_Data_Analysis.ipynb)
- [Cleaned dataset](data/AviationData_cleaned.csv)
