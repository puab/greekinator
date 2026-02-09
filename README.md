# What is this
Tool to visualize options prices on futures contracts with the same underlying. Nasdaq oriented, because that's what i trade

# How to use
Grab data from gexbot using the `!triggers qqq` command (remove the "---TRUNCATED---" row), paste it into the "https://puab.github.io/greekinator" input to get an input string. Grab the input string and put it inside of the text box in the indicator's settings.  

You can, of course, also input your own data string. The format is:  
`{dteNum}dte,{volTriggerStrike},{gammaWallStrike},{callWallStrike},{putWallStrike}`

For example,  
`0dte,606,610,610,610\n1dte,602,610,618,612`  

# Symbol definition
▲ -> call wall  
▼ -> put wall  
Γ -> gamma wall  
⇑ -> vol trigger  

<img width="627" height="577" alt="image" src="https://github.com/user-attachments/assets/42cd3d9b-e4ff-4823-af3f-23e3ac747f08" />

