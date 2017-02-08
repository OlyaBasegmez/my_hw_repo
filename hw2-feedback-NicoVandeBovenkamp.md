### ***Project 2 Feedback***

***Nico Van de Bovenkamp***
***

**Overall** Good work! Your answers are right on track, and you are making good use of Pandas and Seaborn here.

**Some Notes**

Really quick note, you only have to 'import' a package once. So, once you do all those imports at the top, you can just do also include
`import seaborn as sns` and it will be ready for you to use throughout the notebook.

* **Q.9** Even though the distributions do exhibit some skew, they are still approximately normally distributed. Think about how you could apply some statistical tests to find out. For **Q.10** you actually wouldn't really need any 'correction' because it is close enough to normal. An example where we did need a correction can be seen in [Lecture 06](https://github.com/ga-students/DAT-NYC-1.17/blob/master/classes/lesson-06/code/solution-code-6.ipynb).
* **Q.13** This is definitely the information that we would need to carry out the analysis plan. Though, think of our 'Analysis Plan' as the steps we would take in order to get to the point where we would build the model. That means:
    * Finding missing values to drop or [handle in another way](http://chrisalbon.com/python/pandas_missing_data.html)
    * Analyze the distributions
    * Ensure there is no multi-collinearity
    * Make Dummy Variables
    * And then build/test a model of your choosing!
