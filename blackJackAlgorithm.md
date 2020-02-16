##blackJack Algorithm

**create a card object
	**create a constructor that gives it no value for card 
	**create a make card method
		**intialize a private variable called suite which will hold the value returned from the suite function 
		**intialize a private variable called cardvalue which will hold the value of the the card
		**call the suite method and set it equal to var suite
		**call the value method and set it equal to the var cardvalue
		**return the concatanated value of var suite and var cardvalue
	**create a suite method 
		**create a variable called randval which will hold the value of a random number from one to four
		**create an if statment which checks if randval equals one
			**if it does then return "Spades"
		**else if it equals 2
			**return "Clubs"
		**else if it equals 3
			**return "Diamonds"
		**else 
			**make it return "Hearts"
	**create a cardValue method
		**create a private randval variable that takes the random value that goes from 1-14
		**create a for loop that cycles through 14 times
			**check to see if the randval is greater than 9
					**check to see if the value equals 14
						**return the value 14
					**else 
						**return 10
**create the dealer function which gets passed a parameter of 1 or 2
	**create a card object a
	**create another card object b 
	**if the parameter equals 1