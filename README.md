# University-Statistics-For-AI
📄 Theory 📄  my study notes whilst undertaking my stats class *"Statistics required for AI & Machine learning"*

*This MD was styled and edited in [StackEdit.io](https://stackedit.io/app#)*



## INDEX

 1. Introduction 
 2. Descriptive Statistics 1
 3. Descriptive Statistics 2
 4. Probability
 5. Conditional Probability
 6. Discrete probability distribution
 7. Continuous probability distribution
 8. Statistical inference
 9. Hypothese test
 10. Ch-squared test
 11. ANOVA
 12. Simple regression
 13. Multiple regression
 14. Presentation of 6 distributions
 15. presentation Slides



<br>

<br>


*Introduction*
## Descriptive Statistics 1

![DESCRIPTIVE STATISTICS](https://user-images.githubusercontent.com/51651537/149661997-f6de27d0-dfa7-4be9-a868-0aa933322280.png)

*Source: https://www.selecthub.com/business-intelligence/statistical-software/* 


**Descriptive Statistics** 
Descriptive statistics involves describing, summarizing and organizing the data, so it can be easily understood 
Graphical display are often used along with the Quantitative measures to enable clarity of communication 
- Used to describe, organise and summarise information about an entire data set 
- So that it can be easily understood
- Graphical display are often used along with the Quantitative measures to clearly communication findings
- I.e 5% defect product production rate


<br>


## Inferential statistics

- Used to generalise about a data set based on a sample of data
- I.e 5% defect product production rate of 30 projects —> 5% defect product production rate



![Mean, Median, Mode   Range](https://user-images.githubusercontent.com/51651537/149662009-af990c8a-6a55-4d9d-8511-8a7494bc7ae4.png)

*Source: https://www.tes.com/teaching-resource/mean-median-mode-and-range-posters-12024923* 

<br>

*Mean, Median, and Mode (distribution curve)*
![SYMMETRIC](https://user-images.githubusercontent.com/51651537/149662025-702bc043-ba2a-4240-9122-c4a5ac5d5e72.png)

*Source: https://www.tes.com/teaching-resource/mean-median-mode-and-range-posters-12024923* 

<br>

*Variance, and Standard Deviation* 

![En1(x;-x)2](https://user-images.githubusercontent.com/51651537/149662027-7ff7037d-e980-414e-955d-4c71f41c12b8.png)

*Source: https://byjus.com/maths/variance-and-standard-deviation/* 


<br>

**Variance**
- σ2 sigma squared is the symbol for variance
- mathematical terms frequently used in statistics and probability theory
- Variance refers to the spread of a data set around its mean value
- AKA the more clumped the data, the less variance there is in the values of the dataset. Where as a high variance will have numbers spread across the board. 
- “If you pick a number, what are the chances its around the mean?”


**Standard Deviation**
- Any data set that represents a Bell curve/normal distribution can be very useful. Because now Standard deviation applies to this dataset, we can extract cool information from it
- σ - greek sigma
- measures the spread of the data about the mean value (average)
- It is useful in comparing sets of data which may have the same mean but a different range
- For example, 
    - the mean of the following two is the same: 
     - 15, 15, 15, 14, 16 	(avg 62)
      - 2, 7, 14, 22, 30. 	(avg 62)
      - However, the second is clearly more spread out. 
    - low standard deviation = the values are not spread out and clumped around the mean
    - high standard deviation = the values are spread out and the curve is ‘flatter’
    - How do the values deviate from the standard mean

![99 72](https://user-images.githubusercontent.com/51651537/149662031-31b5e605-be12-47ce-826e-f294a2059567.jpg)


<br>

**Sum Notation - ∑ [ˈsɪɡmə]**

![For writing a sum in a short form, one often uses Greek letter E](https://user-images.githubusercontent.com/51651537/149662034-de712cfd-00e4-41e8-a564-e0ba00c13c54.png)

<br>

**Covariance**
- covariance is a measure of the relationship between two random variables. 
- The metric evaluates how much – to what extent – the variables change together.
- Covariance values are not standardised
- E.G: COVID cases increase - available hospital beds decrease — Increase in daily exercise - decrease in weight
- Measures how 2 data sets Correlate	
- 1 = as one grows, the other also grows as much
- -1 = as one grows, the other shrinks as much
    - Covariance is when two variables vary with each other, whereas 
    - Correlation is when the change in one variable results in the change in another variable.
- https://www.mygreatlearning.com/blog/covariance-vs-correlation/ 


![E(x-N(-Y where X = 2](https://user-images.githubusercontent.com/51651537/149662037-2c05c6ae-78f2-47f5-a328-eed98f3f1734.png)

*Source: https://www.tes.com/teaching-resource/mean-median-mode-and-range-posters-12024923* 

<br>

**Correlation**
    - Covariance is when two variables vary with each other, whereas 
    - Correlation is when the change in one variable results in the change in another variable.
- IS covariance BUT not just linear direction but ALSO strength
- Based on covariance
- Covariance values are standardised

![Cov(X, Y)](https://user-images.githubusercontent.com/51651537/149662041-d90873ba-c496-44bb-bbfc-c04bf3deff3d.png)

*Source: https://www.datadeck.com/en/blog/2018/11/28/data-analytics-correlation-vs-causality/* 


<br>

**Model**  
- Example: An ice cream company keeps track of how many ice creams get sold on different days(real world data). 
- By comparing this to the weather on each day they can make a mathematical model of sales versus weather. 
- They can then predict future sales based on the weather forecast, and decide how many ice creams they need to make ahead of time

<br>

**Probability and Statics are polar opposites**
- Probability creates models from real world data
- Statistics creates real world data from models

<br>


## Descriptive Statistics 2



![Florence Nightingale, Data](https://user-images.githubusercontent.com/51651537/149662044-c5b32475-458c-4a66-9a74-5c6c8f758685.png)

*Source: https://daily.jstor.org/florence-nightingale-data-visualization-visionary/* 

**Data Visualisation** 

![LEVEL 1](https://user-images.githubusercontent.com/51651537/149662048-5f4c711f-b7ae-43fd-a831-880a2e3fb555.png)

*Source: https://www.gapminder.org/* 

<br>

**Bar Chart (bar graph, or column chart)** 
A bar chart presents categorical data with rectangular bars with heights or lengths proportional to the values that they represent. A bar graph shows comparisons among discrete categories. 
![page6image29153072](https://user-images.githubusercontent.com/51651537/149662050-73d19088-91df-42b4-8130-212704fef389.png)

*Source: https://en.wikipedia.org/wiki/Bar_chart* 

<br>

**Line Chart (line plot, or curve chart)** 
A line chart displays information as a series of data points connected by straight line segments. A line chart is often used to visualize a trend in data over intervals of time – a time series. 
![Monthly product sales](https://user-images.githubusercontent.com/51651537/149662053-eaaa9706-f4cc-4653-aef8-2eca870c5a59.jpg)

*Source: https://en.wikipedia.org/wiki/Line_chart , https://online.visual-paradigm.com/charts/templates/line-charts/* 


<br>

**Pie Chart (circle chart)** 
A pie chart is a circular statistical graphic, which is divided into slices to illustrate numerical proportion. 
populations of English native speakers 
![page8image11614016](https://user-images.githubusercontent.com/51651537/149662055-b9476089-7da7-4df7-9151-92c4bad5b715.png)

*Source: https://en.wikipedia.org/wiki/Pie_chart* 


<br>

**Radar chart (spider chart, web chart)** 
A radar chart displays multivariate data in the form of a two-dimensional chart to display multivariate observations. One application is quality control, i.e., analysis of strengths and weaknesses. 
![Star Plot of MER IDO and Automated Design](https://user-images.githubusercontent.com/51651537/149662057-635f6b51-fb05-44e8-9754-18acb47312da.png)

*Source: https://en.wikipedia.org/wiki/Radar_chart* 

<br>

**Histogram** 
A histogram is an approximate representation of the distribution of numerical data. 
![Thousands](https://user-images.githubusercontent.com/51651537/149662058-c5cb6ed3-5a94-4f90-9c64-c36ab8106547.png)

*Source: https://en.wikipedia.org/wiki/Histogram* 

<br>


**Scatter plot (scatter chart, scatter graph)** 
A scatter plot uses Cartesian coordinates to display values for typically two variables for a set of data, to identify the type of relationship (if any) between two quantitative variables 
![Weight by Height](https://user-images.githubusercontent.com/51651537/149662063-e9ceaf92-86d8-4525-89ae-ba21566ad63a.png)

*Source: https://en.wikipedia.org/wiki/Scatter_plot , https://blogs.sas.com/content/graphicallyspeaking/2016/10/04/getting-started-sgplot-part-1-scatter-plot/* 


<br>


**Charts with Python** 
- You can check the python code to plot various type of charts at “Python Graph Gallery”, 
- https://www.python-graph-gallery.com/ 

![Distribution](https://user-images.githubusercontent.com/51651537/149662070-20828677-e7ab-4882-aeef-57dd9e01e122.jpg)
![Part Of A Whole](https://user-images.githubusercontent.com/51651537/149662072-3c7829d9-a935-405d-893b-c6da8348d7d4.jpg)



<br>


## Probability

*Counting (Permutation & Combination)* 


<br>

**Combinations**
- When the order of the data set does not matter, it is a combination


<br>

**Permutation**
- When the order of the data set does matter, it is a permutation
- A permutation is a ordered combination
- 2 types of permutation
    - Repetition is allow - e.g a password 3333
    - Repetition is not allowed - e.g if 3 people are running a race, they can not all be 1. It must be 1 2 and 3
- Repetition - Easy - n^r
    - A lock has n dials from 1-10. That is n x n x n, or 10x10x10. Or 1000 possible combinations 
    - Or, more properly written n^r. N is the number of dials, r is the range (1 to 10)
- No repetition - okay - !n
    - Example: what order could 16 pool balls be in?
    - E.g 1:    the idea is -> we pick ball x. Now there is 15 left. We pick ball y. Now there are 14 left
        - 16 × 15 × 14 × 13 × ... = 20,922,789,888,000
    - E.g 2:   we only want the permutations of 3 pool balls
        - 16 × 15 × 14 = 3,360
        - In other words, there are 3,360 different ways that 3 pool balls could be arranged out of 16 balls.
    - We write this as Factorial. 
        - 16 balls 	=	 !16   		=   16 × 15 × ... 					= 20,922,789,888,000
        - 3 balls 	=	 !16  /  !13   	=   16 × 15  x …   /  13 × 14  x … 		= 3,360

<br>

<br>


**Permutation** 
We have 5 participants for a competition, how many possible cases do we have for “who got which prize”? 
![page7image11863056](https://user-images.githubusercontent.com/51651537/149662074-9d100fcb-2ec1-4e71-8684-cb9a02e2d36a.jpg)

We have 5 participants for a competition, how many possible cases do we have for “who got which prize”? 
5 X4 X3 
![Permutation](https://user-images.githubusercontent.com/51651537/149662079-4f22fdbf-1b89-4538-bd3d-a4a268346014.png)


![page10image11746544](https://user-images.githubusercontent.com/51651537/149662085-433be52b-8916-49b9-9c78-b1209fca374b.jpg)

*Source: http://www.fairlynerdy.com/permutations_and_combinations_simplified/ , 2020.10.04* 



<br>

**Permutation with repetition** 
How many combinations in the pass-number for this lock? 
![If an object may be represented by any number of times,](https://user-images.githubusercontent.com/51651537/149662092-c63589d5-7da3-470d-bb64-fdcf61568c4b.png)


<br>

**Combination** 
We have 5 participants for a competition, how many possible cases do we have if we are to choose 3 winners? 
🏆🏆🏆
We have 5 participants for a competition, how many possible cases do we have if there’re “3 first place prizes”? 
( 5 X 4 X 3 )/ ( 3 X 2X 1 ) 

How many combinations in the pass-number for this lock? 
10 X 10 X 10 X 10 

![Combination](https://user-images.githubusercontent.com/51651537/149662100-30b9843d-12bb-4afa-9d29-5d839e16be67.png)

*Source: http://www.fairlynerdy.com/permutations_and_combinations_simplified/ , 2020.10.04* 

<br>

There are 3 types of fruits (apple, pear, orange), and you’re going to buy 5 fruits. 
How many combinations you can have? 

oo/oo/o
![n Hr= n+7_1Cr](https://user-images.githubusercontent.com/51651537/149662112-4ca5c123-d7ab-4ec1-8d82-3b2c38d86908.png)




<br>

<br>

**Probability**
- Number of Desired outcome / number of total possible outcomes 
- Number of times ill drink water a day / number of times a drink anything a day

 Probability – the chance that an uncertain event will occur (always between 0 and 1) 
 Impossible Event – an event that has no chance of occurring (probability = 0) 
 Certain Event – an event that is sure to occur (probability = 1) 
![What is the probability of randomly selecting](https://user-images.githubusercontent.com/51651537/149662114-38a29822-64a5-4662-980b-200991db6d6a.png)

*Source: https://learnzillion.com/lesson_plans/1413-the-addition-rule-for-the-probability-of-disjoint-events/* 


![Probability](https://user-images.githubusercontent.com/51651537/149662116-eb9091b7-5023-4362-af9f-777d38c0842c.png)

*Source: https://www.wikihow.com/Understand-Probability* 

Probability of getting A+ ? 
of favorable event: “Getting A+” = 1
of total events: “Getting A+”, “not Getting A+” = 2 
![EQUALLY LIKELY](https://user-images.githubusercontent.com/51651537/149662119-0c1d1217-b323-4537-b544-e559dd5420f9.png)

*Source: https://www.youtube.com/watch?v=eHJ40sSkYLE* 



<br>


**What’s the probability of having breast cancer?** 
- 1% of women have breast cancer
- A woman got a mammogram detection of a breast cancer
- 80% of mammograms detect breast cancer when it is there
- 9.6% of mammograms detect breast cancer when it’s not there 
- 1 around 80%, 2 over 50% 3 between 10% and 50% 4 less than 10% 


<br>


**Basic probability** 
- Probability – the chance that an uncertain event will occur (always between 0 and 1) 
- Impossible Event – an event that has no chance of occurring (probability = 0) 
- Certain Event – an event that is sure to occur (probability = 1) 


<br>

**Assessing probability** 
- A Priori (Classical approach) – based on prior knowledge of the process 

![probability of occurrence](https://user-images.githubusercontent.com/51651537/149662121-2bd65940-b3b7-4337-a906-ac95fe1f12af.png)
- Empirical probability (Relative frequency) – based on observation from experiment or historical events 
![probability of the event(E)](https://user-images.githubusercontent.com/51651537/149662122-798d12bf-ddd7-44d8-ac18-4a27798be43f.png)
- Subjective probability – based on a combination of an individual’s past experience, personal opinion, and analysis of a particular situation 


<br>

**A Priori (Classical Approach)** 
- Rolling two dice and probability of the total outcomes becomes {2, 3, ..., 12} 
![P(2) = 136](https://user-images.githubusercontent.com/51651537/149662126-ca505be0-314d-4e53-b95e-25f2410ce59d.png)

- Empirical Probability (Relative Freq. Approach) 

![Bits   Bytes Computer Shop tracks the number of desktop computer systems it](https://user-images.githubusercontent.com/51651537/149662128-3fa82511-45d6-471a-90a5-0999a63f3a4f.png)



<br>


**Subjective Probability** 
- “In the subjective approach we define probability as the degree of belief that we hold in the occurrence of an event” 
- E.g. weather forecasting’s “P.O.P.” 
- “Probability of Precipitation” (or P.O.P.) is defined in different ways by different forecasters, but basically it’s a subjective probability based on past observations combined with current weather conditions. 
- POP 60% – based on current conditions, there is a 60% chance of rain (say). 


<br>


**Event** 
- Simple event
	- An event described by a single characteristic o e.g. A day in January in 2020 
- Joint event
	-  An event described by two or more characteristics
	- e.g. A day in January that is also a Wednesday in 2020 
- Complement of an event A (denoted Ac)
	- All events that are not part of event A
	-  e.g. All other days in 2020 that are not in January 



<br>

<br>


**Organising and visualising events** 

![Venn Diagram](https://user-images.githubusercontent.com/51651537/149662132-6f6859bd-f4f7-49e6-9328-c2d9b0f4971b.png)
![Contingency Table](https://user-images.githubusercontent.com/51651537/149662140-b0e864ef-4492-4e69-860e-20080699388e.png)



**Joint, Marginal, Conditional Probability...** 
We study methods to determine probabilities of events that result from combining other events in various ways. 
There are several types of combinations and relationships between events: 
- Complement event
- Intersection of events
- Union of events 
- Mutually exclusive events 
- Dependent and independent events 


<br>

**Complement of an Event...** 
The complement of event A is defined to be the event consisting of all sample points that are “not in A”. 
Complement of A is denoted by Ac
The Venn diagram below illustrates the concept of a complement. 

P(A)+P(Ac )=1 
![Screenshot 2022-01-14 at 21 41 34](https://user-images.githubusercontent.com/51651537/149662143-5b937099-439f-4b29-852f-936a6c66a726.png)

**Intersection of Two Events...** 
![The intersection of events A and B is the set of all sample points](https://user-images.githubusercontent.com/51651537/149662145-77f546f5-8e17-4674-bbef-2f535ccd30b0.png)

**Union of Two Events...** 
The union of two events A and B, is the event containing all sample points that are in A or B or both: 
Union of A and B is denoted: A or B 
![Screenshot 2022-01-14 at 21 42 06](https://user-images.githubusercontent.com/51651537/149662150-69712b98-fff2-45d4-a4f1-8be88ac73b60.png)

**Mutually Exclusive Events...** 
![When two events are mutually exclusive (that is the two](https://user-images.githubusercontent.com/51651537/149662154-4a18fcd8-c581-467e-971f-15bca1a109b6.png)

**Basic Relationships of Probability...** 
![Complement of Event](https://user-images.githubusercontent.com/51651537/149662155-56423b81-b89c-4a7a-8dbd-3c02a3a0daed.png)

**Example 6.1...** 
![The following table compares mutual fund performance against the ranking of the](https://user-images.githubusercontent.com/51651537/149662156-aa102236-cd22-4599-92fa-6bae545900ad.png)


**Marginal Probabilities...** 
![Alternatively, we could introduce shorthand notation to represent the events](https://user-images.githubusercontent.com/51651537/149662159-b6fa6eca-64bb-4182-a6d4-2316e3982ba7.png)

**Union...** 
![Marginal probabilities are computed by adding across rows and down](https://user-images.githubusercontent.com/51651537/149662160-ffd7b047-a52a-4771-8190-3b32ccf151a5.png)

![We stated earlier that the union of two events is denoted as A or B](https://user-images.githubusercontent.com/51651537/149662167-efed86c5-e079-42bc-82d7-6ffb17bbcba0.png)


<br>

**Example 6.7...** 
In a large city, two newspapers are published, the Sun and the Post.
- 22% of the city’s households have a subscription to the Sun
- 35% subscribe to the Post.
- A survey reveals that 6% of all households subscribe to both newspapers. 
What proportion of the city’s households subscribe to either newspaper? 
- P(Sun or Post) = P(Sun) + P(Post) – P(Sun and Post) =.22+.35–.06=.51 
“There is a 51% probability that a randomly selected household subscribes to one or the other or both papers” 
6.44 


<br>

**Conditional Probability...** 
Conditional probability is used to determine the probability of one event given the occurrence of another related event. 
Conditional probabilities are written as P(A | B) and read as “the probability of A given B” and is calculated as: 

![P(A and B)](https://user-images.githubusercontent.com/51651537/149662171-375f2ee9-1b30-4001-9ac2-54992b088ea0.png)

Example 6.2 What’s the probability that a fund will outperform the market given that the manager graduated from a top-20 MBA program? 
Recall: 
A1 = Fund manager graduated from a top-20 MBA program 
A2 = Fund manager did not graduate from a top-20 MBA program 
B1 = Fund outperforms the market 
B2 = Fund does not outperform the market Thus, we want to know “what is P(B1 | A1) ?” 

![P(A, and 3,  11](https://user-images.githubusercontent.com/51651537/149662174-a757a317-5c96-475d-ab6e-837152607296.png)


<br>


**Independence...** 
The probability of one event is not affected by the occurrence of the other event. Two events A and B are said to be independent if 

		P(A|B) = P(A) 
	or
		P(B|A) = P(B) 




<br>

*Conditional Probability...* 
Again, the probability of an event given that another event has occurred is called a conditional probability... 

![P(A and B)](https://user-images.githubusercontent.com/51651537/149662178-d348675a-b815-4786-8c2e-efca7c2a55e0.png)
![P(A and B)](https://user-images.githubusercontent.com/51651537/149662180-9596691c-4bc3-4582-92d5-77637f6ac39f.png)
 Note how “A given B” and “B given A” are related... 


<br>

## Bayes’ Theorem

![page51image11874912](https://user-images.githubusercontent.com/51651537/149662182-13b34b4c-6ea1-4187-9d4e-8eb60af9900f.jpg)


1% of women have breast cancer: P(BC)=0.01 
80% of mammograms detect breast cancer when it is there : P( MP | BC ) = 0.8 
9.6% of mammograms detect breast cancer when it’s not there : P( MP | BCc ) = 0.096 
What’s the probability of having breast cancer given that mammogram detected breast  
cancer? P ( BC | MP ) 


Historically, your asking out a girl for a date was successful with 40%. 
New information: You fancy a girl and she smiled at you today. Historically, among the girls who accepted when you ask out, 60% smiled before. Among the girls who rejected, 20% of girls smiled before. What’s the chance that asking out your crush is accepted? 
* 		●  Let B = accepted, Bc = rejected 

* 		●  P(B)=0.4,P(Bc )=0.6 

* 		●  Define the smile event as A 

* 		●  Conditional probabilities: P(A|B) = 0.6 P(A|Bc ) = 0.2 

* 		●  Goal is to find P(B|A) 

![P(B) = 0 4 , P(B') = 0 6, P(AJB) = 0 6, P(AIB') = 0 2](https://user-images.githubusercontent.com/51651537/149662184-664944be-b997-43db-a281-5b445792ef70.png)


<br>

## Inferential Statistics

To estimate the mean value(μ) from sample mean (𝑿) 
- How confident you are of the estimated value? 
- Confidence interval 
To test a hypothesis (H0) from sample - How probable the hypothesis is?
- Significant level 

![generalize to](https://user-images.githubusercontent.com/51651537/149662187-b8238ba8-176d-4e65-ad5f-4d6ed7995a21.png)


<br>

**Statistics and Probability** 
* Assume that you got 175 cm of average height from the sample. 

* Probably you’d like to mention that the average height of the population would be 175 cm. 

* How confident are you when you mention it? What’s the probability of μ being 175 cm 


![page6image11536624](https://user-images.githubusercontent.com/51651537/149662189-ef6a4554-4b7b-467b-aba0-46afae4e8b8a.png)

*Source: https://medium.com/@garora039/what-exactly-is-central-limit-theorem-7c1531eb2987/* 


# Statistics and Probability 
* Assume that gambler bet $1 for a head and you bet $1 for a tail 

* The gambler won the game, would you be suspicious about the fairness of the coin? 

* What if you lost the game 10 times straight? 

Probability and Statistics 

![Fair Coin](https://user-images.githubusercontent.com/51651537/149662200-8bc3472f-f3f6-44c6-8a3d-82651742e0a3.png)

*Source: http://thai-massagen.com/?page_id=6120* 


<br>

Variable and probability distribution 
Assume a situation that we flip a coin twice. 

Variable X: # of Tails

![toss toss](https://user-images.githubusercontent.com/51651537/149662202-f5e9dbf6-0354-4894-9d41-94f9cf5a69d0.png)

<br>


**Probability Distribution Table**


Probability Distribution Graph
![page9image11772448](https://user-images.githubusercontent.com/51651537/149662204-4209c5dc-bf9a-4d6a-bdcc-c4c4c68e109d.png)

Probability distribution 
![Normal Distribution](https://user-images.githubusercontent.com/51651537/149662209-38a30cb1-1a2e-4763-b536-db50c3965cfd.png)

Probability Distributions 
![a) Discrete](https://user-images.githubusercontent.com/51651537/149662217-87bb56c9-48f0-4f20-9772-8202ccbdd67b.png)
- Binomial distribution 
- Poisson distribution 

- Z distribution (gaussian, normal) - t distribution
- F distribution, χ2 distribution 

*Source: https://medium.com/analytics-vidhya/probability-distributions-444e7babf2e1* 


<br>

**Binomial Distribution** 
Variable: # of Heads when flipping coin 4 times 

![P(x)= p](https://user-images.githubusercontent.com/51651537/149662219-cf80da56-558b-41f3-8079-780b9f4a3bf2.png)


Variable: # of Heads when flipping coin n times 
![Flip n coins](https://user-images.githubusercontent.com/51651537/149662221-27295f77-1912-4c8a-b4a3-e79dc9a383e8.png)


Random Variable: # of Heads when flipping coin 20 times 
![page15image11669776](https://user-images.githubusercontent.com/51651537/149662224-0d877521-98f6-4bd9-a727-a1ff09c98dbf.png)


Assume that the probability of having heads is π, not 0.5 due to certain reason. Then the probability that we have X times of heads(π) when flipping n times 
![PIX=  C  (rE) (1- re)n-x)](https://user-images.githubusercontent.com/51651537/149662227-78bd4428-caf6-42ff-88c3-82c234439603.png)

**Binomial Distribution Example** 
* Suppose the probability of purchasing a defective computer is 0.02. 

* What is the probability of purchasing 2 defective computers in a group of  10?

➔n = 10, x = 2, p = 0.02 
![P(X=2110, 0 02) =](https://user-images.githubusercontent.com/51651537/149662228-448ca909-c3c7-4656-b01c-51c8b907eab4.png)

<br>

**Binomial Distribution Example** 
* What’s the probability of getting zero score when you select the answer randomly? 

* You got 10 multiple choice questions, and each of them has 5 answers ➔n = 10, x = 0, π = 0.2 

![P(X= 0110, 0 2) = -](https://user-images.githubusercontent.com/51651537/149662230-502e68a8-f2d8-45bd-836b-50553746896d.png)


* If a grade on the exam is less than 50, that’s considered a failed 

* What’s the probability of getting failed? 
➔ Given that n=10 and π = 0.2
P(fail quiz) = P(X < 4) = P(0)+P(1)+P(2)+P(3)+P(4) 
This is called a cumulative probability, that is, P(X ≤ x) 


= BINOM.DIST(4,10,0.2,1) = 0.9672 
![BINOM DIST(number_s, trials, probability_s, cumulative)](https://user-images.githubusercontent.com/51651537/149662233-5b2a081e-6503-4e44-8ef0-0a950de00d04.png)


<br>


**Binomial Distribution Table** 
• P(fail quiz) = P(X < 4) = P(0)+P(1)+P(2)+P(3)+P(4)
= 0.1074+0.2684+0.3020+0.2013+0.0881 = 0.9672 
![T= 25 TT= 30](https://user-images.githubusercontent.com/51651537/149662236-f8853c06-293a-4acd-bbae-01d013c93e8e.png)

<br>

**Using Excel** 
• Use the Excel function, “BINOM.DIST”, • BINOM.DIST(4,10,0.2,1) 
![BINOM DIST(number_s, trials, probability_s, cumulative)](https://user-images.githubusercontent.com/51651537/149662237-247af755-c3f7-4109-90f0-a9d656bc3ce6.png)


Shapes of Binomial Distribution 
• The shape of the binomial distribution depends on the values of π and n 
Positively skewed when π (or p) < 0.5 
	Positively skewed when π (or p) > 0.5 
![Binomial Distribution n = 10, p = 0 8](https://user-images.githubusercontent.com/51651537/149662242-ef3bae39-484c-4fa6-8f41-8f7911b17c6f.png)
![Binomial Distribution n = 10, = 0 2](https://user-images.githubusercontent.com/51651537/149662244-df3fd4fa-836b-481b-8786-abccc9888e78.png)

<br>

**Binomial Distribution Characteristics** 
![Variance and Standard Deviation](https://user-images.githubusercontent.com/51651537/149662246-6b71eec4-d0fa-48e1-a3fd-af170b44dd6b.png)

<br>

**Binomial Distribution in Excel** 
• When n=4 and π=0.1 
![Binomial Probabilities](https://user-images.githubusercontent.com/51651537/149662248-e2d2ff5a-ab71-41e7-9e5c-cc31100edbd9.png)
![Cumulative Distribution Function](https://user-images.githubusercontent.com/51651537/149662251-ec8e45f5-3131-4358-b756-8ee68324db78.png)




Binomial Distribution in Excel 
* Suppose that 15% of people are left-handed. 

* What is the probability of finding exactly 9 left-handed people 
in a random sample of 50? 
➔ Using Excel’s BINOM.DIST function, the answer is =BINOM.DIST(9, 50, 0.15, FALSE) = 0.1230 








**Binomial Distribution – Conditions and Criteria** 
* Rule 1: Situation where there are only two possible mutually exclusive outcomes (for example, yes/no survey questions). 

* Rule2: A fixed number of repeated experiments and trials are conducted (the process must have a clearly defined number of trials). 

* Rule 3: All trials are identical and independent (identical means every trial must be performed the same way as the others; independent means that the result of one trial does not affect the results of the other subsequent trials). 

* Rule: 4: The probability of success is the same in every one of the trials. 
* Source: http://www.intellspot.com/binomial-distribution-examples/ 






<br>

<br>





**Probability Distributions** 
![Probability](https://user-images.githubusercontent.com/51651537/149662256-82cf1286-18d5-4441-a2c0-77bab9491351.png)


**Continuous Probability Distribution** 
- Computing probabilities from the normal distribution
- Using the normal distribution to solve real world problems 
- Computing probabilities from the uniform distribution 
 
- A continuous random variable is a variable that can assume any value on a continuum 
✓ thickness of an item
✓ time required to complete a task ✓ temperature
✓ height, weight 

* Continuous probability distributions can have a variety of shapes 

* Two common continuous distributions 


**Normal Distribution**

![page32image12003280](https://user-images.githubusercontent.com/51651537/149662259-7e501307-516f-45b8-af6b-be50af7d03ec.png)

**Uniform Distribution** 

![page32image11993504](https://user-images.githubusercontent.com/51651537/149662265-67711ab3-7396-4022-b689-1615b65dcdad.png)


<br>

**The Normal Distribution** 
* Bell Shaped, Symmetrical (Mean, Median and Mode are Equal) 

* Location is determined by the mean, μ 

* Spread is determined by the standard deviation, σ 

* The random variable has an infinite theoretical range 
f(X) 

μ 
Mean = Median = Mode 
![page33image28769040](https://user-images.githubusercontent.com/51651537/149662266-a6ed3371-3fcf-4c71-9d98-66cf0f5d794e.png)


**The Normal Distribution Shape** 
• A distribution’s mean (μ) and standard deviation (σ) completely describe its shape 
![Changing u shifts the](https://user-images.githubusercontent.com/51651537/149662267-13fff318-dde9-4a98-907d-0173d8f128a8.png)


**The Normal Distribution** 
• The Normal Probability Density Function: 

![page35image11565488](https://user-images.githubusercontent.com/51651537/149662270-653d5f06-2ce2-4467-a323-ab1d3ac00836.png)
![page35image11553632](https://user-images.githubusercontent.com/51651537/149662272-0e3aa612-3959-4c27-827c-a1333a4c26bb.jpg)


✓ e : Euler number, 2.71828......
✓ π : ratio of a circle's circumference to its diameter,3.14159...... 
✓ μ : the mean of the distribution
✓ σ : the standard deviation of the distribution 
✓The range of random variable x: ∞<x<∞ 


**Translation to the Standardized Normal Dist.** 
• Translate from X to the standardized normal (the “Z” distribution) by subtracting the mean of X and dividing by its standard deviation: 
![Screenshot 2022-01-15 at 20 52 26](https://user-images.githubusercontent.com/51651537/149662276-58a6a306-1e19-46e3-a059-4d84b7d71c9c.png)


**Translation to the Standardized Normal Dist** 
![Translate from X to the standardized normal (the 'Z distribution) by](https://user-images.githubusercontent.com/51651537/149662279-a73dde26-cab9-4a7f-88e2-5d4105a8a67c.png)


**The Standardized Normal Distribution** 
* Also known as the “Z” distribution 

* Mean is 0 

* Standard Deviation is 1 

![Screenshot 2022-01-15 at 20 53 07](https://user-images.githubusercontent.com/51651537/149662282-5bdae257-3a22-4732-904a-8194df956427.png)


**Example** 
![of $50, the Z value for X = $200 is](https://user-images.githubusercontent.com/51651537/149662284-c7574cce-109e-4d9c-b48d-a6fe815e1bc5.png)


**Comparison of the X and Z value** 
![The shape of the distribution is the same, only the scale has changed](https://user-images.githubusercontent.com/51651537/149662286-244ad224-d80e-4d04-b1a7-03004a36cbe6.png)


**Probability as Area Under the Curve** 
• The total area under the curve is 1.0, and the curve is symmetric, so half is above the mean, half is below 
![P(-∞  X  u) = 0 5](https://user-images.githubusercontent.com/51651537/149662291-3f2531e4-8172-46bc-b296-2e61e9647cf9.png)



**Procedure for Finding Normal Probabilities** 

- To find P(a < X < b) when X is distributed normally: 
Draw the normal curve for the problem in terms of X Translate X-values to Z-scores
Use the Standardized Normal Table 
Use Excel function 



**Probability as an area** 
What will be the probability of P(Z <2.01)? 
![Screenshot 2022-01-15 at 20 54 21](https://user-images.githubusercontent.com/51651537/149662293-febb939e-f778-4eef-bcd7-7e626ca57154.png)


**Z Table** 
![The Cumulative Standardized Normal](https://user-images.githubusercontent.com/51651537/149662295-838f1200-b5c9-43cd-9214-e8a10a3cd807.png)
![5000  5040](https://user-images.githubusercontent.com/51651537/149662297-c3392819-0afd-48bd-a589-c1f98fc5d35d.png)





**Excel function** 
* 		-  norm.dist(x, mean, standard deviation, cumulative) 

* 		-  norm.inv(probability, mean, standard deviation) 

* 		-  norm.s.dist(z, cumulative) - norm.s.inv(distribution) 





<br>

<br>




**Example - Finding Normal Probabilities** 
![Let X represent the time it takes (in seconds) to download an image](https://user-images.githubusercontent.com/51651537/149662300-10666d3a-00a3-42a8-b294-872cdcb7cd4f.png)

![Translate X-values to Z-scores](https://user-images.githubusercontent.com/51651537/149662302-1bb109f5-bd83-4801-87bc-980b4b1a2174.png)

![Use the Standardized Normal Table](https://user-images.githubusercontent.com/51651537/149662303-5351dc24-60b9-46ac-9147-9dad95bd8598.png)

<br>

**Finding Normal Upper Tail Probabilities** 
![What's the probability of taking longer than 18 6 sec](https://user-images.githubusercontent.com/51651537/149662304-44fd9ede-2fc2-4cb2-94e4-a7fae160efb6.png)


**Normal Probability Between Two Values** 
![Probability of taking longer than 18 0 sec and shorter than 18 sec](https://user-images.githubusercontent.com/51651537/149662306-6baa7138-b190-4d0a-ad08-7a1d4ebe9c8c.png)



**Finding the X value for a Known Probability** 
* X represent the time it takes to download an image file from the internet. 

* Suppose X has normal distribution (μ = 18.0 sec, σ = 5.0 sec). 

* Find X such that 20% of download times are less than X. 

![Screenshot 2022-01-15 at 20 57 00](https://user-images.githubusercontent.com/51651537/149662308-d29d2df9-de3f-4087-904c-a51d8deae4c4.png)


<br>


**Find the Z value for 20% in the Lower Tail** 
• Find the closest Z value for the known probability (20%) 
![Z Table (Portion)](https://user-images.githubusercontent.com/51651537/149662309-e09245a4-3f1f-46fd-bb44-4f48f5d59f79.png)
![Convert to X units using the formula](https://user-images.githubusercontent.com/51651537/149662313-2d08b7a6-48ea-48ba-902d-aaa66ce1d141.png)





**The Uniform Distribution** 
• The uniform distribution is a probability distribution that has equal probabilities within a certain range 
![page58image11659008](https://user-images.githubusercontent.com/51651537/149664119-f85525bd-678c-4d1a-a819-6439a8d85236.png)
![= 0, otherwise](https://user-images.githubusercontent.com/51651537/149664121-ea1dc42a-d7ef-4a71-bb75-bb68fe390853.png)


**Example - The Uniform Distribution** 
![Uniform probability distribution over the range 2 ≤ X ≤ 6](https://user-images.githubusercontent.com/51651537/149664126-bb6b0465-e3e3-4dae-8a6a-ebe0717fc4a5.png)
![Probability of P(3 ≤ X ≤ 5)](https://user-images.githubusercontent.com/51651537/149664128-6897420f-d38c-4b7e-8bb5-a7d07475bd40.png)



<br>


**Sample distribution and Confidence interval** 
- Sampling distribution
- Central Limit Theorem
- Confidence interval of population mean 
- ( Z distribution / t distribution ) 


**Statistical Inference** 
![1  Collecting sample data](https://user-images.githubusercontent.com/51651537/149664139-5857a52e-3de7-4bc5-8e0f-c65aed9aa76f.png)

<br>

**Mathematical Notation** 
![Standard](https://user-images.githubusercontent.com/51651537/149664146-cb9f8e65-d1ce-4370-b888-0c547a213e5c.png)


<br>

**Distribution of sample mean**
- Sample mean (𝑋) changes when you take different sample
- How would sample mean (𝑋) be distributed then? 
![A sample of size n](https://user-images.githubusercontent.com/51651537/149664155-8d8fbffe-fbf9-43f8-a71e-75f2fa099ecf.png)
![A sample of size](https://user-images.githubusercontent.com/51651537/149664162-29d53322-1c78-49bb-8cc0-0d92754a9919.png)


**Mathematical Notation** 
![Standard](https://user-images.githubusercontent.com/51651537/149664168-10de348d-3f8b-43b9-b233-28fa183e4d63.png)


**Distribution of sample mean** 
![distribution](https://user-images.githubusercontent.com/51651537/149664177-ee2ea87c-2d22-470c-99bb-ed6e8735a3c6.png)


**Sample distribution** 
![1  Population](https://user-images.githubusercontent.com/51651537/149664182-91fac5bf-b302-4884-a986-aea8ea65fab4.png)


<br>

**Sample distribution** – when the population is normally distributed
* If a population is normal with mean μ and standard deviation σ, 

* The sampling distribution of 𝑥ҧ is also normally distributed with 

![Screenshot 2022-01-16 at 13 04 46](https://user-images.githubusercontent.com/51651537/149664188-2e8fc273-f9c2-4316-8283-3201081ede8e.png)


**Central Limit Theorem**
* Even if the population is not normal, 

* Sample means from the population will be approximately normal as 
long as the sample size is large enough. 

* Properties of the sampling distribution of 𝑥ҧ : 

![Screenshot 2022-01-16 at 13 05 00](https://user-images.githubusercontent.com/51651537/149664197-b8f8db02-f8ed-45f3-985a-7f7c2fce7463.png)
![Population Distribution (non-normal)](https://user-images.githubusercontent.com/51651537/149664201-ae4783bc-fea5-4aaf-9400-60f827574e6b.png)



**Example - a Sampling Distribution** 

* Assume there are 4 people (N = 4) 

* Random variable, X, is age of individuals (X: 18, 20, 22, 24 years old) 

* Summary measures for the population distribution 

![= 2 236](https://user-images.githubusercontent.com/51651537/149664206-7554ebcf-977e-476c-a61b-2bce0af4a128.png)
![Population, N=4](https://user-images.githubusercontent.com/51651537/149664211-18b37e60-c3bb-4657-995c-1d1e9c28593f.png)


**Distribution of sample mean** 
![distribution 01](https://user-images.githubusercontent.com/51651537/149664215-7e373ea2-75b2-4e92-99fa-6a56bf50ddbf.png)


**Example** 
![Suppose a population is normally distributed](https://user-images.githubusercontent.com/51651537/149664224-e696aeed-f9d6-4e45-890a-830249484caa.png)

**Solution – using excel function (norm.dist)** 
![The sampling distribution is approximately normal, with mean 8 (= uz)](https://user-images.githubusercontent.com/51651537/149664230-52a14ef1-0637-41de-bd05-a2a6c6b46e59.png)


**Confidence interval of the population mean** 
![How much certain, i e  probable, is the estimation of a population](https://user-images.githubusercontent.com/51651537/149664232-ff6b4fb3-bc8b-4bec-b593-f11810216581.png)


**Standard Normal Distribution** 
- Normal distribution with  = 0,  = 1 ത 
- What’s the 𝑋 value where the probability of dashed are is 95%? 
- norm.inv(0.025,0,1) = -1.96, norm.inv(0.975,0,1) = 1.96 

- 95% confidence interval for 𝑋 

*-1.96 ≤ 𝑋 ≤ 1.96* 
![Screenshot 2022-01-16 at 13 07 37](https://user-images.githubusercontent.com/51651537/149664236-76d02cc8-a479-4213-8607-a5378adc67df.png)

<br>


**Normal Distribution: Critical Z-Scores** 
![X=pt Zo;](https://user-images.githubusercontent.com/51651537/149664240-58696629-7efc-4b59-b491-1736d53c2818.png)


<br>

**Common levels of confidence** 
- Commonly used confidence levels are 90%, 95%, and 99% 
![Confidence Level](https://user-images.githubusercontent.com/51651537/149664246-843a4ac4-650e-427e-b646-4945b730290a.png)
![We'd like to know about the average income of data scientist in Korea salary](https://user-images.githubusercontent.com/51651537/149664249-e9abf133-879d-4ef0-a935-6dc5455b1aa3.png)


**Confidence Interval for Population Mean (when population STD(σ) is unknown)** 
* If the population standard deviation σ is unknown, we can substitute the sample standard deviation, s 

* This introduces extra uncertainty, since s varies from sample to sample 

* So we use the Student’s t distribution instead of the normal distribution 
✓ The t distribution allows more uncertainty than normal when the degree of freedom is low 
✓ The tα/2 value depends on degrees of freedom (d.f.) ✓ Degrees of freedom (d.f.) is identified as ‘n-1’ 




Student’s t Distribution 
![As n increases t distribution approaches Z distribution](https://user-images.githubusercontent.com/51651537/149664261-37aed855-083d-441b-8c8b-a0eae029a21f.png)


A few selected t distribution values 
With comparison to the Z value (degree of freedom = sample size -1)
(you can also get the number from excel function “t.inv.2t(probability, d.f.)” 
![Confidence](https://user-images.githubusercontent.com/51651537/149664265-c98e3498-3a5c-4c53-9cd6-d9920c171891.png)


Example of t distribution confidence interval 
![A random sample of n = 21 has X = 50 and S = 8](https://user-images.githubusercontent.com/51651537/149664273-a4a1178c-48e0-4982-a064-290f9c0965de.png)
![Population(mean u, STD o, size N](https://user-images.githubusercontent.com/51651537/149664277-27b9f555-347c-48c7-b2a6-7d34c28f09ae.png)
![Distribution of Sample Average](https://user-images.githubusercontent.com/51651537/149664280-f8ee497a-f123-4d17-89c2-14355478e507.png)


Confidence interval of the population mean 
![How much certain, i e  probable, is the estimation of a population](https://user-images.githubusercontent.com/51651537/149664285-6b30192a-5e49-44c7-8024-f8c2fd31cd17.png)

<br>

Confidence Interval for Population Mean (when population STD(σ) is unknown) 
* If the population standard deviation σ is unknown, we can substitute the sample standard deviation, s 

* This introduces extra uncertainty, since s varies from sample to sample 

* So we use the Student’s t distribution instead of the normal distribution 
 The t distribution allows more uncertainty than normal when the degree of freedom is low 
 The tα/2 value depends on degrees of freedom (d.f.)  Degrees of freedom (d.f.) is identified as ‘n-1’ 


<br>



Student’s t Distribution 
• As n increases t distribution approaches Z distribution 
![Standard Normal](https://user-images.githubusercontent.com/51651537/149664294-ba8cca56-ebf0-4a6b-9937-8988acbfbe7d.png)


<br>

A few selected t distribution values 
• With comparison to the Z value (degree of freedom = sample size -1)
(you can also get the number from excel function “t.inv.2t(probability, d.f.)” 
![Confidence](https://user-images.githubusercontent.com/51651537/149664303-cd77287e-9599-4492-8ad9-7cdaa824a2f6.png)


<br>

Example of t distribution confidence interval 
![A random sample of n = 21 has X = 50 and S = 8](https://user-images.githubusercontent.com/51651537/149664312-d718fc1c-4b02-45b9-9163-a11d9d6f595f.png)


<br>

## Hypothesis Test

- Hypothesis test – Z test, t test  Critical value and p-value
- One-tail test and two-tail test  Type I, II error 

**Hypothesis Testing** 
- While you’re traveling, you met a gambler
	-  He bet $1 for a head, and me bet $1 for a tail
	- He won the game 7 times straight
	- You claim that the coin is not a normal one
	- But he argued that it was an absolute coincidence, nothing’s impossible in the probability distribution  How would you argue? 

<br>

**Hypothesis testing is a process of testing the hypothesis with pre- 
defined confidence level**
- A hypothesis is a claim about a population parameter (e.g. mean)
- Sample mean is estimated
- Checks whether the sample mean is within the confidence interval from the claimed mean (i.e. the hypothesis) 


<br>

**Terminology**
- Null hypothesis (H0): a claim to be test
- Alternative hypothesis (H1): the opposite of the null hypothesis
- Significance level: interval for the rejection (α)
- Confidence level: interval for the acceptance of the H0, ( (1- α) x 100% ) 

<br>


- Confidence level = (1 – α ) x 100%
- Confidence coefficient = 1 – α
- Level of Significance (probability corresponding to 2 tail) = α 
![Region of](https://user-images.githubusercontent.com/51651537/149664330-1141c134-26cc-4af2-ac83-0725404f86c9.png)


<br>

**Hypothesis Testing Process** 
![Claim The population mean age is 50](https://user-images.githubusercontent.com/51651537/149664337-11ecb13f-309d-47a0-8a01-1eedfbc6cf0c.png)


- Suppose the sample mean age was 20, (𝑋 = 20) 
- Check where the sample mean falls on (1) rejection region, (2) non- rejection region 
![Pre-defined](https://user-images.githubusercontent.com/51651537/149664339-b687ea2a-d372-4112-ae77-834d4a0bdd16.png)


<br>


**Hypothesis Testing – Example 1** 
- A manufacturer claims that the average lifetime of a light bulb is 1,000days. (standard deviation: 100days) 
- An inspector found that the sample mean of 100 bulbs is 990 days 
- Test null hypothesis (H0: life-time is 1,000 days) with 5% of 
significance level (i.e. α = 0.05) 


<br>


**Hypothesis Testing – Example 1 (x value)** 
- H0 are not rejected as the 𝑋 value is within the interval 
![1,000 - 1 96•-00u  = 980 4](https://user-images.githubusercontent.com/51651537/149664347-5ea6f805-f9ba-4ee2-bc57-ec6bb6646a0a.png)



<br>


**Hypothesis Testing – Example 1 (z value)** 
- You can check the region with ZSTAT value 
![990- 1,000](https://user-images.githubusercontent.com/51651537/149664360-bf62e35d-a150-4f34-a4e9-a8ef7a18f9bb.png)


<br>

**Hypothesis Testing – Example 1 (p value)** 
![You can check the p-value of ZsTAT (-1 0)](https://user-images.githubusercontent.com/51651537/149664367-6da559b3-1c26-432d-85b4-a1933e4bca4d.png)


**Hypothesis Testing – Example 2 (p-value)** 
* 	A manufacturer claims that the mean diameter of a manufactured bolt is 30mm. (Assume σ = 0.8) 

* 	Test the claim with significant level of 5% 

* 	Sample mean from 100 samples was 29.84 

![-Zan2 (= -1 96)  ZSTAT(= -2 0), Ho is to be rejected](https://user-images.githubusercontent.com/51651537/149664371-52aba8f9-d6b8-412b-9031-96975fc73524.png)

<br>


**Hypothesis Testing when σ is known**
- Z-Test is used when the population standard deviation is known 
![Hypothesis](https://user-images.githubusercontent.com/51651537/149664377-cf7e5ce8-2cc4-4fe0-b6cf-60fa406bc5f8.png)



<br>

**Hypothesis Testing when σ is unknown**
- t-Test is used when the population standard deviation is unknown 
![Hypothesis](https://user-images.githubusercontent.com/51651537/149664387-5a368bf1-f587-4edf-bc4a-c31c5238691f.png)



<br>

**Hypothesis Testing – Example 3 (t-test)** 
- The average price of a hotel room in NY is said to be $168 per night. 
- A random sample of 25 hotels is taken, 𝑋 = $172.50 and s = $15.40. 
- Test null hypothesis with 5% of significance level (i.e. α = 0.05) 
![Ho p = 168](https://user-images.githubusercontent.com/51651537/149664411-dfbbd9f3-da6f-4ce2-beb7-550d93a451da.png)


<br>

**One-Tail Tests** 
- In many cases, the hypothesis focuses on a particular direction 
![This is a lower-tail test since the alternative](https://user-images.githubusercontent.com/51651537/149664421-30c514ba-becb-4bb6-87be-31ef4d6000b3.png)

**Lower-Tail Tests** 
- There is only one critical value, since the rejection area is in only one tail 
![Reject Ho](https://user-images.githubusercontent.com/51651537/149664429-12865484-174a-4000-8b09-c753010afb39.png)

<br>

**Upper-Tail Tests** 
 There is only one critical value, since the rejection area is in only one tail 
![Do not reject H,](https://user-images.githubusercontent.com/51651537/149664436-a1d6d212-2737-44b2-a24c-033ced1ca305.png)


<br>

**Upper-Tail Tests ( unknown) - Example** 
- Average of the monthly cell phone bills is known to be $52 per month 
- A phone industry manager thinks that it has increased, and wishes to test this claim. 
- Suppose that α = 0.10, n=25 is chosen for this test 

<br>

- From the 25 samples (n = 25), we’ve got 𝑋 = 53.1, s = 10. 
![Ho ≤ 52](https://user-images.githubusercontent.com/51651537/149664441-083e467b-60d5-4e15-8f8b-34bb864652fe.png)


<br>

**Upper-Tail Tests ( unknown) - Example** 
- Finding the rejection region: 
![Reject Ho](https://user-images.githubusercontent.com/51651537/149664446-ee984c71-a690-4616-8fa8-39a6ce05f693.png)


<br>

**Type I, II Errors** 
 There are possible errors in hypothesis test decision making 
![Reject Ho](https://user-images.githubusercontent.com/51651537/149664456-b5ef3597-3c33-41ba-b3fa-c87eda437b9b.png)

<br>

**Type of Errors in Hypothesis Test** 
![No Fire](https://user-images.githubusercontent.com/51651537/149664467-84650507-b3e4-4d0a-bbb0-1541f11d6518.png)
![Healthy Person](https://user-images.githubusercontent.com/51651537/149664468-e9f4e97f-0350-4547-bc22-a50f1b93f50d.png)



<br>

<br>


## Regression

**Linear Relationship** 
![Any relationship between the two variables with the data below](https://user-images.githubusercontent.com/51651537/149664476-4eedc650-e4d8-410f-95c2-e64c52a45384.png)

<br>

**Introduction to Regression Analysis** 
- Dependent variable:
	- The variable we wish to predict or explain (e.g. heating cost)
	- Typical symbol is Y. 
- Independent variable(s):
	- The variable used to predict or explain the dependent variable. 
	- E.g. temperature, insulation, age of boiler, number of windows 
	- Typical symbol is X. 


<br>

**Introduction to Regression Analysis** 
- Regression analysis is used for:
	-  Explaining the impact of changes in independent variable(s) on the 
dependent variable.
- Predicting the value of a dependent variable based on the value of independent variable(s). 


<br>

**Simple Linear Regression Model** 
- Only one independent variable, X
- Changes in Y are assumed to be related to changes in X 
![Constant](https://user-images.githubusercontent.com/51651537/149664480-28f7d6dd-c74a-4828-b01c-fb75e3b42ccf.png)
![Error for this X, value](https://user-images.githubusercontent.com/51651537/149664482-bcc0a81a-1f0a-414f-973b-8f259bafbb05.png)

<br>

**The Least Squares Method** 
- b0 and b1 are obtained by minimizing the sum of the squared 
![differences between Y and Y](https://user-images.githubusercontent.com/51651537/149664485-806b578d-c4eb-4cb8-bee8-e56290893792.png)

<br>


**Simple Linear Regression Example** 
- A real estate agent wishes to examine the relationship between the selling price of a home and its size (measured in square feet) 
- A random sample of 10 houses is selected
	- Dependent variable (Y) = house price in $1000s 
	- Independent variable (X) = square feet 
![Regression Statistics](https://user-images.githubusercontent.com/51651537/149664491-a0b04745-38b6-44e4-8cd6-83578c887952.png)
![House price model Scatter Plot and Prediction Line](https://user-images.githubusercontent.com/51651537/149664492-a17258b3-915c-43f0-a6f2-aa35bd48dd24.png)

<br>

**Simple Linear Regression Example: b0** 
![house price = 98 24833 + 0 10977 (square feet)](https://user-images.githubusercontent.com/51651537/149664498-99fe844c-6cf2-4ef9-966f-ff91126920e0.png)

<br>

**Simple Linear Regression Example: b1** 
![house price = 98 24833 +0 10977 (square feet)](https://user-images.githubusercontent.com/51651537/149664506-bdf616f9-360e-4bf6-8878-00e920bb9fd3.png)

<br>

**Simple Linear Regression Example: Prediction** 
![Predict the price for a house with 2000 square feet](https://user-images.githubusercontent.com/51651537/149664510-cce9079b-cde1-4076-b95a-7e17d216d4f3.png)
![Predicting out of the relevant range of data might lead to poor](https://user-images.githubusercontent.com/51651537/149664511-6731049f-1c50-42d2-b66d-057974514296.png)



<br>

**Model Evaluation: Measures of Variation** 
- SST = total sum of squares (Total Variation)
- SSR = regression sum of squares (Explained Variation) 
- SSE = error sum of squares (Unexplained Variation) 
![SSE - Z(Y, - Y,)2](https://user-images.githubusercontent.com/51651537/149664523-59a7569c-6b55-4ecc-bf02-9da23a9a60e1.png)
![Error Sum of](https://user-images.githubusercontent.com/51651537/149664525-7cf9a00d-e3bc-4ef5-b1a5-c063877772e1.png)

<br>


**Simple Linear Regression Example: R2** 
![Regression Statistics](https://user-images.githubusercontent.com/51651537/149664529-caa70268-9684-4419-b754-77e10e80fe2a.png)


<br>

**Coefficient of Determination: R2** 
![-2 = SSR  SST](https://user-images.githubusercontent.com/51651537/149664538-4cde3d62-764a-4f9e-9953-af677f384189.png)
![Perfect linear relationship between X and Y](https://user-images.githubusercontent.com/51651537/149664543-85c6354b-4fd9-4024-894a-0e59a68ff4c0.png)
![Weaker linear relationships between X and Y](https://user-images.githubusercontent.com/51651537/149664544-1b84d235-d685-4669-b182-9b6c6bba470b.png)
![No linear relationship between X and Y](https://user-images.githubusercontent.com/51651537/149664546-6a6d1476-4be0-4fbe-9efc-fe933d82f862.png)

<br>


**Regression Diagnostics (L.I.N.E)** 
![residuals](https://user-images.githubusercontent.com/51651537/149664549-80d71921-eda1-422d-a715-36ac5b949e9b.png)



**Multiple Regression** 
- Often we can obtain more accurate forecasts if we include more  independent variables in our regression model. 
	- Example) heating cost would be affected by not only the size but, temperature, insulation, age of boiler, number of windows as well.
- Allows effect of changes in some variables to be investigated while  others are held constant. 

<br>

**Multiple Regression Model** 
- Idea: Examine the linear relationship between 1 dependent (Yi) and 2 or more independent variables (Xi) 
- Multiple Regression Model with k Independent Variables: 

![¥-intercept](https://user-images.githubusercontent.com/51651537/149664567-741c5b5e-f564-4676-b325-71d1e1a8d8bc.png)

<br>

**Example: two Independent Variables** 
- A distributor of frozen dessert pies wants to evaluate factors thought to influence demand 
	- Dependent variable: Pie sales (units per week) o Independent variables: Price (in $) Advertising ($100’s) 
- Data are collected for 15 weeks 


**Example: two Independent Variables** 
![Pie Sales](https://user-images.githubusercontent.com/51651537/149664580-1a1adb75-1f18-4e0b-ab9d-154663583079.png)
![Regression Statistics](https://user-images.githubusercontent.com/51651537/149664584-0f31eabb-5e0a-4a8d-b42b-6830fef1d034.png)


<br>

**R2 vs. Adjusted R2**
- r2 never decreases even if an irrelevant new X variable is added to the model
- This can be a disadvantage when comparing models 

<br>

 **Adjusted r2** 
- Penalize when adding a new variable 
- If the new variable is very useful, adjusted r2 will still increase 
![Penalized portion](https://user-images.githubusercontent.com/51651537/149664586-1ebb460f-202a-44c1-8572-e055b8c3e278.png)


<br>

**Using Dummy Variables** 
- A dummy variable is a categorical independent variable with two levels: 
	- yes or no, on or off, male or female
- If more than two levels, (number of levels - 1) number of dummy 
variables are needed.
	- Spring, summer, fall, winter  3 dummy variables are needed 


<br>


**Dummy-Variable Example** 
- Let the regression model be
	- Y = pie sales per week
	- X1 =pricein$
	- X2 = holiday ( b2 = 1 if a holiday occurred during the week, 0 otherwise) 

![Y =b, +b,X, +b,X,](https://user-images.githubusercontent.com/51651537/149664591-199a6347-3f40-424d-89c5-7737787bea2a.png)
![(sales)](https://user-images.githubusercontent.com/51651537/149664595-2d4db1c2-54da-4984-91f7-60a9e7d2a2e3.png)

<br>

**Dummy-Variable Example (more than 2 levels)** 
- Let the regression model be
	- Y = heating cost
	- X1 = square feet
	- X2 = 1 if summer, X3 = 1 if winter, (spring/fall be the default category) 

![Y =b, +b,X, +b,X, +b,X,](https://user-images.githubusercontent.com/51651537/149664599-b5654ca4-c3b0-49da-9169-2d726d662473.png)
![Y (cost)](https://user-images.githubusercontent.com/51651537/149664600-7ca68d6d-57d2-452f-8472-54e08ad1ddbf.png)


<br>

**Nonlinear Relationships** 
- Plots show we are fitting a linear model to a relationship that is non- linear (e.g. cost vs capacity). 
- If there is a pattern in residuals, we have missed something. 
![Capacity](https://user-images.githubusercontent.com/51651537/149664606-b818f9a6-81e8-4897-ad96-5a4d31d800f1.png)


<br>

**Nonlinear Relationships** 
- Non-linear relationship can be transformed to linear relationship 
using ‘1/capacity’ instead of ‘capacity’
- After the transformation, the adjusted r2 increases 
![Capacity](https://user-images.githubusercontent.com/51651537/149664614-7abe3901-3251-4af3-be70-2730623c2bc4.png)

<br>

**The problem of multicollinearity** 
![Expenditure on](https://user-images.githubusercontent.com/51651537/149664617-aa1b6e9a-ac1e-4ddc-b1fb-1b36362d12c9.png)


<br>

**The problem of multicollinearity** 
- Occurs when there’s high correlation between the independent variables. 
- Independent variables contribute redundant information to the model. 
- Problems:
	- The coefficients estimated cannot be trusted.
	- The coefficients might even have the wrong signs. 
- Indications:
	- Intuitively Incorrect signs on the coefficients.
	- When a new variable is added to the model, there’s a large change in the value of a previous coefficient. 



<br>

**Detecting and solution to the multicollinearity** 
- Run a separate regression with one suspicious variable as dependent and all the others as independent variables. 
	- If r2 > 0.8, then it’s regarded as there’s a multicollinearity issue 
![Combine correlated variables into a single super variable](https://user-images.githubusercontent.com/51651537/149664623-3866f3ca-06b3-43e9-a311-933feb2afd48.png)




<br>

<br>




# END

