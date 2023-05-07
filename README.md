Download Link: https://assignmentchef.com/product/solved-msds6371-unit-4-systematic-age-discrimination
<br>



<ol>

 <li>In the United States, it is illegal to discriminate against people based on various attributes. One example is age.  An active lawsuit, filed August 30, 2011, in the Los Angeles District Office is a case against the American Samoa Government for systematic age discrimination by preferentially firing older workers. Though the data and details are currently sealed, suppose that a random sample of the ages of fired and not fired people in the American Samoa Government are listed below:</li>

</ol>

<strong>Fired</strong>

34 37 37 38 41 42 43 44 44 45 45 45 46 48 49 53 53 54 54 55 56

<strong>Not fired</strong>

27 33 36 37 38 38 39 42 42 43 43 44 44 44 45 45 45 45 46 46 47 47 48 48 49 49 51 51 52 54

<ol>

 <li>Check the assumptions (with SAS) of the two-sample t-test with respect to this data. Address each assumption individually as we did in the videos and live session and make sure and copy and paste the histograms, q-q plots or any other graphic you use (boxplots, etc.) to defend your written explanation.  Do you feel that the t-test is appropriate?</li>

 <li>Check the assumptions with R and compare them with the plots from SAS.</li>

 <li>Now perform a complete analysis of the data. You may use either the permutation test from HW 1 or the t-test from HW 2 (copy and paste) depending on your answer to part a.  In your analysis, be sure and cover all the steps of a complete analysis:</li>

 <li>State the problem.</li>

 <li>Address the assumptions of t-test (from part a).</li>

 <li>Perform the t-test if it is appropriate and a permutation test if it is not (judging from your analysis of the assumptions).</li>

 <li>Provide a conclusion including the p-value and a confidence interval.</li>

 <li>Provide the scope of inference.</li>

</ol>




(Steps 3-5 are from your previous HW; you are just putting everything together.)

NOTE: THIS QUESTION SHOULD BE EASY AS YOU ARE SIMPLY FORMATTING YOUR RESULTS FROM EARLIER IN THE ABOVE FORM. (Steps 3-5 are from your previous HW; you are just putting everything together.) IT REALLY JUST EQUATES TO ADDING A STATEMENT OF THE PROBLEM AND ADDRESSING THE ASSUMPTIONS (1 and 2 above). You can basically copy and paste the rest.  We are simply putting everything together to make a complete report.




Note: Perhaps you might be wondering at this point in the HW, “Why are we always testing the assumptions of the t-test? Is it the best test?  Should we always run the t-test when we can?”  These are very good questions and open questions that are up for debate!  The one thing that is mathematically proven and not up for debate is that if the assumptions are met, the two-sample t test is the most powerful (in terms of Power = 1 – beta) test in the universe at testing the claim of the difference of means.  Two questions may arise here … 1.  Do we ever really have the assumptions fully met in the real world and just how much power do we give up at varying degrees of violation of the assumptions?  2. Do we always want inference on the equality/difference of means?  We will continue to answer these questions in Unit 4. Also note that we started to answer number two with a t-test of log transformed data.  The inference there is on the equality (ratio) of medians which may be a better measure of center when dealing with right or left skewed data!)

<ol start="2">

 <li>In the last homework, it was mentioned that a Business Stats class here at SMU was polled and students were asked how much money (cash) they had in their pockets at that very moment. The idea was to see if there was evidence that those in charge of the vending machines should include the expensive bill / coin acceptor or if they should just have the credit card reader.  However, a professor from Seattle University polled her class with the same question.  Below are the results of the polls.</li>

</ol>

<strong>SMU</strong>

34, 1200, 23, 50, 60, 50, 0, 0, 30, 89, 0, 300, 400, 20, 10, 0

<strong>Seattle U</strong>

20, 10, 5, 0, 30, 50, 0, 100, 110, 0, 40, 10, 3, 0

