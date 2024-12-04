# Data Portfolio: Excel


# Table of Contents

- [Objective](#Objective)
  - [User Story](#User_Story)
- [Data Source](#Data_Source)
- [Stages](#Stages)
- [Design](#Design)
  - [Dashboard Mockup](#Dashboard_Mockup)
  - [Tools](#Tools)
- [Development](#Development)
  - [Pseudocode](#Pseudocode)
  - [Data Exploration](#Data_Exploration)
  - [Data Cleaning](#Data_Cleaning)
  - [Transform the data](#Transform_the_data)
- [Testing](#Testing)
  - [Data Quality Tests](#Data_Quality_Tests)
- [Visualisation](#Visualisation)
  - [Results](#Results)
- [Analysis](#Analysis)
  - [Findings](#Findings)
  - [Validation](#Validation)
- [Conclusion](#Conclusion)
  - [Discovery](#Discovery)
  - [Recommendations](#Recommendations)
  - [Potential ROI](#Potential_ROI)
  - [Course of Action](#Course_of_Action)


# Objective
- Key issue:

The marketing team wants to find what the best coffee products are to set up marketing campaigns.

- Proposed Solution:
  
A dashboard will be created to provide actionable insights into the top coffee products globally. The dashboard will include:
- Top customers
- Sales per region
- Product sales performance
- Relevant slicers
  
These metrics will assist the marketing team decide on which coffee products would be best for the proposed marketing campaigns.

## User Story
" As the lead of the marketing team, I need to visualise key metrics through an informative dashboard to analyse global coffee sales data.

This should allow our team to identify the top performing coffee products through sales metrics. The insights gathered will drive decisions about which product is best to focus on for our new marketing campaigns and maximise potential ROI"

# Data Source

- We product performance data on coffee sales that includes:
  - Product Information
  - Customer Information
  - Order Information
  - Where the data is coming from? (The data is sourced from an independant source)
  
# Stages

1. Design
2. Development
3. Testing
4. Analysis
   
# Design

## Dashboard Questions
- What should the dashboard contain based on the above requirements?
  
- What are the initial insight questions the dashboard needs to answer?
1. Which is the best selling roast type?
2. Do loyalty cards affect sales?
3. What seasons have the highest sales?
4. Which countries have the highest sales?
5. What size of coffee has the highest sales?
6. Which coffee product performs the best?

As we progress through the analysis, these questions may develop.

## Dashboard Mockup

Recommended data visuals:
1. Timeline
2. Horizontal Time History Graph
3. Slicers
4. Horizontal bar chart

![Dashboard-Mockup](assets/images/dashboard mockup.png)

## Tools

| Tool  | Purpose                                                   |
| --------- | ----------------------------------------------------- |
| Excel     | Exploring the data                                    |
| GitHub    | Hosting the project documentation and version control |
| Mokkup AI | Designing the wireframe of the dashboard              |


# Development
## Pseudocode

- What is the general approach to solving the issue from end to end?

1. Gather the data
2. Explore the data in Excel
3. Clean the data in Excel
4. Create Relevant Pivot Tables in Excel
5. Visualise the data in Excel
6. Generate the findings based on the insights
7. Write-up documentation and commentary
8. Publish the data to relevant stakeholders


## Data Exploration

The gathered data will be audited for quality looking mainly for errors, inconsistencies, bugs and unusual characters and/or layout of data etc.

- What are the findings from the data exploration?

1. All relevant data is present within the files gathered so no need to request more data.
2. Some customers did not provide contact details in the form of an email address.
3. Some Columns have abbreviated data within that could cause confusion.

## Data Cleaning

- What do we expect the clean data to contain and what constraints are required?

1. Relevant columns should be retained.
2. All data types should be appropriate for the contents of each column.
3. There should be no null values i.e. complete data for all records.

- What are the steps needed to clean and shape the data?

1. Combine tables together
2. Edit fields with abbreviations
3. Create sales measures

### Transform the Data

The following Excel formulas were used to combine tables together, edit abbreviations and create sales data:

# Testing
## Data quality tests

- What are the data quality tests?

# Visualization

## Results

How does the dashboards look?

![Power BI Dashboard](assets/images/PowerBI dashboard.png)


# Analysis
## Findings

In this section we will answer our design stage questions:
1. Which is the best selling roast type?
2. Do loyalty cards affect sales?
3. What seasons have the highest sales?
4. Which countries have the highest sales?
5. What size of coffee has the highest sales?
6. Which coffee product performs the best?

### 1. Top 10 Youtubers with the most subscribers?

| Rank | Channel Name         | Subscribers (M) |
|------|----------------------|-----------------|
| 1    | NoCopyrightSounds    | 33.60           |
| 2    | DanTDM               | 28.60           |
| 3    | Dan Rhodes           | 26.50           |
| 4    | Miss Katy            | 24.50           |
| 5    | Mister Max           | 24.40           |
| 6    | KSI                  | 24.10           |
| 7    | Jelly                | 23.50           |
| 8    | Dua Lipa             | 23.30           |
| 9    | Sidemen              | 21.00           |
| 10   | Ali-A                | 18.90           |


### 2. Top 3 channels with the most uploads?

| Rank | Channel Name    | Videos Uploaded |
|------|-----------------|-----------------|
| 1    | GRM Daily       | 14,696          |
| 2    | Manchester City | 8,248           |
| 3    | Yogscast        | 6,435           |


### 3. Top 3 channels with the most views?

| Rank | Channel Name | Total Views (B) |
|------|--------------|-----------------|
| 1    | DanTDM       | 19.78           |
| 2    | Dan Rhodes   | 18.56           |
| 3    | Mister Max   | 15.97           |


### 4. Top 3 channels with the highest average views per video?

| Channel Name | Averge Views per Video (M) |
|--------------|-----------------|
| Mark Ronson  | 32.27           |
| Jessie J     | 5.97            |
| Dua Lipa     | 5.76            |

### 5. Top 3 channels with the highest views per subscriber ratio?

| Rank | Channel Name       | Views per Subscriber        |
|------|-----------------   |---------------------------- |
| 1    | GRM Daily          | 1185.79                     |
| 2    | Nickelodeon        | 1061.04                     |
| 3    | Disney Junior UK   | 1031.97                     |

### 6. Top 3 channels with the highest subscriber engagement rate per video uploaded?

| Rank | Channel Name    | Subscriber Engagement Rate  |
|------|-----------------|---------------------------- |
| 1    | Mark Ronson     | 343,000                     |
| 2    | Jessie J        | 110,416.67                  |
| 3    | Dua Lipa        | 104,954.95                  |


### Outcome

For the next steps we need to look at analysing the metrics that are key for generating the expected ROI for the client:

1. Subscribers
2. Total views
3. Videos uploaded

## Validation

### 1. Youtubers with the most subscribers 


#### Output

![Most views](assets/images/most views campaign.png)

# Concludion
## Discovery

What were the overall findings?



1. NoCopyrightSOunds, Dan Rhodes and DanTDM are the channnels with the most subscribers in the UK
2. GRM Daily, Man City and Yogscast are the channels with the most videos uploaded
3. DanTDM, Dan RHodes and Mister Max are the channels with the most views
4. Entertainment channels are useful for broader reach, as the channels posting consistently on their platforms and generating the most engagement are focus on entertainment and music 

## Recommendations

Actionable Insights:

![Actionable insights](assets/images/actionable insights.png)

1. **Dan Rhodes** is the best YouTube channel to collaborate with if we want to **maximize visbility** because this channel has the **most YouTube subscribers in the UK**.
   
2. Although GRM Daily, Man City and Yogcasts are regular publishers on YouTube, it may be worth considering whether collaborating with them with the current budget caps are worth the effort, as the potential return on investments is significantly lower compared to the other channels.
   
3. **Mister Max** is the best YouTuber to collaborate with if we're interested in **maximizing reach**, but collaborating with **DanTDM and Dan Rhodes** may be better **long-term options** considering the fact that they both have large subscriber bases and are averaging significantly high number of views.
   
4. The top 3 channels to form collaborations with are NoCopyrightSounds, DanTDM and Dan Rhodes based on this analysis, because they attract the most engagement on their channels consistently.



## Potential ROI
What ROI is expected based on the actionable insights?

1. Setting up a **product placement** deal with **Dan Rhodes** would make the client a net profit of **£1,065,000 per video**.
2. An **influencer marketing contract** with **Mister Max** can see the client generate a net profit of **£1,276,000**.
3. If we go with a **product placement campaign** with **DanTDM**, this could  generate the client approximately **£484,000 per video**. If we advance with an **influencer marketing campaign** deal instead, this would make the client a one-off net profit of **£404,000**.
4. **NoCopyrightSounds product placement** could profit the client **£642,000 per video** too (which is worth considering). 


## Course of Action

Based on the analysis, the best channel to partner with on a **product placement** deal would be **Dan Rhodes**.
This initial deal will be assessed againsts the marketing teams initial forecasting. If the milestones are met throughout the deal, then future partnerships with DanTDM, Mister Max and NoCopyrightSounds can be advanced.

Actioning the Insights:

1. Reach out to the teams behind each of these channels, starting with Dan Rhodes.
2. Negotiate contracts within the budgets allocated to each marketing campaign.
3. Kick off the campaigns and track each of their performances against the KPIs.
4. Review how the campaigns have gone, gather insights and optimize based on feedback from converted customers and each channel's audiences.

