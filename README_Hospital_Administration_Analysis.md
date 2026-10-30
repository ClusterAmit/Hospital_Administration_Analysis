# Hospital Administration Analysis

*Improving hospital operations and reducing 30-day patient readmissions*

## 1. Project Overview

This project analyzes **66,587 inpatient encounters from 130 hospitals**
to understand why patients return to the hospital within 30 days. It
also examines hospital stay length, bed usage, medication patterns, and
patient record quality.

The goal is to identify high-risk patients, improve discharge follow-up,
and help hospitals use beds and resources more effectively.

## 2. Business Questions

-   Which age groups have higher readmission rates?
-   Which medical specialties have the longest and shortest hospital
    stays?
-   How do previous emergency visits affect readmissions?
-   Are medication changes and diabetes medication linked with
    readmission?
-   How do medication count and number of diagnoses affect length of
    stay?
-   How complete are patient records, especially weight details?
-   Which patient and diagnosis groups have higher readmission rates?

## 3. Tools and Techniques

-   Microsoft Excel 365 for data analysis, formulas, PivotTables, and
    dashboards.
-   `COUNTIFS`, `AVERAGEIFS`, `SUMIFS`, `CORREL`, and `IFERROR` for
    calculations.
-   ICD-9 diagnosis codes grouped into nine major clinical categories.
-   Patient data grouped into useful ranges for emergency visits,
    medication count, and diagnosis count.

## 4. Challenges

-   **Missing weight data:** 96.8% of patient records had no weight
    value.
-   **Missing specialty details:** 49.08% of encounters had no specified
    medical specialty.
-   **Complex diagnosis codes:** Hundreds of ICD-9 codes were grouped
    into nine categories.
-   **Workbook performance:** The large dataset required separate data,
    calculation, and dashboard sections.

## 5. Key Findings

  Measure                                                                   Finding
  --------------------------------- -----------------------------------------------
  Patient encounters                                    66,587 across 130 hospitals
  30-day readmission rate                                  46.20% (30,764 patients)
  Average length of stay                                                  4.40 days
  Patients on diabetes medication                                            76.90%
  Patients with 9+ diagnoses                                                 48.70%
  Missing weight records                                                     96.80%
  Highest readmission group                Patients with 6+ prior ER visits: 89.01%
  Longest average stay                Physical Medicine & Rehabilitation: 8.89 days

Other findings:

-   Readmission was **48.62%** among patients whose medication was
    changed during admission, compared with **44.13%** when medication
    was unchanged.
-   Average stay increased from **2.87 days** for patients taking 1--10
    medicines to **8.68 days** for those taking 41 or more.

## 6. Recommendations

1.  Flag high-risk patients, especially those aged 70+ or with previous
    ER visits or many diagnoses.
2.  Arrange a pharmacist follow-up within 48--72 hours after discharge
    to review medicines.
3.  Provide extra discharge support and education for patients with
    diabetes.
4.  Use step-down care or rehabilitation services for stable patients
    who need longer stays.
5.  Schedule a primary care or specialist follow-up within seven days
    for high-risk patients.
6.  Make weight recording a required part of hospital admission.

## 7. Estimated Financial Impact

The project estimates that reducing annual readmissions by **15%** could
prevent about **2,130 readmissions**. At an estimated cost of **\$14,200
per readmission**, this represents potential annual cost avoidance of
**\$30.246 million**.

The estimated annual transitional care program budget is **\$2.5
million**, with a projected return above **11:1**. These figures are
model estimates and depend on achieving the reduction target.

## Conclusion

The analysis shows that previous emergency visits, older age, medication
changes, and multiple diagnoses are important indicators of readmission
risk. Better patient flagging, medication follow-up, discharge planning,
and record keeping may help reduce readmissions and improve hospital
operations.
