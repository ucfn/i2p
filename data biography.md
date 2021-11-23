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

It contains ‘host_picture_url’ leading to hosts’ pictures, which support analysis of whether there is racial preference or discrimination when guests select hosts [2]. ‘Latitude’ and ‘longitude’ contain location of each listing. Airbnb location can be applied to analysis as both dependent variable [7] and independent variable [8]. By categorizing ‘room_type’, ‘accommodates’, ‘bathrooms’ and ‘bedrooms’ as ‘Listing Characteristics’; ‘host_is_superhost’ and ‘host_total_listings_count’ as ’Host Characteristics’, together with ‘instant_bookable’, ‘amenities’, ‘number_of_reviews’, all the above can be used as independent variables to analyze their correlation with ‘price’ [8]. ‘Description’ contains key words like ‘distance’, which can be detected with text mining [13] and applied to analysis of correlation between ‘distance to public transportation’ and ‘price’.

---

### 5. To what extent is the data 'complete'?

‘Describing’ this dataset in python, it’s not hard to notice that some variables have much lower ‘Non-Null Count’ (e.g. ‘host_about’ has only 42494 ‘Non-Null Count’ in 74187 listings). In other words, these variables contain large proportion of missing values, for which we should look closely into and be careful when using them in analyses. For example, ‘host_about’ might contain information which can be applied to text mining methodology to analyze the correlation between key words in ‘host_about’ and variable of ‘price’. But even if we really want to look into that, it is crucial for us data analysts to think about the probable reasons for missing values. Some possible explanations behind missing values in ‘host_about’ can be raised --is that hosts hiding something (e.g. disability, race, sexual orientation) from guests or Airbnb in order to get rid of segregation impeding their renting, or, Airbnb hiding true data from data analysts advocating equality in order not to be condemned for exacerbating social inequality (e.g. 80% of the hosts are white) [5].
Therefore, we should be very careful and critical with incomplete data. It is a pre-requisite to ask ourselves would we draw a fair conclusion or just a biased one in use of incomplete data, why or why not, rather than using variables blindly by simply dropping the nulls, regardless of the potential effect (e.g. unreliable/ unconvincing results) that might arise.

---

### 6. What kinds of analysis would this support?

Firstly, this data combined with data of house price and rental rate can be applied to analysis of the impact of home-sharing on residential house prices and rents [1, 11, 15]. Secondly, using data ‘host_picture_url’ in listings combined with bookings/ estimated bookings as an alternative of text mining [13] to distinguish races, we can analyze whether Airbnb aggravated racial discrimination [2]. We can also analyze whether consumers pick more trustworthy hosts from their photos [6]. Thirdly, location data (longitude and latitude) can support analysis of Airbnb locations’ spatial distribution patterns [16, 17, 18] and its determinants [7], and can also be used as independent variable combined with other independent variables (e.g. room characteristic, host characteristic) to support analysis of determinants of Airbnb pricing [8]. Location of the data combined with location data of hotels can be applied to analysis of correlation of spatial distribution patterns between Airbnb listings and hotels [10].

---

### 7. Which of the uses presented in Q.6 are _ethical_?

In conclusion, analyses of the impact of Airbnb home-sharing on housing markets, the impact of Airbnb on gentrification, the impact of Airbnb on racial discrimination, and supervision on Airbnb (short-term rentals (STRs)) are ethical.
Firstly, Barron et al. (2018), Horn & Merante (2017), Shabrina et al. (2019), and Wachsmuth et al. (2018) discovered positive correlation between Airbnb listings and rents.
Secondly, Airbnb-induced growing disparity between short-term and long-term rents is driving continuous housing loss in long-term rental market and gentrification [17, 18]. Shabrina et al. (2017) conducted spatiotemporal analysis and quantitively discovered that ‘Airbnb tends to be located in or adjacent to areas with rapid gentrification’. Cocola-Gant and Gago (2019) conducted informal interviews with residents, shop keepers, real estate agents, landlords and STR property managers, qualitatively related Airbnb to an impulse on gentrification.
Thirdly, on Airbnb white neighborhoods earn more than non-white neighborhoods, and in black neighborhoods white hosts earn more than black hosts [17]. Cheng and Foley (2018) analyzed whether there is racial discrimination when guests select hosts.
Fourthly, Cox and Slee (2016) blamed Airbnb for not interfering hosts with multiple rooms, by showing data of listings before and after Airbnb’s public data release as proof that Airbnb was covering the actual number and percentage by artificially deleting listings from its website right before releasing open data to the public. Cocola-Gant and Gago (2019) even aggressively defined Airbnb as platform for ‘buy-to-let investment’, leading to problems of ‘increasing insecurity and displacement concerns’ for tenants. 
These analyses, overlapping and interrelated, are ethical. Although their entry points seemingly vary --higher house prices and rents, expanding and accelerating gentrification, exacerbating racial discrimination, lacking supervision, the underlying further attempt is the same --focusing on low-income groups [9, 14] and racial stereotype [2], advocating social justice and using valid data to analyze whether Airbnb intensified social inequality and segregation. With academic foundation built up, attention from public, urban planners and government will be raised, laws and regulations on STRs will be refined, and social justice will be enhanced.


