# Directions



**Details:** See D2L for more information

* Prior to coding, create and algorithm in the form of a flowchart or pseudocode. Change your algorithm as you work your way up through the different levels.
* Name your variables appropriately using camelCase (Eg., zombieImage)
*Comment metjods, and complex logic

## Assessment Levels
This assignment is divided into different levels. Start with the easier levels and work your way up.
### Developing:
* Create an array of characters (superheroes, Pokémon, etc.) minimum 10.
* Create a parallel array of powers that are linked to the characters
Create method that assigns a random power level to each character between 5.00 and 50.00, the numbers must be rounded to two decimal places.
* Create a method that prints the character arrays and the powers **(use a for loop)**

**Example:**
>Pokemon: Pikachu | Power: Electric Zap | PowerLevel: 34.78  
Pokemon: Snorlax | Power: Sleep Spell | PowerLevel: 47.96  
Pokemon: MewTwo | Power: Tail Whip | PowerLevel: 13.43  
Pokemon: Charmander | Power: Fire blast | PowerLevel: 41.14  
Pokemon: Eevee | Power: Sonic Pounce | PowerLevel: 14.25  
Pokemon: Ditto | Power:  Gelly Bomb | PowerLevel: 33.05  
Pokemon: Squirtle | Power: Water Canon | PowerLevel: 23.14  
Pokemon: Bulbasaur | Power: Flower Blast | PowerLevel: 36.24  
Pokemon: Jigglypuff | Power: Jiggly Song | PowerLevel: 39.8  
Pokemon: Gengar | Power: Ghost Attack | PowerLevel: 35.21  

 
### Proficient

* Create a method that allows the user to select a character from list (if a valid character is not selected the user can try again until one is selected).
* Create another method that selects a random character for the user to battle against **(the characters cannot be the same)**. The winner is then displayed based on the power level. The user can play again.

**Example**
>Pokemon: Pikachu | Power: Electric Zap | PowerLevel: 33.95  
Pokemon: Snorlax | Power: Sleep Spell | PowerLevel: 10.37  
Pokemon: MewTwo | Power: Tail Whip | PowerLevel: 42.34  
Pokemon: Charmander | Power: Fire blast | PowerLevel: 29.01  
Pokemon: Eevee | Power: Sonic Pounce  | PowerLevel: 38.46  
Pokemon: Ditto | Power:  Gelly Bomb | PowerLevel: 8.92  
Pokemon: Squirtle | Power: Water Canon | PowerLevel: 49.67  
Pokemon: Bulbasaur | Power: Flower Blast | PowerLevel: 17.76  
Pokemon: Jigglypuff | Power: Jiggly Song | PowerLevel: 46.18  
Pokemon: Gengar | Power: Ghost Attack | PowerLevel: 20.77  

>Please select a hero from the list:

>Pikachu

>Pikachu  vs Jigglypuff

>Jigglypuff wins!

 
### Exemplary

* Create a 2d Array that stores 3 powers each for the characters that the user can select.
* The powers do random damage between 0.00 and 5.00.
* Create a battle method that continues the attacks from the user and the computer until one of them reaches 0 health (cannot go below 0).
* The computer will choose a random power from one of the 3 that does damage between 0.00 and 5.00.
The winner is then displayed based on the power level. The user can play again.

**Example**
>Pokemon: Pikachu | Powers: Electric Zap,Lightning,Static | PowerLevel 28.26  
Pokemon: Snorlax | Powers: Sleep Spell,Body Slam,Earthquake | PowerLevel 27.58  
Pokemon: MewTwo | Powers: Tail Whip,Hyper Beam,Focus Blast | PowerLevel 13.35  
Pokemon: Charmander | Powers: Fire blast,Scary Face,Slash | PowerLevel 27.8  
Pokemon: Eevee | Powers: Sand Attack,Quick Attack,Baby-Doll Eyes | PowerLevel 49.25  
Pokemon: Ditto | Powers: Gelly Bomb,Transform,Copy Cat | PowerLevel 22.75  
Pokemon: Squirtle | Powers: Water Canon,Tackle,Water Gun | PowerLevel 15.82  
Pokemon: Bulbasaur | Powers: Flower Blast,Growth,Tackle | PowerLevel 17.06  
Pokemon: Jigglypuff | Powers: Jiggly Song,Sleep Spell,Demon Stomach | PowerLevel 37.13  
Pokemon: Gengar | Powers: Ghost Attack,Sludge Bomb,Shadow Ball | PowerLevel 35.98  

>Select a pokemon from the list:  

>Squirtle
>Squirtle vs Gengar

>Health:Squirtle 15.82 | Gengar 35.98  
Choose an attack for Squirtle between 1 and 3  
1  
Squirtle attacks Gengar with Water Canon doing 2.87 of damage.  
Gengar attacks Squirtle with Sludge Bomb doing 3.48 of damage.  
Health:Squirtle 12.34 | Gengar 33.11  
Choose an attack for Squirtle between 1 and 3  
2  
Squirtle attacks Gengar with Tackle doing 0.73 of damage.  
Gengar attacks Squirtle with Sludge Bomb doing 3.23 of damage.  
Health:Squirtle 9.11 | Gengar 32.38  
Choose an attack for Squirtle between 1 and 3  
3  
Squirtle attacks Gengar with Water Gun doing 0.43 of damage.  
Gengar attacks Squirtle with Ghost Attack doing 4.11 of damage.  
Health:Squirtle 5.0 | Gengar 31.95  
Choose an attack for Squirtle between 1 and 3  
2  
Squirtle attacks Gengar with Tackle doing 3.51 of damage.  
Gengar attacks Squirtle with Ghost Attack doing 4.04 of damage.  
Health:Squirtle 0.96 | Gengar 28.44  
Choose an attack for Squirtle between 1 and 3  
2  
Squirtle attacks Gengar with Tackle doing 2.87 of damage.  
Gengar attacks Squirtle with Sludge Bomb doing 3.69 of damage.  
Health:Squirtle 0.0 | Gengar 25.57  
Gengar wins!  
Do you want to play again? (y/n)  
y  
