# Sentiment Analysis 
NLP Sentiment Analysis on Walkthrough data for Transformation Waco

# Process
1. Use Python in Jupyter Notebook to perform a Sentiment Analysis   
2. NLTK to determine positive, neutral, and negative    
3. Review for subjectivity and objectivity  
4. Perform Topic Analysis   
5. Pull results into Tableau for an interactive Dashboard    
6. PowerPoint for sharable file for those outside the organization     
7. Refine data collection process to save hours of work from campus leaders   

# Narrative
We had a teacher observation form created by an outside organization.  30 questions, 3 fill in the blanks.  My team asked for analysis on all but the fill in the blanks.  I completed the analysis in Tableau, but I pushed on why we did not look at the fill in the blanks.  I do not prefer to collect data that is not used.  Data is only valuable if it is actionable.  It is not time efficient on the staff to fill out unnecessary questions on forms.  Knowing how long a walkthrough and follow up take, my best estimate is the principals/APs spent 2000 work hours combined filling out the walkthrough forms over the course of the school year.  With over 5000 text entries to sift through, the leadership team was at a loss for how to analyze that type and volume of qualitative data.       

And true to any leadership team, they wanted the cliff notes version!  I said my data boot camp introduced me to NLP and that I can analyze that for them.  They signed off on giving me a shot at it.  I ran the entries through a sentiment analysis and found that the coaching feedback from the 3 fill in the blanks forms was significantly positive and only slightly subjective in language.  Both of those indicators meant the coaches were on track to giving good mentoring advice to teachers.  I also made a word cloud in Tableau where they could explore the different positive/negative and objective/subjective words.  And I did 2 versions of a topic analysis, where I found that using 5 words in a row gave a good general sense of some interesting topics discussed in the coaching feedback.      

The other key finding was the word count trailed off as the form progressed.  I ran down some other possibilities such as focusing on one domain over another and another.  When those did not pan out, I finally attributed the decrease in words to form fatigue.  To address form fatigue, I met with the outside team to analyze the questions on the form and to build it better from a data collection view for the new school year.  We were able to trim the form down from 30 questions to 12 questions and only 1 fill in the blank, none of which sacrificed any of my team’s key data points!  I removed many redundant data collection pieces that could be merged with a static file when an analysis was needed.  We easily recover 1000 work hours!  

# Code Coming Soon! 
I am working on finding an alternative data set to share my code and work. 

# Future Research Areas 
Super Duper NLP Repo: https://notebooks.quantumstat.com/             
Datasets: https://index.quantumstat.com/         
Visualize: https://iclr.cc/virtual_2020/papers.html?filter=keywords         
Pick the ML model: https://towardsdatascience.com/automated-machine-learning-using-pycaret-4bb90ab3e2c7 
Visualize the math of ML models: https://github.com/Gautam-J/Machine-Learning
powerbi in jupyter notebook: https://github.com/microsoft/powerbi-jupyter
