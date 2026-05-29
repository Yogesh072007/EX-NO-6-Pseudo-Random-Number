# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:

    Start the program and import the required libraries.
    
    Seed the random number generator using the current time(i.e) rand(time(0));
    
    Get the number of randon number to generate.
    
    Pass the value for number of iterations and print the numbers.
    
    End the program.

# PROGRAM:
```py
import random
def main():
    n = int(input("Enter how many random numbers to generate: "))
    print("Generated Random Numbers:")
    for _ in range(n):
        print(random.randint(0, 2**31 - 1), end=" ")  
if __name__ == "__main__":
    main()

```

# OUTPUT:

<img width="1864" height="925" alt="image" src="https://github.com/user-attachments/assets/c6097dd0-9df1-473d-a21e-37786c1a2746" />



# RESULT:
Thus the Implementation of Pseudorandom Number Generation Using Standard library successfully completed and executed 

