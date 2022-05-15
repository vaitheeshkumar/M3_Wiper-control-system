## OUTPUT
1) User button is hold for two seconds,the red LED is on
2) Wiper Speed is LOW
3) Wiper Speed is MEDIUM
4) Wiper Speed is HIGH 
5) User button is pressed and hold for 2 seconds, the red LED is off

 
# TEST CASES 
# High Level Test Cases
| Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | STATUS |
| --------|:------------|:--------|:--------|:-----------|:-------------|
| 1 | check if the BUTTTON is pressed | program execution | Microcontroller/Engine starts | LED ON(RED)| PASS |
| 2 | check if the BUTTTON is pressed | program execution | WIPER starts | LED ON(BLUE)| PASS |
| 3 | check if the BUTTTON is pressed | program execution | WIPER starts | LED ON(GREEN)| PASS |
| 4 | check if the BUTTTON is pressed | program execution | WIPER starts | LED ON(ORANGE)| PASS |
| 5 | check if the BUTTTON is pressed | - | Microcontroller/Engine stops | LED TURNED OFF| PASS |
# LOW LEVEL TEST CASE
 | Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | STATUS |
 | --------|:------------|:--------|:--------|:-----------|:-------------|
 | 1 | check if the BUTTTON is pressed | program execution | Microcontroller/Engine starts | LED ON(RED)| PASS |
 | 2 | check if the BUTTTON is pressed again | program execution | WIPER starts and speed of wiper is slow | LED ON(BLUE) | PASS |
 | 3 | check if the BUTTTON is pressed again | program execution | WIPER starts and speed of wiper is moderate | LED ON(GREEN) | PASS |
 | 4 | check if the BUTTTON is pressed again | program execution | program execution WIPER starts and speed of wiper is good | PASS |
 | 5 | check if the BUTTTON is pressed again | - | Microcontroller/Engine stops | LED TURNED OFF | PASS |
