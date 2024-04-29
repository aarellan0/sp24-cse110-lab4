1. In line 12, 3 will be printed. I is declared as a var inside the for loop and increments for every item in prices, which there is 3. After the loop, it keeps this value.

2. Line 13 will return 150, the last value of discountedPrice. This value changed for every iteration of the loop and for every item in prices. The last item in prices is 300, and after applying the 0.5 discount then becomes 150.

3. Line 14 returns 150, finalPrices value changed for every item in prices. The last item was 300, and after applying the calculation, the last value that finalPrices had was 150.

4. This function returns the discounted array [50, 100, 150]. This is because the function applies the input discount to every item in the input prices array of 100,200,300. The discount was 0.5, and appying that to the original values gets 50,100,150

5. Line 12 will cause an error because i is out of scope with the let declaration. i is only witin the scope of the loop, therefore trying to access it afterwards results in error

6. line 13 causes an error because discountedPrice only exists witin the scope of the loop (with let declaration). Therefore attemtping to access it after the loop causes an error

7. line 14 returns 150. finalPrice updates after every iteration of the for loop and for every item in prices. The item item in the input array is 300, and after applying 0.5 discount, finalPrice becomes 150. This value is returned because finalPrice was declared at the beginning of the function (with let), thus the entire function has access to it.

8. This function returns the discounted array [50,100,150]. The function works by taking every element in the input array and applying a 0.5 discount, adding the reduced values to a new array. The original input values were 100,200,300, and after applying a discount of 0.5, it then becomes 50,100,150

9. line 11 returns error because i is only defined within the scope of the loop with the let keyword. Therefore, attempting to access it after the loop will cause an error

10. line 12 returns 3. This is because length was a constant declared at the beginning of the variable to be equal to the length of the input array, which had 3 elements. Its scope applies to the entire function as well.

11. This functions returns an array [50,100,150]. The function works by applying the input discount (0.5) to the each of the values of the input array (100,200,300). After applying the discount, the new values then become 50,100,150, as is returned in the array.

12. A - student.name
    B - student['Grad Year']
    C - student.greeting()
    D - student['Favorite Teacher'].name
    E - student.courseLoad[0]

13. A - '3'+2 = 32, the 2 is treated a string, thus the result is the string concatenation
    B - '3'-2 = 1, the '3' is converted into a integer because of substraction, so 3-2 = 1
    C - 3 + null = 3, when used in arithmetic, null is treated as 0, so 3+0=3
    D- '3' +null= 3null, since 3 is a string, the null is converted into a string and concatenated to 3, thus 3null
    E - true + 3 = 4, true is converted to 1 numertically, and then added to 3, so 3+1=4
    F - false + null = 0, false and null are converted to their numeric values of 0 and added, 0+0=0
    G - '3'+undefined = 3undefined, undefined is converted into string and concatenated to 3, thus 3undefined
    H - '3'-undefined = NaN, during subtraction, JS tries to make undefined into a number,but its not possible, thus not a number (NaN)

14. A - '2' > 1 = true, when comparing, JS converts string '2' into a number, and then compared with 1, 2 > 1 = true
    B - '2' < '12' = false, JS compares strings from left to right, since '2' is not less than '1', false is returned
    C - '2' == 2 is true, == converts both operands to the same type, in this case '2' is converted into a number, and 2==2 is true
    D - 2 === '2' is false, === does comparison without type conversion, since one is a string and one is a number, they are not the same
    E - true == 2 is false, == converts both to the same type, and true is converted to 1, 1 == 2 is false
    F - true === Boolean(2) is true, Boolean(2) becomes true, and true === true is correct

15. Both the == and === operators are used for comparison, but == performs type converstion to make both operands of the same type, while === does not. Essentially, === is more strict in type and value comparison.

16. See part2-question16.js

17. The result of calling modifyArray with parameters [1,2,3] and doSomething will return [2,4,6]. The doSomething function returns the input after being doubled. Inside the modifyArray function, a new array is filled with the return values of calling doSomethign on every item in the input array [1,2,3]. Since this function doubles numbers, the new array returned contains the original values doubled, thus [2,4,6].

18. 

    
