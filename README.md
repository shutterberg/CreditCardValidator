# CreditCardValidator
    Credit Card Validator Using Lun's Algorithm

Luns Algorithm Steps 

1Remove the last element from the array, (but remember, you don’t want to alter the original array!).
2.Reverse the array (now without the last digit).(I havent in code)
3.Multiply the digits in odd positions (e.g. first digit, third, fifth…etc) by 2. 
4.If the resulting number is over 9, subtract 9 from the number.(Sum of digits)
5.Add up all the numbers in the array as well as the dropped digit from step 1. 
6.If the sum modulo 10 is 0 then the array contains a valid number. Conversely, 
if the result is any number but 0, then the array contains an invalid number.



