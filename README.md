
## Analyzing Para-Social Relationships with Content Creators




- Scrape YouTube comments using the YouTube Data API.  
- Save the comments in a structured format (CSV/JSON).  
- Perform sentiment analysis, word frequency analysis, and other insights on the scraped data.  
- Generate visualizations like word clouds, bar charts, and pie charts to present findings.  



## Installation  

1. Clone this repository:  
   ```bash  
    git clone https://github.com/yourusername/youtube-comments-analysis.git  
    cd youtube-comments-analysis  
    ```
2. Install required Python packages:
```bash
pip install -r requirements.txt  
```
## Usage  

### 1. Scrape YouTube Comments  

- Open `youtube_comments_scraper.py` and update the `VIDEO_ID` and `API_KEY` fields with the desired YouTube video ID and your API key.  
- Run the script to scrape comments:  
   ```bash  
   python youtube_comments_scraper.py  
   ```
- The comments will be saved in a comments.csv file in the root directory.

### 2. Analyze the data

 - Open the Jupyter Notebook comments_analysis.ipynb:
 ```bash
 jupyter notebook comments_analysis.ipynb 
 ```

 - Follow the steps in the notebook to load the comments.csv file and run various analyses.

- Modify the notebook to include custom analyses as needed.




