## School_District_Analysis

# Overview

The purpose of this project was to use the data available to investigate the presence of academic dishonesty
relating to test score and their reporting. This analysis included fifteen schools and over 39 thousand students.
The data included reading and math test scores for students in grades 9-12. Student-specific data included ID
number, name, gender, grade, school, reading score, and math score.

# Results

- Effects on district summary:
  Replacing the Thomas HS 9th grade scores had very small effect on the district summary. The change in the
  averages was so small there was no change in the data after rounding. 
  District summary before removal:
  ![Dist_Summary_Before_Removal](https://user-images.githubusercontent.com/91306342/139627305-396fa02b-9d70-4985-9d29-e28b61962b00.JPG)
  District summary after removal:
  ![Dist_Summary_After_Removal](https://user-images.githubusercontent.com/91306342/139627372-104733d9-9d70-48e9-bbac-68d0c84467f3.JPG)

- Effects on school summary:
  The effects of replacing the 9th grade data had a much more significant effect on the school summary.
  The % overall Passing drops from 90.95 to 65.08. This is a very strong indication of academic dishonesty
  because it is highly unlikely 9th graders would preform better than the rest of the student body to an
  extent that would pull that percentage up so significantly, shown below.
  Top 5 schools by % Overall Passing, before removal:
  ![School_stats_before_removal](https://user-images.githubusercontent.com/91306342/139628717-5ed5835b-7c11-45cd-87ee-2dee8984df45.JPG)
  notice Thomas HS is 2nd in the district
  Bottom 10 schools by % Overall Passing:
  ![School_stats_after_removal](https://user-images.githubusercontent.com/91306342/139629417-9f1bde12-92c1-4c10-be1b-deacb8a09380.JPG)
  Notice Thomas HS slips to 8th overall, and last among charter schools after the 9th grade data is replaced.

- Replacing ninth-grade math and reading scores effect on school performance relative to other schools
  As mentioned above, in addition to the Overall passing % slipping from 91 to 65, the school's rank slips to 8th.
  Even more significantly, while compared to other charter schools, it slips from 2nd to last. Thomas HS ends up
  just over 14% lower than the second lowest charter school, which is Holden HS at 89.23% overall passing
  
  Replacing ninth-grade scores effect on:
- Math and reading scores by grade
  Replacing ninth-grade scores had little to no effect on AVERAGE scores by grade but a large effect on PASSING RATES
  because it the average scores of other grades are similar to the 9th graders at Thomas HS (more on this in summary below)
  
- Scores by school spending
  the 9th grade data replacement had little to no effect on scores when taking school spending in to account

- Scores by school size
  Large schools (2000-5000 students) performed, on average, 4% worse in math and almost 3% worse in reading than
  medium and small schools, whose performances were very similar to each other. However, the data replacement did
  not have a different effect on scores by school size.
  ![Scores_by_school_size](https://user-images.githubusercontent.com/91306342/139631915-518ae4a2-16b9-4da0-988b-23c7b4db3f43.JPG)

- Scores by school type
  Charter schools performed better than district schools in all metrics. Even after the adjustment of the 9th
  grade data plunged Thomas High's stats it still outpreformed most district schools. More info will need to
  be gathered on the effect on scores by school type because the data replacement didn't have a substantial
  effect on the reported reading score, indicating any tampering with low scores was "counter-balanced" so the
  average wouldn't be affected.
  ![Scores_by_school_type](https://user-images.githubusercontent.com/91306342/139632048-b6539d3f-7cce-4085-b299-19a2ff452721.JPG)

# Summary
The alarming observations relating to the data replacement were the following:
-The major change on overall passing % from 91 to 65 at Thomas HS
-93% math passing rate slipping to 66.9%
-97% reading passing rate slipping to 69.66%
-The math and reading average scores were unchanged
  These scores being unchanged despite the plummet in passing percentage indicate a skew in the data- There is likely 
  a drop-off at or around the failing threshold where scores were bumped up above 70. This would likely be counteracted
  by bumping down scores where it would not cause student to cross the failure threshold
  (so the net effect on the average is zero)

