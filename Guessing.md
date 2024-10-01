'''mermaid
flowchart TD
    A>Start- Guessing Game] --> B{Role the Dice-
     Numbers: 1-6 }
    B -- rolling --> C[Random number- #3 - too low]
    C --> D([Incorrect - Role dice again])
    D -- rolling --> B
    B -- rolling --> E[Random number - #6 - too high]
    E --> F([Incorrect - Role dice again])
    F -- rolling --> B
    B -- rolling --> G[Guess is correct - #4]
    G --> H>Game over! You won!]
'''

Step 1: Start the guessing game
Step 2: Role the dice until desired number is rolled (in this case, desired number is #4) (the dice will cotinously roll until the right number is produced)
Step 3: Get the correct number (#4)
Step 4: Game over
