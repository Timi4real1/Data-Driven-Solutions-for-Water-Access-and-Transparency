# Data-Driven-Solutions-for-Water-Access-and-Transparency

This Project is aimed at improving water access, optimizing resource allocation, and enhancing financial transparency. By leveraging AI, data analytics, and visualization tools, the project provides insights into infrastructure improvements, tracks funding usage, and ensures equitable water distribution. With an emphasis on community impact and accountability, this project empowers both policymakers and the public with real-time data to drive meaningful change.

![Project Overview](./Images/National_Pic_3.PNG)

## Project Overview

The analysis is centred on the following

- Monitoring project progress through interactive visualizations at national, provincial, and town levels.
- Ensuring financial accountability by tracking expenditures, comparing actual spending with the budget, and analyzing cost variations.
- Assessing impact by measuring improvements in water accessibility and estimating the number of beneficiaries.
- Support decision-making with data-driven insights that help prioritize interventions and optimize resource allocation.

## Database Structure

The project uses the following tables:

- **`queue_composition`**: Records the percentage of males, females, or children present in the queue during each site visit.
- **`visits`**: Logs water source visits, including queue times, assigned personnel, and the date and time of each visit.
- **`water_source`**: Stores details about the source type and the population it serves.
- **`well_pollution`**: Records contamination levels in well water.
- **`project_progress`**: Tracks improvement efforts, their status, and related comments.
- **`infrastructure_cost`**: Contains details on the estimated cost of each improvement.
- **`vendors`**: Stores information about vendors contracted to implement improvements, including company name and type.
- **`location`**: Contains geographic data such as town, province, and address.
