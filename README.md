# Amazon-Echo-Buttons-Trivia
This is an Alexa Simpsons Trivia Skill that uses Echo Buttons You can Edit the content of the skill in the index.js (its zipped so it can be easly be prossessed by Lambda) 

*******HOW TO LINK SKILL TO AWS LAMBDA CODE*******

1)make sure youre region is set to N.Virginia
2)Add alexa skillskit trigger
3)upload entire zip file in Upload function
4)test "Alexa Start" and see if it runs (if it doesnt, something is wrong with your code)
5)if step 4 is completed then Save ARN (should be in the top right corner)
6)go to your developer console
7)Get on interfaces
8)Click Alexa Gadget  
9)Go to Endpoints
10)Paste ARN
11)Copy Json from file
12)paste Json into Json Editor

This should get you a Basic Button Trivia Skill, Let me Know if you are having trouble with any of these steps... (I know you can edit code in the Alexa developer console now, but this file is just to big to do so)
