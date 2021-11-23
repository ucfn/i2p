# Data Biography

### Declaration of Authorship

I, [Yujun Yuan], confirm that the work presented in this assessment is my own. Where information has been derived from other sources, I confirm that this has been indicated in the work.

[Yujun Yuan]

Date of signature: 26/11/2021
Assessment due date: 26/11/2021
Student Number: 20095783

_Please write your answer immediately below the level-3 headers and delete the guidance prior to submission._

---

### 1. Who collected the data?

Inside Airbnb collected the data from Airbnb web-site (the source). Therefore, Inside Airbnb should be critical about the data when conducting generating process.

---

### 2. Why did they collect it?

The data was collected for giving people quantitative cognition of the impacts of short-term rentals on housing and residential communities, to protect cities from the impacts [12]. So the data might include content like “how often an Airbnb listing is being rented out”, or “a listing's income”, for comparison with long-term rentals.

---

### 3. How was it collected?

The data was collected by combining directly collection with modification. For example, ‘neighbourhood’ for each listing is compiled by comparing the listing's geographic coordinates with a city's definition of neighbourhood [12]. A Review Rate of 50% is used to convert reviews to estimated bookings, after elaborate analysis comparing 50% with 72% and 30.5% [12]. Instead of directly pulling all data from Airbnb blindly, data might become more convincing with such modification [4].

---

### 4. What useful information does it contain?

It contains ‘host¬_picture_url’ leading to hosts’ pictures, which support analysis of whether there is racial preference or discrimination when guests select hosts [2]. ‘Latitude’ and ‘longitude’ contain location of each listing. Airbnb location can be applied to analysis as both dependent variable [7] and independent variable [8]. By categorizing ‘room_type’, ‘accommodates’, ‘bathrooms’ and ‘bedrooms’ as ‘Listing Characteristics’; ‘host_is_superhost’ and ‘host_total_listings_count’ as ’Host Characteristics’, together with ‘instant_bookable’, ‘amenities’, ‘number_of_reviews’, all the above can be used as independent variables to analyze their correlation with ‘price’ [8]. ‘Description’ contains key words like ‘distance’, which can be detected with text mining [13] and applied to analysis of correlation between ‘distance to public transportation’ and ‘price’.

---

### 5. To what extent is the data 'complete'?

‘Describing’ this dataset in python, it’s not hard to notice that some variables have much lower ‘Non-Null Count’ (e.g. ‘host_about’ has only 42494 ‘Non-Null Count’ in 74187 listings). In other words, these variables contain large proportion of missing values, for which we should look closely into and be careful when using them in analyses. For example, ‘host_about’ might contain information which can be applied to text mining methodology to analyze the correlation between key words in ‘host_about’ and variable of ‘price’. But even if we really want to look into that, it is crucial for us data analysts to think about the probable reasons for missing values. Some possible explanations behind missing values in ‘host_about’ can be raised --is that hosts hiding something (e.g. disability, race, sexual orientation) from guests or Airbnb in order to get rid of segregation impeding their renting, or, Airbnb hiding true data from data analysts advocating equality in order not to be condemned for exacerbating social inequality (e.g. 80% of the hosts are white) [5].
Therefore, we should be very careful and critical with incomplete data. It is a pre-requisite to ask ourselves would we draw a fair conclusion or just a biased one in use of incomplete data, why or why not, rather than using variables blindly by simply dropping the nulls, regardless of the potential effect (e.g. unreliable/ unconvincing results) that might arise.

---

### 6. What kinds of analysis would this support?

#### 200 words; 15 points; Given the issues discussed above, what kinds of analysis would this data support?

---

### 7. Which of the uses presented in Q.6 are _ethical_?

#### 350 words; 35 points; Which of the uses presented in Q.6 are ethical?  Justify the ethics of these analyses with reference to examples drawn from both your earlier answers and to the literature. 35 points

## Bibliography


## Appendix 
