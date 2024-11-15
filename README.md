# **AIRBNB DASHBOARD OF NEWYORK-2019**

This repository contains a Power BI dashboard built to analyze the Airbnb New York City dataset for the year 2019. The dashboard provides insights into key metrics such as listing distribution, pricing trends, reviews, and host information across different neighborhoods and room types. This project is aimed at showcasing Airbnb trends in New York City, focusing on neighborhood group popularity, room type availability, and review patterns.

## Dataset Overview
**The dataset contains the following key fields:**

**1.Listing ID:** Unique identifier for each Airbnb listing. 

**2.Name:** Name/title of the listing.

**3.Host ID:** Identifier for the host managing the listing.

**4.Neighborhood Group:** Broad area where the listing is located (e.g., Manhattan, Brooklyn).

**5.Neighborhood:** Specific neighborhood within a neighborhood group.

**6.Latitude/Longitude:** Geographical location of the listing.

**7.Room Type:** Type of room offered (e.g., Entire home, Private room, Shared room).

**8.Price:** Nightly price for the listing.

**9.Minimum Nights:** Minimum number of nights required to book.

**10.Number of Reviews:** Total reviews for the listing.

**11.Last Review:** Date of the most recent review.

**12.Reviews per Month:** Average monthly reviews.

**13.Availability:** Total days available in a year.

![Screenshot 2024-11-15 170321](https://github.com/user-attachments/assets/0d557974-c656-4a09-aac2-3eae00fe6599)



# **Dashboard Overview:**

## Key Metrics Displayed:

1.Location Filter: Allows users to filter the dashboard by neighborhood.
2.Total Reviews: Displays the cumulative number of reviews across all listings in New York City.
3.Total Hosts: Shows the total number of unique hosts in the dataset.
4.Average Reviews by Month: Average number of reviews per listing, calculated monthly.
5.Total Neighborhoods: The total number of neighborhoods with active Airbnb listings.

### Main Visualizations:

**1.Total Listings by Neighborhood Groups:**
~A bar chart that highlights the total number of listings across neighborhood groups (Manhattan, Brooklyn, Queens, Bronx, and Staten Island). This visualization indicates which areas have the highest concentration of Airbnb listings.

**2.Availability of Room Types by Neighborhood Group:**
~A donut chart showing the distribution of room types (Entire home/apartment, Private room, Shared room) across neighborhood groups. This highlights which room type is most available in each neighborhood group.

**3.Average Price of Room Types by Neighborhood Groups:**
~A bar chart comparing the average price per night for different room types in each neighborhood group. This allows users to identify the most and least expensive areas and room types.

**4.Neighborhood Groups with Most and Least Listings:**
~two button that displays the neighborhood group with the highest and lowest number of listings,which are connected by two different bookmarks where all relations of those buttons can be seen.

**5.Comparison of Reviews: 2019 vs. 2018:**
~A line chart that shows the rate of reviews over months for 2018 and 2019, allowing for a comparison of year-over-year review growth.

**6.Top 10 Hosts by Total Reviews:**
~A bar chart listing the top 10 hosts based on the total number of reviews, helping identify the most popular hosts in terms of guest feedback.

**7.Listings Density Across New York City by Neighborhood Group and Neighborhood:**
~A map visualization displaying the geographical density of listings across New York City. Each neighborhood group is color-coded, showing areas with high listing density.

## Insights Derived:
**Neighborhood Popularity:** Manhattan and Brooklyn are the most popular neighborhood groups, having the highest number of listings.


![Screenshot 2024-11-15 170918](https://github.com/user-attachments/assets/136e8310-dfc6-484a-bfb5-d0111d1313bb)

**Room Type Distribution:** Entire homes/apartments are the most common room type, especially in Manhattan and Brooklyn.


![Screenshot 2024-11-15 192634](https://github.com/user-attachments/assets/a74b0f5d-81a0-4fae-82b9-945093a1c8ea)

**Price Variation:** Manhattan has the highest average price per night across room types, while the Bronx and Staten Island are generally more affordable.


![image](https://github.com/user-attachments/assets/ff36778d-b9f3-4d7f-82bb-edfb88e57e87)

**Review Trends:** A comparison of 2019 vs. 2018 review counts shows growth in guest engagement across the year.


![image](https://github.com/user-attachments/assets/90f6cef1-5ff1-4d10-b8b3-d94ba11445a5)

**Top Hosts:** The top hosts, such as Maya and Brooklyn & Breakfast -Len, receive the highest number of reviews, indicating a large customer base or frequent stays.


![image](https://github.com/user-attachments/assets/b92b48d2-cdef-43e3-bb1e-2b9ac54d5531)

**Listings Density:** The map shows the highest density of listings by the size og the bubbles.The five different colors of the bubble(legend) distiguishes five neighbourhood groups.

![Screenshot 2024-11-15 171023](https://github.com/user-attachments/assets/723716bc-26ec-4bb5-9493-0b79b898519e)

**Details of neighbourhood of highest listings density and lowest listings density:** The button named 'Manhattan' shows every relation of Manhattan with other factors which is marked as a bookmark.And the button named 'Staten Island' shows every relation of Staten Island with the other factors in the visualization.

![Screenshot 2024-11-15 193836](https://github.com/user-attachments/assets/f312935a-62c0-45ef-ac0b-2f85df4d9f3d)


**Slicers:** Two slicers where users can select the desired location and room types and see its relations.

![Screenshot 2024-11-15 194037](https://github.com/user-attachments/assets/0230b0b7-05ac-4b78-9194-f9403a6f6cdf)


![Screenshot 2024-11-15 194044](https://github.com/user-attachments/assets/51d8b445-3d7d-4b3e-97b7-9f5b4512dbc4)



## Technical Details:
**Tools Used:** Power BI for data visualization, DAX for calculations.

**Data Source:** Airbnb New York City dataset (2019).

**DAX Calculations:** Used for calculating metrics such as average price, total listings, availability percentages, and YOY review growth.

