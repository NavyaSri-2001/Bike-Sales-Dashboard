# Bike-Sales-Dashboard
Overview
The purpose of this repository is to look at what factors may go in to determining whether or not a customer opts to purchase a bike. The dashboard displayed below is interactive upon downloading the Bike Buyers Data Excel Sheet in the main branch.
 

Data Preprocessing
⦁	Duplicate rows were removed
⦁	Column values were adjusted for the visualizations
⦁	Marital Status: M/S --> Married/Single
⦁	Gender: M/F --> Male/Female
⦁	Income decimals removed for a more polished looking income number
⦁	New column created for Age Brackets, using a nested IF statement
⦁	Varying individual ages with a large range --> 3 age group categories (Young, Middle Aged, Older)
⦁	Reformatted the Commute Distance Column Values for sequential ordering in the visualizations
⦁	"10+ Miles" --> "More than 10 Miles"	

Results
Original Dashboard Results

 
The average income was higher for males than it was for females for both customers who purchased bikes, and those who did not.

 
Adults ages 31-54 purchased more bikes than those both younger and older.

 

More customers purchased a bike when they had a commute of 1 mile or less. However, those who opted to not purchase a bike also had the highest number in the 0-1 mile commute distance. Due to the spike in bike purchases from customers who had a daily commute of 2-5 miles, it's difficult to determine whether or not commute distance was a big contributing factor for these purchases.
