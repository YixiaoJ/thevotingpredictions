# the Voting Predictions

<li>project of the analytics edge

**Description of the Project**

What predicts voting outcomes? In this competition, you'll be using data from Show of Hands, an informal polling platform for use on mobile devices and the web, to see what aspects and characteristics of people's lives predict how they will be voting for the presidential election.

Show of Hands has been downloaded over 300,000 times across Apple and Android app stores, and users have cast more than 75 million votes. In this problem, we'll use data from thousands of users and one hundred different questions to see which responses predict voting outcomes.
 

**data descriptions**

<li>train2016.csv - the training set of data that you should use to build your models
<li>test2016.csv - the test set that you will be evaluated on. It contains all of the independent variables, but not the dependent variable.
<li>sampleSubmission2016.csv - a sample submission file in the correct format.
<li>Questions.pdf - the question test corresponding to each of the question codes, as well as the possible answers.

**Data Fields**
<li>*USER_ID* - an anonymous id unique to a given user
<li>*YOB* - the year of birth of the user
<li>*Gender* - the gender of the user, either Male or Female
<li>*Income* - the household income of the user. Either not provided, or one of "under $25,000", "$25,001 - $50,000", "$50,000 - $74,999", "$75,000 - $100,000", "$100,001 - $150,000", or "over $150,000".
<li>*HouseholdStatus* - the household status of the user. Either not provided, or one of "Domestic Partners (no kids)", "Domestic Partners (w/kids)", "Married (no kids)", "Married (w/kids)", "Single (no kids)", or "Single (w/kids)".
<li>*EducationalLevel* - the education level of the user. Either not provided, or one of "Current K-12", "High School Diploma", "Current Undergraduate", "Associate's Degree", "Bachelor's Degree", "Master's Degree", or "Doctoral Degree".
<li>*Party* - the political party for whom the user intends to vote for. Either "Democrat" or "Republican
<li>*Q124742, Q124122, . . . , Q96024* - 101 different questions that the users were asked on Show of Hands. If the user didn't answer the question, there is a blank. For information about the question text and possible answers, see the file Questions.pdf.
