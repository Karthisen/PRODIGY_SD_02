PRODIGY_SD_02 - Guessing Game Program

How It Works
- The program uses random.randint(1, 100) to generate a secret number.
- It keeps track of how many guesses you make using the attempts counter.
- It runs in a loop until you guess the correct number.
- If you enter something that's not a number, it catches the error and asks you to try again.
Sample Output
Welcome to the Guessing Game!
I'm thinking of a number between 1 and 100.
Enter your guess: 30
Too low! Try again.
Enter your guess: 80
Too high! Try again.
Enter your guess: 65
Correct! You guessed the number in 3 attempts.
How to Run the Game
- Save the code in a file named guess_game.py.
- Open your terminal or command prompt.
- Run the game using:
python guess_game.py
Features
- Random number generation
- Input validation (handles non-integer input gracefully)
- Feedback after each guess
- Tracks number of attempts
