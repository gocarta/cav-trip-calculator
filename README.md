# cav-trip-calculator
Calculate the Cost of a Care-a-Van Trip 

## cost
| program | description | cost |
| --------- | ---------- | ----|
| 1 | ¾ mile from fixed route | ??? |
| 2 | outside program 1 and inside City of Chattanooga | ??? |
| 3 | inside Red Bank and East Ridge | ??? |

## data sources


## cost calculation algorithm
- Step 1: assign program to origin and destination.
- Step 2: calculate the highest program. For example, traveling from program 1 to program 3, would make it a "program 3" trip for the cost calculation.
- Step 3: look up the cost for that program

## assigning a program details
- Check if point is within 3/4 mile of a fixed route.  If yes, program 1; if no, continue
- Check if point is within program 2 or program 3