## Bibliography

[1] Barron, K., E. Kung, and D. Proserpio. 2018. “The Sharing Economy and Housing Affordability: Evidence from Airbnb.”

[2] Cheng, M., and C. Foley. 2018. “The Sharing Economy and Digital Discrimination: The Case of Airbnb.” International Journal of Hospitality Management 70: 95–98.
[3] Cocola-Gant, A., and A. Gago. 2019. “Airbnb, Buy-to-Let Investment and Tourism-Driven Displacement: A Case Study in Lisbon.” Environment and Planning A: Economy and Space 0 (0): 1–18.
[4] Cox, M., and T. Slee. 2016. “How Airbnb’s Data Hid the Facts in New York City.” Inside Airbnb.
[5] D’Ignazio, C., & Klein, L. 2018. Chapter 6: The Numbers Don’t Speak for Themselves. Data Feminism.
[6] Ert, E., A. Fleischer, and N. Magen. 2016. “Trust and Reputation in the Sharing Economy: The Role of Personal Photos in Airbnb.” Tourism Management, 55: 62–63.
[7] Eugenio-Martin, J. L., J. M. Cazorla-Artiles, and C. Gonzàlez-Martel. 2019. “On the Determinants of Airbnb Location and Its Spatial Distribution.” Tourism Economics 25 (8): 1224–4.
[8] Gibbs, C., D. Guttentag, U. Gretzel, J. Morton, and A. Goodwill. 2017. “Pricing in the Sharing Economy: A Hedonic Pricing Model Applied to Airbnb Listings.” Journal of Travel & Tourism Marketing 35 (1): 46–56. 
[9] Gurran, N., and P. Phibbs. 2017. “When Tourists Move in: How Should Urban Planners Respond to Airbnb?” Journal of the American Planning Association 83 (1): 80–92.
[10] Gutiérrez, J., J. C. Garcı́a-Palomares, G. Romanillos, and M. H. Salas-Olmedo. 2017. “The Eruption of Airbnb in Tourist Cities: Comparing Spatial Patterns of Hotels and Peer-to-Peer Accommodation in Barcelona.” Tourism Management 62: 278–91.
[11] Horn, K., and M. Merante. 2017. “Is Home Sharing Driving up Rents? Evidence from Airbnb in Boston.” Journal of Housing Economics 38: 14–24.
[12] Inside Airbnb. 2021. ‘Disclaimers, The Occupancy Model’ (WWW) (http://insideairbnb.com/; 19 November 2021)
[13] Lavin, Matthew J. 2019. “Analyzing Documents with Tf-Idf.” The Programming Historian, no. 8.
[14] Lee, D. 2016. “How Airbnb Short-Term Rentals Exacerbate Los Angeles’s Affordable Housing Crisis: Analysis and Policy Recommendations.” Harvard Law & Policy Review 10 (1): 229–54.
[15] Shabrina, Z., E. Arcaute, and M. Batty. 2019. “Airbnb’s Disruption of the Housing Structure in London.” ArXiv Prepring. University College London.
[16] Shabrina, Z., Y. Zhang, E. Arcaute, and M. Batty. 2017. “Beyond Informality: The Rise of Peer-to-Peer (P2p) Renting.” CASA Working Paper 209. University College London.
[17] Wachsmuth, D., D. Chaney, D. Kerrigan, A. Shillolo, and R. Basalaev-Binder. 2018. “The High Cost of Short-Term Rentals in New York City.” McGill University.
[18] Wachsmuth, D., and A. Weisler. 2018. “Airbnb and the Rent Gap: Gentrification Through the Sharing Economy.” Environment and Planning A: Economy and Space 50 (6): 1147–70.


## Appendix 
