## Analytics Design to Recommend Flavors to Launch / Shell Out for Greek Yogurt Trend, Group Project

**Project description:** To briefly summarize, in this case, we are conducting analytics to provide input or recommendations to the decision of which flavors to launch next. Assume for this analysis that the private label recently launched six flavors--Blueberry, Honey, Peach, Plain, Strawberry, and Vanilla. We will be focusing on providing analytics to help determine what the next flavors to launch should be. We now having access to the data from a survey that captures information about consumers’ flavor preferences.
<img src="images/greek-style-yogurt-difference-1140x563.jpg?raw=true"/>

### 1. Understanding & Cleaning Data

After extracting and merging data using SQL, two issues were found   
```javascript       
       #1#  Representativeness of Sample
```      
“The survey was only sent to individuals that had previously purchased Greek Yogurt and were screened during the survey based on a question about purchase of Greek Yogurt. Thus, the sample is not a general sample of Wegmans customers, but instead a sample of current buyers of Greek Yogurt. “ Although this is the most relevant population for this survey, we still need to check whether the survey represents the overall population on gender, income, family size, preference for yogurt and so on, which would influence all the analysis in the following. 
```javascript
       #2#  Quality of Response
```
We re-examined the survey data and we deleted the 1.2.3.
1.respondents who took too long to finish the data (above average response time
2.respondents answered the survey not in the time we sent out the survey(some profiles may be from the pretest
3.respondents who have not finished the response(incomplete answers showing NA in the database)

### 2. Refine the Measurement Goal

```javascript
       #1#  Analytic goal 
```
Decide which flavors to launch next, include current flavors (Black Cherry, Blueberry, Honey, Lemon, Mango, Peach, Plain, Raspberry, Strawberry, and Vanilla) and new flavors (Almond, Banana, Caramel, Chai, Chocolate, Cinnamon, Coconut, Key Lime Pie, Maple, Pineapple, Pomegranate, Strawberry Banana, and Vanilla Banana)  

```javascript
       #2#  Limitation of Domain 
```
The purpose of this analysis is to understand category behaviors in the Greek Yogurt subcategory. This subcategory at the time of this survey was growing dramatically. Understanding different segments, usage situations, attribute importance, and brand perceptions is critical to determining the best approach to merchandising this growing category.	

```javascript
       #3#  Analytics Tool
```
Descriptive analysis to identify the sales of yogurt in seperate categories; 
conjoint analysis with discrete choice model to simulate market scenarios; 
predictive analysis using TURF to predict the best flavor to gain market share

```javascript
       #4#  Analytics Outcome 
```
Key metrics include market share and profitablity


### 3. R code (describe how we approach) 

```javascript
if (isAwesome){
  return true
}
```

### 4. PowerPoint

<img src="images/Screen Shot 2020-02-15 at 02.22.00.png?raw=true"/>

### 4. Provide a basis for further data collection through surveys or experiments

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
