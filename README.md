Download Link: https://assignmentchef.com/product/solved-aglm-assignment-n-o-1
<br>
Applied Generalized Linear models




<ol>

 <li>Amati</li>

</ol>

<h1></h1>




<h2>Task 1                                                                                                         3 points</h2>

A multiple linear regression model has been estimated to study the relationship between <em>Y </em>= violent crime rate (per 100,000 people), <em>X</em><sub>1 </sub>= poverty rate (percentage with income below the poverty line) and <em>X</em><sub>2 </sub>= percentage living in urban area. Data are collected in 51 cities in the U.S.

The table below reports the output.

<table width="362">

 <tbody>

  <tr>

   <td width="85"></td>

   <td width="158">                Est.            s.e.</td>

   <td width="62">t-value</td>

   <td width="57">p-value</td>

  </tr>

  <tr>

   <td width="85">SSTSSRegSSR</td>

   <td width="158">1841257.15</td>

   <td width="62"></td>

   <td width="57"></td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Fill in the missing information.</li>

</ul>

(Please report the formula and computation).

<ul>

 <li>Interpret the coefficient of determination <em>R</em><sup>2</sup>.</li>

 <li>Compute and interpret the overall F-test.</li>

</ul>

<strong>5 points</strong>

The table below shows the scores of the first test (maximum score 10 points) in a beginning German course. Students in the course are grouped as follows:

<ul>

 <li>Group A:</li>

</ul>

Never studied foreign language before, but have good English skills

<ul>

 <li>Group B:</li>

</ul>

Never studied foreign language before, have poor English skills

<ul>

 <li>Group C:</li>

</ul>

Studied other foreign language

<table width="228">

 <tbody>

  <tr>

   <td width="84">Group A</td>

   <td width="76">Group B</td>

   <td width="68">Group C</td>

  </tr>

  <tr>

   <td width="84">4</td>

   <td width="76">1</td>

   <td width="68">9</td>

  </tr>

  <tr>

   <td width="84">6</td>

   <td width="76">5</td>

   <td width="68">10</td>

  </tr>

  <tr>

   <td width="84">8</td>

   <td width="76"></td>

   <td width="68">5</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Use an adequate method to compare the mean scores of the groups. Specify the assumptions, hypotheses, test statistics and p-values.</li>

 <li>Suppose that the first observation in the second group was actually 9, not 1. Then, the standard deviations are the same, but the sample means are 6, 7 and 8, rather than 6, 3 and 8. Do you think that the F-test statistic would be larger, the same or smaller? Explain your reasoning without doing any computation.</li>

 <li>Suppose you have the same means as these data, but the sample standard deviations were 1.0, 1.8 and 1.6, instead of the actual 2.0, 2.8 and 2.6. Do you think that the F-test statistic would be larger, the same or smaller? Explain your reasoning without doing any computation.</li>

 <li>Suppose you have the same means and standard deviations as these data, but the sample size were 30, 20 and 30, instead of 3, 2 and 3. Do you think that the F-test statistic would be larger, the same or smaller? Explain your reasoning without doing any computation.</li>

 <li>In (1), (2), (3) and (4), would the p-values of the F-tests be larger, the same or smaller? Why?</li>

</ul>

<strong>4 points</strong>

The compressive strength of concrete is being studied, and four different mixing techniques are being investigated. The following data have been collected. For each mixing technique, 4 compressive strength measurements (in pounds per square inch) have been recorded.

<table width="252">

 <tbody>

  <tr>

   <td width="72"></td>

   <td colspan="4" width="181">Compressive strength</td>

  </tr>

  <tr>

   <td width="72">Mixing</td>

   <td width="47">1</td>

   <td width="47">2</td>

   <td width="47">3</td>

   <td width="39">4</td>

  </tr>

  <tr>

   <td width="72">1</td>

   <td width="47">3129</td>

   <td width="47">3000</td>

   <td width="47">2865</td>

   <td width="39">2890</td>

  </tr>

  <tr>

   <td width="72">2</td>

   <td width="47">3200</td>

   <td width="47">3300</td>

   <td width="47">2975</td>

   <td width="39">3150</td>

  </tr>

  <tr>

   <td width="72">3</td>

   <td width="47">2800</td>

   <td width="47">2900</td>

   <td width="47">2985</td>

   <td width="39">3050</td>

  </tr>

  <tr>

   <td width="72">4</td>

   <td width="47">2600</td>

   <td width="47">2700</td>

   <td width="47">2600</td>

   <td width="39">2765</td>

  </tr>

 </tbody>

</table>

Does the technique affect the compressive strength?

To answer this question draw comparative box plots and perform an analysis of variance using R.

<strong>8 points</strong>

Consider the data set munich.csv. The data set contains information on the rent prices of apartments in Munich. The variables in the data set are:

<ul>

 <li><em>rent</em>: net rent per month (in Euro)</li>

 <li><em>area</em>: living area in square meters</li>

 <li><em>yearc</em>: year of construction</li>

 <li><em>location</em>: quality of location according to an expert assessment</li>

</ul>

(0 = average location, 1 = good location, 2 = top location)

<ul>

 <li>Read the data into R and tell R that location is a categorical variable.</li>

 <li>Discuss whether a linear regression model would be adequate to investigate the relationship between <em>rent</em>, <em>area</em>, <em>yearc </em>and <em>location</em>.</li>

 <li>Estimate the model</li>

</ul>

<em>Y </em>= <em>β</em>0+<em>β</em>1<em>X</em><em>area</em>+<em>β</em>2<em>X</em><em>loc</em>:<em>good</em>+<em>β</em>3<em>X</em><em>loc</em>:<em>top</em>+<em>β</em>4<em>X</em><em>loc</em>:<em>good</em><em>X</em><em>area</em>+<em>β</em>5<em>X</em><em>loc</em>:<em>top</em><em>X</em><em>area</em>+<em>β</em>6<em>X</em><em>yearc .</em>

<ul>

 <li>Run and comment on the model diagnostics. Hint: use the Rcode mod <em>&lt;</em>– lm(rent ∼ location+area+area:location+yearc, data=munich)</li>

 <li>Interpret the model results.</li>

 <li>Compare the fit of the model in (3) with the model including only the variable <em>area</em>.</li>

</ul>

Please submit your solutions using moodle.

The solutions should also include the R script.

Only one person has to submit the solutions for each group.

Please do not forget to specify the name of all the members of the group.