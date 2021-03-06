# A/B TESTING A LANDING PAGE

A/B tesing is a statistics concept that is very useful in Data Science/Marketing Data science.
It is a way to compare two versions of a single variable and determine whether a subject (or similar subjects) respond differently to one of the versions.

An example is comparing a website's landing page with a twerked version, as demontrated in this [example](https://github.com/KevinLolochum/A-B-Testing/blob/main/A_B_testing_a_landing_page.ipynb) using this cleaned [data](https://github.com/KevinLolochum/A-B-Testing/blob/main/abtest.csv).

# MAIN CONCEPTS

The main concepts in A/B testing are.
1. Control group - The group that is shown the original version of the variable(website).
2. Treatment group - The group that is shown the twerked version(new) of the variable(website).
                   - This group should have the same characteristics as the control group.
3. Testing inclusion criteria - This is a test to ensure that there is no bias when assigning a subject(participant) to the
                                treatment and control group i.e assignment is random.
                              - It is done using the chi-squared test.
                              - The null hypothesis is "assignment to verison is independent of treatment status".
                              
4. Two sample t-test - A test used to test the statistical significance of the twerk (change) assuming step three is good.
5. P_Value - The probability of observing results as extreme as seen given that the null is correct (i.e if the the null was correct, what is the probability we will see this results). Low P_value reject the null. High P_value, fail to reject the null.

# RESOURCES
1. Good [article](https://www.datasciencecentral.com/profiles/blogs/a-b-testing-in-one-picture) for real life business use cases.
2. The [book](https://www.oreilly.com/library/view/ab-testing-the/9781118536094/) about A/B testing.
