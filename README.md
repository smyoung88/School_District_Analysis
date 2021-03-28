# School_District_Analysis

## Overview
Analysis on 15 High Schools was compiled for a school board to provide a succinct summary on various metrics for those schools. Upon review of the analysis, the school board gave notification that evidence of academic dishonesty was detected for Thomas High School's ninth grade reading and math scores which appeared to have been altered. Because of this, the board asked that Thomas High School's math and reading scores be nullified (replaced with NaNs) until the full extent of academic dishonesty had been vetted and new analysis be ran on the updated dataset to see what kind of impact this has on the different metrics.

## Results
### How is the district summary affected?
The affect of the new dataset on the district summary without Thomas High School's ninth grade math and reading scores is summarized in the following images:

<p align="center">
  <b>Affect on District Summary</b>
 <br>
</p>
<b>District Summary Original</b><br>
<img src="https://github.com/smyoung88/School_District_Analysis/blob/main/Resources/district_summary_original.png" title="District Summary Original">
<b>District Summary New</b><br>
<img src="https://github.com/smyoung88/School_District_Analysis/blob/main/Resources/district_summary_new.png" title="District Summary New">


### How is the school summary affected?
The affect of the new dataset on the school summary without Thomas High School's ninth grade math and reading scores is summarized in the following images:
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The affect on performance of replacing the ninth graders' math and reading scores at Thomas High School is summarized in the following images:

### How does replacing the ninth-grade scores affect the following:
**1) Math and Reading Scores by Grade**
The only affect identified from replacing the ninth grade scores on math and reading scores was on Thomas High School where previous ninth grade scores are now displayed as "nan". All other scores from THS and other school remained the same as previous. 
**2) Scores by School Spending**
Since only 461 students out of the total student count of 39,170 were impacted (1.18%), the overall story of Scores by School Spending from the original dataset to the dataset with replaced ninth-grade scores did not change.
**3) Scores by School Size**
Since only 461 students out of the total student count of 39,170 were impacted (1.18%), the overall story of Scores by School Size from the original dataset to the dataset with replaced ninth-grade scores did not change.
**4) Scores by School Type**
Since only 461 students out of the total student count of 39,170 were impacted (1.18%), the overall story of Scores by School Type from the original dataset to the dataset with replaced ninth-grade scores did not change.

## Summary
In summary, the four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School were replaced with NaNs all were specific to Thomas High School itself.
   