<ol>

 <li>Check the assumptions <strong>(with SAS or R)</strong> of the two-sample t-test with respect to this data. Address each assumption individually as we did in the videos and live session and make sure to copy and paste the histograms, q-q plots, or any other graphic you use (boxplots, etc.) to defend your written explanation.  Do you feel that the t-test is appropriate?</li>

 <li>Now perform a complete analysis of the data. You may use either the permutation test from HW 1 or the t-test from HW 2 (copy and paste) depending on your answer to part a.  In your analysis, be sure to cover all the steps of a complete analysis.</li>

 <li>State the problem.</li>

 <li>Address the assumptions of the t-test (from part a)</li>

 <li>Perform the t-test if it is appropriate and a permutation test if it is not (judging from your analysis of the assumptions).</li>

 <li>Provide a conclusion, including the p-value and a confidence interval.</li>

 <li>Provide the scope of inference.</li>

</ol>

NOTE: AGAIN, THIS QUESTION SHOULD BE EASY, AS YOU ARE SIMPLY FORMATTING YOUR RESULTS FROM EARLIER IN THE ABOVE FORM.  IT REALLY JUST EQUATES TO ADDING A STATEMENT OF THE PROBLEM AND ADDRESSING THE ASSUMPTIONS (1 or 2 above.) Steps 3-5 are from your previous HW; you are just putting everything together. You can basically copy and paste the rest.  We are simply putting everything together to make a complete report.

<ol start="3">

 <li>Note the potential outlier in the SMU data set. Re-check the assumptions in SAS or R without the outlier. Does this change your decision about the appropriateness of the t-tools?  Compare the p-value from the t-test with and without the outlier. Based on your analysis so far, what should we do with this outlier?  Consult the outlier flowchart in Section 3.4.</li>

</ol>

<ol start="3">

 <li>Find the “Education Data” data in the course materials. This data set includes annual incomes in 2005 of the subset of National Longitudinal Survey of youth (NLSY79) subjects who had paying jobs in 2005 and who had completed either 12 or 16 years of education by the time of their interview in 2006. All the subjects in this sample were between 41 and 49 years of age in 2006.  Test the claim that the distribution of incomes for those with 16 years of education exceeds the distribution for those with 12 years of education.  (Hint: pay careful attention to the ratio between the largest and smallest incomes in each group … also …. is the bigger mean associated with the bigger standard deviation? … Transformation?) <strong><em>You may use SAS or R for this problem but be sure and include your code!</em></strong></li>

</ol>

<em>Note: There is some SAS code in the course materials to help you download the data into SAS. It is a very large dataset… “datalines” is not a good idea here! You could also use the File/Import option.</em>

Finally, make sure you present your findings as you would to a client:

<ol>

 <li>State the Problem.</li>

 <li>Address the Assumptions (graphically and using words).</li>

 <li>Perform the Most Appropriate (Powerful) Test. (In reality, this may be a pooled t-test on the original data, a t-test on the log transformed data, or a permutation test on the original data, since these are the ones we have studied so far. For now, assume you must choose between the pooled t-test on the original data or on the log transformed data.)</li>

 <li>Provide a conclusion including a p-value and a confidence interval.</li>

 <li>Provide a scope of inference.</li>

</ol>

Bonus (5 pts): Create two q-q plots (by hand) for the original data in Chapter 3, question 20 of the text book.  A q-q plot for the In-State and a q-q plot for the Out-Of-State data.  Show all work by filling in a table like the one below (one for In-State and one for Out-of-State):

<table>

 <tbody>

  <tr>

   <td width="102">Original Data</td>

   <td width="132">Percentage for percentiles given number of values</td>

   <td width="102">Z-score of original data</td>

   <td width="222">Z-score percentiles assuming normal distribution given the values in column 2.</td>

  </tr>

  <tr>

   <td width="102"> </td>

   <td width="132"> </td>

   <td width="102"> </td>

   <td width="222"> </td>

  </tr>

  <tr>

   <td width="102"> </td>

   <td width="132"> </td>

   <td width="102"> </td>

   <td width="222"> </td>

  </tr>

  <tr>

   <td width="102"> </td>

   <td width="132"> </td>

   <td width="102"> </td>

   <td width="222"> </td>

  </tr>

  <tr>

   <td width="102"> </td>

   <td width="132"> </td>

   <td width="102"> </td>

   <td width="222"> </td>

  </tr>

 </tbody>

</table>




Check your q-q plots by comparing them with the ones from proc ttest. (Run proc ttest but just for the q-q plots. You do not need to run a full hypothesis test.) What would you conclude about the normality of the distributions these data came from?


