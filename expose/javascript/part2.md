1. line 12 will print 3, since that is the prices.length which is 3 elements and var is a variable in the function scope.
2. it will print out 150 which is the result of the algorithm since discountedPrice will be the final discounted price which is 300 * 1-0.5 = 150
3. it will print 150 because that is the last value that is pushed to the finalPrice var
4. it will return the discounted array which is [50,100,150] because that is an array that is pushed by the values in finalPrice
5. it will error cause let i will not be inside of the scope of that log
6. it will return an error cause discountedPrice is not in scope
7. it will be the final value of finalPrice which is 150
8. it will return the array values [50,100,150] since it returned discounted array which is pushed with final price values
9. it will cause an error since i is out of scope
10. it will print out the length of prices based on the variable declaration which is 3
11. it will return the discounted value whcih is [50, 100, 150] because you didn't re assign the array, the address is the same but just with value in it now
12. 
```
student.name
student['Grad Year']
student.greeting()
student['Favorite Teacher'].name
student.courseLoad[0]
```
13.     
    A. '32' since + coerse to the first variable
    B. 1 since - expects an int so it will coerce to an int
    C. 3 since 3+ 0 (null) is 3
    D. '3null' since it coerced to string
    E. 4 since true is 1 in literal
    F. 0 since both values are 0
    G. '3undefined' since it coerced undefined to be a string literal
    H. NaN since undefined is an actual undefined definition

14. 
    A. True, since > will change string to int when comparing it to an int
    B. it will return false since js does lexicographic comparison and 1<2 hence it will return false
    C. True since == is a loose equality, where the string will be coerced into an int and it is equal
    D. it is false since === is true equality where it also checks the datatype and it has different data type hence false
    E. False since true turned to int is 1 and 1!=2
    F. True since boolean(2) will change into true and true is === true since both are boolean now
15. the difference is that while both checks the value === cares about what data type they are in, while == does not care if the data type are different they will just coerce it.
16. [./part2-question16.js]
17. the output is [2,4,6] since the function 'callback' is just another name of doSomething in this case since it is passed hence it will just multiply the elements in the array by 2
18. it will out put 1 4 3 2 where 2 is printed out 1 second after 1 is printed.