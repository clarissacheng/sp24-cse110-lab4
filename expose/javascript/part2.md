1. The console log will print 3 because i iterates at the length of prices array which is a length of 3
2. The console log will print 150 because it is the last discountedPrice
3. The console log will print 150 because it is the last finalPrice
4. Return an array [50, 100, 150]
5. There will be an error because the scope of i is the for loop block and it wants to print i outside of it's scope which will result in an error
6. There will be an error because the scope of discountedPrice is the the for loop block and printing outside of the block will result in an error
7. The console log will print the last finalPrice of 150 since the variable is still in scope
8. Return an array [50, 100, 150]. There are no scope issues because all discounted uses are within the same block in which it was declared.
9. There will be an error because the scope of i is the for loop block and it wants to print i outside of it's scope which will result in an error
10. The console log will print 3 because that's the length of the prices array
11. Return an array [50, 100, 150]. The let and const keywords don't affect the final array output. 
12. a. student.name
    b. student["Grad Year"]
    c. student.greeting()
    d. student["Favorite Teacher"].name()
    e. student.courseLoad[0]
13. a. '32', 2 is converted to a string and concatenated
    b. 1, 3 is converted to an int and 3-2=1
    c. 3, null becomes 0
    d. '3null', null becomes a string
    e. 3, true is converted to 1
    f. 0, false and null are converted to 0
    g. '3undefined', undefined is converted to string
    h. NaN, undefined is converted to NaN and any arithmetic involving NaN is NaN
14. a. true,'2' is converted to 2 and 2>1
    b. false, string comparison instead and '2' is lexographically larger than '12'
    c. true, '2' converted to 2 and they're equal
    d. false, no conversion and they're not the same since different types
    e. false, true converted to 1 and 1 doesn't equal 2
    f. true, Boolean(2) is true
15. == compares two values after converting them to a common type. === compares two values but doesn't convert them to a common type. === only returns true if  the values being compared are same type and same value.
16. Check code file
17. The result will be [2, 4, 6]. The function modifyArray iterates through the original array and applies the callback function to them which is doSomething. Since doSomething multiplies each number by 2, the original array is multiplied by 2 adn the new array is outputted resulting in [2, 4, 6].
18. Check code file
19. 1 4 3 2, 2 and 3 are delayed while 1 and 4 are printed instantly