## Analytics Design to Recommend Flavors to Launch / Shell Out for Greek Yogurt Trend, Group Project

**Project description:** In this case, we conducted analytics to provide input or recommendations to the decision of which flavors to launch next for Wegmans private label Greek yogurt. Assume for this analysis that the private label recently launched six flavors--Blueberry, Honey, Peach, Plain, Strawberry, and Vanilla. We will be focusing on providing analytics to help determine what the next flavors to launch should be. We now having access to the data from a survey that captures information about 200 consumers’ flavor preferences, historical sales data and demographic infomation of the consumers who belong to Wegmans membership card system.
<img src="images/greek-style-yogurt-difference-1140x563.jpg?raw=true"/>

### 1. Understanding & Cleaning Data

After extracting and merging data using SQL, two issues were found that needed to be settled before we begin digging deep into the survey data.

```javascript       
 #1#  Representativeness of Sample
```      
“The survey was only sent to individuals that had previously purchased Greek Yogurt and were screened during the survey based on a question about purchase of Greek Yogurt. Thus, the sample is not a general sample of Wegmans customers, but instead a sample of current buyers of Greek Yogurt. “ Although this is the most relevant population for this survey, we still need to check whether the survey represents the overall population on gender, income, family size, preference for yogurt and so on, which would influence all the analysis in the following. 

```
 #2#  Quality of Response
```
We re-examined the survey data and we deleted the 1.2.3.
1.respondents who took too long to finish the data (above average response time
2.respondents answered the survey not in the time we sent out the survey(some profiles may be from the pretest
3.respondents who have not finished the response(incomplete answers showing NA in the database)

### 2. Refine the Measurement Goal

```
 #1#  Analytic goal 
```
Decide which flavors to launch next, include current flavors (Black Cherry, Blueberry, Honey, Lemon, Mango, Peach, Plain, Raspberry, Strawberry, and Vanilla) and new flavors (Almond, Banana, Caramel, Chai, Chocolate, Cinnamon, Coconut, Key Lime Pie, Maple, Pineapple, Pomegranate, Strawberry Banana, and Vanilla Banana)  

```
 #2#  Limitation of Domain 
```
The purpose of this analysis is to understand category behaviors in the Greek Yogurt subcategory. This subcategory at the time of this survey was growing dramatically. Understanding different segments, usage situations, attribute importance, and brand perceptions is critical to determining the best approach to merchandising this growing category.	

```
 #3#  Analytics Tool
```
Descriptive analysis to identify the sales of yogurt in seperate categories; 
conjoint analysis with discrete choice model to simulate market scenarios; 
predictive analysis using TURF to predict the best flavor to gain market share

```
 #4#  Analytics Outcome 
```
Key metrics include market share and profitablity


### 3. R code (describe how we approach) 

```
<em>(/Yogurt-Project-Team8.html)</em>
```

### 4. PowerPoint
This is not a great PowerPoint to show our whole approach, because in this case we were asked to limited the PowerPoint in 5 pages to illustrate the ideas(exclude the name page & the last page of appendix). We skipped some part of our analysis and only retained the most relevant part of the whole analyzing process. Our final recommendations are 'raspberry' and 'strawberry'.  Here-->[Link for Detail](/pptyogurt.pdf)
<img src="images/Screen Shot 2020-02-15 at 02.22.00.png?raw=true"/>

### 5. Case Take-away
Our survey limited us because among the existing flavors, we already reached 98% of the population even when only considering Regular Buyers & Not Occasional buyers. This is a common problem that happens when retailors want to do the survey about a new product in its already reached customers before the new product being produced. In this case, the customers who buy the yogurt in Wegmans would only have the buy-action if they like the flavors, if not, they would not come to Wegmans and would not buy the Greek yogurt.

Then, if not on reach, to find out the best flavor to launch, we think about the approaches based on market acceptance and competitive landscape, here are the 2 ways that lead us to the final recommendations(our analytics results):

A: Try to influence switchers from regular yogurt (limit cannibalization)
Things to considered: Which flavor ranks the top in the regular yogurt category that excluding the flavors we already launched? Who is our competitor? How many brand already launch the flavor? 


B: Try to influence switchers / Interest from direct Greek yogurt competitors
Things to considered: Which flavor ranks the top in the Greek yogurt category that we haven't introduce in our private brand? Who are our competitor? How many brand already launch the flavor? 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
