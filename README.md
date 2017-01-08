# Analyzing-NYC-High-School-Data-and-SAT-scores
Performing analysis on a clean dataset by making maps and visualizations.

Introduction:-

I have already explored the relationship between SAT scores and demographic factors in New York City public schools. For a brief bit of background, the SAT, or Scholastic Aptitude Test, is a test given to graduating high schoolers in the US every year. The SAT has 3 sections, each of which is worth a maximum of 800 points. The SAT is used by colleges to determine which students to admit. 
High average SAT scores are usually indicative of a good school.

New York City has published data on the SAT scores of students, along with additional demographic datasets. I have combined the following datasets into a single, clean, Pandas Dataframe:

1. SAT scores by school -- SAT scores for each high school in New York City.
2. School attendance -- attendance information on every school in NYC.
3. Class size -- class size information for each school in NYC.
4. AP test results -- Advanced Placement exam results for each high school. Passing AP exams can get you college credit in the US.
5. Graduation outcomes -- percentage of students who graduated, and other outcome information.
6. Demographics -- demographic information for each school.
7. School survey -- surveys of parents, teachers, and students at each school.

New York City has a significant immigrant population, and is very diverse, so comparing demographic factors such as race, income, and gender with SAT scores is a good way to figure out if the SAT is a fair test. If certain racial groups consistently performed better on the SAT, we would have some evidence that the SAT is unfair, for example.

Since we're interested in exploring the fairness of the SAT, finding that demographic factors like race and gender are strongly positively or negatively correlated with SAT scores would be an interesting result that merited investigation. For example, if men tended to score more highly on the SAT, it would indicate that the SAT is potentially unfair to women.

We can use the Pandas corr method to find correlations between columns in a Dataframe. The result of the method is a Dataframe where each column and row index is the name of a column in the original dataset.
