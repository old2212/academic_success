# academic_success
Predict students' dropout and academic success


1 - Data analysis
Mostly categorical : marital type, classification dad/mum activity
Few numerical discrete value : grades
few numerical continuous data : GDP, grades, age of enrollment

Y analysis : 50% graduate, 30% drop out, the rest enrolled (double/repeat a year?)

Questions : unit credited ? Unemployment rate? Inflation? GDP?

--> first thoughts : 
- check the correlation with the age of enrollment, scholarship holder, parent's occupation, previous grade, marital status, 
- Do a heatmap for numerous value like parents professions, previous qualification
- Do pie chart for binary a few classes features
- Do barchart/groupby for numerical discrete/continuous values.
Do a heatmap : for 


Insigths :
Marital status : 2 and 4 are increased significantly (Married and divorced)
previous qualification : 12 - Other - 11th year of schooling --> slightky increase chances of dropout
Nationality : No impact
form of application:  > 23y related to dropout
Previous qualification : high correlation
Father's profession : (not qualification) is related
Educational special need : no correlation by category
Debtor : strong correlation
Age at enrollment : strong correlation


Selected features :
Previous qualification
Father's qualification
Debtor
Age at enrollment
Scholarship


Try :
Booset model with few params (no idea what do they mean)

save the model and try it on the validation test
