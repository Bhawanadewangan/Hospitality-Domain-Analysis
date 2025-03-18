### AtliQ Hospitality Analysis

#### Problem Statement

AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights. Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historical data.

#### Task

•	Project Title: AtliQ Hospitality Revenue Analysis Dashboard 🏨
•	Project Statement: This project centers on the development of an intuitive revenue analysis dashboard tailored for AtliQ Grands, an esteemed player in the hospitality sector. The primary goal is to empower the revenue team with data-driven insights for more effective business analysis. 

#### Key Takeaways:
•	In this project, we explore critical business concepts within the hotel industry, including various pricing strategies such as:

•	1. Flat Pricing

•	2. Weekend/Weekday Pricing

•	3. Dynamic Pricing

#### Here's a quick glimpse of some noteworthy facts about AtliQ Grands:

➡️AtliQ Grands proudly stands as a five-star hotel chain with a presence in four bustling cities.

➡️Across these urban hubs, AtliQ Grands boasts a network of seven distinct properties, strategically situated to cater to diverse clientele.

➡️Within these upscale properties, guests are offered a choice of four room categories: Elite, Premium, Presidential, and Standard, ensuring a tailored experience for every visitor.

➡️To enhance guest convenience, AtliQ Grands offers reservations through six prominent booking platforms, optimizing accessibility and ease of booking.

#### Project Scope: My mission was clear - to harness the power of data and provide insights that would pave the way for smarter decision-making at AtliQ Grands. To achieve this, we leveraged several datasets:

dim_date - This table contains date-related information, such as dates, week numbers, and day types (weekend and weekday). We utilized this data to analyze booking trends over time.

dim_hotels - This table provided crucial details about the properties, including property ID, property name, category, and cities. It was essential for understanding the hotel chain's properties and their characteristics.

dim_rooms - This table included information about room IDs and room classes. We used this data to analyze which types of rooms were more popular or profitable.

fact_aggregated_bookings - This fact table contained data related to property ID, check-in dates, room categories, successful bookings, and capacity. It served as a crucial source for calculating key metrics related to bookings and occupancy.

#### Tools Used -
Power BI

#### Dashboard

<img width="627" alt="image" src="https://github.com/user-attachments/assets/f8c912b0-66f9-43de-ba91-ad63ccf19225" />


#### Most Important Metrics:

•	Our journey into revenue analysis covers essential metrics, including:

•	📌 RevPAR (Revenue per Available Room): A key indicator of hotel performance.

•	📌 Occupancy: Measuring room occupancy among all available rooms.

•	📌 ADR (Average Daily Rate): Calculating the average rate paid for rooms sold.

•	📌 DSRN (Daily Sellable Room Nights): Reflecting the rooms ready for sale.

•	📌 DBRN (Daily Booked Room Nights): Tracking rooms booked per night, including cancellations and no-shows.

•	📌 Cancellations: Analyzing customer cancellations, leading to a 40% refund.

•	📌 No Show: Identifying cases where customers neither canceled nor arrived.

•	📌 DURN (Daily Utilized Room Nights): Quantifying rooms utilized per night.


#### Key Revelations:

▶Total Revenue: A staggering 1.71 billion rupees! 💰

▶Highest Revenue City: Mumbai, contributing 40% of the total revenue.

▶Top-rated City: Delhi, boasting an impressive average rating of 3.8.

▶Luxury vs. Business: Luxury category reigns supreme, generating a whopping 1053 million rupees.

▶Star Performer: AtliQ Exotica property emerged as the hero, raking in a remarkable 320 million rupees in revenue.

▶Room Class Leader: Elite rooms were the preferred choice among guests, showcasing their popularity, which we identified using data from the dim_rooms table.

▶Platform Power: Makeyourtrip emerged as the revenue powerhouse among the booking platforms.

▶Hotel Performance: AtliQ Exotica led the pack with 320 million rupees in revenue, while AtliQ Seasons, identified from the dim_hotels table, held its ground at 66 million rupees.

▶RevPAR Showdown: AtliQ Exotica took the lead with an impressive 7.8k RevPAR, while AtliQ Grands followed closely at 6.5k.

▶ADR (Average Daily Rate): AtliQ Seasons triumphed with an ADR of 16.6k, whereas AtliQ Blu, also from the dim_hotels table, stood strong at 11.9k.


These insights are not just numbers; they are the roadmap to revitalizing AtliQ Grands' revenue strategy. With Mumbai as a revenue stronghold and Delhi as a top-rated city, targeted marketing efforts can be focused here. The popularity of Elite rooms suggests a need for tailored promotions, while Makeyourtrip's dominance points to a lucrative partnership opportunity.

AtliQ Exotica's stellar performance highlights the potential for replication across other properties, leveraging data from the fact_aggregated_bookings table. Moreover, optimizing ADR at AtliQ Blu can further boost revenue.

In conclusion, data intelligence has unlocked a world of possibilities for AtliQ Grands. By leveraging these insights, the hotel chain can regain its competitive edge and secure its position as a leader in the luxury/business hotels category.


