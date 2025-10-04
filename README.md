# EXP-2 Welcome message in Message box with IF Condition and Switch case
## NAME : KARSAVARTHAN R R
## REG.NO : 212223230100
## AIM :
to create a Welcome message in Message box with IF Condition and Switch case.

## PROCEDURE :
IF Condition Robot (special for RAM)

IF:
if name = RAM → say Welcome Mr. Ramachandran

else → say Welcome

steps
open UiPath Studio → make new Process → open Main.xaml.

drag a Sequence.

create variable → userName (String).

drag Input Dialog:

Title: Enter Name

Label: Please type your name:

Result → userName

drag an If activity:
Condition → userName.ToUpper = "RAM"

inside Then → add Message Box:
Text → "Welcome Mr. Ramachandran"

inside Else → add Message Box:
Text → "Welcome " & userName

Run ▶ → try with RAM and with other names.
2) SWITCH Case Robot (different greeting for every name)
RAM → Welcome Mr. Ramachandran

SITA → Welcome Ms. Sita Devi

JOHN → Welcome Mr. John Carter

anything else → Welcome

steps
add variable userName (String).

drag Input Dialog →

Title: Enter Name

Label: Type your name:

Result → userName

drag a Switch activity:
TypeArgument → String

Expression → userName.ToUpper

Add Case "RAM" → Message Box:
"Welcome Mr. Ramachandran"

Add Case "SITA" → Message Box:
"Welcome Ms. Sita Devi"

Add Case "JOHN" → Message Box:
"Welcome Mr. John Carter"

Add Default → Message Box:
"Welcome " & userName

Run ▶ → type different names.

## WorkFlow:
 <img width="1920" height="1080" alt="RPA 2 1" src="https://github.com/user-attachments/assets/ad50e210-febe-461a-bbe8-dccf240eb2d4" />


## Output:
<img width="1920" height="1080" alt="RPA 2" src="https://github.com/user-attachments/assets/563d86c0-9b22-4431-8b90-052613c12388" />

## IF-ELSE:
 <img width="1920" height="1080" alt="RPA 2 3" src="https://github.com/user-attachments/assets/0159f395-cc9b-4383-8eb0-e0549361ee5b" />


## SWITCH:
 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9f9fdf9b-f596-458e-aaa3-e0c47c84adf4" />
<img width="1920" height="1080" alt="RPA 2 3" src="https://github.com/user-attachments/assets/44e8045b-8b12-4fb7-bed6-e6b2f40594dd" />


## RESULT:
Thus the process to display Welcome message in Message box with IF Condition and Switch case is created successfully.



