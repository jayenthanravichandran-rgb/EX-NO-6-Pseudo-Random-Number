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
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int n, i;

    printf("Enter the number of random numbers: ");
    scanf("%d", &n);

    // Initialize random number generator
    srand(time(NULL));

    printf("Pseudorandom numbers:\n");

    for (i = 0; i < n; i++) {
        printf("%d ", rand());
    }

    return 0;
}


# OUTPUT:
<img width="1536" height="707" alt="Screenshot 2026-10-28 083523" src="https://github.com/user-attachments/assets/9d5d7e9b-fe79-4b3a-996c-df51e3733e5b" />


# RESULT:
The program was executed
