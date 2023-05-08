Download Link: https://assignmentchef.com/product/solved-stat210-410-assessment1-animal-wren
<br>
<h1>Question 1</h1>

In each assignment you will be able to earn up to 5 marks based on your engagement on the moodle Discussion forums from the topics associated with the given assignment. See the Assignment assessment criteria document for more details.

<h1>Question 2</h1>

The Maximum Life Expectancy (MLE) of different animals is thought to be correlated to a variety of biological and physiological factors including those contained in the <em>Animals </em>data-set.

<table width="436">

 <tbody>

  <tr>

   <td width="101">Variable</td>

   <td width="334">Description</td>

  </tr>

  <tr>

   <td width="101">species</td>

   <td width="334">Species of animal</td>

  </tr>

  <tr>

   <td width="101">non_dreaming</td>

   <td width="334">Slow wave sleep (hrs/day)</td>

  </tr>

  <tr>

   <td width="101">dreaming</td>

   <td width="334">Paradoxical sleep (hrs/day)</td>

  </tr>

  <tr>

   <td width="101">MLE</td>

   <td width="334">Maximum life span (years)</td>

  </tr>

  <tr>

   <td width="101">gestation</td>

   <td width="334">gestation time (days)</td>

  </tr>

  <tr>

   <td width="101">predation</td>

   <td width="334">Relative risk of being preyed upon (Low, Med, and High)</td>

  </tr>

  <tr>

   <td width="101">exposure</td>

   <td width="334">Protection during sleep (Low, High)</td>

  </tr>

  <tr>

   <td width="101">log_body</td>

   <td width="334">Log body weight (in kg)</td>

  </tr>

  <tr>

   <td width="101">log_brain</td>

   <td width="334">Log brain weight (in g)</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Use a combination of figures and summary statistics to explore the <em>Animals </em>data-set. Make sure you declare any factors and use only complete records. You should:

  <ul>

   <li>visualise and quantify relationships between numerical variables,</li>

   <li>examine the relationship between the response variable and any categorical variables, and</li>

   <li>provide a general summary of your exploratory analysis.</li>

  </ul></li>

 <li>Fit a multiple regression model to predict the MLE of a given animal. Use all variables in the data-set with the exception of the ID variable, species. Provide a summary of your model, interpretation of output, and commentary on model assumptions.</li>

 <li>Is multicollinearity a problem for the model fitted in (b)? If so, take appropriate steps to address this issue, and present an updated model. Again, include a summary of your model, interpretation of output, and commentary on model assumptions.</li>

 <li>Use the model in (c) to provide insight into the following questions:</li>

</ul>

<ol>

 <li>How does relative predation risk affect MLE?</li>

 <li>What effect does length of gestation have on MLE?</li>

</ol>

<h1>Question 3</h1>

A study on wrens was conducted both prior to and after a severe drought event. Physical characteristics (listed below) of all birds were measured along with a report of whether each bird survived the drought or not.

<table width="422">

 <tbody>

  <tr>

   <td width="64">Variable</td>

   <td width="358">Description</td>

  </tr>

  <tr>

   <td width="64">survive</td>

   <td width="358">Whether the bird survived the drought (“1”) or did not (“0”)</td>

  </tr>

  <tr>

   <td width="64">length</td>

   <td width="358">Body length (mm)</td>

  </tr>

  <tr>

   <td width="64">alar</td>

   <td width="358">Maximum wingspan (mm)</td>

  </tr>

  <tr>

   <td width="64">weight</td>

   <td width="358">Body weight (g)</td>

  </tr>

  <tr>

   <td width="64">lbh</td>

   <td width="358">Lenght of beak and head (mm)</td>

  </tr>

  <tr>

   <td width="64">lhum</td>

   <td width="358">Length of humerous (mm)</td>

  </tr>

  <tr>

   <td width="64">lfem</td>

   <td width="358">Length of femur (mm)</td>

  </tr>

  <tr>

   <td width="64">ltibio</td>

   <td width="358">Length of tibiotarsus (mm)</td>

  </tr>

  <tr>

   <td width="64">wskull</td>

   <td width="358">Width of skull (mm)</td>

  </tr>

  <tr>

   <td width="64">lkeel</td>

   <td width="358">Length of keel of sternum</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Use a combination of figures and summary statistics to explore the <em>Wren </em>data-set. Make sure you declare any factors and use only complete records. You should:

  <ul>

   <li>visualise and quantify relationships between numerical variables,</li>

   <li>examine the relationship between the response variable and the predictor variables, and</li>

   <li>provide a general summary of your exploratory analysis.</li>

  </ul></li>

 <li>Split the <em>Wren </em>data-set into 70:30 training:testing data-sets. <em>Note: </em>There are a wide variety of methods to undertake this task. You are welcome to use any method you would like as long as it is clearly documented in your R Script and you use the last three numbers of your Student ID number as the set.seed value so that the results can be replicated.</li>

 <li>Use all variables in the <em>Wren </em>data-set to fit a logistic regression model to predict Survival. Summarise the steps of your analysis including any testing of assumptions, clearly report and provide commentary on your results, and estimate the training and testing prediction accuracy of your model.</li>

 <li>Use all variables in the <em>Wren </em>data-set to fit a KNN model to predict Survival. Use a range of values for <em>k </em>in order to present an optimised value of <em>k</em>. Summarise the steps of your analysis including any testing of assumptions, clearly report and provide commentary on your results, and estimate the training and testing prediction accuracy of your model.</li>

 <li>Compare and contrast the two different statistical analyses you conducted in (c) and (d). Which approach do you think is the best choice for this research question?</li>

</ul>