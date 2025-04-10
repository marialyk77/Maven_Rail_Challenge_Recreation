# British Railway Performance Analysis

## Overview

This report provides a detailed analysis of the UK railway system, focusing on operational performance, passenger behavior, and the financial impact of disruptions. The aim is to offer actionable insights that can help improve service reliability, optimize operations, and enhance the customer experience.

## Purpose

The purpose of this report is to:
- Examine key trends in disruptions, delays, and cancellations.
- Analyze passenger behavior patterns, including booking lead times, journey durations, and payment methods.
- Assess the impact of operational issues on revenue.
- Provide recommendations to improve service reliability, reduce delays, and optimize ticket sales.

## Key Insights

- **Peak Travel Periods:**
   - March recorded the highest number of journeys (8,117), closely followed by January (8,111).
   - March also led in cancellations, delays, and refunded passengers, while January saw the highest revenue and the largest refund amounts.
   - The **top route in total journeys** is Manchester Piccadilly to Liverpool Lime Street, while the **top revenue-generating route** is London Kings Cross to York.

- **Delays and Cancellations:**
   - A significant number of journeys experience delays beyond 15 minutes.
   - Refund percentages are highest for moderate delays (1-30 minutes), peaking at 60.7% for delays of 1-5 minutes.
   - Interestingly, 12 passengers received refunds despite no recorded delays.
   - **Delay Causes:** Weather (1,372 instances) is the most frequent cause of delays, followed by signal failures (970) and staff shortages (809). Traffic, while rare, causes severe delays, with half of traffic-related delays lasting over 7 hours.
   - **Cancellations:** Signal failures are the leading cause of cancellations, followed by staff shortages and weather. March saw a sharp rise in cancellations (+14.6%).

- **Journey Durations:**
   - **First Class** passengers generally take longer journeys (average of 73.26 minutes) compared to Standard Class.
   - **Journey durations** tend to be more stable in the morning, midday, and evening, while the afternoon shows more variability. The shortest journeys tend to occur in the evening, with 50% lasting 60 minutes or less.

- **Ticket Purchase Behavior:**
   - Online ticket purchases peak in the morning (69.0%) and at night (35.1%), likely reflecting booking patterns before or after work hours.
   - Station ticket purchases peak in the afternoon (51.2%) and late at night (64.9%).
   - **Most common booking window:** 1-3 days before travel (14,395 journeys), followed closely by same-day bookings (14,092 journeys).
   - **Railcard holders** account for 33.9% of journeys, with non-Railcard holders making up the remaining 66.1%. This suggests that frequent travelers might not always rely on discounts.

- **Refunds and Cancellations:**
   - The route with the most cancellations is **Liverpool Lime Street to Birmingham New Street**.
   - **Routes with 100% delays:** Edinburgh Waverley to London Kings Cross, London Euston to York, and York to Wakefield.
   - **Highest refund amount:** £13,126 for the Liverpool Lime Street to London Euston route, with a delay rate of 71.1% and a cancellation rate of 9%.

## Methodology

- **Data Sources:** The data used for this analysis comes from the Maven Analytics Rail Challenge, which includes operational data from UK railways, passenger behavior, and revenue information.
- **Tools Used:** Microsoft Power BI was used for data visualization and analysis.
- **Assumptions:** A simulated 10% fare adjustment was applied to estimate revenue loss, and refund requests were based on average ticket prices (without confirmation of processing).

## Recommendations

- **Traffic Management:** Addressing traffic management can help reduce severe delays, particularly on routes where traffic-related disruptions are most impactful.
- **Staffing and Signal Reliability:** Enhancing staffing levels and improving signal infrastructure would help reduce delays and cancellations caused by weather, staff shortages, and signal failures.
- **Revenue Optimization:** Exploring fare adjustments or offering better-targeted promotions for off-peak hours could help optimize revenue, particularly for routes that experience high variability in journey times.

## Data Sources

The data for this analysis was sourced from the following:

1. **Maven Analytics Rail Challenge:**  
   The primary dataset used for this analysis was sourced from the [Maven Analytics Rail Challenge](https://mavenanalytics.io/challenges/maven-rail-challenge/08941141-d23f-4cc9-93a3-4c25ed06e1c3).

## How to Use This Report

1. **Review Key Insights:** The report provides a comprehensive overview of operational performance, delays, and cancellations.
2. **Explore Interactive Visualizations:** Power BI visualizations allow for interactive exploration of data, enabling you to filter by routes, time periods, and more.
3. **Decision Support:** The insights provided are aimed at helping stakeholders make informed decisions to improve performance, reduce cancellations, and optimize passenger experience.



