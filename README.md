# Java Mad Libs

A simple command-line Mad Libs game built in Java. The program prompts the player for a few words, then plugs them into a short story for a (usually silly) result.

## How It Works

The game asks the user to enter a series of words — adjectives, a noun, and a verb — using `Scanner` to read input from the console. These words are then inserted into a pre-written story template and printed back out.

## Running the Game

1. Clone the repository:
   ```bash
   git clone https://github.com/AlfieMcPhee/java-mad-libs.git
   ```
2. Open the project in your IDE of choice (e.g. IntelliJ).
3. Run `Main.java`.
4. Follow the prompts in the console and enter a word each time you're asked.
5. Read your randomly generated story!

## Example

```
Enter an adjective
> silly
Enter a noun
> giraffe
Enter an adjective
> blue
Enter a verb
> jumped
Enter an adjective
> excited

Today I went to a silly zoo.
In exhibit, I saw a giraffe.
The giraffe was blue and jumped!
I was excited!
```

## What I Learned

This project was a chance to practice the basics of Java, including:
- Taking user input with `Scanner`
- Storing and combining `String` variables
- Printing formatted output to the console

## Possible Future Improvements

- Add more story templates for variety
- Validate user input (e.g. reject empty answers)
- Let the player choose how many rounds to play
