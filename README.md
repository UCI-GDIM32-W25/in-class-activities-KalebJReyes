# GDIM32 In Class Activities
## W1
### Activity 1
- Gauge how much time it will take to finish the minigames
- Look for help from your table mates or the LAs

### Activity 2
1. 10
2. 2
3. Prints "hello world" in the console every frame
4. Monobehavior
5. Prints "x = 10" in the console once when the game is started
6. Method argument and method parameter. They are used to give values to the method
7. Transform is a class and Translate can only be called on an object
8. Change Transform to _playerTransform

### Activity 3
[MG 1 Break-down](https://docs.google.com/document/d/1ZloeI2O3HLCZUm7UvvfKdylog4EuKHg3eZPcW1Tevz0/edit?usp=sharing)

## W2
### Activity 1
![IMG_2691](https://github.com/user-attachments/assets/53504ada-2a9f-4848-9572-d28399103bf2)

### Activity 2
[MG 2 Commit](https://github.com/UCI-GDIM32-W25/mg2-KalebJReyes/commit/9a96456762c297bee54ff1db4b967586b1ce9391)

## W3
### Activity 0 - 2
My partner is Sebastian Magana

### Activity 3
<img width="957" height="1500" alt="MG 3 Break-Down" src="https://github.com/user-attachments/assets/f69a7900-b041-433a-be67-676df937b59f" />

## W4
### Activity 0
Partner: Sebastian Magana

### Activity 1
When I ran the game, all but one of the locator objects lost the locator component. This happened because in the Locator script, it checks if an instance of locator already exists and if it does, it destroys the component. If it doesn't, the locator is set as the instance.

### Activity 2
<img width="1334" height="1180" alt="MG 4 Break-Down" src="https://github.com/user-attachments/assets/b7312468-c403-4e9b-8126-cc1c63e36eac" />

### Activity 3
[MG 4 Commit](https://github.com/KalebJReyes/HW4/commit/a4862776433da71739800b501ae3fb6b20edf749)
In this commit, I added the player, pipes, and Game Controller scripts. The player can jump, the pipes spawn at a certain position, and the pipes get destroyed at a certain x position.

## W5
### Activity 1
I think the design of the interfaces and abstract classes are solid for a project like this. With the items used, it makes sense to have an abstract class for items and a seperate interface class for breakable items since not all items will be designed to break. I also think the item class works well as an abstract for future items that may not be useable but are still items. I don't see a reason to change this design if I were doing this project myself.

### Activity 2
The scriptable objects and Enemy stats represent the model aspect as they hold game data in some way, the view aspect is represented by the dialogue bubble and inventory UI classes, and the controller aspect is represented by the Player class.

### Activity 3
Scenario 1: 
The beats in the rhythm game can be represented by prefabs with scriptable objects tied to them. The scriptable object can contain where in the song the beat needs to be hit or other data tied to the notes.

Scenario 2: 
In a team shooter, the model aspect could be represented by the stats of each ability, the view aspect could be represented by the animations and sounds, and the controller aspect could be represented by the activation of abilities.

Scenario 3:
For scenario 3, I see how all of the design patterns can be used in the making of the game. This game can easily become very complex so have a MVC with C# events could help decouple them. Inheritance with polymorphism can work when you have multiple items that do similar things like being able to use them. The finite state machine could be used for animation states; like when the player is walking, planting seeds, hitting rocks, etc. A singleton can be used in a GameController as a locator. Scriptable objects can be used to give different plant types their own stats.

### Activity 4
Attendance: Kaleb Reyes, Sebastian Magana, Jess Tran
Proposal: [Final Project Proposal First Draft](https://docs.google.com/document/d/11WOaLqc5etO8rKHDXbb_FdNeKd7ZzC0tJGFpK8PWQyE/edit?usp=sharing)
