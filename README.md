# trending_music_analysis

Exploratory data analysis & insight mining 


Goals: 
1. find out the Key features that make a song popular
2. In a 5 year cycle, what are the trends of popular music genre? 







1.1 Data Preparation: where to get data?  
-	Spotify: Go to file  ‘Loading Data API.ipynb’
-	Billboard: Official Download on https://www.billboard.com/charts/hot-100/ 
-	YouTube: official API : https://www.youtube.com/feed/trending 
-	TikTok: Go to ‘Tiktok scraper’. Run in terminal. 

1.2 Data cleaning and transformation: What to do when I get raw data? 
1.	Save it locally in csv format 
2.	Cleaning stages: 
a.	Cleaning stage 1: using open refine for renaming, removing columns and clustering, type transformation. 
b.	Cleaning stage 2: see python file for more clustering and value Standarization                 


1.3 Data Storing: what do I do after data is clean?

-	Export from OpenRefine in both csv file and SQL export file

-	We will be working with SQL after this step 
-	In SQL: 
1.	Create a Schema called: music 
2.	Import the SQL file from last step
3.	Insert table and values in SQL


1.4 Visualization: how to visualize thousands of data? 
-	Method1-TABLEAU: connect SQL server to TABLEAU 
-	Method2-TABLEAU: import cleaned local csv file
  	Remember to link csv files on genres/ ids  

-	Method3-Python: visualization packages










