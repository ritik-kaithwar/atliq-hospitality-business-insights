# AtliQ Hospitality — Business Insights Case Study 

## Project Highlights
- Built an end-to-end BI solution in Power BI for AtliQ Hospitality.  
- Analyzed 150K+ bookings across cities, properties, channels, and room types.  
- Identified ₹295M revenue risk due to cancellations and created a 90-day action roadmap.  
- Delivered an interactive dashboard and executive report to drive revenue, occupancy, and RevPAR growth.  
 
## Overview  
This project analyzes hotel booking data for AtliQ Hospitality using Power BI.  

The goal was to uncover:  
- Revenue drivers  
- Performance gaps  
- Risks such as cancellations  

and provide actionable recommendations to improve:  
- Realized revenue  
- RevPAR (Revenue per Available Room)  
- Occupancy rate  
- ADR (Average Daily Rate)  

This project demonstrates end-to-end analytics, data storytelling, and dashboarding — skills crucial for business data roles.  

---

## Objectives  
- Evaluate booking performance across cities, properties, channels, and room categories.  
- Identify key risks (cancellations, underperforming assets, capacity bottlenecks).  
- Build DAX-driven KPIs and insights for decision-making.  
- Deliver an interactive Power BI dashboard for business users.  

---

## Data & Model  
- dim_date → calendar table (day type, weekend flag, etc.)  
- dim_hotels → hotel metadata (property, city, category)  
- dim_rooms → room categories (type, class)  
- fact_bookings → booking-level data (booking_id, dates, platform, status, amounts etc.)  
- fact_aggregated_bookings → aggregated daily performance  

The data model was designed as a star schema for efficient reporting.  

---

## Tools & Technologies  
- Power BI (data modeling, dashboards)  
- DAX Studio (DMV queries, metadata extraction)  
- Excel (data exploration, validation)   

---

## Methodology  
1. **Data Understanding & Cleaning**  
   - Explored raw booking datasets and dimension tables.  
   - Validated data types, handled missing values, and ensured referential integrity across fact/dim tables.  

2. **Data Modeling**  
   - Designed a star schema (fact_bookings, fact_aggregated_bookings + dimensions).  
   - Established relationships in Power BI for efficient slicing/filtering.  

3. **DAX Measures & KPIs**  
   - Built calculated measures for revenue, RevPAR, ADR, occupancy, cancellations, etc.  
   - Designed contribution analysis across city, property, channel, and room category.  

4. **Exploratory Analysis**  
   - Identified cancellation patterns, capacity bottlenecks, low occupancy, premium vs. standard room performance.  
   - Compared weekday vs weekend demand to reveal utilization gaps.  

5. **Dashboard Development**  
   - Created interactive dashboards in Power BI with slicers and drill-throughs.  
   - Built views tailored for executives (high-level KPIs) and analysts (detailed insights).  

6. **Insights & Recommendations**  
   - Converted findings into actionable strategies with a 0–30, 30–60, and 60–90 day roadmap.  

---

## Metrics & KPIs  

### Core KPIs  
- Revenue  
- RevPAR (Revenue per Available Room)  
- ADR (Average Daily Rate)  
- Occupancy %  
- Cancellation %  
- Realization %  
- Average Rating  
- DSRN
- DBRN
- DURN
- Lead Time

### Contribution Analysis  
- Revenue by city, property, channel, room category  

---

## Key Insights  
1. Cancellations = major risk → ~25% cancellation rate caused ₹295M revenue loss.  
2. Occupancy drives weekly performance → Week 29 best, Week 26 worst.  
3. Property-level variation → Atliq Exotica (Mumbai) leads; Atliq Exotica (Hyderabad) drags.  
4. Premium-heavy portfolio → Luxury = 61.6% of revenue; standard rooms underperform.  
5. Channel mix → Offline generated ~3.7× Logtrip revenue.  
6. Weekend advantage → 46% bookings on weekends, higher occupancy vs weekdays.  
7. Reputation matters → Higher guest ratings correlated with higher occupancy.  

---

## Recommendations  

**0–30 Days**  
- Lead-time based refund tiers & deposits.  
- Renegotiate cancellation terms with OTAs.  
- Weekend-focused offers.  

**30–60 Days**  
- Expand premium suites; repackage standard rooms.  
- Protect Offline revenue, selectively grow Logtrip.  

**60–90 Days**  
- Address capacity bottlenecks (e.g., Atliq Grands Delhi).  
- Localized pricing tests in weak markets.  
- Guest rating uplift program.  

---

## Deliverables  
- Power BI Dashboard File & Images
- Final Business Report
- Data Model Image  
- Metadata (Excel): Data model documentation exported via DMV queries in DAX Studio  

---

## How to Run the Project  
1. Clone this repository.  
2. Open `powerbi/Atliq_Grand_Insights.pbix` in Power BI Desktop.  
3. Connect to CSVs in `/data`.  
4. Refresh data and interact with filters (city, property, week, channel, room).  

---

## Learnings  
- End-to-end business intelligence project lifecycle (data → model → insights → recommendations).  
- Deepened expertise in DAX, data modeling, and visualization best practices.  
- Practiced converting raw analysis into business strategy — a core skill for data analyst roles.  

---

## Author  
**Ritik Kaithwar**  

![Data_Model](images/overview)