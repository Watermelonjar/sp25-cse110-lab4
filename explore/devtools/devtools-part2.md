1. the bug was that it took num1 and num2 as string, which then if you add it up turns it into a string
2. by passing in  calculateSum(Number(num1), Number(num2)) rather than  calculateSum(num1, num2)