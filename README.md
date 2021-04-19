# laravel-test

## Thoughts
- In some places validation is done manually instead of laravel way. 
- Queuries are not optimized. In some places queries are being run in loops which is a bad practice. It puts load on the system and increases the response time as well.
- Length of functions is very large. According to some standards it is not a good practice to write a function that is bigger than 23 lines or even 15 lines.
- In Booking controller notification functions are written. (Low Cohesion)
- Exception handling is not in place. 