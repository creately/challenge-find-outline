# Challenge: Find outline of shape.
This is a Creately hiring challenge. For more details on this go to our challenge page.

## How to Participate
- Push your solution to a public github repo under your personal account and send us the link to the repo.
- Include a README.md file with your thought process/solution design.
- We have very few rules/guidlines so that you can let your creativity go nuts on this.

## The Challenge
The challenge is to come up with a solution that can find the outline of a given shape. 
<Example Image Here>

### Input Shape
The input for the solution will be a shape in any format/structure defined by you. You can 
assume that the API of (EaselJS Graphics class)[https://www.createjs.com/docs/easeljs/classes/Graphics.html] is used to draw the shape (It is not a must to use the EaselJS framework but you can use it if you wish). This defines the scope of the drawing capabilities of that can create a shape. Here are some examples.

#### A rectangle.
```
graphics.beginFill( 'blue' );
graphics.drawRect( 0, 0, 100, 70 );
graphics.endFill();
```
#### Set with two circles.
```
graphics.beginFill( 'blue' );
graphics.drawCircle( 50, 50, 50 );
graphics.endFill();
graphics.beginFill( 'red' );
graphics.drawCircle( 120, 50, 50 );
graphics.endFill();
```

### Expected Output
The output of the solution should be a data structure or graphics object which represents the outline of the given shape. This can be defined by you. The output data/graphics should be structured in such way that the following information can be derived (you dont need to implement this).
- Identify if given point is on the outline.
- Visualise the outline on canvas.

## Expectations
The solution must adhere to the following guidelines
- The primary expectation is the **solution design**. The design constructs, data structures and algorithms. 
- A fully working solution is not a must, but it would be great to see a fully working solution.
- You can use any language/framework of your liking.
- You cannot use frameworks which directly solve the problem. The solution and related design/algorithm must be developed/designed by you. 
- You can use framework/libraries to solve supporting problems such as basic math or geometry functions.
- Good code comes with good documentation.
