<<<<<<< HEAD
#Agramith - Loaded terms parser, Fact checker
	- Works by parsing news articles and checking for loaded term, then applying a score for said article. That score will then be shown to the reader, allowing the reader to make an informed decsion into validility of the information and the author. 
	- Journalists will have to be verified inorder to post articles on the site.
	- Free to read initally.
	- readers will be able to read the parsed article or both to see the difference. 
	- Aim of the project is to eradicate fake news.
	- Will be 100% unbasis and 100% fact based.
	- Hopefully be connect with large databases to fact check articles.
	- Will have to train AI to detect areas of an orticle to fact check.

## To Do's
	- figure out funding for emploies.
	- make a plan on potential for usefullness.   
	- make a large enough dataset to test the AI
	- make a plan for funding and possible expensies.
	Deadline - June 30th 2021.

## Possible Approach
	- First Identify for loaded terms, terms that can be persuasive (possible highlight for the reader).
	- parse the entire document and look for sentences that end in a question make. 
	- verify that it is in fact a article.
	- highlight the corrections, but do not change the text.
## What does Argramith offer to the reader
Agramith offers news articles from large news organizations which are then parsed and fact checked by AI to ensure that the reader is able to make the most informed desision on the news. this isjust the 
the beginning as I would like this project to expand into a multi country news organization. Plans are the we will launch with a mobile app, then bringing in journalist and building the brand. Goal of the  project is to bring trust back into news. We will try to never show any basis and when bais is identified, it is quickly dealt with.




### Notes From The Article
- one of the main issues in detecting fake news is making sure that the article used to verify claims is revelant to the claim
- what every algorithim used to detect fake news, must locate the claim, find a crediatable article to fact check from and then inform readers about the fact checked claim


### Logistic Regression
	- Is  a Machine Learning Classification algorithim that is used to preictthe probability of a categorical dependent variable. The Dependant variable is a binary variable that contains data codded as a 1(yes, success) or 0 (no, failure). In other words, the logistic regression model predicts P(Y=1) as a function ox X. 


	- For a binary regression, the factor level 1 of the dependent variable should represent the the desired outcome.

## How to build 
- First I will need to parse the article
	- using the newspaper3 api to find articles and pick the important information from them.
	- will have to build a logistic regression expression to further identify and then parse the news articles.


## Step 2
	- Make a script that updates and looks for new article every 10 mins.
		- Make sure that it fetches all the data.
		- I believe that a very important step is to check for Euphemism's and Dysphemism's. These are often used instead of using extremely harsh words.

## step 3 
	- Using an algorthim to filter through all the article, looking for similarities in all the articles. 


### Factd.io
- This will be the actual name of the App.
	- the app will be powered by Agramith.
=======
#Agramith - Loaded terms parser, Fact checker
	- Works by parsing news articles and checking for loaded term, then applying a score for said article. That score will then be shown to the reader, allowing the reader to make an informed decsion into validility of the information and the author. 
	- Journalists will have to be verified inorder to post articles on the site.
	- Free to read initally.
	- readers will be able to read the parsed article or both to see the difference. 
	- Aim of the project is to eradicate fake news.
	- Will be 100% unbasis and 100% fact based.
	- Hopefully be connect with large databases to fact check articles.
	- Will have to train AI to detect areas of an orticle to fact check.

## To Do's
	- figure out funding for emploies.
	- make a plan on potential for usefullness.   
	- make a large enough dataset to test the AI
	- make a plan for funding and possible expensies.
	Deadline - June 30th 2021.

## Possible Approach
	- First Identify for loaded terms, terms that can be persuasive (possible highlight for the reader).
	- parse the entire document and look for sentences that end in a question make. 
	- verify that it is in fact a article.
	- highlight the corrections, but do not change the text.
## What does Argramith offer to the reader
Agramith offers news articles from large news organizations which are then parsed and fact checked by AI to ensure that the reader is able to make the most informed desision on the news. this isjust the 
the beginning as I would like this project to expand into a multi country news organization. Plans are the we will launch with a mobile app, then bringing in journalist and building the brand. Goal of the  project is to bring trust back into news. We will try to never show any basis and when bais is identified, it is quickly dealt with.




### Notes From The Article
- one of the main issues in detecting fake news is making sure that the article used to verify claims is revelant to the claim
- what every algorithim used to detect fake news, must locate the claim, find a crediatable article to fact check from and then inform readers about the fact checked claim


### Logistic Regression
	- Is  a Machine Learning Classification algorithim that is used to preictthe probability of a categorical dependent variable. The Dependant variable is a binary variable that contains data codded as a 1(yes, success) or 0 (no, failure). In other words, the logistic regression model predicts P(Y=1) as a function ox X. 


	- For a binary regression, the factor level 1 of the dependent variable should represent the the desired outcome.

## What needs to be built?
	- build or find an algorithim that can fetch data and check for;
		- extrenal links in articles
		- checks news sites to see if there are new articles being published.
	- use this article for guidence: https://scholar.smu.edu/cgi/viewcontent.cgi?article=1036&context=datasciencereview;
	- build an server that can hold all the data.
	- write a script that updates the information on the app and in the website. app will likely be built with xarmin.

>>>>>>> 289a854f6beff596cd81ba19c96aae7d0810f8a6
