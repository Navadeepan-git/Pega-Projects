# Pega-Projects

# ABC Recruitment Usecase

Description:

OJP is an organization that wants to use a Pega 8 application to automate their Recruitment process. 
Any Job seeker should be able to login to this application and apply for job. Job seeker can 
view the open positions available and can select his/her suitable position to apply. 
The Job application case should capture the personal details, educational qualifications, 
work experiences, skills. Once the information is submitted, the case should get routed to 
the manager for approval. The manager can approve or reject the application. In any case, 
an email should be sent to the job seeker informing him of the manager’s decision. 
If approved, the date of interview will be fixed by the manager and it is communicated to 
the candidate by email. The interview child case will be started on the day of interview. 
The interviewer will view the details of the candidate, conduct the interview and either 
select or reject the candidate. The result of the interview (Selected/Rejected) will be sent 
back to the Parent case. The parent case will wait till the child case is resolved. In the parent case, manager will 
verify the result of the interview, and the mail will be sent to the selected candidate.

Concepts Covered
1. Case Design (Primary & Alternate stages)
2. Multi step form
3. Optional Actions
4. Child case, Case dependency using wait shape 
5. Data Design
6. Data Transform
7. Data Propagation
8. Locally Sourced Data
9. Data pages
10. Correspondence
11. Validations
12. Reports
13. Delegation

# To Run Project

Download zip file and import it in your pega portal. Just run it with needed operators. Happy!!!
