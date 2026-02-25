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

## W6
### Activity 1
Gizmos
- OnDrawGizmos is a method like Update or Start where it doesn’t need to be called
- Making a dedicated gizmos script can make it so you can add it to other game objects with similar colliders/rigidbodies and not just one
- Gizmos are only visible in the scene view and not the game view
- This can be used to visualize the player’s interaction distance in our game

Profiling
- LEARN THIS. IT’S IMPORTANT FOR THE FUTURE
- Profiler helps you diagnose your game and see what is causing your game to become extremely laggy
- To open the profiler, got to Window -> Analysis -> Profiler
- With the profiler open, run the game and you can pause the game at a certain frame and see what is causing lag
- This can be useful if we ever run into an issue where our game is laggy when we run it
- The two most important columns in the profiler hierarchy are overview and time m/s
- Having multiple objects with complex colliders could be a big reason why the game lags
- Work is split between two processors: CPU and GPU
- CPU runs program logic
- GPU renders the frame

Breakpoint
- With a breakpoint, you can run your game and pause it once the program hits a certain line.
- This can help if you get an error and are not sure what exactly is causing it
- If you click the empty space to the left of a line’s number, you add a breakpoint. To continue, press Attach to Unity and start your program.
- Once your program hits the line with the breakpoint, Unity pauses and VS shows you what happened while your code ran; such as variable values and what methods were called

### Activity 2
Attendance: Kaleb Reyes & Jess Tran / Sebastian Magana is attending GDW

Proposal: [Final Project Proposal Final Draft](https://docs.google.com/document/d/11WOaLqc5etO8rKHDXbb_FdNeKd7ZzC0tJGFpK8PWQyE/edit?usp=sharing)

## W7
### Activity 1
- Duck uses raycast for their line of sight
- _raycastStart is the point where the raycast begins
- _raycastDir is the direction that the raycast is pointing in
- When the player is in the duck’s line of sight, the duck enters its pursue state
- Spherecast can help NPCs know when they are running into an obstacle
- Gizmos can be used to check raycasts

### Activity 2
Attendance: Kaleb Reyes, Jess Tran, Sebastian Magana

### Activity 3
<img width="1300" height="1284" alt="Final Project Breakdown" src="https://github.com/user-attachments/assets/82ac6354-4e5f-4a49-8ac3-4003933cff42" />

### Activity 4
[Trello Board with our Tasks](https://trello.com/invite/b/69951f944f330958a4e6bf2f/ATTI17ad7db252f5940d0bfb947c93137da4F101C3AD/goofy-goobers-final-tasks)

### Activity 5
[Final Project Commit](https://github.com/aconitephoenix/GDIM32-Final/commit/6e61ec015224cc707f4bae467da758e820faf403)
In this commit, I added the main scene and added the terrain game object in it and played with lighting to try to make it look dark. 

## W8
### Activity 1
- A rendering pipeline is a sequence of instructions of how everything will be drawn in a game
- Shaders are a part of the rendering pipeline
- Unity has many different rendering pipelines
- Likely chose built-in or a scriptable rendering pipeline (URP or HDRP)
- Post processing effects are shaders that affect the look of the entire screen
- Steps to add post processing (built in pipeline):
1. Install post processing package
2. Make a new object
3. Put it on the post processing layer
4. Add the post-processing volume component to it

### Activity 2
Attendance: Kaleb Reyes, Jess Tran, Sebastian Magana
