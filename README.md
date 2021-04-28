# UiPath HR OnBoard New Hire

![alt text](https://github.com/bacdillon/UiPath-HR-OnBoard-New-Hire/blob/main/hr.png)

# INTRODUCTION

Looking for new ways to become more efficient by reducing the human effort needed to perform various repetitive tasks.
HR recognized Robotic Process Automation (RPA) was the integrated, scalable solution that could be applied across its organization and regional office.

# CURRENT SITUATION

George Dwell from Human resource department have to raise Service Request for new hire  to be on boarding user account creation for ServiceNow and ZOHO from ServiceNow.
IT Admin needs to remind to create user account which takes sometimes to create the IDs, will slowdown its recruiting process.
It happens human errors to create user account and assign not appropriate roles for the user.
George, doing high volume, mundane tasks for new hire on-boarding process and not having advance the human potential of the workforce.
George is looking for a new ways that the range of tasks can be automated to become more efficient by reducing the human effort needed to perform various repetitive tasks.

# PROJECT OVERVIEW

1. Pick up HR’s requests ticket information from Email with EXCEL (Employee-Onboard.xlsx) attachment downloaded. 
2. Assuming the new onboarding email ID and AD user account was present and has created. 
3. Alfred extract Service Request item from ServiceNow
4. Update into existing downloaded EXCEL file (Employee-Onboard.xlsx) 
5. Read the necessary details from EXCEL file (Employee-Onboard.xlsx) 
6. Create the onboarding user account credential which are not Single Sign-On for ServiceNow and ZOHO
7. Once the credential account has created, the bot renames the EXCEL file (Completed.xlsx) 
8. Moves the updated HR’s EXCEL to Processed folder
9. Finally, Alfred sent an email to HR Requestor and cc copy to himself, to notify activities has completed

Automation program focusing on HR- New Hirer On-boarding, IT- manage, create user account credentials, approach was to start small while planning to scale for the future to purchase IT equipment and Finance processes

# Process overview of what Alfred will do

![alt text](https://github.com/bacdillon/UiPath-HR-OnBoard-New-Hire/blob/main/Workflow.PNG)
