# Heat-Hunter-C-Project

[8 points] Remember that great application you wrote for Heat Hunters (Lab 6-3).  Now they want you to add a data validation feature that restricts the entered temperature.  Start with the key or your Lab 6-3 code.  Prompt for and get from the user a temperature in Fahrenheit in the range -60 to 120.  If the value is outside the range, print an error message (and nothing else except the application close).  If the value is within the range, convert it to Celsius and show both values.  Use formatted output manipulators (setw, left/right) to print the following two rows:● Fahrenheit temperature● Celsius temperatureAnd three columns:● A left-justified label.● A right-justified value.● A left-justified units (output manipulators not needed here, but don't place one space before the units name to separate it from the second column).Define constants for the column widths.  Format all real numbers to two decimal places.  Include the degree symbol in the output:● Windows users – declare a constant for the degree symbol:DEGREE_SYMBOL = (char) 167Use the constant in the output.● Mac OS users – copy the degree symbol above to your code.Run the program five times with the following Fahrenheit values.  What are the results?


2) [9 points] You've been hired by Best Bugs to write a C++ console application that calculates and displays the cost of a customer’s purchase of one item.  Prompt for and get from the user the quantity of the item purchased in the range 1-10.  If the value is outside the range, print an error message (and nothing else except the application close).  If the value is within the range, prompt for and get from the user a product character code per the following table:CodeProductCostcMemory card$30hHeadphones$350mMicrowave$54pPlayStation$300rRouter$110Use a switch statement to determine which code was entered and to set product and name variables for later calculation and printing.  Assume a value of 'c' if the user didn't enter one of the five codes.  Calculate the cost of the purchase.  Use formatted output manipulators (setw, left/right) to print the following five rows:● Quantity● Product code● Product name● Product cost● Purchase costAnd two columns:● A left-justified label (including $ where necessary).● A right-justified value.Define constants for the column widths and product prices.  Format all real numbers to two decimal places.  Run the program five times with different product codes.  Get a screenshot of each run.



[8 points] You've been hired by Letter Lovers to write a C++ console application that analyzes the types of characters in a string entered by the user.  Prompt for and get from the user a string containing at least ten characters.  Use getline() to read the string.  If the string contains fewer than ten characters, print an error message  (and nothing else except the application close).  If the string contains at least ten characters, test the third, sixth, and ninth characters to answer the following:● Is the character a digit?● Is the character alphanumeric?● Is the character punctuation?Use formatted output manipulators (setw, left/right) to print the rows and columns shown below.  Define constants for the column widths.  Run the program five times with different strings.  Get a screenshot of each run.  The output should look like this:
