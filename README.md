## GitHub User and Repository Data

This data was scraped using the GitHub API and includes users in Austin with over 100 followers and their public repositories (up to 500 most recent).

### Analysis

* **Data Scraping:** Users were found by searching for location:"Austin" and filtering by followers:>100. Repositories were retrieved using the user's login information.  Excel operations were performed to clean the data,  unwanted columns were deleted, Required data in column was fitered using column filter
data to colum filter was used to get Licence name, Unwanted columns were deleted manually
* **Interesting Finding:** When we select top 5 by date, the data is not sorted by, it should be carefully checked for order to get right answer,  Regression charts of repo to followeer is very peculiar its peculiar line there is no specific correlation can be established. Pivot tables and filters in excel are useful to solve most of the problems.
* **Recommendation for Developers:** Initial  API response gives huge amount of data, it can be filtered by code or by Excel operations, However Excel filtering looks easy. Python coding can be very tedious and can consume lot of time.
