Description:
This project utilizes guest review data from Disneyland parks to uncover insights into visitor experiences, sentiment trends, and country-wise feedback distribution. The dashboard was created using Tableau and relies on a cleaned and filtered dataset for accuracy and clarity.


📦 DisneylandReviewProject
 ┣ 📄 Group8.twbx
 ┣ 📄 DisneylandReviews_Complete_Filtered_ExactMatch.csv
 ┣ 📄 Country_Continent_Mapping_Completed.csv

🔍 How to Use:
1. Opening the Dashboard:
Open Group8_Disneyland_Dashboard.twbx in Tableau Desktop or Tableau Public.

Ensure that the CSV files are in the same folder as the .twbx file so Tableau can automatically link to the data sources.

If you encounter a data connection prompt, manually reconnect to DisneylandReviews_Complete_Filtered_ExactMatch.csv.

2. Understanding the Data:
DisneylandReviews_Complete_Filtered_ExactMatch.csv: This is the primary dataset, containing cleaned and exact-match reviews with fields like Review Text, Rating, Reviewer Country, Branch, and Submission Date.

However the final DataSet was created by mering the Extracted features we got from the two IPYNB files that is Pre Processing 1 and Pre Processing 2. The Sentiment Scores were extracted from the IPYNB named Pre Processing 3

Country_Continent_Mapping_Completed.csv: Used for mapping each reviewer’s country to a continent for geo-analysis layers in the dashboard.

3. Navigating the Dashboard:
Use filters to explore data by branch (e.g., California, Paris, Hong Kong), country, or rating.

View sentiment trends, review distribution, and rating averages.

Interactive charts and maps enable deeper insights by clicking or hovering over visual elements.

4. Customization and Extension:
You can modify visualizations or add new charts within Tableau.

Replace datasets with newer versions (maintaining the same column structure) for updated analysis.

Export charts as PDFs or images for reports and presentations.

🛠 Requirements:
Tableau Desktop or Tableau Public (recommended: latest version)

Optional: Excel, Google Sheets, or a text editor to view/edit .csv files