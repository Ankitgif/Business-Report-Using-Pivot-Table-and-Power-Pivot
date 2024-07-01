# Business-Report-Using-Pivot-Table-and-Power-Pivot
Creating Business report using Pivot Table and Power Pivot

The goal of this task is to recreate the reports that have been created using PowerPivot and DAX measures. To accomplish this, you have been provided with two CSV files: "fact_bookings" and "dim_properties".

1.	fact bookings: The "fact_bookings" file contains various columns, including booking_id, property_id, check_in_date, month, week_no, booking_pIatform, ratings_given, booking_status, successfuI_bookings, and capacity. This file contains details about every booking made for a specific property/hotel.

2.	dim_properties: The "dim properties" file contains additional details about each property.


To complete this assignment, please follow the steps below:

1.	Open a new Excel file, use the "From Text/CSV" option to load the two provided CSV files directly into the Data Model, and select the option to create only connections, as shown in the lectures.

2.	Next, open "Power Pivot for Excel", switch to the Diagram view, and establish a relationship between the two tables by connecting the "property_id" column in the "dim_properties" table to the "property id" column in the "fact_bookings" table.
 
3.	To proceed further, create a Pivot Table and ensure that you choose the ”From Data Model” option. Construct the PivotTable as per the format presented in the "report1.pdf' and "report2.pdf' files. During the process, generate the DAX measures as per the specifications provided. You will primarily use the SUM(), COUNT(), and AVERAGE() functions to create the DAX measures.


Once the reports are generated, answer the following questions:

1.	Among properties falling in the Business category, which property generated the highest revenue in the month of June as compared to others?
    Insight: Insight  : In category Business, Atliq Exotica generated highest revenue in the month of June as compared to others.

2.	For Atliq Grands in the week of'W 27’, which booking platform was the most effective in generating revenue?
    Insight  : For Atliq Grands in week 27 booking platform makeyourtrip was the most effective in generating the revenue.

3.	What was the average rating of ’Atliq Blu’ in the month of July?
    Insight : Average rating of Atliq Blu in the month of July was 4.58
