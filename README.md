# Amazon-Echo-Buttons-Trivia
This is an Alexa Simpsons Trivia Skill that uses Echo Buttons You can Edit the content of the skill in the index.js (its zipped so it can be easly be prossessed by Lambda) 

HOW TO LINK SKILL TO AWS LAMBDA CODE*******

make sure youre region is set to N.Virginia
Add alexa skillskit trigger
upload entire zip file in Upload function
test "Alexa Start" and see if it runs (if it doesnt, something is wrong with your code)
if step 4 is completed then Save ARN (should be in the top right corner)
go to your developer console
Get on interfaces
Click Alexa Gadget  
Go to Endpoints
Paste ARN
Copy Json from file
paste Json into Json Editor

This should get you a Basic Button Trivia Skill, Let me Know if you are having trouble with any of these steps... (I know you can edit code in the Alexa developer console now, but this file is just to big to do so)
