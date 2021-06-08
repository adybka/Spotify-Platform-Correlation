# Spotify Platform Correlation

Data source: [Spotify Dataset 1921-2020, 160k+ Tracks](https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks)


### Running Twitter Notebook (Twitter.ipynb)
- You will need to create a file called Keys.ipynb. 
- In that file there needs to be a line with your Twitter API Bearer token:<br> 
  BEARER_TOKEN= 'Your Twitter API bearer token here'<br>
- Warning: Running the Twitter scraping code block takes ~1hour20mins to complete (it is commented with WARNING)

### Running TikTok Notebook (TikTok_Analysis.ipynb)
- You can run this notebook without scraping TikTok data again. Skip running the cells in Section 2.2, upload 'TikTok_data.csv' to the notebook, and use this file from the first cocde cell in '3.0: Analysis' onwards.
- If you desire to run scraping anew instead, run the code cells in Section 2.2 to scrape the TikTok data. Once scraping is complete, change 'TikTok_data.csv' in the first code cell in '3.0: Analysis' to the name of your trends file (it will be saved in the notebook's content for that runtime).

### Running Google Trends Notebook (GoogleTrends.ipynb)
- Notebook contains regression analysis of Spotify dataset. Following is introduction to pytrends API. The correlation between google trends and Spotify metrics. Raw data stored in .zip containing all input files. Trending_data.csv contains dataframe with Google trends data. File currently set to redo API requests.

### Running Youtube Notebook (YouTube_Analysis.ipynb)
- Notebook runs as is with selenium access to Youtube info. Recorded data contained in youtube_data.csv, Spotify dataset contained within data.zip.
- Notebook is designed to have both data files located in a Google Drive. Need to change file paths if one wants to use local storage.

### Running WhoSampled Notebook (WhoSampled-Analysis.ipynb)
- Scraping notebook contains data collection process. Results.csv is stored and used in the analysis notebook for results.

### Running Billboard Notebook (Billboard.ipynb)
- Notebook contains analysis and data processing. Runs as is based on data files contained in .zip folder.


### Libraries Used
- numpy, seaborn, matplotlib, scipy, pytrends, selenium, pandas, google_colab, bs4, requests, time
