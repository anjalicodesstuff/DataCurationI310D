# DataCurationI310D
Coding Assignment: Data Curation and Analysis, I310D

Goal of the Project:
The goal of this project is to provide a dataset of Walt Disney Pictures films, including essential information like film titles, U.S. release dates, directors, and whether they won any awards. This dataset is intended for analysis, visualization, and research on Disney films over the years.

Data Sources/API Documentation:
The data was collected from the Wikipedia page "List of Walt Disney Pictures films" using web scraping techniques in Python. Beautiful Soup, a Python library, was used for web scraping. There are no external APIs other than Wiki APII used in this project. The data is directly sourced from the Wikipedia page.

License:
The raw data collected from the Wikipedia page is part of the licensing of Wikipedia. The consolidated data is provided under the Creative Commons License.

Data Dictionary:
  The dataset contains the following attributes:

  Title (String): Title of the Disney Film
  U.S. release date (Date): U.S. Release Date -- later converted to integer of year
  Notes (String): Additional Notes or Info abt film
  Decade (Integer): The decade film was released
  Award Winner (Boolean): Indicates if film won an award (True/False)

Known Issues:
The data is collected from a Wikipedia page, which is a public forum -- meaning data could be inaccurate, misleading, and/or not up to date. The Notes section may also not be completely encompassing of each film's performance. 
