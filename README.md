# Netflix Titles - Case Study

This was a quick and short Power BI project about Netflix titles I took on, and my first one using Power BI!
The goal of this project was to better understand Netflix's catalogue, by answering questions such as: what country/genre is more present in the catalogue? Was there a significant peak of movies/tv shows released from one year to another in the platform? Does Netflix invest more on older (arbitrarily pre-2015) or newer released movies?
I have also added a _conclusion_ txt file, which tries to answer the questions above and explore other findings.

*****About the dataset*****

- The dataset contains the fact table named ****netflix_titles****, and the dimension tables with information about ****directors****, ****countries****, ****cast****, and ****category****, each in its own sheet.
- The primary key is the show_id column, which is present in all tables and is used to either JOIN using SQL and/or to manage relationships in Power BI.
- Most of the data cleaning and prep was done in Google Sheets, some of it in Power Query (the tool within Power BI) during the ETL process.
