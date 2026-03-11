# GDIM32 In Class Activities
## W1
### Activity 1
How to get a good grade(A)? : 

Make sure you understand the meaning of the coding before and after, and know how to use and write by yourself. 

Also, accept and try to understand the advices gave by playtester, try to imporve the problems during and after assignments.

### Activity 2
1. 10
2. 2
3. What do these lines of code do? 

        private void Update() { 
            PrintMessage(); 
        } 
            private void PrintMessage() { 
                Debug.Log(“hello world”); 
        }

Ans: This code shows "hello world" on Console for each frame.
    
   "private" means that only other methods within the *same class* can call this method.
    
   "void" indicates the return type, void means no-return-value.
    
   "Update()" is a special Unity method that is *automatically called once per every frame*.

4. Monobehaviour

    Since MonoBehaviour is the "passport" or "base template class" for all scripts in Unity.

5. Print "x = 10" on the Console when open the game
6. (10): argument; (“x = ” + x): parameter

    use to pass input data to the method/function.

7. To operate on someone (move, rotate) -> Use "transform" (in lowercase, referring to "this object"). 

    To refer to or store the transformation component of an object -> Use Transform (in uppercase, as a variable type).

    *Translate can only be called on an object. Transform is a class.*

8. use *transform* instead of Transform, since Transform is a class.

    Or use _playerTransform instead. Call Translate on the _playerTransform object

