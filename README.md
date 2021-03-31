# Lab-05

## Names
* Jack McGrath
* Olivia Joe-West
* Amos Lou

#### Excerise 1
```
 private String reverseString(String word) {
        String revWord = "";
        for (int i = 0; i<word.length();i++) {
            // int order = word.length()-1;
            // order -= i;
            // revWord = revWord + word.charAt(order);
            revWord =  word.charAt(i)+revWord ;
```  
#### Exercise 2
```
n = 6
temp = 0 #initialise temp
num = 1 #start at 1
prevNum = 0 #prev num is 0
for i in range(n - 1):
    temp = num #hold num temporarily
    num += prevNum #add previous number
    prevNum = temp #make the previous number the temp so that it is held for the next iteration

print("The value at the ", n, "th postion in the Fibonacci sequence is ", num, sep = "")
```
  
#### Exercise 3
```
  private boolean isStringPalindrome(String word) {
        String revWord = reverseString(word);
        return revWord.equals(word);
        
    }
    
}
private boolean isStringPalindrome(String word) {
        String revWord = reverseString(word);
        return revWord.toLowerCase().equals(word.toLowerCase());
        
    }
    
```
