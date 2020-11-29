# PythonAssignments
This program will extract and visualize rental data to accompany my Major studio 1 project based on trial rentals. This data is used as supporting evidence for the need to create a system wherein the apartments can be rented for a couple of days before signing the lease. The median rent burden makes the case that a large percentage of income is spent on rent and breaking lease is unlikely in the event that people moved into a non suitable apartment. 


## pseudocode for function:

asks user if they would like to view rent burden for either “a. sub-boroughs”, “b. boroughs” or “c. whole city”

a second input, 'user_input_year' asks the user to input the year of interest, ranging from 2008 to 2018.

function rentBurden:
if user inputs = ‘a’, chart with all the Sub borough data will be plotted on the specified user_input_year,

else if user inputs = ‘b’ chart with borough data will be plotted on the specified user_input_year

else if user inputs = ‘c’ chart with the whole city average will be plotted on the specified user_input_year

Additional repeat function to call the rentBurden() function again and view other charts.

if input in the repeat function does not match ‘y’ for yes or ’n’ for no, user input will be asked again.

if repeat is selected, whole process starts again, asking for user input for data type and year.




### data source:

http://app.coredata.nyc/?mlb=false&ntii=rent_burden_med&ntr=Sub-Borough%20Area&mz=12&vtl=https%3A%2F%2Fthefurmancenter.carto.com%2Fu%2Fnyufc%2Fapi%2Fv2%2Fviz%2F98d1f16e-95fd-4e52-a2b1-b7abaf634828%2Fviz.json&mln=true&mlp=true&mlat=40.761566&ptsb=&nty=2018&mb=roadmap&pf=%7B%22subsidies%22%3Atrue%7D&md=table&mlv=false&mlng=-73.924536&btl=Borough&atp=neighborhoods

