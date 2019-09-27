#  Feature Engineering in Data Science



One of the most important steps in learning data science is to master the art of feature engineering. In the world of Data Science, it is like a backbone of every machine learning model. It sounds like a very fancy word and I am sure you have encountered this term many times in case you have worked on data science problems. In this post, I am going to address the core meaning of feature engineering and also covering the concept behind it.

Let's start with the pictures below:

<img src="images/config.PNG" width="180" height="200" align="left"/><img src="img/engineer.JPG" width="180" height="200" align="middle"/><img src="img/prof.JPG" width="180" height = 200 align="middle"/>





What is the `profession` of the persons in the picture? Are they Doctor, Engineer or professor? It is evident that the gentlemen in the pictures are Doctor, Engineer and professor respectively.  **Just think about what made you answer the question**. I am able to see the `stethoscope` in first pic, `helmet` in second pic and some `mathematical formulas` in the last one.  These are the key information present in the pictures that helped me in making my decision.  There are also other information present in the pictures such as mood of the individuals, gender, type of clothes, colour of the clothes etc.  All this information contribute to the attributes of the picture and the process of finding the right attribute to make the decision is termed as feature engineering. This process is based on our past knowledge. In this case, since I have seen how doctor, engineer and professor look like therefore I am able to isolate the right attribute to solve my problem.  Other attributes are not relevant for me in answering the question.

In more technical terms, **Feature engineering**  is the process of using `domain knowledge` of the data to create `features` that make `machine learning` algorithms work .

<img src="img/feature1.jpg" width="600" height="150" align="middle"/>

Now,it is the time to see the application of feature engineering in one of the data science problems. Let's say in the **UBC Master of Data Science cohort of 2019-2020**, I need to `predict` the probability if a student will `pass or fail` in the program.  The features of the student that I will look upon are :

- Student's grade in courses attended so far and for this problem I am considering the grades of the following three subjects:
  - Probability and Statistics
  - Computing platform for Data Science
  - Programming for Data Science
- Average Daily study Hours
- No. of holidays taken
- Background information (For eg, Finance, statistics, engineering)
- Distance of the home from University
- Average number of hours taken to complete the assignments
- Gender

These features are sufficient for my machine learning model to work. Now let's consider three students from the previous year cohort of 2018-2019 for which I am aware of the value of the features defined above and information about whether these students passed or failed.



​                     **Alex**								         	**Feature**																	**Value**

​		- Probability and Statistics										:		C <img src="img/student1.jpg" width="200" height="270" align="left"/>

​		-  Computing platform for Data Science				:		C

​		-  Programming for Data Science							:		D			

​		-  Average Daily Study Hours						  	 	 	:		2	 	

​		-  No. of holidays taken											:		 6

​		-  Background information							   			:	Arts

​		-  Distance of the home from University				:		3 km				

​		-  Average no. of hrs to complete assignments	:		6

​														-  Gender																	 :		Male





​					**Jess**								         	**Feature**																		**Value**

​		- Probability and Statistics										:		A <img src="img/student2.jpg" width="200" height="270" align="left"/>

​		-  Computing platform for Data Science				:		B

​		-  Programming for Data Science							:		B			

​		-  Average Daily Study Hours						  	 		:		4

​		-  No. of holidays taken											 :		 2

​		-  Background information							   		 	:		Finance

​		-  Distance of the home from University				:		3 km				

​		-  Average no. of hrs to complete assignments	:		5

​														-  Gender																	 :		Female



​					**John**								         	**Feature**																	**Value**

​		- Probability and Statistics										:		B <img src="img/student3.jpg" width="200" height="270" align="left"/>

​		-  Computing platform for Data Science				:		A

​		-  Programming for Data Science							:		B			

​		-  Average Daily Study Hours						  	 		:		4.5

​		-  No. of holidays taken											:		 3

​		-  Background information							   			:	Statistics

​		-  Distance of the home from University				:		7 km				

​		-  Average no. of hrs to complete assignments	:		5

​														-  Gender																	 :		Male





The information regarding their passing the program last year is known to me which is as.

​																**Alex 	: 		Fail**

​																**Jess      :     Pass**

​																**John     :     Pass**



Some of the observations:

-  The **grades in the individual courses** of the students are affecting significantly the final result. **Jess** and **John** have comparatively better grades than **Alex** and both of them passed.
- Attributes such as **gender and distance of the home from University** are less relevant features since their values have no implications on the final result of the students. **Jess** lives near the University and  **John** lives far from University and still both of them passed. 

Finally, I need to pluck out the important features based on my observations. The grades in the courses are the most important feature for my model. The change in the values of grades is determining the student result at the end of the program. In addition, I can use average daily study hours in my model as well. **These features will be then used to predict pass or fail for students in cohort 2019-2020 while developing my model.**  *You can also think of other feature from the list of mentioned features that are also relevant.*

<u>The relationship between the feature and the final decision is an important aspect of feature engineering. The features are very relevant if they talk to the final decision well and less relevant when they have no impact on the final decision. Feature engineering plays an important role in improving the performance of any machine learning model.</u>



References:-

- https://myblue.bluecrossma.com/health-plan/well-connection

- https://money.usnews.com/careers/best-jobs/civil-engineer

- https://en.wikipedia.org/wiki/Feature_engineering

- https://www.analyticsvidhya.com/blog/2018/08/guide-automated-feature-engineering-featuretools-python/
- [https://www.pinterest.ca](https://www.pinterest.ca/)
