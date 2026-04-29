# Customer Support Ticket Analyzer
A Python-based analysis of customer support tickets to identify recurring issues, sentiment trends, priority distribution, and service improvement opportunities.

## Table of Contents
- [Project Overview](#-project-overview)
- [Dataset](#-dataset)
- [Tools & Technologies](#-tools--technologies)
- [Data Cleaning Process](#-data-cleaning-process)
- [Exploratory Data Analysis](#-exploratory-data-analysis)
- [Key Insights](#-key-insights)
- [Sentiment Analysis](#-sentiment-analysis)
- [Recommendations](#-recommendations)
- [Conclusion](#-conclusion)

## Project Overview
This project analyzes customer support tickets to understand **customer issues, priority levels, sentiment distribution, and keyword patterns**. The analysis helps identify service gaps and provides recommendations to improve customer support performance.

### Objectives
- Analyze customer support tickets  
- Identify frequently reported issues  
- Perform sentiment analysis (Positive / Negative / Neutral)  
- Find most common keywords  
- Identify longest issue descriptions  
- Extract unique words from tickets  
- Generate actionable insights and recommendations  

## Dataset
The dataset is stored as a **dictionary-of-lists** containing the following fields:
- **Ticket No** – Unique ticket identifier  
- **Customer Name** – Customer raising the issue  
- **Issue Description** – Customer problem description  
- **Priority** – Ticket priority (High / Medium / Low)  

## Tools & Technologies
- Python  
- Lists & Dictionaries  
- Loops & Functions  
- String Manipulation  
- Basic NLP (Keyword-based Sentiment Analysis)  

## Data Cleaning Process
The following steps were applied to clean the issue descriptions:
- Removed punctuation (., ! ? -)  
- Converted text to lowercase  
- Removed leading and trailing spaces  
- Replaced multiple spaces with single space  
- Standardized slang words (ok → okay)  
- Split text into words for analysis  
These steps ensured consistent and analysis-ready text data.

## Exploratory Data Analysis
The following analyses were performed:
- Keyword frequency analysis  
- Priority distribution analysis  
- Longest issue description detection  
- Unique words extraction  
- Most common word identification  
- Ticket count by keyword  
- Sentiment classification  

### Metrics Generated
- Total tickets analyzed  
- High / Medium / Low priority count  
- Most common word  
- Unique words count  
- Longest ticket description  
- Sentiment distribution  

## Key Insights
- Total tickets analysed: **23**  
- The keyword **"good"** appears more frequently compared to other keywords  
- High-priority issues dominate the dataset with **10 tickets**  
- Rahul submitted the first ticket with the longest issue description (6 words)  
- Vikas and Priya also submitted tickets with the longest descriptions  
- A total of **44 unique words** were identified across all tickets  
- The most common word across tickets is **"good"**, with a frequency of **6**  
- Recurring words indicate issues related to response time and service quality  

## Sentiment Analysis
Sentiment analysis was performed by tracking keywords and categorizing tickets into:
- **Positive Tickets:** 10  
- **Negative Tickets:** 12  
- **Neutral Tickets:** 1  
The analysis shows slightly more negative feedback, indicating areas requiring service improvement.

## Recommendations
- Reduce response time to address "slow" and "poor" complaints  
- Improve first-contact resolution  
- Prioritize high-priority tickets  
- Provide technical training for support agents  
- Improve communication quality with customers  
- Monitor recurring issues (login, internet, technical problems)  
- Increase proactive updates to customers  
- Review negative tickets regularly  
- Maintain positive support practices  
- Implement SLA tracking for faster turnaround  

## Conclusion
- The analysis highlights both positive and negative customer experiences  
- High-priority and recurring issues indicate operational gaps  
- Sentiment analysis shows slightly more negative feedback  
- Keyword analysis helps identify common customer pain points  
- Implementing recommendations can improve service quality and customer satisfaction  
