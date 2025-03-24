# Fizz Buzz

Given an integer n, for every positive integer i <= n, the task is to print:

"FizzBuzz" if i is divisible by 3 and 5,
"Fizz" if i is divisible by 3,
"Buzz" if i is divisible by 5,
"i" as a string, if none of the conditions are true.

## April Fools' Day Special Logic

On April 1st (April Fools' Day), the function should use alternative logic:

"AprilFizz" if i is divisible by 3,
"AprilBuzz" if i is divisible by 5,
"AprilFizzBuzz" if i is divisible by both 3 and 5,
Return i in reverse order as a string (e.g., 123 becomes "321") if none of the conditions are true.

Examples:
Regular Logic (Not April 1st)

Input: n = 15

Output: ["1", "2", "Fizz", "4", "Buzz", "Fizz", "7", "8", "Fizz", "Buzz", "11", "Fizz", "13", "14", "FizzBuzz"]

April Fools' Logic (April 1st)

Input: n = 15

Output: ["1", "2", "AprilFizz", "4", "AprilBuzz", "AprilFizz", "7", "8", "AprilFizz", "AprilBuzz", "11", "AprilFizz", "31", "41", "AprilFizzBuzz"]

## Future requirements

- Create a web service that can return the output in json format

- The web service must respect the april 1st rules
