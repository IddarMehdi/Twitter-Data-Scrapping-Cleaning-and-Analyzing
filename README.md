# Twitter-Data-Scrapping-Cleaning-and-Analyzing
Real-world data rarely comes clean. Using Python and its libraries, I gathered data from a variety of sources and in a variety of formats, assessed its quality and tidiness, then cleaned it. This is called the data wrangling process.   
The dataset used gathered from Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10.   

In this project, I conducted a data wrangling process through gathering data from a variety of sources and in a variety of formats: 
- First is downloaded manually a .csv file named ‘twitter_archive_enhanced.csv’ and stored it in ‘archive’ table 
- Then, I used the Requests python library to download programmatically a ‘.tsv’ file named ‘tweet-image-predictions.tsv’ and I stored it in the ‘images’ table. This file contains the results of a neural network's analysis which predicts a dog's breed based on images. 
- After this, I created an API object that I used to programmatically download a JSON file stored as ‘twitter_counts’ table, which contains additional Twitter data.  

For the second section of the project, which is devoted to data assessing, I first, looked for quality issues that pertain to the content of data I identified ten quality issues, then I examined tidiness issues, which pertain to the structure of data.   

In the last section of the wrangling process, I structured and cleaned dirty data into the desired format for better analysis and visualizations using Python and its libraries. For each identified issue, I defined the actions to undertake before translating those actions to lines of code. I also tested every code to check the result of the cleaning.
