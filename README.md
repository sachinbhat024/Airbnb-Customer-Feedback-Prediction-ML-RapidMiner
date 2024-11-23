# A2-RapidMiner-rename

AirBnb is world leader in providing accommodations to people (customers) around the globe who want to rent the spaces 
for several purposes such as vacations, work, travel etc. The firm also caters to people (property hosts) by helping them 
post their accommodations’ advertisements in particular locations around the world using the houses and locality’s 
images, descriptions about property, neighbourhood, people it can accommodate etc. Airbnb generates its earnings by 
taking commissions on the successful bookings that customers are able to make. It operates as an easy-to-use digital 
platform that links tourists with private property hosts.  

Executive Problem Statement: 

We are currently looking at Sydney (Australia) based listings. The company has provided us with 2 datasets that include 
approximately 37,000 rental listings and 5,49,000 associated customer reviews. Every day there are new hosts 
registering their properties along with new customers who are making bookings on their platform. Airbnb has approached 
us with a request to develop an advanced and effective method which would enable them to analyse and predict 
customer feedback about their stays particularly at their Sydney rental properties. It is extremely hard for the firm to 
assess each customer review and plan course of action on its basis.  

Executive Solution Statement: 

We are provided with negative and positive words which the hosts may use in their property descriptions, or the 
customers may use in their stay’s reviews. Based on those words, we have devised a method to make use of hosts’ 
property descriptions and customers’ reviews to provide deductions. After carefully working around the data provided to 
us, we were able to derive a positive correlation between property hosts’ description and customer reviews. It came to 
light that hosts who wrote more positive and well-oriented property descriptions (Figure 1) received more positive reviews 
from their guests (Figure 2). Key factors (Figure 3.1) such as accommodates, bathrooms, bedrooms, price, host 
responsiveness, cleanliness, location, accuracy, check-in, value, reviews per month and security deposit emerged as 
influential factors impacting review scores. For identifying meaningful property segments in the data, we made use of the 
influencing factors (Figure 4.2) such as accommodates, bathrooms, bedrooms, accuracy, check-in, cleanliness, host 
responsiveness, location, and value. 

After performing the predictive modelling and applying techniques to increase their efficiency, we would recommend the 
following: (1) Linear Regression Model with the least root mean squared error of 4.534 +/- 0.000 and squared corelation 
of 0.746 (Figure 6). (2) Improved Data Clustering Model (k-Means) with clustering k = 5, Davies Bouldin = 1.220 and 
Example distribution = 0.319 (Figure 10,11). 

After following our recommendations, Airbnb would be able to efficiently identify the dynamics of customer feedback, host 
property descriptions, property segmentation in their Sydney market. Insights generated using our methods would 
empower the hosts and Airbnb to optimise property descriptions, predict review ratings for new listings and modifying 
their offerings to cater to different guest preferences. Ultimately it would provide an excellent customer experience while 
supporting the host. Bringing in more users (hosts and customers) and in-turn revenue, this would further strengthen 
Airbnb’s position in the competitive domestic tourism sector. 

Limitation of our Linear Regression model is that it may suffer from multicollinearity wherein some independent factors 
might be highly correlated with each other. Limitation of our k-Means Data Clustering model is that it requires us to input 
the number of clusters beforehand and it is also sensitive towards outliers. 