### Activity 3
[W1 activity 3 Google doc](https://docs.google.com/document/d/1RY8G4u76Aeqqu-rppdIJhAqMhHotRh3U2m445UlfjAs/edit?usp=sharing)


## W2
### Activity 1
<img width="1635" height="1054" alt="image" src="https://github.com/user-attachments/assets/167b1cb7-0950-4450-b377-15ed3b772836" />

### Activity 2
[In-class pre-mg2](https://github.com/UCI-GDIM32-W25/mg2-Cordelia77/commit/795f96de425685d197bca73a275254e31129d6a2)


[In-class pre-mg2 second](https://github.com/UCI-GDIM32-W25/mg2-Cordelia77/commit/e3acbbd3262e110fb6e4b1e0b265ebe8d7a4b148)


[In-class pre-mg2 third](https://github.com/UCI-GDIM32-W25/mg2-Cordelia77/commit/d1571057735ab347de4812048e164812397d6a9f)

What I have done: I created the scene (the ground), the sprites of the penguins and the gold coins, and attached their rigidbodies and colliders, and also bound their scripts.
One small issue faced during the process was that the things I made kept being saved in my newly created hierarchy instead of the provided "main". 
With the help of TA, I created a new "main" for it and replaced the old one. (Now, "main" inside refers to my work, while "main3" is empty.)


## W3
### Activity 0-2
I work with Peiyi Xiong.
### Activity 3
<img width="1861" height="1264" alt="image" src="https://github.com/user-attachments/assets/1cad6947-94f6-4305-b1e3-9bf8f001dea9" />


## W4
### Activity 0
I work with Tina Meng.

### Activity 1
When the game is awake and running, multiple locators in the hierarchy are reduced to only one. Because it was destroyed.

### Activity 2
<img width="1642" height="1053" alt="image" src="https://github.com/user-attachments/assets/95a5ee6f-163f-4d44-a891-4c0e309625ec" />


### Activity 3
[github update link](https://github.com/Cordelia77/HW4/commit/298d53f87b18bae14b0db9302f81838a77eaed33)

I independently initiated the creation of a project by using the Link tool. All the major sections in the hierarchy have been constructed. Then the parts of the sprite were divided. Adjusted the size of the game view and made it vertical.
The Sprite's resources were downloaded and successfully imported into Unity.


## W5
### Activity 1
#### Devlog
I think this design is reasonable. It effectively applies the core concept of object-oriented programming. An abstract class is like a "template", defining the common attributes and behaviors that all entities must implement, ensuring code consistency and avoiding duplication. An interface is more like a "contract", specifying what an object can do but not caring about its specific nature. This makes the code very flexible, facilitating the addition of the same functionality for different objects. The combination of the two results in a clear program structure, making it easy to maintain and expand.
I will retain this core design because it is very classic and efficient.

### Activity 2
Model: Item.cs, Enemystats.cs
View: DialogueBubble.cs, Inventory.cs
Controller: Enemy.cs, Player.cs

### Activity 3
Scenario 1-
*scriptableobjects: each button (sprites, _movespeed)
finite state machine: player whether missed button & different scores each button will give
model-view-controller:
    - model: list of buttons(buttons)
    - view: score UI, time count down
    - controller: response to player's finger, 
singleton: locator of player
inheritance: button move to a place, button disappear and add scores.*

ScriptableObjects: Store beat sprites, move speed and other config data
Finite State Machine: Judge player's beat miss status, assign different scores for different judgment levels
MVC: Model = beat list, View = score UI & countdown timer, Controller = respond to player input
Singleton: Provide player locator function
Inheritance: Realize general logic of beat movement, disappearance and score addition

### Activity 4
All members in our team are present.
Attendance: Yuxin Ding, Yan Zhang, Tina Meng

[Final Project Draft](https://docs.google.com/document/d/1oGQXyqTOWLLG3tDOO_RGtfLVnASe5ZuaAI4uGt-2Nhs/edit?usp=sharing)


## W6
### Activity 1
- **Profiler:** is in Window -> Analyse -> profiler
  
It can help me identify which part of the game is causing the overall lagging. It can monitor performance and conduct analysis.

For example, it can show if a certain frame suddenly slows down, and where exactly is the problem.


- Avoiding use GetComponent() method, unless is necessary. (Do not use it too often, it's slow)
- Don't use GetComponent() in Update. *Just use it at Start (public class: mono...) or in Start.*

<img width="1860" height="900" alt="image" src="https://github.com/user-attachments/assets/79c2587a-29ff-435c-893a-8f38b3fc3d02" />

- Important to test Web build (itch build)
- **Gizmos:** Showing the distance between player and objects (how far apart will objects be collided); and the direction objects toward (red arrow); collider range (rigidbody blue circle collider)
- Gizmos only seen in Scene. gizmos.cs
- **Breakpoints:** coding page, left line click red dot. -> *Stop program running and to see what happen with the code.*
- Call stack can directly see the sequence of function calls during runtime.
  

### Activity 2
Attendance: Yuxin Ding, Tina Meng, Yan Zhang
[final draft document link](https://docs.google.com/document/d/1oGQXyqTOWLLG3tDOO_RGtfLVnASe5ZuaAI4uGt-2Nhs/edit?usp=sharing)
Still in process.


## W7
### Activity 1
**Raycast**: bool, *the red line*

Send out an invisible line to see if it hits anything.
- yes (hit): ture
- no: false


HitInfo: (maybe also called RaycastHit?): If you actually hit something, let you know what it is.


RunWonderState: walk around randomly.

**Sphere Cast**: Throw a "ball/sphere" forward and see if it will hit anything.
Comparing with *Raycast*, the raycast is thin and it is just a line. 
If the object is very small and moves very fast, it might just "brush past" and not be detected. 
SphereCast has a radius (thickness), which *makes it easier to detect collisions*.


### Activity 2
Attendance: Yuxin Ding, Tina Meng, Yan Zhang
### Activity 3 final break-down
<img width="894" height="1014" alt="image" src="https://github.com/user-attachments/assets/308ebf7b-cacb-42a8-bdb3-739f0b627eeb" />

### Activity 4
[Trello Board task assignments](https://trello.com/invite/b/69951b72679c6bfc86fd7473/ATTI70c8a41e7621770b66384972757bdf5a7B9012D8/gdim-32-final)
### Activity 5
[Final Project](https://github.com/tinamengxq/GDIM32-Final/commits/main/)

Schedule final project component, starting creating cs.files with teammates.


## W8
### Activity 1
**Rendering Pipeline:** The complete process of determining how the game graphics are drawn onto the screen.


- what be rendered
- order of rendering
- how CPU and GPU work together

-> BUild-in

-> URP

->HDRP

If there is "Not compatible", it cannot be used.

**How to check Pipeline:** Edit-Project Settings-Graphics

-If SRP Settings is empty → Built-in

-If there is an asset → URP or HDRP


### Activity 2
Attendance: Yuxin Ding, Tina Meng, Yan Zhang

### Activity 3
The scene is very beautiful and the characters have distinct features. The UI can be further improved, and some of the interaction codes may also be enhanced. The overall game has taken shape and can now incorporate background music and sound effects (not have yet).


**Buddy Team's playtest notes to us:** The Zoo team’s scene is relatively basic (only one platform), but the interaction is well‑designed. What is confusing is that the to‑do list provides no result or feedback whatsoever after a task is completed.

### Activity 4
Add and improve the scene and fix minor bugs; Find sound effect for Cat Playing


### Activity 5
The initial stage involved importing some of the environmental materials and carrying out some of the ground work.
[What we did today](https://github.com/tinamengxq/GDIM32-Final/commit/f9f2a3fd564c0d68345d73330b164d7cfec18901)


## W9
### Activity 1
*_activeDialogue* is a variable used to store the current conversation.
It controls:
1. Whether the sentence can be continued to be played
2. Whether the player is allowed to move
3. Whether the conversation has ended


When the player clicks on a certain option: 

Read the "next node" pointed to by this option -> Update _activeDialogue to that node -> Re-display the text and options


If the current node: 

No options. 

Or mark as the end node 

Then: 

Set _activeDialogue to null 

Close the UI 

Restore player control


### Activity 2
Attendance: Yuxin Ding, Tina Meng, Yan Zhang

### Activity 3
We found that the task instructions were not clear enough. Some players couldn't confirm that there were multiple quests. They also didn't understand the end state of the game. And our cat is a bit small, and it might not be easy for them to find immediately. Therefore, we might plan to create a start UI at the beginning to explain the background and adjust the UI content to ensure clear instructions.
### Activity 4
Finished tasks: 
- All tasks listed last time
- Built scenes
  
Pending tasks:
- create transparent well around the terrain
- update dialogue system (scriptable objects)
- more specific guidelines for players
- create start game (inform players game background) and end game UI

  
### Activity 5
[Commit link](https://github.com/tinamengxq/GDIM32-Final/commit/35079cb0b9c1fa00e0d0115e3820bf6a8a2e7cd2)
We change the size of the Terrain and created an air barrier/transparent wall.


## W10
### Activity 1
Attendance: Yuxin Ding, Tina Meng, Yan Zhang

### Activity 2
I assume the role of the captain. We would like to know if the playtesters understand what they need to do, where to pick up the game characters, and whether they are familiar with the game's background and overall gameplay. Before we started the actual gameplay, we added a "start dialogue" which explained to players what they should do next and how to begin the game. The overall playtest went smoothly. The cat still occasionally needed some time for players to find where it is (we will make it larger in the future), but the game progress has improved significantly compared to the previous playtest. And our dialogue optimization enables them to understand that we have two tasks. So after completing the first task, they will return to the NPC to pick up the second one.

### Activity 3
We wanted to improve the dialogue part by changing the script in UI and dialogue managers to be using scriptableobject. We did such things but enormous bugs appeared. Our game broke down and the quest can not be called. But in our scripts, everything worked well, we couldn't find any error in codes. We plan to solve one bug in class. And try to solve the other bug in class or after class.

### Activity 4
[update link](https://github.com/tinamengxq/GDIM32-Final/commit/82dcddd658cdbf13166c89ded4b9297ad0a4f150)
We are continuously optimizing and modifying the dialogue and UI, but no issues have been resolved. We are currently attempting to further revise the code.
