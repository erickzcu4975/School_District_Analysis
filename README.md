#School_District_Analysis

#Overview of the school district analysis: Explain the purpose of this analysis.

Analysis on school district performance tooling on Jupyter(Python), Pandas & Numpy.

Results: Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected? 

1st % passing: 65.172326 vs 2nd % passing :64.855718 (tiny difference).

How is the school summary affected?

Top:
Schools were not affected by the update.
Mean score in subjects, and overall at THS do were affected with the new version. Variance was less than 1%.

Botton:

Just affected THS.

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

How does replacing the ninth-grade scores affect the following:

Math and reading scores by grade

Score affected in this df 9th grade students @ THS has NaN in math and reading, we can catch better the difference with value i/o Nan.

Scores by school spending

Changed < .1% 

Scores by school size

Slighly changes in Medium size schools (<1%). Thought THS was imapacted.

Scores by school type

THS/ Charter school, we do see changes in the scores for the charter's (<.1%), however no changes in the District.