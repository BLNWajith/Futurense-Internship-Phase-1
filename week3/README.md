<div align="right">
  <img height="140"
    src = "![75ez](https://github.com/BLNWajith/Internship-work/assets/161812511/997cea05-8a93-485e-8ed0-ae366073dbd8)" />
  </div>

  ###

<h3 align="left">Introduction</h3>

###

<p align="left">This project involves data analysis of Netflix titles, aiming to uncover insights into content types, genre popularity, directors' contributions, and much more using Python and its powerful libraries like Pandas, Matplotlib, Seaborn, and TextBlob.</p>

###

<p align="left">Data Set brief screenshot</p>

![Screenshot (3448)](https://github.com/BLNWajith/Internship-work/assets/161812511/076315af-c744-4427-bd8e-5d1edfc079c3)

###

<h2 align="left">Data Cleaning & Processing Overview</h2>

###

<h4 align="left">Data cleaning, also known as data cleansing or data preprocessing, is a crucial step in the data science pipeline that involves identifying and correcting or removing errors, inconsistencies, and inaccuracies in the data to improve its quality and usability.<br><br>" src = geeksforgeeks "</h4>

###

<p align="left">During the stage where we clean and process the data, our goal is to polish the Netflix dataset so we can analyze it accurately. First off, we take a good look at how the dataset is organized to get a grip on what we're dealing with. Some of the main things we do include spotting and getting rid of any rows that are missing information to keep our data solid. We also change the name of the 'listed_in' column to 'genre' to make it more understandable. After we've cleaned everything up, we go back and double-check the dataset to make sure our cleaning efforts did the trick. And we don't forget to look for any duplicates, because we want to keep our dataset one of a kind. These steps are super important to make sure we're building a strong foundation for a data analysis that's both reliable and packed with insights.</p>

###

<h2 align="left">EDA - Exploratory Data Analysis</h2>

###

<h4 align="left">Exploratory Data Analysis (EDA) refers to the method of studying and exploring record sets to apprehend their predominant traits, discover patterns, locate outliers, and identify relationships between variables. EDA is normally carried out as a preliminary step before undertaking extra formal statistical analyses or modeling.<br><br>" src = geeksforgeeks "</h4>

###

<h3 align="left">Visualizing Content Types Distribution</h3>

###

<p align="left">We start by examining the distribution of Movies vs. TV Shows available on Netflix. A count plot reveals the prevalence of each type, providing a visual understanding of Netflix's content strategy.</p>

![output 1](https://github.com/BLNWajith/Internship-work/assets/161812511/c38f0184-ea8b-4cb1-9d52-e1e933f7d072)

###

<h3 align="left">Investigate Movie Durations</h3>


###

<p align="left">Focusing on movies, we clean the 'duration' column by converting it to integers and removing the 'min' suffix. This process enables us to analyze movie durations effectively, including plotting a histogram to visualize the distribution of movie lengths.</p>


![output 2](https://github.com/BLNWajith/Internship-work/assets/161812511/5bbdaa56-2f1f-40f2-ae12-a9862edc235a)


###

<h3 align="left">Exploring Release Year Versus Duration</h3>

###

<p align="left">A scatter plot of 'release_year' against 'movie duration' illustrates trends over time, potentially highlighting changes in movie-making preferences or technological advancements affecting film length.</p>

![output 3](https://github.com/BLNWajith/Internship-work/assets/161812511/28f4742a-1063-41ea-b81d-b14860f5e5dd)

###

<h3 align="left">Identifying Extremes in Movie Durations</h3>

###

<p align="left">By pinpointing the movies with the minimum and maximum durations, we gain insights into the range of content lengths on Netflix, from quick watches to epic sagas.</p>

![output 4](https://github.com/BLNWajith/Internship-work/assets/161812511/7801c4e3-5ab7-491d-b8b2-39a3a017c54e)


###

<h3 align="left">Genre Popularity Analysis</h3>

###

<p align="left">Extracting and counting unique genres from the dataset allows us to visualize which types of content are most prevalent on Netflix, indicating audience preferences or content strategy focuses.</p>

![output 5](https://github.com/BLNWajith/Internship-work/assets/161812511/62d64316-7787-42c2-a8c1-b553f9644b17)

###

<h2 align="left">IDA  -  Initial Data Analysis</h2>

###

<h4 align="left">Initial data analysis is the process of data inspection steps to be carried out after the research plan and data collection have been finished but before formal statistical analyses. The purpose is to minimize the risk of incorrect or misleading results.<br><br>" src = ScienceDirect "</h4>

###

<h3 align="left">Distribution of Content Ratings</h3>

###

<p align="left">Understanding the distribution of content ratings (e.g., PG, R) is crucial for content managers. A pie chart visualization helps in planning marketing strategies and ensuring a diverse content catalog that appeals to various audience segments.</p>

![output 6](https://github.com/BLNWajith/Internship-work/assets/161812511/eff52662-1557-43ba-b6b1-533b5ef7a183)


###

<h3 align="left">Top Content-Producing Countries</h3>

###

<p align="left">Identifying and visualizing the top 10 content-producing countries reveal geographical diversity in Netflix's catalog and can guide regional content development strategies.</p>

![output 7](https://github.com/BLNWajith/Internship-work/assets/161812511/094d0ee1-7b5c-4d2b-8c31-862078c96a40)

###

<h3 align="left">Directors with the Most Titles</h3>

###

<p align="left">Highlighting the top 10 directors by their number of titles on Netflix can inform partnership strategies and content promotion plans, showcasing the platform's key creative collaborators.</p>

![output 8](https://github.com/BLNWajith/Internship-work/assets/161812511/f68b2350-75c8-464e-a7e3-6ae95e4cc370)

###

<h2 align="left">Text Analysis</h2>

###

<h4 align="left">Text Analytics is a process of analyzing and understanding written or spoken language. It employs computer algorithms and techniques to extract valuable information, patterns, and insights from extensive textual data. In simpler terms, text analytics empowers computers to understand and interpret human language.<br><br>" src = geeksforgeeks "</h4>

###

<h3 align="left">Keywords Extraction from Descriptions</h3>

###

<p align="left">Utilizing basic NLP techniques to extract common keywords from content descriptions uncovers prevalent themes and subjects, aiding in content categorization and recommendation algorithms.</p>

###

<h3 align="left">Sentiment Analysis on Descriptions</h3>

###

<p align="left">Performing sentiment analysis on content descriptions categorizes them as positive, negative, or neutral. This insight helps understand how content is perceived and can inform content curation and marketing strategies.</p>

![output 9](https://github.com/BLNWajith/Internship-work/assets/161812511/9eaa1069-357e-4c64-822e-ec6073b4f93a)

###

<h2 align="left">Conclusion</h2>

###

<h4 align="left">This project demonstrates the power of data analysis and natural language processing in extracting meaningful insights from a content database. The findings can assist content managers, marketers, and strategists in making informed decisions to enhance user experience, content diversity, and platform growth.</h4>

###
