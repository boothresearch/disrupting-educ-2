This report was created by the Stata command iesave (version 7.3). Read more about this command and the purpose of this report on https://dimewiki.worldbank.org/iesave

- **Number of observations:** 619
- **Number of variables:** 64
- **ID variable(s):** st_id
- **.dta version used:** 14
- **Data signature:** 619:64(81093):281631850:3670860972
- **Last saved by:** User info withheld, see option userinfo in command iesave.
- **Last saved at:** 14:49:54 25 Sep 2024

## Variable type: String

| Name | Label | Type | Complete obs | Number of levels |
|---|---|---|---|---|
| cp | "Session type at Chhattarpur Mindspark center" | str11 | 313 | 1 |
| gp | "Session type at Govindpuri Mindspark center" | str11 | 313 | 1 |
| ms_center | "Mindspark center" | str2 | 313 | 3 |
| ms_center1 | "Mindspark center" | str10 | 619 | 3 |
| st_id | "Student ID" | str5 | 619 | 619 |
| tk | "Session type at Tekhand Mindspark center" | str11 | 313 | 1 |
| ts_grade1 | "Test grade" | str3 | 619 | 3 |
| ts_grade2 | "Test grade" | str3 | 539 | 2 |

## Variable type: Continuous

| Name | Label | Type | Complete obs | Mean | Std Dev | p0 | p25 | p50 | p75 | p100 |
|---|---|---|---|---|---|---|---|---|---|---|
| any_tuition1 | "Attends tuition" | byte | 619 | .7528 | .4317 | 0 | 1 | 1 | 1 | 1 |
| any_tuition2 | "Attends tuition" | byte | 533 | .8949 | .3069 | 0 | 1 | 1 | 1 | 1 |
| att_per | "Proportion of days attended" | float | 313 | .5775 | .3351 | 0 | .2791 | .7209 | .8605 | .9767 |
| att_tot | "Total attendance (days)" | byte | 618 | 25.15 | 32.21 | 0 | 0 | 0 | 62 | 84 |
| cal_att_hin_tot | "Total CAL attendance - Hindi (days)" | byte | 313 | 17.5 | 10.9 | 0 | 7 | 21 | 26 | 36 |
| cal_att_mat_tot | "Total CAL attendance - Math (days)" | byte | 313 | 22.5 | 13.85 | 0 | 12 | 26 | 34 | 48 |
| cal_att_tot | "Total CAL attendance (days)" | byte | 267 | 46.89 | 19.13 | 1 | 36 | 52 | 61 | 80 |
| d_sch_grade4 | "Grade 4" | byte | 604 | .008278 | .09068 | 0 | 0 | 0 | 0 | 1 |
| d_sch_grade5 | "Grade 5" | byte | 604 | .01656 | .1277 | 0 | 0 | 0 | 0 | 1 |
| d_sch_grade6 | "Grade 6" | byte | 604 | .2831 | .4509 | 0 | 0 | 0 | 1 | 1 |
| d_sch_grade7 | "Grade 7" | byte | 604 | .2599 | .439 | 0 | 0 | 0 | 1 | 1 |
| d_sch_grade8 | "Grade 8" | byte | 604 | .293 | .4555 | 0 | 0 | 0 | 1 | 1 |
| d_sch_grade9 | "Grade 9" | byte | 604 | .1391 | .3463 | 0 | 0 | 0 | 0 | 1 |
| h_theta_eap1 | "Baseline Hindi score" | float | 617 | -7.39e-10 | 1 | -2.576 | -.6553 | -.00744 | .6658 | 3.105 |
| h_theta_eap2 | "Endline Hindi score" | float | 537 | .2996 | 1.081 | -2.441 | -.4643 | .4218 | 1.063 | 2.998 |
| h_theta_mle1 | "Baseline Hindi score" | float | 617 | 1.98e-09 | 1 | -3.819 | -.4766 | .07559 | .6381 | 2.808 |
| h_theta_mle2 | "Endline Hindi score" | float | 537 | .2812 | 1.018 | -3.819 | -.2883 | .4007 | .9234 | 3.21 |
| m_theta_eap1 | "Baseline math score" | float | 617 | 9.63e-10 | 1 | -2.428 | -.5851 | .1152 | .6025 | 2.442 |
| m_theta_eap2 | "Endline math score" | float | 537 | .5875 | 1.147 | -2.261 | -.2961 | .578 | 1.396 | 3.702 |
| m_theta_mle1 | "Baseline math score" | float | 617 | 1.78e-09 | 1 | -3.713 | -.391 | .1481 | .5786 | 1.889 |
| m_theta_mle2 | "Endline math score" | float | 537 | .4944 | .9601 | -3.672 | -.1137 | .5344 | 1.115 | 3.149 |
| mean_attend | "Mean attendance by date" | float | 313 | .278 | 0 | .278 | .278 | .278 | .278 | .278 |
| per_hindi1 | "Hindi test, percent-correct score" | float | 619 | .4278 | .1648 | 0 | .3 | .4333 | .5333 | .9 |
| per_hindi2 | "Hindi test, percent-correct score" | float | 539 | .5522 | .1911 | 0 | .4 | .5667 | .7 | .9667 |
| per_math1 | "Math test, percent-correct score" | float | 619 | .3177 | .1115 | 0 | .2571 | .3143 | .4 | .7429 |
| per_math2 | "Math test, percent-correct score" | float | 539 | .5031 | .1726 | 0 | .3714 | .5 | .6286 | .9412 |
| present | "Student attended Mindspark session" | byte | 313 | .278 | .4487 | 0 | 0 | 0 | 1 | 1 |
| quint_hindi1 | "Baseline Hindi quintile" | byte | 617 | 2.99 | 1.415 | 1 | 2 | 3 | 4 | 5 |
| quint_math1 | "Baseline math quintile" | byte | 617 | 2.99 | 1.415 | 1 | 2 | 3 | 4 | 5 |
| ses_index | "SES index" | float | 619 | -7.49e-09 | 1.7 | -5.631 | -1.302 | .1241 | 1.389 | 4.776 |
| sgi_att_hin | "Attended: Hindi SGI" | byte | 313 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| sgi_att_hin_tot | "Total SGI attendance - Hindi (days)" | byte | 313 | 17.24 | 10.46 | 0 | 7 | 22 | 26 | 32 |
| sgi_att_mat | "Attended: Math SGI" | byte | 313 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| sgi_att_mat_tot | "Total SGI attendance - Math (days)" | byte | 313 | 15.21 | 8.9 | 0 | 9 | 18 | 22 | 30 |
| sgi_sch_hin | "Scheduled: Hindi SGI" | byte | 0 | . | . | . | . | . | . | . |
| sgi_sch_mat | "Scheduled: Math SGI" | byte | 0 | . | . | . | . | . | . | . |
| st_age1 | "Age" | byte | 461 | 12.54 | 1.538 | 6 | 11 | 13 | 14 | 17 |
| st_female1 | "Female" | byte | 619 | .7593 | .4279 | 0 | 1 | 1 | 1 | 1 |
| st_grade1 | "Grade" | byte | 604 | 7.23 | 1.106 | 4 | 6 | 7 | 8 | 9 |
| st_tui_hindi1 | "Attends Hindi extra tuition" | byte | 619 | .3683 | .4827 | 0 | 0 | 0 | 1 | 1 |
| st_tui_hindi2 | "Attends Hindi extra tuition" | byte | 533 | .1726 | .3783 | 0 | 0 | 0 | 0 | 1 |
| st_tui_math1 | "Attends Math extra tuition" | byte | 619 | .4653 | .4992 | 0 | 0 | 0 | 1 | 1 |
| st_tui_math2 | "Attends Math extra tuition" | byte | 533 | .3377 | .4734 | 0 | 0 | 0 | 1 | 1 |
| st_tui_other1 | "Attends extra tuition in other subjects" | byte | 619 | .3958 | .4894 | 0 | 0 | 0 | 1 | 1 |
| st_tui_other2 | "Attends extra tuition in other subjects" | byte | 533 | .5084 | .5004 | 0 | 0 | 1 | 1 | 1 |
| strata | "Randomization stratum" | byte | 619 | 11.24 | 5.568 | 1 | 5 | 13 | 16 | 19 |
| terc_hindi1 | "Baseline Hindi tercile" | byte | 617 | 1.995 | .8168 | 1 | 1 | 2 | 3 | 3 |
| terc_math1 | "Baseline math tercile" | byte | 617 | 1.992 | .8168 | 1 | 1 | 2 | 3 | 3 |
| tot_hindi1 | "Hindi test, total raw score" | byte | 619 | 12.84 | 4.945 | 0 | 9 | 13 | 16 | 27 |
| tot_hindi2 | "Hindi test, total raw score" | byte | 539 | 16.57 | 5.733 | 0 | 12 | 17 | 21 | 29 |
| tot_math1 | "Math test, total raw score" | byte | 619 | 11.12 | 3.904 | 0 | 9 | 11 | 14 | 26 |
| tot_math2 | "Math test, total raw score" | byte | 539 | 17.32 | 5.965 | 0 | 13 | 17 | 22 | 32 |
| treat | "Treatment" | byte | 619 | .5073 | .5004 | 0 | 0 | 1 | 1 | 1 |

## Variable type: Date or date-time

| Name | Label | Format | Complete obs | Unique values | Mean | Std Dev | Min | Median | Max |
|---|---|---|---|---|---|---|---|---|---|
| date | "Date of Mindspark session" | %tdnn/dd/CCYY | 313 | 1 | 10/17/2015 | 0 | 10/17/2015 | 10/17/2015 | 10/17/2015 |

## Variable type: Categorical

| Name | Label | Value label | Complete obs | Number of levels | Number of unlabeled levels | Top count |
|---|---|---|---|---|---|---|
| st_tui_math_hrs1 | "Hours of extra math tuition per week" | q29 | 281 | 5 | 0 | 1-2 hours:106 More than 4 hours:81 Less than 1 hour:56 2-3 hours:24 3-4 hours:14 |
| st_tui_math_hrs2 | "Hours of extra math tuition per week" | q29 | 176 | 5 | 0 | 1-2 hours:76 More than 4 hours:44 Less than 1 hour:26 2-3 hours:18 3-4 hours:12 |

