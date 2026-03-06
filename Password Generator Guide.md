# Password-Generator
This repository has my Python implementation of a Strong Password Generator



Description:

## **Random Password Generator (Python)**

### **Overview**

This program generates a random password based on user-defined criteria. The user selects the desired password length and chooses from different character sets — letters, digits, and special symbols. The script then randomly assembles a secure password using the selected sets.

### **Features**

* Interactive command-line interface.
* Supports customizable password length.
* Allows inclusion of letters, digits, and/or special characters.
* Ensures randomness using Python’s `random.choice()`.

### **Requirements**

* Python 3.x
* No external libraries (uses standard `string` and `random` modules).

### **Usage**

1. Run the script:

   ```bash
   python password_generator.py
   ```
2. Enter the desired password length.
3. Choose one or more character sets (letters, digits, symbols).
4. Select “4” to finish and generate the password.
5. The program prints the final password.

### **Example**

```
Enter password length: 10  
Choose character set for password from these :  
         1. Digits  
         2. Letters  
         3. Special characters  
         4. Exit  
Pick a number 1  
Pick a number 2  
Pick a number 4  
The random password is q5WjD7sK2T
```

### **How It Works**

* The script builds a character pool (`characterList`) based on user selections.
* For each character in the password, `random.choice()` selects a random element from the pool.
* The final password is printed as a concatenated string.

