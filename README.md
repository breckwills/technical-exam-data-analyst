Welcome to the WSJ Data Lab takehome exam. Please submit answers in the form of a Jupyter notebook, in any scripting language of your choice. Please email zipped files to breck.wills@dowjones.com within one week of receiving the exam.

## Scenario

The WSJ Data Lab is helping design a campaign to target attendees of the upcoming [SXSW](https://www.sxsw.com/) festival in 2019. The team would like to better understand website traffic during the most recent SXSW festival (March 2018) to inform what type of content to promote in 2019.

The data in `data.csv` is a sample of website traffic to [wsj.com](https://www.wsj.com/) from first-time visitors who are non-subscribers in the Austin, Texas area (based on IP address). 

The objective is to identify which content will turn first-time visitors into loyal readers and subscribers. 

**Note: Each row in `data.csv` represents a single page view.**

## Data

| Column Name     | Description       |
| --------------- | ----------------- |
| customerID | unique customer ID
| firstVisitDate | Date and time of first visit
| secondVisitDate | Date and time of second visit, if any
| articleID | unique ID of the article read on the first visit
| section | section of the article read on the first visit
| author | author(s) of the article read on the first visit
| headline | headline of the article read on the first visit
| topicKeywords | topic keywords in article read on the first visit
| totalVisits | total visits to-date since `firstVisitDate`
| wordCount | word count of the article
| videoCount | number of videos in article


## Questions

1. What percent of customers returned after the first visit?

2. What are the top three best-performing stories in each section, by pageviews?

3. Based on this data, would you choose to promote a Tech story or a Markets story on social media? Why?

4. Create a visualization exploring the relationship between content characteristics (section, author, keywords etc...) and returning visitors. This is an open-ended task. Briefly describe the visualization and the insight.

5. Create a simple model predicting the likelihood of a first-time visitor returning.

6. What additional data would you add to improve the model? (Answer in 3-5 sentences)


