Pseudocode for rock paper scissors
/*Second solution is here
        Set a global variable playerChoice to store the player's input into
        create a global variable playerValue
        Create a global variable computerChoice
        create a global variable gameCalculator
        create a global variable playerWins
        create a global variable computerWins
        Create a function called numerizeChoice that passes in a param (moveName) and returns an integer 0, 1 or 2
            If the variable input in all lower case is equal to 'rock'
                return 0
                end if
            else if the lowercase value for the variable is equal to 'paper'
                return 1
                end if
            else if the lowercase value for the variable is equal to 'scissors'
                return 2
                end if
            else
                output to console.log "Enter a new option... must be rock paper or scissors
        
        Create a function generateComputer() that sets the computerValue to a random generator
            set a local variable "numberValue" to -> Use a Math random Javascript function to create a floating number between 0...1, multiply the result by 3... take the floor and add 1.
            if numberValue equals 0, set computerChoice to 'rock'
            else if numberValue equals 1, set computerChoice to 'paper'
            else set computerChoice to 'scissors'
            return numberValue;
            //Should set numberValue to a number between 0-2

        Create a function gameLogic that has 2 param (player, computer)
            set gameCalculator equal player minus computer
            if gameCalculator equals 0
                output "tie game. nothing happens" to the console.
            if gameCalculator equals 1
                check if player > computer if yes increment playerWins and output to conole "$playerValue beats $computerValue. user wins this round!", else increment computerWins and output to conole "$computervalue beats $playerValue. Computer wins this round!"
            if gameCalculator equals 2
                check if player < computer if yes increment playerWins and output to conole "Rock beats Scissors. User wins this round!", else increment computerWins and output to conole "Rock beats Scissors. Computer wins this round!"

        Create a function for the game()
            Set a playerInput tp prompt user to input a new value
            set playerValue equal to the return value of numerizeChoice passing in (playerInput)
            call gameLogic passing in (playerValue, generateComputer())

        On HTML button click call game function while 
        create a while loop as long as playerWins is less than 3 and computerWins is less than 3
            call game();
        if playerWins is greater than computerWins output to alert "You won the Rock Paper Scissors Series!" else alert "Computer wins this time. Sorry!"
        
        */