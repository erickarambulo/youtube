# Google Sheets Documentation

This documentation page will solely focus on keep tracking my changes that I made to spreadsheet. This will help me to make good habits of practicing my documentations for future employers; therefore, that way they will be able to keep tracking on the modifications I have made to Google Sheets.

I obtained my [dataset](https://www.kaggle.com/datasets/rashminslnk/youtube-subscribers-data-2024) from Kaggle.com. It contains 50 rows + 1 header and 6 columns. I decided to use this dataset because it was recently most updated by a month ago.

Here is my updated [spreadsheet](https://docs.google.com/spreadsheets/d/1iU5AqJhoyd4ypMkamjDsyWFWF5B1aEMLNiSBFzdZGKg/edit?gid=618659102#gid=618659102), which come in two separate sheets: original and updated.

---

## Changes That I Made

### 1. Data Cleaning and Preparation

**NOTE:** According to Wikipedia page called [List of most-subscribed YouTube channels](https://en.wikipedia.org/wiki/List_of_most-subscribed_YouTube_channels), This website is updated in real-time, so the number of subscribers (millions) column is always changing based on real-time data.

- I **updated** my dataset by changing the 'Subscriber (millions)' column for all 50 rows. I referenced the Wikipedia page to ensure that the numbers in my spreadsheet align with the data on Wikipedia.
- I used Gemini AI to obtain 50 rows of channel names. I then analyzed these names to detect their nationality and added a new column called 'Nationality' to the dataset. This allowed me to understand which nationality has the most impact on its audience. I also **double-checked** to ensure that the nationality was correctly inputted for all 50 rows.
- I noticed that there was a symbol [a] next to 'Cyprus,' like this: 'Cyprus[a].' So, I removed it and left it as 'Cyprus'.
- I removed some rows that contain whitespaces by clicking Data -> Data cleanup -> Trim whitespace
- The channel name is **Like Nastya**, and the **Country** column previously listed 'United States, Ukraine.' However, **Like Nastya** is not from Ukraine. The channel originates from Russia, and she was born in Russia. She eventually moved to Miami, Florida; therefore, I corrected the entry to 'United States'.

### 2. Exploratory Data Analysis (EDA)


