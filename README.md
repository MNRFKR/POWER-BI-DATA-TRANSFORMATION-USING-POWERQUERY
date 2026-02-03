# POWER-BI-DATA-TRANSFORMATION-USING-POWERQUERY
NOTE : FINALISED FILE HAVE BEEN DELETED SO INCASE I UPLOADED SOME SCREENSHOTS AND A FINALISED VISUAL DATA LOOK WITH GRAPHICAL CHART SCREENSHOT
Step 1 – Remove unnecessary columns
I started with a messy HR dataset and dropped irrelevant fields to keep only useful employee information. This reduced clutter and made the dataset easier to manage.
Step 2 – Rename columns
I renamed raw column headers like Column2 and Column3 into clear names such as FirstName and LastName. This improved readability and consistency across the model.
Step 3 – Handle missing values
I identified nulls in fields like ExitDate and replaced or removed them where needed. This ensured calculations and visuals wouldn’t break due to blanks.
Step 4 – Detect & handle duplicates
I checked for duplicate employee records and removed them. This kept the dataset accurate and prevented inflated counts in visuals.
Step 5 – Change datatypes
I converted columns into correct types: dates into Date, scores into Numeric, and names into Text. This allowed proper calculations like satisfaction averages and time‑based trends.
Step 6 – Split / Merge columns
I split combined fields (like Start/Date) into separate columns and merged where necessary. This gave cleaner structure and made transformations easier.
Step 7 – Create conditional columns
I added logic‑based fields such as SalaryBand from PayZone. These new columns categorized employees into Low, Medium, and High bands for analysis.
Step 8 – Apply changes & load model
I clicked Close & Apply to lock in all transformations. The cleaned dataset was loaded into the Power BI model, ready for reporting.
Step 9 – Build visuals
I created three visuals: a pie chart for PayZone distribution, a bar chart for Satisfaction Score by DepartmentType, and a line chart showing employee growth by year. These gave clear insights into workforce patterns.
