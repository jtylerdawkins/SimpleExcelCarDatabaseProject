# SimpleExcelCarDatabaseProject
This is a simple Excel project where a CSV file of car data was used. Data in empty columns was filled out using existing data points such as the Car ID. Driver data and their respective mileage is displayed in a Pivot Table. Car mileage and age are visualized in a scatter chart with a trend line.

The Make, Model, and Manufacture Year were included in the Car ID as abbreviated values. In this project, I used features in Excel to show the information about the vehicles in more readable detail. 
Essentially, the Car ID is a cluster of information that is arranged uniformly across all vehicles in the database but using different values for different vehicles, and by deconstructing a Car ID we can gather necessary information. To deconstruct, we use the LEFT, MID, and RIGHT functions to look at specific characters of the ID to figure out what belongs in the other columns using the VLOOKUP function.

Excel features used in this project:<br>
•	Importing text file (CSV) into Excel.<br>
•	LEFT, MID, and RIGHT formulas to split cells.<br>
•	VLOOKUP function to find full names based on abbreviations.<br>
•	Relative and absolute cell references.<br>
•	IF conditional.<br>
•	CONCATENATE function to form new Car IDs.<br>
•	Pivot Table for Driver data and their respective Mileage.<br>
•	Scatter chart with trendline to display a car’s Mileage in relation to its Age.<br>
