# Go_Module-11_gRPC_assignment

- Assignment for GO MODULE 11 : gRPC Implementation
    
- Create a Calculator Service which implements the following APIs:

- 1. A Sum rpc which takes two numbers as input and returns the integer sum of those numbers.
    
- 2. A PrimeNumbers rpc which takes one integer as an input and returns all prime numbers smaller than the given number.

- 3. A ComputeAverage rpc, which accepts a stream of numbers and returns the calculated average.
    
- 4. A FindMaxNumber rpc, which takes a stream of numbers and returns a stream of numbers whenever a maximum number is received.
    Example:  Client Side Stream: 1,  3, 7,  9,  2,  5,  22, 15,  21, 19         Server Side Stream:  1, 3,  7,  9,  22