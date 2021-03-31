# Lab-05

## Names
* Jack McGrath
* Olivia Joe-West
* Amos Lou

### Excerise 1
```
 private String reverseString(String word) {
        String revWord = "";
        for (int i = 0; i<word.length();i++) {
            // int order = word.length()-1;
            // order -= i;
            // revWord = revWord + word.charAt(order);
            revWord =  word.charAt(i)+revWord ;
```  
### Exercise 2
```
n = 6
temp = n - 1
num = 1
prevNum = 0
for i in range(n - 1):
    temp = num
    num += prevNum
    prevNum = temp

print("The value at the ", n, "th postion in the Fibonacci sequence is ", num, sep = "")
```
### Exercise 3
```
num = input(str("Enter a  value: "))
if num[0] == "-":
    num = num[1:]
    print(num)
length = len(num)
print("The number of digits for a value of", num, "is", length)
```
