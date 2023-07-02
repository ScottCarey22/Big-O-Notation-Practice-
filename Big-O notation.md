
Part 1: Simplify the following big O expressions as much as possible

O(n + 10) : O(n)
O(100 * n) : O(n)
O(25): O(1)
O(n^2 + n^3) : O(n^3)
O(n + n + n + n): O(n)
O(1000 * log(n) + n) : O(n)
O(1000 * n * log(n) + n) : O(nlog(n))
O(2^n + n^2) : O(2^n)
O(5 + 3 + 1) : O(1)
O(n + n^(1/2) + n^2 + n * log(n)^10) : O(n^2)

Part 2: Calculating Time Complexity 
1. logUpto(n) : O(n)
2. logAtLeast10(n) : O(n)
3. logAtMost10(n) : O(1)
4. onlyElementsAtEvenIndex(array) : O(n)
5. subtotals(array) : O(n^2)
6. vowelCount(str) : O(n)



Part 3 - short answer
Answer the following questions

True or false: n^2 + n is O(n^2). : True
True or false: n^2 * n is O(n^3). : True
True or false: n^2 + n is O(n). : False
What’s the time complexity of the .indexOf array method? : O(n)
What’s the time complexity of the .includes array method? : O(n)
What’s the time complexity of the .forEach array method? : O(n)
What’s the time complexity of the .sort array method? : O(nlog(n))
What’s the time complexity of the .unshift array method? : O(n)
What’s the time complexity of the .push array method? : O(1)
What’s the time complexity of the .splice array method? : O(n)
What’s the time complexity of the .pop array method? : O(1)
What’s the time complexity of the Object.keys() function?:O(n) 


BONUS
What’s the space complexity of the Object.keys() function? : O(n)