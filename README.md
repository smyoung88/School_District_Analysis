# School_District_Analysis

## Overview
Analysis on 15 High Schools was compiled for a school board to provide a succinct summary on various metrics for those schools. Upon review of the analysis, the school board gave notification that evidence of academic dishonesty was detected for Thomas High School's ninth-grade reading and math scores which appeared to have been altered. Because of this, the board asked that Thomas High School's math and reading scores be nullified (replaced with NaNs) until the full extent of academic dishonesty had been vetted and new analysis be ran on the updated dataset to see what kind of impact this has on the different metrics.

## Results
### How is the district summary affected?
The affect of the new dataset on the district summary without Thomas High School's ninth grade math and reading scores is summarized in the following images:

<p align="center">
<b>Affect on District Summary</b>
<br>
</p>
<b>District Original Summary</b>
<br><br>
<img src="https://github.com/smyoung88/School_District_Analysis/blob/main/Resources/district_summary_original.png" title="District Summary Original">
<b>District New Summary</b>
<br><br>
<img src="https://github.com/smyoung88/School_District_Analysis/blob/main/Resources/district_summary_new.png" title="District Summary New">

The overall district summary itself was not heavily impacted. Although the total students still reflect all students including Thomas High School's ninth-graders, the statistics shown are calculated based on the total student body without them. The average math score decrease by .1, the % passing math decreased by .2%, the % passing reading decreased by .3%, and the overall passing % decreased by .1%. Impacts may be more significant after finalized grades are correctly for THS ninth graders.


### How is the school summary affected?
The affect of the new dataset on the school summary without Thomas High School's ninth grade math and reading scores is summarized in the following images:

<p align="center">
<b>Affect on School Summary</b>
<br>
</p>
<b>School Original Summary</b>
<br><br>
<img src="https://github.com/smyoung88/School_District_Analysis/blob/main/Resources/school_summary_header.png">
<img src="https://github.com/smyoung88/School_District_Analysis/blob/main/Resources/school_summary_original.png" title="School Summary Original">
<b>School New Summary</b>
<br><br>
<img src="https://github.com/smyoung88/School_District_Analysis/blob/main/Resources/school_summary_header.png">
<img src="https://github.com/smyoung88/School_District_Analysis/blob/main/Resources/school_summary_new.png" title="School Summary New">

The overall school summary itself was not heavily impacted. Since only data from THS was altered, effects were only seen on THS in the school summaries. Although the total students at Thomas High School still reflect all students including the ninth graders, the statistics shown are calculated based on the total student body without them (1174 total). The average math scores decrease by .1, the average reading scores increased by .05, the % passing math decreased by .08%, the % passing reading decreased by .29%, and the overall passing % decreased by .32%. Impacts may be more significant after finalized grades are correctly for THS ninth graders.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The affect on performance of replacing the ninth graders' math and reading scores at Thomas High School is summarized in the following images:

<p align="center">
<b>Affect Thomas High School's Performance Relative to Other Schools</b>
<br>
</p>
<b>THS Original Performance</b>
<br><br>
<img src="https://github.com/smyoung88/School_District_Analysis/blob/main/Resources/THS_performance_original.png" title="THS Performance Original">
<b>THS New Performance</b>
<br><br>
<img src="https://github.com/smyoung88/School_District_Analysis/blob/main/Resources/THS_performance_new.png" title="THS Performance New">

As seen in the images, the rank of Thomas High School relative to the Overall Passing % did not change. Excluding THS ninth-grade scores did not have a significant impact on the overall story.

### How does replacing the ninth-grade scores affect the following:
**1) Math and Reading Scores by Grade**
The only effect identified from replacing the ninth-grade scores on math and reading scores was on Thomas High School where previous ninth-grade scores are now displayed as "nan". All other scores from THS and other schools remained the same as previous. 
<br>
<br>
**2) Scores by School Spending**
Since only 461 students out of the total student count of 39,170 were impacted (1.18%), the overall story of Scores by School Spending from the original dataset to the dataset with replaced ninth-grade scores did not change. Scores on school spending would only be impacted in the $630-$644 range which is where Thomas High School's per-student budget lies. Major score differences from THS ninth-grade class will be reflected in this bucket if there are any when updated.
<br>
<br>
**3) Scores by School Size**
Since only 461 students out of the total student count of 39,170 were impacted (1.18%), the overall story of Scores by School Size from the original dataset to the dataset with replaced ninth-grade scores did not change. Scores on school size would only be impacted in the Medium (1000-2000) student range which is where Thomas High School lands with 1635 students. Major score differences from THS ninth-grade class will be reflected in this bucket if there are any when updated.
<br>
<br>
**4) Scores by School Type**
Since only 461 students out of the total student count of 39,170 were impacted (1.18%), the overall story of Scores by School Type from the original dataset to the dataset with replaced ninth-grade scores did not change. Scores in the "Charter" school type would be the only data impacted as Thomas High School is a charter school. Major score differences from THS ninth-grade class will be reflected in this school type only if there are any when updated.

## Summary
In summary, the four notable changes in the updated school district analysis, although minimal, after reading and math scores for the ninth grade at Thomas High School were replaced with NaNs were all specific to Thomas High School statistics itself. Those changes were the impact on the average math score and the respective passing math %, the average reading score and the respective passing reading %, the overall passing % within the school, and the total impact of the overall rank on passing % relative to the other schools. Once the final corrected math and reading scores are updated, depending on how close those scores fall to the original data set, the aforementioned categories will see the biggest impact out of the others. Also, depending on the severity of difference in scores, a significant impact might be seen on scores by school spending, school size, and school type that were currently not impacted by the new dataset.
   
