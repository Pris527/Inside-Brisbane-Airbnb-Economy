# Inside-Brisbane-Airbnb-Economy
**Demystifying Brisbane's Airbnb market: A data visualization project analyzing price, occupancy, and host performance to reveal optimal value across neighbourhoods.**

**Overview**
Before relocating to Brisbane, I wanted to understand how the Airbnb market worked across the city — which neighbourhoods were affordable, which generated high revenue, how room types differed, and what occupancy looked like throughout the year. 
This personal question became the foundation of a full analytical project: a Tableau dashboard revealing how **price, occupancy**, and **host performance** vary across Brisbane. Thus, the main question this project seeks to answer is; 

**How do pricing behaviour, listing distribution, and occupancy trends vary across Brisbane’s Airbnb market — and what can this tell hosts, investors, and future residents about short-term rental dynamics**

To answer this question, I began by doing an initial exploration on the different room types in Brisbane and their average prices(see image below)

![Inside-Brisbane-Airbnb-Economy/Avg_Price_Roomtype.jpeg]

**Objective**

Specifically, this project aims to explore how Airbnb market characteristics differ across Brisbane’s neighbourhoods and room types, and to uncover insights relevant for:

. Prospective hosts

. Property investors

. Travellers looking for optimal value

. Analysts examining housing & tourism dynamics

. The dashboard provides a clear picture of how **price, occupancy**, and **revenue potential** vary across the city.


**Tableau Public Dashboard:**[https://public.tableau.com/app/profile/presca.evans/viz/AirbnbBrisbanedataset/Dashboard1]

**Tools Used**
**Tableau Public**

. Data cleaning & preparation

. Calculated fields (occupancy rate, average revenue, KPIs)

. Interactive filtering

. Desktop  & mobile layout optimisation

Since this dataset was lightweight and clean, the entire workflow was completed within Tableau.


**Methodology**

Although this project was completed fully in Tableau, the workflow followed a structured analytical process:

1. **Data Import & Initial Review**

. Loaded Brisbane Airbnb dataset into Tableau Public

. Inspected variable quality (e.g., price fields, host counts, occupancy proxies)

2. **Data Cleaning in Tableau**

. Removed incomplete or unusable records

. Standardised neighbourhood names

. Created calculated fields:
    . Monthly revenue

    . Occupancy rates

    . KPI metrics

3. **Visual Development**

. Built multiple exploratory sheets:

    . Price by room type

    . Listings by neighbourhood

    . Revenue and price over time (dual-axis)

    . Occupancy vs. price scatter plot

. Added filters for dynamic exploration (Neighbourhood, Room Type)


4. **Dashboard Assembly**

. Applied a consistent design style

. Added KPIs, colour rules, and mobile responsiveness

. Wrote tooltips that explain data context


**Dashboard Features**

. **KPI Summary:**
Total Listings | Average Price | Average Monthly Revenue | Total Hosts

. **Interactive Filters:**
Neighbourhood • Room Type • Price Range

. **Visuals Included:**
    . Average price by room type

    . Listing distribution by neighbourhood

    . Monthly revenue & pricing trends

    . Occupancy vs price scatter plot


**Key Insights and Visualisation**

**1. Room Type Pricing & Demand**

Entire homes and private rooms dominate the market, but their pricing differs substantially.
Some neighbourhoods show premium pricing with only moderate occupancy, suggesting competition or oversupply.


**2. Neighbourhood Variation**

A clear divide exists between inner-city suburbs and outer suburbs:

. Central areas attract higher listing density

. Some fringe suburbs offer high value-for-money with competitive occupancy

The neighbourhood patterns reflect socioeconomic diversity, tourism access, and local housing dynamics.

**3. Revenue & Seasonal Patterns**

The dual-axis chart reveals noticeable trends:

. Monthly revenue fluctuates more sharply than price

. Demand appears to shift with seasonal and event-based activity

**4. Pricing vs Occupancy Relationship**

. Scatter plot analysis shows that higher price ≠ higher occupancy.
. Optimal pricing requires balancing host strategy with neighbourhood competitiveness.
. Mid-priced listings often perform more consistently. This insight can support host pricing strategies.


**Future Enhancements**

To strengthen the analytical depth of this project, future improvements may include:

1. **Expand Analysis Using Listing Amenities**
Airbnb amenities (e.g., Wi-Fi, parking, air conditioning, pools) play a major role in pricing and occupancy.
A future version of this dashboard will include:

-  Amenity frequency for each neighbourhood

-  Relationship between specific amenities and higher prices

-  Amenity-based clustering of high-performing listings

-  Visual filtering by amenities (e.g., “Show me all listings with free parking”)

This would allow prospective hosts or investors to understand which amenities yield the strongest returns in Brisbane.

2. **Improve Data Quality for Hotels & Non-Airbnb Accommodation**
The current dataset shows limited coverage of hotel rooms, which underrepresents the full short-stay accommodation market.
Future improvements include:

. Supplementing Airbnb data with official hotel capacity datasets (ABS, tourism reports, Queensland government open data)

. Comparing Airbnb performance to nearby hotels

    . Enhancing market-level insights, such as:

    . Price comparison (Airbnb vs hotels)

    . Occupancy comparison

    . Neighbourhoods where hotels dominate the supply

This will make the dashboard more accurate and useful for analysts evaluating competition in the short-stay rental market.

3. **Seasonality & Trend Decomposition**
Using Tableau forecasting tools to breakdown: 

. Peak demand periods

. Event-driven surges

. Seasonal low-points

4. **Neighbourhood Profiles**
Add a short narrative explaining neighbourhood characteristics (proximity to CBD, beaches, universities) to help map Airbnb performance to real-world context.

5. **Host Strategy Insights**
Create a second dashboard page tailored to prospective hosts, offering:

. Recommended neighbourhoods

. Price bands with consistently strong occupancy

. Amenity combinations associated with above-average performance

Apart from these, other suggestions for future enhancements may include; 
.  Adding neighbourhood-level socio-economic context (housing pressure, visitor demand, commuting patterns)
.  Adding a map view for listing density if coordinates become available. 

These enhancements would deepen the interpretive value while matching the progression of my analytics skill set.


**Takeaway**

This project demonstrates my ability to translate a real-world question into an analytical framework using Tableau.

It reflects a blend of:

    . Social science research thinking

    . Analytical reasoning

    . Visual communication

    . Practical interpretation for business or policy contexts

Whether used by a host evaluating pricing strategy or a data team assessing housing trends, the dashboard brings clarity to Brisbane’s Airbnb activity.

