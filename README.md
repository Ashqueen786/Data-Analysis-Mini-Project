Project Documentation  
Project Title: Audible Data Report
1. Project Overview 
This project analyzes a large dataset of audiobooks from Audible to uncover insights into audiobook trends, top authors, narrators, release patterns, and customer ratings. The goal is to clean and transform the raw data using Power Query, then build an interactive Power BI report that helps visualize key metrics like total books, average ratings, price distributions, and listening durations. Ultimately, the project aims to support data-driven decisions and provide a clear overview of the audiobook market.
 2. Tools Used 
-	Microsoft Excel 
-	Power Query
-	Power BI 
 3. Dataset 
-	Source: "C:\Users\USER\OneDrive\Desktop\Data Analytics\Assignments\Mini project\Datasets\Datasets\audible_uncleaned.csv"
-	Data contains:  Name, Author, Narrator, Time, Release Date, Star, Price
 4. Steps Followed 
-	Cleaned data in Excel & Power Query (Remove empty rows, Remove Duplicates, Fix data types, Trim & clean text columns, Split Columns, Merged Columns, Create Calculated Columns, Rename columns to clear names, Remove text prefixes (e.g., `Written by:`),Split `time` into numeric hours & minutes, Extract star rating & number of reviews, Convert `releasedate` to proper Date format, Ensure `price` is numeric.) 
-	Used Excel formulas for basic analysis 
-	Imported cleaned data into Power BI and create DAX for making report.
-	Built, dashboards using charts, slicers, and KPIs 
 5. Key Insights 
-	KPI card for Books YTD and Target
-	Card for Total Books 
-	Guage for Average Price
-	Guage for Total Listening Hours
-	Clustered Column Chart for Books and Released Date(month)
-	Donut Chart for Top 10 Authors and their Total books
-	Slicers for Year and Language
-	Pie Chart for Total books by Language vise
-	Stacked Area Chart for Total Duration by minutes(bins) of Count of Books
-	Stacked Bar Chart for Top 10 Authors with their Books and Average Price
-	Table for Top 20 Books and their important details.
-	Buttons for Next page and Home page.
 6. Screenshots 
 
 
 7. Files Included 
-	"C:\Users\USER\OneDrive\Desktop\Data Analytics\Assignments\Mini project\Datasets\Datasets\audible_uncleaned.csv"– Uncleaned data.
          -"C:\Users\USER\OneDrive\Desktop\Data Analytics\Assignments\Mini      project\Audible_Data.xlsx"– Cleaned data and basic analysis         
-	"C:\Users\USER\OneDrive\Desktop\Data Analytics\Assignments\Mini project\Audible_Report.pbix"– Power BI dashboard
-	‘README.md’ – Project description
 8. How to Use 
-	Open `Audible_Data.xlsx` to view the cleaned data. 
-	Open `Audible_Report.pbix` in Power BI Desktop to explore the visuals. 

