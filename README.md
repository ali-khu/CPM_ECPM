# CPM_ECPM
Implementations for CPM and ECPM for Building Models

<img width="2850" height="5604" alt="enhanced_phase_1_readability" src="https://github.com/user-attachments/assets/de90429e-6848-402b-8867-8b6945441ff5" />

<img width="4710" height="6066" alt="enhanced_phase_2_flowchart" src="https://github.com/user-attachments/assets/48139eee-e8f2-4f29-9c0a-d76e1290932b" />

KCL Final Results - Evaluation Summary
1. Case Scenarios
1)	Kepco Original Results
2)	Kea Original Results
3)	Kepco 2 var Multiplicative Results
4)	Kea 2 var Multiplicative Results
5)	Kepco 31 models Cooling
6)	Kepco 31 models Heating
7)	Kea 31 models Cooling
8)	Kea 31 models Heating
9)	Individual Original Group 2 Add., Multiplicative
10)	Individual Original Group 3 Add., Multiplicative
11)	Individual Original Group 4 Add., Multiplicative
12)	Individual Original Group 5 Add., Multiplicative
13)	Individual Original Group 6 Add., Multiplicative
14)	Group 2 31 models Cooling
15)	Group 3 31 models Cooling
16)	Group 4 31 models Cooling
17)	Group 5 31 models Cooling
18)	Group 6 31 models Cooling
19)	Group 2 31 models Heating
20)	Group 3 31 models Heating
21)	Group 4 31 models Heating
22)	Group 5 31 models Heating
23)	Group 6 31 models Heating
24)	Group 2 multiplicative 2 var
25)	Group 3 multiplicative 2 var
26)	Group 4 multiplicative 2 var
27)	Group 5 multiplicative 2 var
28)	Group 6 multiplicative 2 var 
2. Detailed Results
Group 2 multiplicative 2 variables
•	C2, H1, H2 all pass
Group 3 multiplicative 2 variables
•	Some C1 cases, H1 and H2 all pass (C1 passes for "all_years")
Group 4 multiplicative 2 variables
•	C1 Fails for all
•	C2 Fails for only one year and C2 "all_years" passes
•	H1, H2 all pass
Group 5 multiplicative 2 variables
•	C1 Fails for all
•	C2, H1, H2 all pass
Group 6 multiplicative 2 variables
•	C1 Fails for all
•	C2, H1, H2 all pass
Group 2 31 models heating
•	10, 13, 14, 16, 19, 20, 22, 23, 25, 26, 27, 29, 30, 31 pass for all years
Group 3 31 models heating
•	8, 9, 10, 11, 13, 14, 15, 16, 17, 19, 20, 21, 22, 23, 24, 25, 26, 27, 29, 30, 31 pass
Group 4 31 models heating
•	10, 13, 14, 16, 19, 20, 22, 23, 25, 26, 27, 29, 30, 31 pass for all years
Group 5 31 models heating
•	8, 10, 11, 13, 14, 15, 16, 17, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31 pass
Group 6 31 models heating
•	8, 10, 11, 13, 14, 15, 16, 17, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31 pass
Group 2 31 models cooling
•	8, 9, 10, 11, 13, 14, 15, 16, 17, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31 pass for all years
Group 3 31 models cooling
•	8, 9, 10, 11, 13, 14, 15, 16, 17, 19, 20, 21, 22, 23, 24, 25, 26, 27, 29, 30, 31 pass for all years
Group 4 31 models cooling
•	9, 10, 13, 14, 15, 16, 19, 20, 22, 23, 25, 26, 27, 29, 30, 31 pass for all years
Group 5 31 models cooling
•	8, 9, 10, 11, 13, 14, 15, 16, 17, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31 pass for all years
Group 6 31 models cooling
•	8, 9, 10, 11, 13, 14, 15, 16, 17, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31 pass for all years
Group 2 Original H/C
•	Multiplicative model passes for all-years and metrics
•	Improved by changing cooling set point from 25 -> 18
•	Addi model fails for cooling; passes for heating
Group 3 Original H/C
•	Addi passes for cooling, heating
Group 4 Original H/C
•	Multiplicative model passes for all-years and metrics
•	Increased by changing cooling set point from 25 -> 18
•	Add. model fails for cooling; passes for heating
Group 5 Original H/C
•	Add. passes (for cooling, heating)
Group 6 Original H/C
•	Add. model passes for heating for all-years and for cooling only passes for all-years weekday.
Kepco 2 var Multiplicativeplicative Results H/C
•	H1 passes for all-years, all years
•	C2 passes for some cases, and passes only for 2022 weekend
•	C1 Fails for all years
•	H2 Fails for all years
Kea 2 variables Multiplicativeplicative H/C
•	C1 all cases fail
•	H1, H2 passes for all-years weekday (passes for 2022, 2024 weekday)
•	H2 passes only for 2023 weekend
•	C2 passes only for 2023, 2024 weekdays
Kea 31 models Heating (*Check weekday/weekend)
•	8, 10, 11, 13, 14, 15, 16, 17, 19, 20, 22, 23, 25, 26, 27, 29, 30, 31 pass
Kea 31 models Cooling
•	8, 9, 10, 11, 14, 15, 19, 20, 21, 22, 23, 24, 25, 27, 29, 30, 31 pass
Kepco 31 models Heating
•	8, 10, 11, 14, 15, 19, 22, 25 pass all years
Kepco 31 models Cooling
•	8, 9, 10, 11, 13, 14, 15, 19, 22, 25 pass for all years
