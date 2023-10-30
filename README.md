RSA-Factoring-Challenge README Summary:

Mission: Our mission is to intercept data from an insecure network, which includes numerical values used to encrypt sensitive documents.
These values are not consistently generated with large prime numbers. Your task is to quickly factorize these numbers before the target
patches this vulnerability, allowing us to decrypt the documents.

Primary Goal: Your main objective is to factorize as many numbers as possible into the product of two smaller numbers.

Usage: Use the command factors <file> to factorize natural numbers in a file. Each number should be on a separate line, be greater than 1,
and have no empty lines or extraneous spaces. The output format should be "n=p*q," and the program must run independently without external
dependencies. It has a 5-second time limit for execution.

Compilation: Compile the C function using the command: cc -fPIC -shared -o lib_factors_functions.so factors_functions.c.

Feel free to integrate this README into your project documentation while retaining essential details.
