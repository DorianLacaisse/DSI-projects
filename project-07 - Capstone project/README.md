# Capstone project

Do you know someone who would like to open a small business but have no idea where his idea would reach the largest number of customers?

Starting with the idea that the small business is a restaurant, I am trying to build a tool that will assess the likelihood of success for opening a restaurant.  
My case being in London, the idea is to return, in function of diverse features such as _Type of cuisine, location in London, price range_ , an estimation of the success in a scale of 1 (very low) to 5 (very high).

To that extent, I am gathering data from different source to create a dataset that will contain all the necessary feature to assess the position of a restaurant at its location.

Features will include:

__Demographic data__:  
- Population density per zone. (dataset: gov.uk)  
- Labour working density per zone. (dataset: gov.uk)
- Population age density per zone (dataset: gov.uk)
- Unemployment rate per zone (dataset: gov.uk)

__Competitors data__:
- Same cuisine type restaurants density per zone + performance (Just-eat, Zomato, TripAdvisor)
- Other cuisine types restaurants density per zone + performance (Just-eat, Zomato, TripAdvisor)

__Visibility__:
- Accessibility (dataset: gov.uk)
- Attraction in the area

__Financial Data__:
- Average household income per area ( data.gov)
- Housing value (data.gov)

__Calculated features__:
- Number of restaurants in a 200 m radius plus cluster belonging
- Area covered without competitors
- Estimated profit


On that extent, I have created folders that relates my chronological progress.

**Part 1.**  
Introductory slides

**Part 2**
- Getting data from food take-away website just-eat.com.  
- Exploratory Analysis, cleaning and compilation of the data from just-eat.com + Demographic and Financial data.

**Part 3**
- Getting restaurant data from website zomato.com.  
- Exploratory Analysis, cleaning and compilation of the Zomato data.
- Creation of a categorisation model based on estimated profit.
- First try on fitting classification model over Zomato data.

**Part 4**
- Optimising actual features.  
- Carrying out dimensionality reduction
- Fitting new models with parameters optimisation.
- Validation of the best classification model

**Ongoing**

- Getting TripAdvisor restaurants information to validate categorisation model.
- Business process to eventually deploy a model in a production environment
