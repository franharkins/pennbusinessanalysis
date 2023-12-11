Created by Fran Harkins

Goals: 
-Using websites API docs, access data set provided by data.pa.gov on active businesses.
-Pull and Spot Check Data, generate pipeline function, join any other needed data onto set for context
-organize data via provided fields
-visualize findings in tableau dashboard
-write update function to check for new data

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

-With this current schema, difficult to determine change in number of businesses over time.
-No column or record of business being de-registered
-dataset maintainer notes that data lags due to legal reasons for listing/delisting businesses

Project Ideas:

-aggregate number of businesses by county, city, zip, typeofbusinessregistration could be interesting
-catolog values as well as most recent file, update totals if values change or business name no longer exists
-visualize trend of businesses over time for each demographic

Pseudocode:

-Pull in Data using API
-Reference if any changes to data compared to previous Pull
    -document based off of business_name/address_line1? If address line or name changes how to account for it
    -storing totals in space that can be accessed by script
-update data viz to include new data

