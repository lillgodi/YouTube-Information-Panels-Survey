# Data Description
This webpage contains details about the data accompanying TWC 2022 paper Investigating the Effect of YouTube Information Panels on Video
Watching Behavior. The data was collected from a Qualtrics survey distributed using Amazon Mechanical Turk. The survey data is used to investigate 
how YouTube Information Panels affect watch behavior of conspiracy theory videos as well as how they are percieved as credibility signals. Our 
experiments collect 309 survey responses. Participants provided responses of example conspiracy query phrases, predicting watch behavior, 
and indicating the usefulness of Information Panels as tools for determining credibility. Demographic questions were also collected. Here 
you will find 11 files across three parts: survey question and condition examples, raw survey data, topic groupings, watch score, and 
feature proportion analysis. The description of each file is listed below.

**1. Survey questions and conditions examples** 

  - Watch score question and survey subject condition  
  
  filename: *watchScoreExample_surveySubject.png* 
  The file consists of a photo of the question that collected watch scores. Respondents assigned to this condition
  self-reported predicted watch scores.
  
  - Watch score question and average YT user condition  
  
  filename: *watchScoreExample_averageYTUser.png*  
  The file consists of a photo of the question that collected watch scores. Respondents assigned to this condition
  predicted watch scores for their view of the average YT user. 
  
  - Feature hotspot question and IP present condition    
  
  filename: *hotspotExample_IPpresent.png*  
  The file consists of a photo of the question that collected feature proportion data. Respondents assigned to this condition
  were given six control features and the IP feature and asked to report whether they liked, disliked, or were neutral toward the feature as
  a credibility signal. Note: respondents did not see the colors associated with each region. Outlines around the region were only shown when the 
  respondent's mouse hovered over the region.
  
  - Feature hotspot question and IP absent condition
  
  filename: *hotspotExample_IPabsent.png* 
  The file consists of a photo of the question that collected feature proportion data. Respondents assigned to this condition
  were given six control features and asked to report whether they liked, disliked, or were neutral toward the feature as
  a credibility signal. Note: respondents did not see the colors associated with each region. Outlines around the region were only shown when the
  respondent's mouse hovered over the region.  
  
**2. Raw Qualtrics data**  

filename: *YT IP survey_October 11, 2022_08.46.csv*  
This file contains all data collected from 309 responses to our survey. Here is a guide to the condition labels:  
- 1: survey subject and IP  
- 2: average YT user and IP  
- 3: survey subject and no IP  
- 4: average YT user and no IP  

**3. Grouping queries**  

filename: *topicQueryCount.csv*  
This file contains each unique query, the topic that the query was grouped into, and the number of times the query was repeated in the original data. 

**4. Watch score**  

filename: *topicQueryCount.csv*  
This file contains a table with the statistical analyses performed using watch score, including main effect and interaction analyses. 

**5. Feature analysis**  

All tables included in this part show proportion of response, either like, dislike, or neutral, for a given feature at each condition. 95% CI on the 
proportion is given. 

- Survey subject IP

filename: *featureProportions_surveySubject_IP.pdf*  

- Average YT user IP

filename: *featureProportions_averageYTUser_IP.pdf*  

- Survey subject no IP

filename: *featureProportions_surveySubject_noIP.pdf*  

- Average YT user no IP

filename: *featureProportions_averageYTUser_noIP.pdf*
