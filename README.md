## GitHub User and Repository Data

This data was scraped using the GitHub API and includes users in Austin with over 100 followers and their public repositories (up to 500 most recent).

### Analysis

* **Data Scraping:** Users were found by searching for location:"Austin" and filtering by followers:>100. Repositories were retrieved using the user's login information.
data to colum filter was used to get Licence name, Unwanted columns were deleted manually
* **Interesting Finding:** In repository the Login name is in last column had to move it to front, To retrieve licence name column operations in excel had to be performed, Many unwanted colunmns had to be delted
* **Recommendation for Developers:** Initial  API response gives huge amount of data, it can be filtered by code or by Excel operations.
