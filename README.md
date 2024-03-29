# Arithmetic Formatter

# Live demo : https://replit.com/@aliounelo/freeCodeCamp#main.py <br > 

This is the boilerplate for the Arithmetic Formatter project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/scientific-computing-with-python/scientific-computing-with-python-projects/arithmetic-formatter

Students in primary school often arrange arithmetic problems vertically to make them easier to solve. For example, "235 + 52" becomes:
![Screenshot 2022-06-28 at 15-52-54 freeCodeCamp org](https://user-images.githubusercontent.com/53930501/176224649-7b0c3766-c8bf-4b0c-b057-d763b1a34f9e.png)

Create a function that receives a list of strings that are arithmetic problems and returns the problems arranged vertically and side-by-side. The function should optionally take a second argument. When the second argument is set to True, the answers should be displayed.
Example

Function Call:

![image](https://user-images.githubusercontent.com/53930501/176224806-45a89921-2d2e-41bd-bae2-ac3c3b52e0d4.png)


Output:

![image](https://user-images.githubusercontent.com/53930501/176224898-7819ea0a-ca3d-4b25-957d-729de04a6d61.png)

Function Call:

![image](https://user-images.githubusercontent.com/53930501/176224972-63dc8964-e3c5-4ff0-8cb1-d803470a91d3.png)


Output:

![image](https://user-images.githubusercontent.com/53930501/176225055-b883189c-f1f1-494a-926a-b91e18bc91fd.png)

<h1><b>Rules</b></h1>

The function will return the correct conversion if the supplied problems are properly formatted, otherwise, it will return a string that describes an error that is meaningful to the user.

+ Situations that will return an error:
  + If there are too many problems supplied to the function. The limit is         five, anything more will return: Error: Too many problems.
  + The appropriate operators the function will accept are addition and           subtraction. Multiplication and division will return an error. Other           operators not mentioned in this bullet point will not need to be tested.       The error returned will be: Error: Operator must be '+' or '-'.
  + Each number (operand) should only contain digits. Otherwise, the function     will return: Error: Numbers must only contain digits.
  + Each operand (aka number on each side of the operator) has a max of four       digits in width. Otherwise, the error string returned will be: Error:         Numbers cannot be more than four digits.
+ If the user supplied the correct format of problems, the conversion you       return will follow these rules:
  + There should be a single space between the operator and the longest of the     two operands, the operator will be on the same line as the second operand,     both operands will be in the same order as provided (the first will be the     top one and the second will be the bottom.
  + Numbers should be right-aligned.
  + There should be four spaces between each problem.
  + There should be dashes at the bottom of each problem. The dashes should       run along the entire length of each problem individually. (The example         above shows what this should look like.)

<h1><b>Development</h1></b>

Write your code in arithmetic_arranger.py. For development, you can use main.py to test your arithmetic_arranger() function. Click the "run" button and main.py will run.

Testing

The unit tests for this project are in test_module.py. We are running the tests from test_module.py in main.py for your convenience. The tests will run automatically whenever you hit the "run" button. Alternatively you may run the tests by inputting pytest in the console.
