<p align="center">
  <img src="https://github.com/SirMore/REDWARN/blob/main/Figures/REDWARN_img.png" width="450" title="REDWARN">
</p>

# TABLE OF CONTENTS
- [REDWARN](#redwarn)
  * [Team Members:](#team-members-)
  * [Mentors:](#mentors-)
  * [Background and Description:](#background-and-description-)
  * [Project Plan:](#project-plan-)
      - [Tasks and Sub-Tasks](#tasks-and-sub-tasks)
      - [Resources Required](#resources-required)
  * [Implementations:](#implementations-)
    + [Data and Preprpocessing](#data-and-preprpocessing)
      - [DATA SOURCES](#data-sources)
      - [DATA DESCRIPTION:](#data-description-)
  * [Deliverables:](#deliverables-)
    + [Team Introduction Slide:](#team-introduction-slide-)
    + [Goals + Tasks:](#goals---tasks-)
    + [Project Plan:](#project-plan--1)
    + [Updates:](#updates-)
  * [Resources:](#resources-)

***

# REDWARN
REDWARN (Reddit Data for Early Warning and Response to Pandemics) is an acronym for Reddit Data for Pandemic Preparedness.
This project is part of HackHPC - SC23's HPC in the City: Pandemics hackathon.  In this project, conversations in the  [Austin sub-Reddit](https://www.reddit.com/r/Austin/) are used to:
1. Track community opinions to pandemic-related policies.
2. Estimate community pandemic preventative behaviors such as Masking, Vaccination, and Social Distancing.

For more infomation please check out the HackHPC webpage [here](https://hackhpc.github.io/hpcinthecity23/).

## Team Members:
- Xinyi Miao
    - [LinkedIn]()
    - [University of Science and Technology of China](https://en.ustc.edu.cn/)
- Coreen Mullen
    - [LinkedIn](https://www.linkedin.com/in/coreenmullen/)
    - [Elizabeth City State University](https://ecsu.edu/)
- Qimora Mason
    - [LinkedIn](https://www.linkedin.com/in/qimora-mason)
    - [Elizabeth City State University](https://ecsu.edu/)
- Ahmad Samyono
    - [LinkedIn](https://www.linkedin.com/in/ahmadsamyono)
    - [University of Texas at Tyler](https://www.uttyler.edu/)
- Rachel Foong
    - [LinkedIn](https://www.linkedin.com/in/rachel-foong1)
    - [University of Texas at Austin](https://www.utexas.edu/)
- Evans Etrue Howard
    - [LinkedIn](https://www.linkedin.com/in/evans-etrue-howard-phd-a1228058/)
    - [University of Texas at El Paso](https://www.utep.edu/)


## Mentors:
- Oluwasegun Ibrahim
    - [LinkedIn](https://www.linkedin.com/in/oluwasegunibrahim)
    - [Center for Pandemic Decision Science](https://www.centerforpandemicdecisionscience.org/)
- Emily Javan
    - [LinkedIn](https://www.linkedin.com/in/emily-javan-8b685293/)
    - [Center for Pandemic Decision Science](https://www.centerforpandemicdecisionscience.org/)
- Lydia Fletcher
    - [LinkedIn](https://www.linkedin.com/in/lydia-fletcher-3b6b9a272/) 
    - [Texas Advanced Computing Center](https://www.tacc.utexas.edu/)


## Background and Description:
**Research Question 1: Can we use Reddit conversations to track community opinions to pandemic-related policies?**

Description 1: A major source of uncertainty during the pandemic was our inability to anticipate community responses to pandemic policies. For example, not all individuals followed guidelines related to mask wearing or business closing when they were implemented.Many regions hired communication specialists and carried out traditional surveys to guide their decision-making, but these can be costly for measuring public opinions in real-time. Community conversations on social media platforms may serve as an inexpensive and real-time option for tracking community sentiment to guidelines. For this project, we will ask groups to harness the text communications available on Reddit city-level subreddits to estimate community opinions and sentiment related to policy changes during the pandemic. We will provide Reddit data from Austin and a timeline of impactful Austin policies to participants, and it will be up to participants to come up with strategies to do so.

**Research Question 2: Can we use Reddit conversations to estimate community pandemic preventative behaviors?**

Description 2: It was difficult to measure community protective efforts such as vaccination or mask wearing behaviors during the pandemic in real-time, so researchers resorted to traditional and digital surveys. However, these surveys were costly and were discontinued following the emergence of the Omicron variant. However, infectious disease modelers and public health officials continue to have a pressing need to estimate and anticipate changes to mask.wearing and vaccination rates. Community conversations on social media platforms may provide a lens to community protective behaviors. For this project, we will ask groups to harness text conversations from Reddity city-level subreddits to estimate the rates which community members are wearing masks and being vaccinated. To do so, we will provde access to Reddit conversations from multiple cities alongside the estimates for mask wearing and vaccination rates from the same time period.

## Project Plan:

**Project Title**: Community Sentiment Analysis on Pandemic Policies

**Project Objectives**:
1. Goal 1: Track community sentiments on pandemic policies.
2. Goal 2: Estimate community opinion and accuracy based on real-world responses.

#### Tasks and Sub-Tasks

**Task 1: Sentiment Analysis**
- Sub-Task 1.1: Data Cleaning
  - Clean the "text" column to remove noise.
  - Handle missing values, if any.
- Sub-Task 1.2: Sentiment Scoring
  - Implement a sentiment analysis model.
  - Classify text sentiments as positive, negative, or neutral.

**Task 2: Time Series Analysis**
- Sub-Task 2.1: Sentiment Aggregation Over Time
  - Aggregate sentiment scores on a daily/weekly basis.
- Sub-Task 2.2: Trend Analysis
  - Identify trends and patterns in sentiment over time.
  - Correlate sentiment trends with major pandemic events or policy announcements.

**Task 3: Distribution of Posts Over Time**
- Sub-Task 3.1: Identify Active Authors
  - Analyze the frequency of posts from individual authors.
- Sub-Task 3.2: Author Activity Over Time
  - Determine the distribution of posts from the most active authors over time.

**Task 4: Temporal Analysis**
- Sub-Task 4.1: Temporal Sentiment Patterns
  - Analyze how sentiments change at different times (e.g., before and after policy announcements).
- Sub-Task 4.2: Response Time Analysis
  - Study the time taken for sentiment shifts after policy changes.

**Task 5: Topic Modeling**
- Sub-Task 5.1: Preprocessing for Topic Modeling
  - Prepare the text for topic modeling (tokenization, stop-word removal, etc.).
- Sub-Task 5.2: Extracting Topics
  - Apply algorithms like LDA (Latent Dirichlet Allocation) to identify prevalent topics in the text body.
- Sub-Task 5.3: Topic Correlation with Sentiment
  - Correlate the identified topics with sentiment scores to understand context.

#### Resources Required
- Data Set with "body" column and author information.
- Sentiment analysis tools or libraries (e.g., NLTK, TextBlob, or custom ML models).
- Time series analysis tools (e.g., Python's pandas and statsmodels).
- Topic modeling tools (e.g., Gensim for LDA).
- Computational resources for data processing and analysis.
- Github.
- Human resources: computer scientists, data analysts, and domain experts (mentors).
- Data analysis tools (Python and R).


**Project Scope**:
- Analyzing sentiment from a given dataset.
- Conducting time series analysis.
- Identifying the most active authors.
- Performing temporal analysis.
- Implementing topic modeling.

**Project Communication Plan**:
- Regular team meetings on Zoom and Discord.
- Daily status reports to mentors.
- Daily progress presentations to staff.

**Project Risks and Mitigations**:
- Data Quality: Mitigation involves data cleansing and validation.
- Scope Creep: Clearly define project scope and objectives.
- Technical Challenges: Allocate time for problem-solving and troubleshooting.


**Project Timeline**:
- Task 1: Sentiment analysis (Done).
- Task 2: Time series analysis (Done).
- Task 3: Post distribution analysis (Done).
- Task 4: Temporal analysis (5 hours).
- Task 5: Topic modeling (Done).

## Implementations:
- The implementation of this code is that it is able to do all of the computational analysis needed to then compare results and get the answers to our main goal questions.

***
### Data and Preprpocessing

#### DATA SOURCES
1. [Staged alert timeline](https://docs.google.com/spreadsheets/d/1WuiltmgAQsmVy3C8V_S9OvVld2PNcXtzcBxKkbJbStM/edit?usp=sharing)

2. [Reddit data](https://utexas.box.com/s/rnyd9y4w5k8vxg9is4pw11670f943zt9)

3. [More organized datasets](https://docs.google.com/spreadsheets/d/1EJ4_YT9vfSXQ-tKHc1KBMeOVhbcBARESICiMXePbP1s/edit?usp=sharing)

4. [Disease Data Sources (not really organized)](https://docs.google.com/spreadsheets/d/1V6WGQRDkD38MZrfg4urQvhmEdERBm-MHnRH1Vsjm4CY/edit?usp=sharing)

5. [Staged-Alert Paper](https://covid-19.tacc.utexas.edu/media/filer_public/f9/58/f95850cc-1428-4966-8873-601bae0dc0e6/projections_for_austins_covid-19_staged_alert_system_incorporating_reported_cases_as_additional_indicator.pdf)

#### DATA DESCRIPTION:
The main data used for this project is the Reddit data which consist of post of users in the Austin subreddit from January 01, 2019 to August 22, 2023. This data includes a very detailed set of information about the posts. Some of the labesl fro the individual posts is the date, author, and the body of th the text. This data also underwent text analysis by LIWC-22 software. The text analysis results give an even deeper insight into the contents of the different 'body' messeges. 

<p align="center">
  <img src="https://github.com/SirMore/REDWARN/blob/main/Figures/redit/see.PNG" width="750" title="page1">
</p>

## Deliverables:
***
### Team Introduction Slide:
<p align="center">
  <img src="https://github.com/SirMore/REDWARN/blob/main/Figures/main_page.png" width="450" title="page1">
</p>

***

### Goals + Tasks:
<p align="center">
<img src="https://github.com/SirMore/REDWARN/blob/main/Figures/map_goals.png" width="450" title="page2">
  </p>

***

### Project Plan:
<p align="center">
<img src="https://github.com/SirMore/REDWARN/blob/main/Figures/projectplan.png" width="450" title="page3">
  </p>

***

### Updates:
<p align="center">
<img src="https://github.com/SirMore/REDWARN/blob/main/Figures/updates.png" width="450" title="page4">
  </p>

***

## Resources:
- https://docs.google.com/spreadsheets/d/1WuiltmgAQsmVy3C8V_S9OvVld2PNcXtzcBxKkbJbStM/edit?usp=sharing
- https://utexas.box.com/s/rnyd9y4w5k8vxg9is4pw11670f943zt9
- https://covid-19.tacc.utexas.edu/media/filer_public/f9/58/f95850cc-1428-4966-8873-601bae0dc0e6/projections_for_austins_covid-19_staged_alert_system_incorporating_reported_cases_as_additional_indicator.pdf




