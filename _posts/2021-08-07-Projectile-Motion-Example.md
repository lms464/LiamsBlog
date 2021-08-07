# How to solve a physics problem

##### Note to the reader: This is a big one!

Want to skip the intro? Jump to **Example: rolling a ball off a cliff**. Before going too much further however, I am going to assume you've got you 3 laws of physics down, and you have knowledge of your equations of motion. While I do bring them up, this will give you a leg up.

## Intro: Is physics math or not?

Why are you required to take math and physics if your a chemistry or a biology major? To my knowledge, the answer is math and physics teach problem solving, please note, I am biased here. Math and physics don't follow a cookie cutter "formula"; you need to practice and study the concepts of math and physics for them to make sense, and for you to be able to use them. 

I heard two general statements at the beginig of the fall semester when I tutored algebra and physics: 1)  I understand math, I don't get physics. 2) Well physics is just math.

For statement 1): on average, students lumped trig in with physics because pre-calc for biology doesn't do trig, and it was the first time they saw it. The idea of vectors didn't click with them initially either, and vecotrs are too important to skim over when learning physics.

For statement2): Physics is an applied math. I like XKCD's explanation to be honest (https://xkcd.com/435/):

![Displacement Figure](https://imgs.xkcd.com/comics/purity.png)

What does applied math mean? In the case of physics, you **first** figure out what you need to know (what is the speed of an unlaidend swallow), **then** use math to find it. If physics is a car, math is the engine (v = v<sub>0</sub> + a t). 

## Example: rolling a ball off a cliff

Ok ok, enought pontificating like a recipe! How do you solve a physics problem? 

Step 1, reading

​	1) Read the problem, don't worry about what they are asking, or what they have given you

​	2) Read it a second time, underline what you want to find

​	3) Read it a third time, underline information they give you

Step 2, Draw it and build a table populated with the information you were given. Break the table into x and y for initial and final positions, initial and final velocity, acceleration, and time (though time will be the same in both collumns).

![Displacement Figure](https://github.com/lms464/lms464.github.io/blob/master/_images/Physics_Math_or_Not/Physics_Math_or_Not.0011.png?raw=true)

#### The question

I'm going through breaking down a question using the steps listed above.

1.1) 

You kick a ball off of a 10 m high cliff. The ball is kicked with an angle of 0 deg from the x axis with an initial velocity of 2 m/s. 1) How long before the ball hits the ground? 2) What is the distance the ball travels?

1.2)

You kick a ball off of a 10 m high cliff. The ball is kicked with an angle of 0 deg from the x axis with an initial velocity of 2 m/s. 1) **How long before the ball hits the ground? 2) What is the distance the ball travels?**

So we want two peices of information (**bold**), the time it takes for the ball to hit the ground, and how far the ball travels.

1.3)

You kick a ball off of a *10 m high cliff*. The ball is kicked with an angle of *0 deg from the x axis* with an *initial velocity of 2 m/s*. 1) **How long before the ball hits the ground? 2) What is the distance the ball travels?**

We've got a lot here (*italic*). The inital y position is 10 m, and we can make the initial x position 0 (might seem like a cheat but I'll explain later).

Next the initial velocity is 2 m/s *only* in x (implied by 0 deg from the x axis), the initial velocity in y is 0 m/s.

**Note** There is an implied acceloration in the y direction! This is gravity!

2) I've included both the table and drawing. X is in blue, y is in red. The little axis at the side of the drawing shows the positive directions for x and y (the negative directions are in the opposite directions).

The ball should move along half a parabola. 

![Displacement Figure](https://github.com/lms464/lms464.github.io/blob/master/_images/Physics_Math_or_Not/Physics_Math_or_Not.0012.png?raw=true)



#### Are we missing anything?

Yup! We need an equation to act like an engine to solve our problem. Our general equation is used to calculate displacement.

r = r<sub>0</sub> +v<sub>0</sub>t + <sup>1</sup>&frasl;<sub>2</sub>a t<sup>2</sup> 

r can be replaced with x and y depending, and v<sub>0</sub> and a are in the same direction as r. 

What do we start looking for first time or position? In this question, where the ball lands is dependant on the questions initial conditions. *and* time, while time is only dependant on the initial conditions. We should start by looking for time.

How do we do that? In the question, I note that gravity is assumed. Gravity plays a role pulling the ball in the negative direction, intuitivly we know that the ball will hit the ground and stop moving. There is no acceloration in the x direction, meaning that without the role of gravity in y, the ball could move along the x-axis forever (recall Newton's First law (Inertia)).

Starting with how to solve for time by setting up the equation in the y direction:

![Displacement Figure](https://github.com/lms464/lms464.github.io/blob/master/_images/Physics_Math_or_Not/Physics_Math_or_Not.0041.png?raw=true)

Lets stop here for a moment. I make a statement that we now have a quadratic equation. You should have seen this equation in algebra and pre-calc:

<img src="https://github.com/lms464/lms464.github.io/blob/master/_images/Physics_Math_or_Not/QuadraticEq.png?raw=true" alt="Displacement Figure" style="zoom: 33%;" />

Please note, I've not written the equation you have exactly, but ours is a quadratic equation! Our constant term (a) is the difference in position (y-y<sub>0</sub>). Our linear term b is v<sub>0,y</sub>. Lastly, our second order term (c) is <sup>1</sup>&frasl;<sub>2</sub>a<sub>y</sub>. With this in mind we can populate the last equation posted with our information! Sstart by populating the equation with our variables. THEN, fill in the numbers (numbers are _**always**_ second).

![Displacement Figure](https://github.com/lms464/lms464.github.io/blob/master/_images/Physics_Math_or_Not/Physics_Math_or_Not.0042.png?raw=true)

One more reminder, you will get two answers, remember we are looking for a time, if you get an imaginary or negative time, its not the one you want. If you ONLY get negative or imaginary time, something has gone wrong. For us, we get a time that says the ball was in the air for 1.01 seconds! Great!! We can use this time to find the displacement in x!

![Displacement Figure](https://github.com/lms464/lms464.github.io/blob/master/_images/Physics_Math_or_Not/Physics_Math_or_Not.005.png?raw=true)

So the ball should have travled about 2m in x! Excellent! 



Lets take a moment and talk about why we could *choose* an initial x position. The initial and final numbers, honestly, don't matter terribly much. What does matter is the for Δx. If the difference in x is 2m, everyhting is ok, the initial x could be 10m and the final could be 12m, and Δx is still 2m!

Ok, we're all set! **Wrong!** We are looking for a distance, the *magnitude* of displacement. So what would the distance be? I'll be using the variable s to denote distance.
$$
s=\sqrt{\Delta x^2+\Delta y^2}\\
s=\sqrt{2.02m^2 + 10m^2}\\
s=10.2m
$$
So the total distance the ball travels is 10.2m's!

#### Wrapping things up

Lets go back to the question:

You kick a ball off of a 10 m high cliff. The ball is kicked with an angle of 0 deg from the x axis with an initial velocity of 2 m/s. 1) How long before the ball hits the ground? 2) What is the distance the ball travels?

Using the initial condistions stated in the question, we find it takes about 1.01 seconds for the ball to hit the ground. We also find the total distance the ball traveled wat 10.2 m's.

So what is important in what I've set up here? It's not the math, that while important can be done by nearly any calculator or website. It was the set up: isolating what you want to know and what information you have. In most of physics, if you can draw an image and make a chart, you have MOST of the hard work done! Keep this in mind while playing with your questions!!

