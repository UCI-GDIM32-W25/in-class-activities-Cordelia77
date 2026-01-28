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
[github undate link](https://github.com/Cordelia77/HW4/commit/298d53f87b18bae14b0db9302f81838a77eaed33)

I independently initiated the creation of a project by using the Link tool. All the major sections in the hierarchy have been constructed. Then the parts of the sprite were divided. Adjusted the size of the game view and made it vertical.
The Sprite's resources were downloaded and successfully imported into Unity.
