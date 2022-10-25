![Recruiting agency](https://github.com/aubin560/recruiting_agency_project/blob/main/Recruiting_Agency_Project%20(1).png)

## SCENARIO
Let’s assume that I am a junior data analyst at a recruiting agency. This recruiting agency helps all sorts of companies find skilled people to fill open data analytics jobs. The agency has collected data about job applications for opportunities posted on its website for the year 2019. 

The agency has asked your team to optimize its online application process. Your assignment is to summarize the agency’s job application data. In particular, you want to answer the following questions: 

- What was the total number of applications received per month in 2019?
-	Which months had the least and greatest number of total applications received? 
-	What was the average number of applications received per month?

To do this, you’ll work with a spreadsheet. You’ll use spreadsheet functions to make calculations based on your data and create a custom data table to summarize your results. 

## BUSINESS TASK
The agency has asked my team to optimize the online application process. The purpose of the analysis was to discover information about these questions:
-	What was the total number of applications received per month in 2019?
-	Which months had the least and greatest number of total applications received? 
-	What was the average number of applications received per month?
Insights from these questions will help the agency to summarize the job application data then the summary will enable stakeholders to take some data-driven-decisions. 

## DESCRIPTION OF DATA SOURCE
The agency’s data contains information about all of the data analytics job applications received in 2019. The data includes the following column headers: Applicant ID, Date, Job Title, Job Location, Hired, and Easy Apply. Below is a description of each column header and sample values.

![data description](https://github.com/aubin560/recruiting_agency_project/blob/main/charts/data%20description.png)

## DATA CLEANING DOCUMENTATION AND MANIPULATIONS
#### Data cleaning verification checklist 

<table>
  <tr>
    <th>COMMON PROBLEMS</th>
    <th>TOOL USED</th>
    <th>OBSERVATION</th>
  </tr>
  <tr>
    <td>Null data</td>
    <td>Conditional formatting and filter</td>
    <td>I found no missing value in the dataset</td>
  </tr>
  <tr>
    <td>Misspelled words</td>
    <td>Filter</td>
    <td>
      I filtered the hired column and for easy_apply to check if the words were well spelled. We have only two data points that are: True or false. 
      I filtered the months column to check if we either or not the months of the year were well spelled. And I found no misspelled words. 
    </td>
  </tr>
  <tr>
    <td>Mistyped numbers</td>
    <td>Sort and filter</td>
    <td>I don’t have any mistyped number </td>
  </tr>
  <tr>
    <td>Extra spaces and characters</td>
    <td>Trim function</td>
    <td>I removed extra spaces in all the dataset </td>
  </tr>
  <tr>
    <td>Duplicates</td>
    <td>Remove duplicate function</td>
    <td>I found no duplicated data </td>
  </tr>
  <tr>
    <td>Mismatched data types</td>
    <td>------</td>
    <td>I corrected data types</td>
  </tr>
  <tr>
    <td>Messy(inconsistent) string</td>
    <td>------</td>
    <td>No inconsistent string</td>
  </tr>
  
  <tr>
    <td>Messy (inconsistent) data formats</td>
    <td>------</td>
    <td>No inconsistent data format</td>
  </tr>
  
   <tr>
    <td>Misleading variable labels (columns)</td>
    <td>------</td>
    <td>No misleading variable </td>
  </tr>
  
  <tr>
    <td>Business Logic</td>
    <td>------</td>
    <td>My data make sense to answer the business question. </td>
  </tr>
</table>

No data manipulation in order to answer the questions that have been asked.

## SUMMARY OF THE ANALYSIS

####  First question to be answered:

What was the total number of applications received per month in 2019?

I created a pivot table to quickly calculate the total number of applicants received per month.

Rows = months and Values = id 

![first answer](https://github.com/aubin560/recruiting_agency_project/blob/main/charts/First_answer.png)

#### Second question to be answered:

Which months had the least and greatest number of total applications received? 

I used the min function to get which month had the least number of applicants and the max function to get the month with the greatest number of total applicants

![second answer](https://github.com/aubin560/recruiting_agency_project/blob/main/charts/Second%20answer.png)

#### Third question to be answered 

What was the average number of applications received per month?

We used the average function to get the average number of applicants received per month.

![third answer](https://github.com/aubin560/recruiting_agency_project/blob/main/charts/Third%20answer.png)

## SUPPORTING VISUALIZATION AND KEY FINDINGING 

![Applicants per month](https://github.com/aubin560/recruiting_agency_project/blob/main/charts/Number%20of%20applicants%20per%20month.png)
