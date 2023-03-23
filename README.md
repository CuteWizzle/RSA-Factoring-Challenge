# Mission

We have sniffed an unsecured network and found numbers that are used to encrypt very important documents. It seems that those numbers are not always generated using large enough prime numbers. Your mission should you choose to accept it, is to factorize these numbers as fast as possible before the target fixes this bug on their server - so that we can decode the encrypted documents.

##  Factorize all the things!

Factorize as many numbers as possible into a product of two smaller numbers.

### Usage: factors <file>
where <file> is a file containing natural numbers to factor.
One number per line
You can assume that all lines will be valid natural numbers greater than 1
You can assume that there will be no empy line, and no space before and after the valid number
The file will always end with a new line
Output format: n=p*q
one factorization per line
p and q don’t have to be prime numbers
See example
You can work on the numbers of the file in the order of your choice
Your program should run without any dependency: You will not be able to install anything on the machine we will run your program on
Time limit: Your program will be killed after 5 seconds if it hasn’t finish
Push all your scripts, source code, etc… to your repository
we will only run your executable factors

Compile C function:
gcc -fPIC -shared -o lib_factors_functions.so factors_functions.c


## Author :black_nib:

* **Caleb Ezemadu** [CuteWizzle](https://github.com/CuteWizzle)

## Acknowledgements :pray:

All work contained in this project was completed as part of the curriculum for ALX Africa SE. ALX Africa is an online full-stack software engineering program that prepares students for careers in the tech industry using project-based peer learning. For more information, visit [this link](https://www.alxafrica.com//).

<p align="center">
  <img
   src="https://www.alxafrica.com/wp-content/uploads/2022/01/header-logo.png"
       alt="ALX Africa Logo"
  >
</p>

