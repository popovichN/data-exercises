# Data exercises

**FAA Wildlife Strike Database: [http://wildlife.faa.gov/database.aspx](http://wildlife.faa.gov/database.aspx)**

Once on the site, select State == NY and limit the date range to between 1/1/2014 and 12/31/2014 -> Submit -> Export to Excel (this will download an excel file, which you should open in Sheets)
(If that doesn’t work copy [this spreadsheet](https://docs.google.com/spreadsheets/d/1PCgwbF190Hl0V_CQPhciBXKT1fSHN22pfqXvk1WQIVo/edit?usp=sharing)) 

* How many (reported) times did an aircraft strike wildlife in New York in 2014?
* What species was associated with the most aircraft strikes in 2014?
* Which was associated with the most “S” class damage? 
* Which airline hit the most wildlife?
* Were more robins killed by aircraft at JFK or La Guardia? How many more?

**Bureau of Labor Statistics (BLS) data on occupation, gender, and pay: [http://www.bls.gov/cps/cpsaat39.htm](http://www.bls.gov/cps/cpsaat39.htm)**

There’s no way to download this dataset on this page (darn!), but luckily it’s not very difficult to copy and paste the table to a spreadsheet. To save you the hassle, I’ve done this ahead of time. Go [here](https://docs.google.com/spreadsheets/d/1Jp8QMON6JbkvX22SHDFYZeYCjsX2ILoZx5XMPCntag0/edit?usp=sharing), copy the spreadsheet and do all your calculations in your new copy. 

* What is the best-paying job, at the median … 
  * Overall? 
  * For men?
  * For women?
* What occupation (with pay data for both men and women) has the largest gender pay gap …
  * By total dollars?
  * By percentage?
*In how many of the listed occupations do women earn more than men? 

**NYC data: toilets in public parks: [https://data.cityofnewyork.us/Recreation/Directory-Of-Toilets-In-Public-Parks/hjae-yuav](https://data.cityofnewyork.us/Recreation/Directory-Of-Toilets-In-Public-Parks/hjae-yuav)**

* How many WCs are there in public parks in…
  * Manhattan? 
  * Brooklyn? 
  * Queens?
* How many in each borough are handicap accessible? And what percent of the total in each borough do handicap-accessible WCs make up?
* Create new column named “full_address” at the end of the main sheet: combine “location” address field + “borough” field to get the full address. 

**California arrest data: [http://openjustice.doj.ca.gov/data.html](http://openjustice.doj.ca.gov/data.html)**

Download “Arrest Rate Summary Part 1 - CSV.” (See the readme file for notes on how the data was collected.)

* For each year (1980-2013), what was the race/ethnicity of people arrested in California as a percent of total arrests?
Hint: you will need to use filters on your pivot table to make sure you’re not double-counting combined categories along with specific categories.
* For each year, what percent of the total population in California did each race/ethnic group make up? 
