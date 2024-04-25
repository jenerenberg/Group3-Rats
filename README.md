# Group 3
## NEW YORK CITY RATS

1. **BRIEF DESCRIPTION:**

  New York City is infamous for its abundance of rodents and other varying pests roaming the streets. In response, many of the city's residents and visitors will send in service requests through the 311 line in hopes of reducing the ever-boading presence of these rats. For this project, Group 3 asks the questions: **How do 311 rodent-related service requests vary between NYC boroughs? What months and seasons receive the most, as well as the least, rat service requests from the public?**

2. **EXECUTION EXPLANATION:**
- Requests by borough
  - Create row count variable
  - Group the rat_requests dataframe by 'borough' and sum the number of observations
  - Export rat_requests_bor to .csv
- Requests by Month
  - Convert 'created_date' to datetime variable
  - Pull the month out of 'created_date' to generate 'created_month' variable
  - Group the rat_requests dataframe by 'created_month' and sum the number of observations
  - Map each month number to its text form so they show up in datawrapper chart (e.g., 1:'Jan')
  - Export rat_requests_month_txt to .csv
- Requests by Season
  - 

4. **DESCRIBE EACH DATASET**
- 311 Rat Requests:
  -   Source: https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/about_data Office of Technology and Innovation (OTI)
  -   Updated: Daily
  -   Period: 2010 - Present
  -   Each row represents one 311 call requesting rat service


4. **GITSCRAPER EXPLANATION**

