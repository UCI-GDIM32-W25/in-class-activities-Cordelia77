# GDIM32 In Class Activities
## Instructions
Put each week's activities under new headers like the one shown above. Headers are created with the # symbol. More # symbols = smaller header.


Hit enter TWICE to create a new line.


- Create bullet points by writing dashes.
- Here's another bullet point entry.


Remove all placeholder text in order to get full credit for README file formatting.
## W1
### Activity 1
How to get a good grade(A)? : 
Make sure you understand the meaning of the coding before and after, and know how to use and write by yourself. 
Also, accept and try to understand the advices gave by playtester, try to imporve the problems during and after assignments.

### Activity 2
#### q1
10
#### q2
2
#### q3
What do these lines of code do?
private void Update() { 
    PrintMessage(); 
} 
    private void PrintMessage() { 
        Debug.Log(“hello world”); 
}
Ans: "private" means that only other methods within the *same class* can call this method.
"void" indicates the return type, void means no-return-value.
"Update()" is a special Unity method that is *automatically called once per every frame*.
This code shows "hello world" on Console for each frame.
#### q4
Monobehaviour
Since MonoBehaviour is the "passport" or "base template class" for all scripts in Unity.
#### q5
Print "x = 10" on the Console when open the game
#### q6
(10): argument
(“x = ” + x): parameter
use to pass input data to the method/function.
#### q7
To operate on someone (move, rotate) -> Use "transform" (in lowercase, referring to "this object"). 
To refer to or store the transformation component of an object -> Use Transform (in uppercase, as a variable type).
*Translate can only be called on an object. Transform is a class.*
#### q8
use *transform* instead of Transform, since Transform is a class.
Or use _playerTransform instead. Call Translate on the _playerTransform object
