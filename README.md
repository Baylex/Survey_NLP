# Sentiment Analysis 
NLP, Sentiment Analysis, and Topic Analysis on Walkthrough data for Transformation Waco

# Process
1. Use Python in Jupyter Notebook to perform a Sentiment Analysis   
2. NLTK to determine positive, neutral, and negative    
3. Review for subjectivity and objectivity  
4. Perform Topic Analysis   
5. Pull results into Tableau for an interactive Dashboard    
6. PowerPoint for sharable file for those outside the organization     
7. Refine data collection process to save hours of work for campus leaders   

# Problem Statement
An outside organization created a teacher observation form with several questions including 3 fill in the blanks.  My best estimate for the time investment for one year of data tracking is that the principals/APs spent 2000 work hours completing the walkthrough form.  My team asked for an analysis on the quantitative data but left out the qualitative data.  I completed the core part of the analysis in Tableau, but I still wanted to dig into the qualitative data, which was over 5000 text entries to sift through.   
## Analyzing the Qualitative Data 
I wrote code in Jupyter Notebook and ran the text entries through a sentiment analysis and found that the coaching feedback was significantly positive and only slightly subjective in language.  Both of those indicators meant the coaches were on track to giving good mentoring advice to the teachers.  I spent a lot of time tinkering with what made an appropriate stop word removal list with an education data set.  I uploaded the results and made a word cloud in Tableau where they could explore the different positive/negative and objective/subjective words.  I also completed 2 versions of a topic analysis, where I found that using 5 words in a row gave a good general sense of some interesting topics discussed in the coaching feedback.      
## Addressing Form Fatigue
The other key finding was the word count trailed off as the form progressed.  After some investigation, I finally attributed the decrease in words to form fatigue.  To address form fatigue, I met with the outside team to analyze the questions on the form and to build it better from a data collection view for the new school year.  We were able to trim the form down considerably while not sacrificing any of the team’s key data points!  I removed many redundant data collection pieces that could be later merged with a static file when an analysis was needed.  We easily recovered 1000 work hours in making this adjustment!    

# Code Coming Soon! 
I am working on finding an alternative data set to share my code and work for other educators.  Machine Learning and NLP is not commonly used among school campuses.  I am working to make advanced analysis techniques more accessible to school districts.  I used Jupyter Notebook for this project, but for accessibility, I will add code for Google Colaboratory as it does not require a data environment to be set up and allows for non-technical educators to run the code on their survey data.  Most ISDs have access to Google products.    

# Future Research Areas 
Super Duper NLP Repo: https://notebooks.quantumstat.com/             
Datasets: https://index.quantumstat.com/         
Visualize: https://iclr.cc/virtual_2020/papers.html?filter=keywords         
Pick the ML model: https://towardsdatascience.com/automated-machine-learning-using-pycaret-4bb90ab3e2c7 
Visualize the math of ML models: https://github.com/Gautam-J/Machine-Learning
PowerBI in Jupyter notebook: https://github.com/microsoft/powerbi-jupyter

