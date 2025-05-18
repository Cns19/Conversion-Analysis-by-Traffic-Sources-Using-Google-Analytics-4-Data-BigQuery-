# Conversion Analysis by Traffic Sources Using Google Analytics 4 Data (BigQuery)

**Goal:** To measure the impact of different traffic sources and campaigns on purchases by querying GA4 data with BigQuery.

**Method and Tools:** Used SQL in BigQuery to analyze session, user, and event data. Focused on 4 key events from 2021 (session_start, add_to_cart, begin_checkout, purchase). Created date from event_timestamp. Built conversion steps like visit_to_cart, visit_to_checkout, and visit_to_purchase based on users and sessions. Separated users with the same session ID to get the correct conversion rates.

**Result:** Created a conversion funnel by source and campaign. For example, the "google / organic" channel had a 3.6% add-to-cart rate but only a 0.4% purchase rate. The funnel showed a big drop at the checkout step.

**Skills Gained:** Understanding GA4 data structure, building conversion paths with SQL, linking users and sessions, and measuring channel performance.


![image](https://github.com/user-attachments/assets/58f9ca7a-1384-429a-905f-5341b47c7e55)
