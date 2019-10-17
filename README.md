# Encryption-Decryption
## Aim
To perform operation of encryption and decryption on a string
## Theory
For encryption and decryption, we use the ascii values of the characters. We also use a "isalpha()" function which is predefined in the C library. This function takes one a single argument in the form of an integer and returns 0 if the character is not an alphabet.
Here, a number is entered, and that number is either added or subtracted from the ascii value depending on the operation being performed. Once the addition or subtraction is done, the encrypted or decrypted value is obtained. Encryption and Decryption is generally used for encoding a message or personal information which is not meant for public masses. 
## Algorithm
Step 1:Start. 
Step 2:Initialize a string and get the input value from user. 
Step 3:Get the encryption key from user. 
Step 4:Using while loop, check if the current character is null. If not null, enter loop. 
Step 5:Using isalpha, check if the (ascii value of the character + encryption key) is a alphabet, then enter loop and increment the value of that specific character's value by the encryption key. Else, decrement the value of that character by (26 - encryption key). 
Step 6:Print the encrypted string. 
Step 7:Using while loop, check if the current character is null. If not null, enter loop. 
Step 8:Using isalpha, check if the (ascii value of the character - encryption key) is a alphabet, then enter loop and decrement the value of that specific character's value by the encryption key. Else, increment the value of that character by (26 - encryption key). 
Step 9:Print the decrypted string. 
Step 10:End. 
## Conclusion
In this practical, we learnt about the basic concept and use of encryption and decryption. We also learnt about isalpha() function, its use and return values for different inputs given to it. 
