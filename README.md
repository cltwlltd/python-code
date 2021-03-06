## How to:
1. Install a ChromeDriver from right here: https://chromedriver.chromium.org/downloads
2. Remember where you saved the ChromeDriver.
3. You should also have Google Chrome installed.
4. You will see the line that starts with "with Chrome(executable_path" in the thrid cell from the attached Python code file. Copy and paste the path where your ChromeDriver was saved. (I saved mine in C:\Program Files. if you did the same, you won't have to change the code I wrote)
5. After running the required libraries and function cells, go to the bottom of the page.
6. Input the url and the desired number of comments you would like to scrape.
7. Run the last cell and "ScrapedYoutubeComment.csv" file will be created & saved!

## Pro tips:
Depending on your network environment, it may take longer to load the comments from each scroll-down.
When the code is running, I highly recommend opening up the activated Youtube page and scroll down to initiate loading the comments. The rest will be covered by the automated command, but the initial load of the comments is key to successfully scraping the data. Note that the total number of comments you see on the Youtube page includes re-replies, so naturally the number of rows of the csv file will not match. However, if you still experience the lack of comments being scraped, try increasing time.sleep(5) to time.sleep(10). It should help!

#### Reference:
https://towardsdatascience.com/how-to-scrape-youtube-comments-with-python-61ff197115d4<br/>
https://github.com/dddat1017/Scraping-Youtube-Comments
