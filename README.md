<h1 align="left">Hi 👋! My name is BLN Wajith Ali and I'm a Student from Jain</h1>

###

<h2 align="left">About the Repository</h2>

###

<div align="right">
  <img height="140" src="https://camo.githubusercontent.com/7de37139d0b4c1ce40865e799b446c0e963a3dd8fb68d239707237c40604fa3d/68747470733a2f2f63646e2e6472696262626c652e636f6d2f75736572732f3733303730332f73637265656e73686f74732f363538313234332f6176656e746f2e676966"  />
</div>

###

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="30" alt="python logo"  />
</div>

###

<br clear="both">

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=BLNWajith&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false&order=1" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=BLNWajith&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" height="150" alt="languages graph"  />
</div>

###

<h2 align="left">Week 1</h2>

###

<p align="left">1.Add Two Numbers: Enter two numbers to get their sum.<br><br>2.Find Maximum of Two Numbers: Input two numbers and find out which is bigger.<br><br>3.Factorial of a Number: Enter a number to calculate its factorial using the math.factorial() method.<br><br>4.Simple Interest Calculation: Calculate simple interest by providing principal, rate, and time.<br><br>5.Compound Interest Calculation: Compute compound interest with inputs for principal, rate, time, and compounding frequency.<br><br>6.Check for Armstrong Number: Enter a number to check if it's an Armstrong number, which means the sum of its own digits each raised to the power of the number of digits equals the number itself.<br><br>7.Area of a Circle: Find the area by inputting the radius of a circle.<br><br>8.Prime Numbers Within an Interval: Print all prime numbers within a given start and end interval.<br><br>9.Check if a Number is Prime: Input a number to check if it's prime, meaning it's only divisible by 1 and itself.<br><br>10.N-th Fibonacci Number: Enter a number to get the corresponding Fibonacci number at that position in the sequence.</p>

###

<h2 align="left">Week 2</h2>

###

<h4 align="left">Data Structure 1</h4>

###

<p align="left">1.Flatten Nested Tuples: Combine elements from nested tuples into one.<br><br>2.Set <-> Tuple Conversion: Swap between sets and tuples easily.<br><br>3.List of Dictionaries to Tuple List: Turn each dictionary in a list into a tuple.<br><br>4.Sort Tuples by Element: Sort a list of tuples by any specific element.<br><br>5.Find Tuple Indices: Locate where certain elements appear in a tuple list.<br><br>6.Dictionary Values to List of Dictionaries: Spread dictionary values into individual dictionaries within a list.</p>

###

<h4 align="left">Data Structure 2</h4>

###

<p align="left">Q1 Description:<br>This Python program is designed to calculate the product by multiplying all the numbers present in each given tuple. It iterates through each number in the tuple, multiplies them together, and prints the final product for each original tuple provided. The function prod_of_tuples is responsible for calculating the product, and it's tested with tuples containing both positive and negative numbers as well as a variety of integers to demonstrate its functionality.<br><br>Q2 Description:<br>However, there seems to be a mistake in the provided code for calculating the average value of numbers in a tuple of tuples. The intention of the program is to compute and display the average values of corresponding elements across the tuples contained within a larger tuple. This means each position in the resulting list of averages should reflect the average value at that position across all inner tuples. The function avg_of_tuples aims to accomplish this by iterating over the tuples and calculating the averages, but the implementation needs correction to accurately perform as described. Specifically, it should average across the same positions in each tuple and fix the incorrect appending operation.</p>

###

<h2 align="left">Week 3</h2>

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

<div align="left">
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/twitter/default.svg" width="52" height="40" alt="twitter logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/discord/default.svg" width="52" height="40" alt="discord logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg" width="52" height="40" alt="gmail logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/instagram/default.svg" width="52" height="40" alt="instagram logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/stackoverflow/default.svg" width="52" height="40" alt="stackoverflow logo"  />
</div>

###
