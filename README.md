# bedickerson_assignment_5
Demonstrating mastery of While loops, For loops, and Nested loops.


# Why did you choose each loop for each challenge?

Challenge 1 (While Loop): Since there wasn't an explicit range we needed to work in, While loops were chosen to give the user a wider range of opportunity to produce an input.

Challenge 2 (Nested For Loop): There was a range given, and the nested for loop was combined with an if statement to define the specific range that the loop needed to be in.

Challenge 3 (For Loop): There was a limited range available because Multiplication Tables typically only go up to 10. 

# How your Solutions work

Challenge 1 (Collatz Conjecture): The point of this loop was to input a number, get it to return to 1, and check how many steps it took to get there.
- The input number couldn't be equal to 1, since the conjecture is supposed to count how many steps it takes for the input number to return to 1.
- So, the while loop starts off with the command "while current_number != 1:", which means while the current_number variable isn't equal to 1.
- For the first half of the loop body, if the current_number (or numbers combined with the modulo of 2 that equal zero) would be floor divided by 2.
- For the second half, odd numbers would be multiplied by 3 and added by 1.
- Once the loop returns an output of 1, the loop ends. Then, a step_count variable will output how many steps it took for the loop to return a value of 1.

Challenge 2 (Prime Number Checker): The purpose of this loop was to check and see if the user's inputted integer is a prime number or not.
- For this challenge, the input number also had to be greater than 1.
- The range of this loop starts at 2, and ends at the value of one less than the input.
- The modulo operator is used again. If the modulo of the input and another integer is equal to 0, the number is obviously not prime. However, this statement was made for numbers divisible by 3 only.
- If that isn't true, the first else statement determines that this number is prime.
- If neither of the other two statements are true, then the loop determines that this is a non-prime number that is not divisible by 3.

Challenge 3 (Multiplication Table): The purpose of this loop was for the for loop to produce a set amount of numbers in rows and columns, representing a standard multiplication table.

- In Challenge 3, the range function is used to limit the amount of numbers printed. Since the range is (1, 11), the numbers 1-10 are included. 11 is excluded.
- Next, for loops are used to loop the numbers on the rows and columns within the 1-10 range.
- For the values within the table, the row and column variables are multiplied together to produce the products of the multiplication table. 



# AI Citations (or any AI assistance used)
- For this assignment, I used AI to explain concepts to me to make sure I had an understanding of what they did, and I also had it help me explain concepts to make sure I was using the right one. The AI that I used was Google Gemini.
