# About Me

<p align="justify">With 3 years of professional experience honing my skills in client communication, requirement gathering, and overall business conduct, I am currently pursuing Master's in Data Science at Northeastern University, Boston with concurrent professional experience as a Product Analyst Co-op at Homesite Insurance within the American Family Insurance group. My passion for data science, analysis, and visualization drives me to craft compelling narratives through data exploration and my curiosity extends to Machine Learning and Natural Language Processing. I seek opportunities within organizations that not only leverage my existing knowledge but also foster my growth by embracing new technologies and contributing to their continued success. </p>

## Technical Skills
**Programming Languages:** Python (Pandas, PyTorch, NumPy, Scikit Learn, Keras, Seaborn, Matplotlib, PySpark, TensorFlow, NLTK, Spacy, Hugging Face), R (ggplot2, Dplyr, Tidyr, Rshiny), SQL (Postgres, MsSQL, MySQL, T-SQL), NoSQL (Firebase), Java (Spring, Boot, Hibernate, Hadoop), JavaScript, Typescript, C, CSS3 (Bootstrap), HTML5.

**Cloud Services:** AWS (S3, EC2, Lambda), GCP (BigQuery), Azure (Data Studio).

**Business Intelligence Tools:** Lookers, Looker Studio, MS Power BI, Tableau, Quicksight, MS Excel, Power Query, Weka, Google Analytics.

## Education

- Master of Science in Data Science
  Northeastern University, Boston (_May 2024_)
  <div style="text-align: center;">
    <img src="https://github.com/Kunal18/kunal_indore_portfolio/blob/main/assets/img/Northeastern_seal.svg.png" alt="Northeastern University" width="100px" height="100px">
  </div>

- Bachelor of Engineering in Computer Engineering
  University of Mumbai, India (_May 2019_)
  
  <div style="text-align: center;">
    <img src="https://github.com/Kunal18/kunal_indore_portfolio/blob/main/assets/img/mu.jpg" alt="University of Mumbai" width="100px" height="100px">
  </div>

## Work Experience
**Product Analyst @ Homesite Insurance (_July 2023 - Present_)**
<p align="justify">
-	Designed data models, formulated SQL queries in Google BigQuery to track partner companies incoming quotes and extracted diverse data from partner firms for advanced analysis.
</p>
<p align="justify">
-	Designed and implemented a Looker dashboard to monitor new quotes across all operating companies, presenting key metrics, analyzing trends, thereby empowering business teams and state managers to make well-informed, data-driven decisions.
</p>
<p align="justify">
-	Utilized SQL and SAS programming to execute ETL processes, effectively querying large datasets, leveraged the generated data in reporting tools to track top and bottom-line metrics, conducting detailed analysis of Loss Ratios based on perils.
</p>

**Software Engineer @ Majesco Software and Solutions (_July 2019 - July 2022_)**
<p align="justify">
- Created a recommendation system for providing preliminary quotes, the recommendation system and a proprietary rating algorithm were integrated into a web portal to deliver real-time results, decreasing the process lifecycle by 54 seconds.
</p>
<p align="justify">
- Analyzed data and generated insights for insurance agents and brokers, utilizing Power BI created KPI dashboards to display daily insurance quotes, issued policies, payments, and number of users. Automated the process for determining processed and unprocessed quotes and policies by sending weekly emails using SQL Batch Procedures, reducing insurance team’s efforts.
</p>
<p align="justify">
- Managed numerous production releases while leading the project team and collaborating with the client, making sure that all pre- and post-release tasks like application's performance analysis using Instana, code review, release team sign-off, and functional validations were finished on schedule which led to 100% hassle-free project deployment.
</p>
<p align="justify">
- Built Cloud-Native Digital Portals for Insurance Brokers and Underwriters which provided real-time insurance-specific capabilities using integrations based on Microservices architecture, setting code base in T-SQL, Angular, JavaScript & API’s along with Postman, Pilotfish and Google Analytics. 
</p>

**Intern @ Majesco Software and Solutions (_Jun 2018 - July 2018_)**
<p align="justify">
- Developed a dynamic application that allowed users to choose variables and generate reports using dynamic T-SQL stored procedures, A/B testing was performed to see how users react, and it led to 2.8% increase in engagement with the application.
</p>

**Virtual Experience Program Intern @ Boston Consulting Group (_Mar 2020 - Apr 2020_)**
<p align="justify">
- Analyzed data and performed market research analysis on the financial statements of a telecommunications operator, generating insights such as declining profits from the operator. 
</p>
<p align="justify">
-	Recommended a handset leasing consumer offer to reduce customer churn rate and help drive profitability improvement with a revenue growth of 2.5% - 4.25%.
</p>

## Recent Projects
### [Counting Blood cells and WBC type Prediction](https://github.com/Kunal18/Blood-Cell-Detection){:target="_blank"}

<p align="justify">- Trained the YOLOv5 model on blood cell images, augmenting the dataset to identify the bounding boxes of RBCs, WBCs, and platelets, and achieving a mAP of 92.6% within 100 epochs of training.</p>
<p align="justify">
- Classified WBC cell type using transfer learning using the Inception model, with an accuracy of 99.15%, followed by ResNet-50 (96.08%), and developed a custom CNN architecture with an accuracy of 98.34% despite having fewer parameters.</p>

![Counting Blood cells](/assets/img/cbc.jpg)

### [Trending YouTube Video Statistics using sentiment analysis](https://github.com/Kunal18/Youtube_Statistics#youtubestatistics_sml){:target="_blank"}

<p align="justify">
- Generated robust insights into the factors that influence video trending by creating additional features, determined the sentiments for titles, comments, and descriptions using hugging face transformer, and predicted categories of unlabeled videos using random forest algorithm with an F1 score of 95%.</p>
<p align="justify">
- Created a Rshiny application for filtering video searches based on various parameters enhancing user’s ability to browse content.</p>

![Youtube Statistics](/assets/img/yt.jpg)

## Publication
### Depression Detection System by Analyzing Tweets
[Publication](https://dx.doi.org/10.2139/ssrn.3358809){:target="_blank"}
<p align="justify">
Developed a system that uses the Twitter API to scrape the real-time tweets, classified the tweets employing a Hybrid Naive Bayes and SVM (NB-SVM) model and used data visualization methodologies to classify depression into two major categories - Major depression and Bipolar depression with an F1 score of 85%.
</p>

## Contact Me
<ul>
  <li><a href="mailto:indore.k@northeastern.edu">Email</a></li>
  {% for social_link in site.social %}
    <li><a href="{{ social_link.url }}" target="_blank">{{ social_link.title }}</a></li>
  {% endfor %}
</ul>
