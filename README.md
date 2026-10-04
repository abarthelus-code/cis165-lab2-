# cis165-lab2-

Plan to Run "sum.cpp"

Create Variables for 2 integers, make a formula to add them both up, label as "sum" in final answer.

Plan to run "mpg.cpp"

Create Variables for Miles and Gallons, make formula to divide miles by gallons, label the result with "miles per gallon" at the end.


Program	                  Values used	                Expected result before running	Actual output	    Match or fix
sum.cpp — assigned values	50 and 100	                       150	                    150	                 Match
sum.cpp — changed values	65 and 265 	                       340	                    340	                 Match
mpg.cpp — assigned values	312 miles; 16 gallons	              19.5	                  19.5	               Match
mpg.cpp — changed values	560 miles; 20 gallons     	        28	                    28	                 Match

All values tested in code

sum.cpp: explain how the starting values move through your calculation into total and then to the output. Why store the calculation in total before printing?
- Calculation is stored in total before printing so that if the values are changed its easy to just run the code again to instantly get the new result without having to change everything.

mpg.cpp: explain the formula, the data types you chose, and what can happen if C++ performs division using two integer operands. Trace your changed-value test from the values through the result.

- The formula I used was Miles/Gallons, data types used were double in case decimals show up, If C++ does division with two integers it won't produce any decimals even if the answer for the formula is one. Changed Values formula: 560/20 = 28 Miles per gallon.

To run the code in OnlineGDB upload the file into it.
