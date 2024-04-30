1. The bug was that the js program was treating the inputs from the textboxes as strings, thus when the program added num1 and num2, they were treated as strings and concatenated instead of actually added. So '2' + '2' = 22 instead of 4

2. I would fix it by parsing the inputs num1 and num2 into integers inside the sum function, therefore when they are added in result, they are added as numbers instead of strings, giving the proper summation for the program to run.
