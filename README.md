# **Project Overview**
_______________________
# ***Exploring factors that affect students' final math grade***
## *Introduction*
In our preliminary data analysis, we will explore a student performance data set to investigate how different attributes affect students' math grades in two Portuguese secondary schools. This dataset measures attributes under binary or five-level classification methods. We will be selecting quantitative variables under the five-level classification to conduct a linear regression analysis. To predict a student’s final math grade, we will assess our data with attributes such as student absences, student health, student freetime, and students’ parents education.  
The data we are using is [Student Performance]( https://archive.ics.uci.edu/ml/datasets/student+performance) which can be found by going on the link provided.

![student performance](https://user-images.githubusercontent.com/90440745/140980802-033a00bf-2f76-46d0-b4ad-947bb7379b0d.jpeg)

## *Methods*
The project explores the strongest correlation between attributes and students’ final math grade. The end result would be a graph with the one attribute that best predicts the final math grade. The following is a list of the considered attributes and our assumption of how they would affect the final math grade:

- Absences: Higher absences would mean more missed material.
- Health: Poorer health would cause more absences and prevent efficient studying. 
- Free-time: More free-time means less study time. However, students also need breaks for their mental balance.
- Study-time: The more time a student studies would lead them to cover more material and have more practice. However, too much studying can lead to burn-out.
- Failure: If a student fails often it affects their confidence, thereby affecting exam performance.
- Travel-time: More travel time would decrease study time.
- Age: The student's mind matures and becomes more practical with age.
- Workday alcohol consumption: Alcohol consumption might negatively affect grade causing lack of focus and health issues.
- Mothers education: The mother would help with studies and her education would reflect on the students.
- Fathers education: The father would help with studies and his education would reflect on the students.


For our visualization, we have selected scatterplots with the linear regression model because we will be assessing quantitative data. We will plot a series of scatterplots with the final math grade on the y-axis and a predictor attribute on the x-axis and assess the strength in relationship between the predictor and the final math grade. We chose a linear regression model over the K-nearest neighbors model in order to assess a simple and clear linear trend in the data.

An example of a scatterplot is included below.
![Screen Shot 2021-11-09 at 3 30 36 PM](https://user-images.githubusercontent.com/90440745/141022330-af1fc840-9665-4988-938f-e2acec1f0e2b.png)


## *Expected Outcomes and Significance*
Through our analysis, we expect to find attributes with a strong correlation to the final mathematics grade and create a model where we utilize scores in these attributes to predict a students’ final mathematics grade. The impact of our findings is we can gain insight on what attributes best support and do most harm to students in achieving a high final mathematics grade. Looking into the future, our findings could lead to more research regarding the particularities of attributes that affect final mathematics grade the most.


