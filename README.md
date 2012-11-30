crackcode
=========

Game to crack the code in 10 attempts

This game is inspired by the Mastermind game. 

Objective is to Crack the code using characters VIBGYOR rainbow colors.
<br>
V - Violet
<br>
I - Indigo
<br>
B - Blue
<br>
G - Green
<br>
Y - Yellow
<br>
O - Orange
<br>
R - Red

A random code is generated everytime the game is initialized.

Eg: BGRO

The user has 10 attempts to crack the code. On input of any code the user if provided a feedback. 
Using two separate codes C & P.
<br>
C - Indicates a Color Match in the code. (Position incorrect)
<br>
P - Indicates Both Color and Position Match.

Codes P & C are mutually exclusive, which means for a single code you could either only have C or P as outputs.

Sample Execution (How to Play) -- Just Crack the code :)
------------------------------
Secret Code:  BGRO (Hidden not displayed)
<br>
User Attempt 1: VBGY
<br>
Output: CC
<br><br>
User Attempt 2: RBGY
<br>
Output: CCC
<br><br>
User Attempt 3: RBGO
<br>
Output: PCCC
<br><br>
User Attempt 4: ORGB
<br>
Output: CCCC
<br><br>
User Attempt 5: BRGO
<br>
Output: PPCC
<br><br>
User Attempt 6: BGRO
<br>
Success, You cracked the code.
<br><br>