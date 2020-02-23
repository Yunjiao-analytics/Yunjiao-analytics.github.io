## Analytics Design to Recommend Flavors New Product Line, Group Project

**CASE BACKGROUND:**  

>EarlyRiders, our client, had a recent management change and realized that their product set was underperforming. They currently offer two products and one in particular was not doing well. The management team decided after much deliberation to revitalize their product portfolio based on the opinions of potential end-users. 


For this purpose, we ran a conjoint analysis based on 200 individuals, these individuals are made up of parents of 2-4 year old kids who planned to purchase a toy horse. And we were in charge of analyzing the data and creating a presentation to give to the management team of EarlyRiders. 	

[Click here to see the whole PowerPoint](/pdf/ToyHorsePPT_Team8.pdf)
<img src="images/Toyhorse.png?raw=true"/>

### Analytics Design

Decision: Which product line based on long term profitability

Decision Criteria:
* Expect profit (Completely New or Adjust Current) v.s. Current product line (Expected)
* Clustering Output (Segmentations)
* Market share simulation
* Scenario, Possibility of Product Line, Influenced by clustering

      
### Attributes 
    
* From Survey: Gender, Age
* From Products: Size, Motion, Style, Price

### Priori Segment by “Age” 

>  summary (lm(ratings~price*age+size*age+motion*age+style*age, data=prioridf))   

<img src="images/Toyhorse1.png?raw=true"/> 

### Priori Segment by “Gender”

>  summary (lm(ratings~price*gender+size*gender+motion*gender+style*gender,data=prioridf))
<img src="images/Toyhorse2.png?raw=true"/>

### Post Hoc: Cluster Modeling

3 segments supported by average silhouette
Total within sum of square--visual intuition

<img src="images/Toyhosre3.png?raw=true"/>

### 4. R Code

[Click here to see the code that describes how we approach](/Yogurt-Project-Team8.html)




<img src="images/Screen Shot 2020-02-15 at 02.22.00.png?raw=true"/>

### 5. Case Take-away

Our survey limited us because among the existing flavors, we already reached 98% of the population even when only considering "Regular Buyers" & "Not Occasional buyers". This problem sometimes happens when retailors want to do the survey about a new product in its already reached customers before the new product being produced. In this case, the customers who buy the yogurt in Wegmans would only have the buy-action if they like the flavors, if not, they would not come to Wegmans and would not buy the Greek yogurt.

Then, if not on reach, to find out the best flavor to launch, we think about the approaches based on market acceptance and competitive landscape, here are the 2 ways that lead us to the final recommendations(our analytics results):

> A: Try to influence switchers from regular yogurt (limit cannibalization)

Things to considered: Which flavor ranks the top in the regular yogurt category that excluding the flavors we already launched? Who is our competitor? How many brand already launch the flavor? 


> B: Try to influence switchers / Interest from direct Greek yogurt competitors

Things to considered: Which flavor ranks the top in the Greek yogurt category that we haven't introduce in our private brand? Who are our competitor? How many brand already launch the flavor? 

<img src="images/yogurtimage2.jpg?raw=true"/>
For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
