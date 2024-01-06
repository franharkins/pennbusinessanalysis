Created by Fran Harkins

Goals: 
-Using websites API docs, access data set provided by data.pa.gov on active businesses. *COMPLETE
-Pull and Spot Check Data, generate pipeline function, join any other needed data onto set for context
-organize data via provided fields
-visualize findings in tableau dashboard

First Thoughts:

-API docs are fairly robust
Schema for dataset:
-business_name
-address_line1
-address_line2
-city
-state
-zip
-typeofbusinessregistration
-creationyear
-shortcountyname
-countycode
-geofence column

-With this current schema, difficult to determine change in number of businesses over time.
-No column or record of business being de-registered
-dataset maintainer notes that data lags due to legal reasons for listing/delisting businesses

Project Ideas:

-aggregate number of businesses by county, city, zip, typeofbusinessregistration could be interesting
-catolog aggregate values on a weekly basis to see if any changes in business totals over time, or any changes to split based on fields
-visualize trend of businesses over time for each field (primary field is county)
