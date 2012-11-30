crackcode
=========

Game to crack the code in 10 attempts

This game is inspired by the Mastermind game. 

Objective is to Crack the code using characters VIBGYOR rainbow colors. 
<br>
V - Violet
I - Indigo
B - Blue
G - Green
Y - Yellow
O - Orange
R - Red

So a random code is generated everytime the game is initialized.

Eg: BGRO

The user has 10 attempts to crack the code. On input of any code the user if provided a feedback. 
Using two separate codes C & P.
C - Indicates a Color Match in the code. (Position incorrect)
P - Indicates Both Color and Position Match.

Codes P & C are mutually exclusive, which means for a single code you could either only have C or P as outputs.

Sample Execution
----------------
Secret Code:  BGRO (Hidden not displayed)

User Attempt 1: VBGY
Output: CC
User Attempt 2: RBGY
Output: CCC
User Attempt 3: RBGO
Output: PCCC
User Attempt 4: ORGB
Output: CCCC
User Attempt 5: BRGO
Output: PPCC
User Attempt 6: BGRO
Success, You cracked the code.