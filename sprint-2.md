# Sprint 2 Tasks Completed
## Monday
- Added a new table named 'User_Results' to store user's results after their quiz(this will be overwritten if they have existing results and they take another quiz)
- Changed our NEXT logo to the Client's Provided logo.
- Changed the styling for our home page 'Start Here' button
### Evidence:
<div style="display: flex">
  <img src="Evidence/user-results-table.png" alt="Image showing a new table named 'User_Results' that will store the user's quiz results and be compared with job roles" style="width: 400px"/>
  <img src="Evidence/new-logo-and-start-btn.png" alt="Image showing our new NEXT logo and updated Start here button to suit the theme" style="width: 600px"/>
</div>

## Tuesday
- Added details for the 'Questions' table from the database to our quiz page.
- Fixed issue with buttons during the quiz not being selected after click
- Addes two columns to Questions table names 'type' and 'branch'

### Evidence:
  <img src="Evidence/questions-from-db-code-1.png" alt="Image showing the code i added to pull the questions details from the db to our website" style="width: 800px"/>
  <img src="Evidence/questions-from-db-code-2.png" alt="Image showing the code i added to pull the questions details from the db to our website" style="width: 800px"/>
<div style="display: flex">
  <img src="Evidence/button-selected.png" alt="Image showing buttons remaining selected and remaining green" style="width: 600px"/>
  <img src="Evidence/new-columns.png" alt="Image showing two new columns added to the questions table 'type' and 'branch'" style="width: 350px"/>
</div>

## Wednesday
- Created a new table named 'Job_Roles' that will store various job roles the candidate could be suggested for after the quiz and will display their relevant details and a link if possible
### Evidence:
 <img src="Evidence/job-roles-table.png" alt="Image showing a new table named 'Job_Roles' that will store any NEXT careers job roles and their details" style="width: 400px"/>
 
## Thursday
- Added extra columns to the 'Job_Roles' to allow each job role to hold values for each category(Analytics,Creativity,Communication).
- Made the job skills details from the db appear on the website in a bullet point list format.
### Evidence:
 <img src="Evidence/new-jobRole-table-columns.png" alt="Image showing three new columns added to the questions table 'AnalyticaL','Creativity' and 'Communication'" style="width: 350px"/>
 
## Friday
- Filled out our template for our Testing plan outlining everything used to test our project and compare our test cases to check whether they work as intended or not.
- changed the appearance of the buttons on the results page and ensured our 'Register' button for that page only displayed if the user is not logged in. If they are, display a 'View Profile' button instead.
### Issue (Resolved)
- During the last day of our second sprint, we all faced an issue with our database's Vcore seconds being fully used for the month (Microsoft Azure) and no longer having any access with our tables.
- To resolve this issue, I made another database with a slight name change and ,as i luckily saved our previouse CREATE and INSERT queries for all our tables, pasted all our details back in the db fixing the errors.
### Evidence:
<img src="Evidence/visit-account-btn.png" alt="Image showing buttons remaining selected and remaining green" style="width: 900px"/>
<img src="Evidence/register-btn.png" alt="Image showing two new columns added to the questions table 'type' and 'branch'" style="width: 950px"/>
<img src="Evidence/testing-plan-document.png" alt="Image showing the introduction section of our Testing Plan" style="width: 600px"/>
