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
~~~
import random
def main():
    n = int(input("Enter how many random numbers to generate: "))
    print("Generated Random Numbers:")
    for _ in range(n):
        print(random.randint(0, 2**31 - 1), end=" ")  # randint to mimic C's rand() range
if __name__ == "__main__":
    main()
~~~
# OUTPUT:
<img width="1919" height="1079" alt="Screenshot 2025-09-15 104300" src="https://github.com/user-attachments/assets/324a3814-4099-4e03-bbd8-e349f7466f8a" />

# RESULT:
the above program is executed in Implementation of Pseudorandom Number Generation Using Standard library
