# Snake-and-Ladders-game

### USER
+ Board size is defined by the user
+ Number of players is given by the user
+ Input to number of snakes is given by the user
+ Input to number of laders is given by the user
+ According to the input of the snakes and ladders the size of snakes and laders also given
+ That is the head and tail of the snake and start and end of the ladder
+ Names of the players also given

### Using SOLID principles each class is seperately defined 
 + Dice class
 + User class
 + Board class
 + Main class

### Dice class

+ We first make a rolldice method 
+ We are considering one dice so the minimum number will be equal to "1" and maximum number will be "6"
+ If for example we consider two dice the minimum number would be "2" and maximum number will be "12"
+ After assigning minimum and maximum numbers 
+ Using "math.random()" which is an inbuilt method 
+ "random()" method is used to generate a random number between the sepecific range
+ in this rolldice method the range is from 1 to 6
+ our minimum number is 1 and maximum number is 6

### User class

+ Using private variables to store the player position and player name
+ this keyword is used to refer current class instance variable
+ Player method with parameters playerposition is an integer and string playername
+ using this keyword we are referring playerposition as playerpos and playerName and playerName
+ int method to get player position and player position value 
+ string method to get player name

