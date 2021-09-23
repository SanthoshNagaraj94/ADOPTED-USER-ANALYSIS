# ADOPTED-USER-ANALYSIS
REPORT FOR THE USER ADOPTION-ANALYSIS     
                      
ANALYSING CONCEPT
•	With The Groping Function I GroupUp The User Id And Count The Number Of Times Log By Indiduval User And Merge The Logg Count Into User Signup Table.
•	Using Time Stamp Of Log Analysed The Number Of Log Atleast 3 Times Per Week And Merge It With  The User Signup Table And Make The Adopted Colum With It.
•	Compare Each Factor Influence The Adoptability Of User(Creation Source, Marketing Drip Enabled, Enabled Opted To Mail And Time Span To Use The App)

ML MODEL USED FOR TRAINING AND PREDICTION
•	Here I Am Using Logistic Regression Algorithm To Train The Model.
•	By Using Classification Report We Get 99.5% Accuracy  
•	Factors                               = [Creation Source, Opted To Mailing List, Marketing Drip, Time Span]
•	Regression Co-Efficient    = [-0.15446028, -0.14785362, 0.08701948, 1.02253987]
•	Intercept		              = [-7.64831909]
    
SUMMARY

•	Org_Invites Was Play Major Role In The Adopted User And Google_Auth Is The Least 
•	0.15 Factor of Creation Source Increase In Adapted User.
•	0.14 Factor of Enable To Marketing Mail Increase The Adapted User.
•	0.08 Factor of Opted To Mailing List Decrease The Adapted User
•	Factor Of Time Taken To Log Decrease  The Adapted Used

FUTURE RESEARCH DATA TO BE INCLUDED

•	 Personal info: gender, married status, income, location
•	Social info     : No. of social media active, No of friends, social media post regard this product category.
•	App installed: categories of app used previously. 
•	Need of using this app (reason).
