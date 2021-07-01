# leads_analysis
This is my first project in Data Analytics where I used Excel to clean the data and Tableau to visualize it. 

I decided to use Excel because my client sent me an Excel file and the dataset has 2000-3000 lines. 
My client asked me to do an analysis to see what months, days of the week, and times of day tended to have a higher frequency of web sourced leads.

He sent me an Excel Workbook with his Web Traffic and Opportunities from Google Analytics(Web Traffic_source).
I removed the phone number, name, e-mail, Campaign, and Destination URL to preserve the confidential information. 

Step 1: Cleansing - Delete all the columns or tabs that are not important for the analysis in Excel.

	1.1:Delete the Web Traffic Tab
	1.2:Delete the columns at the Leads Tab: Medium, Source, Campaign, Key Words, Landing Page, Conversion Page, Phone Number, Name and Email.

Step 2: Prepare the data with the usable formats(Date and Time).

Step 3: At the LinkLeadsQuotes tab: Use UNIQUE in the LEADID because there were multiple quotes to one lead. 

Step 4: At LinkLeadsQuotes_Leads tab: Use VLOOKUP to join two tabs(Leads and the LinkLeadsQuotes) matching the ID (LeadID and Unique ID).

Step 5: Divide the LinkLeadsQuotes_Leads into two tabs filtering by Lead type: webform(132 lines) and calls(356).

Step 6: Create three columns from the date such as month, day of the week, and time of the day. (Web Traffic_cleansing_sample) 

Step 7: Upload the Excel file in Tableau and create some graphs.(Tableau Graphs-Visualizations) 