## Homework Week 2

>[Here](https://github.com/SocialHackersCodeSchool/JavaScript/tree/master/Week2/README.md) you find the readings you have to complete before the third lecture.

## Step 1: Recap/Read

- Have a look at [The Secret Life of JavaScript Primitives](https://www.youtube.com/watch?v=2ZUDcmWW4Hc)
- Go through the review of [last week](https://github.com/SocialHackersCodeSchool/JavaScript/blob/master/Week1/REVIEW.md) (Work in progress, update this week :wrench:)
- Go through the review of [this week](https://github.com/SocialHackersCodeSchool/JavaScript/blob/master/Week2/REVIEW.md) (work in progress, update this week :nut_and_bolt:)

## Step 2: Watch

1. If you haven't done already, watch: [What is programming](https://www.khanacademy.org/computing/computer-programming/programming/intro-to-programming/v/programming-intro) Just watch the 2 min video, you do not have to do the entire JavaScript course (It could be useful later on though). 

2. If you want a refresher on Functions you should see [this video](https://www.youtube.com/watch?v=5nuqALOHN1M).

3. If you want a refresher on Objects you should see [this video](https://www.youtube.com/watch?v=mgwiCUpuCxA)

## Step 3: JavaScript
> For all the following exercises create a new .js file. Try to find a proper name for each file or make a small comment about what it does inside for future reference

1. Create a function that takes 3 arguments and returns the sum of the three arguments.

2. Create a function named `colorCar` that receives a color, and prints out, "a red car" for example. (Hint: put it in your file and run it like before.)

3. Create an object and a function that takes the object as a parameter and prints out all of its names and values.

4. Create a function named `vehicleType` that receives a color, and a code, 1 for car, 2 for motorbike. And prints "a blue motorbike" for example when called as `vehicleType("blue", 2)`

5. Can you write the following without the `if` statement, but with just as a single line with `console.log(...);`?
```js
if (3 == 3) {
    console.log("true")
} else {
    console.log("false")
}
```

6. Create a function called `vehicle`, like before, but takes another parameter called age, so that `vehicle("blue", 1, 5)` prints "a blue used car"

7. Make a list of vehicles, you can add `"motorbike"`, `"caravan"`, `"bike"`, or more.

8. How do you get the third element from that list?

9. Change the function `vehicle` to use the list of question 4. So that `vehicle("green", 3, 1)` prints "a green new caravan".

10. Use the list of vehicles to write an advertisement. So that it prints something like: `"Amazing Joe's Garage, we service cars, motorbikes, caravans and bikes."`. (Hint: use a `for` loop.)

11. What if you add one more vehicle to the list, can you have that added to the advertisement without changing the code for question 7?

12. Create an empty object

13. Create a function that takes two objects as parameters and compares them. You will actually need to write two functions — one that compares with `==` and one that compares with `===`. Remember that objects can have objects inside of them so you'll need to find a way to compare every element of every object (types and values). For example: 

```js
    var obj1 = {
        a: 1, 
        b: 'this is the letter b', 
        c: { foo: 'what is a foo anyway', 
             bar: [1,2,3,4]
        }
    }
    
    var obj2 = {
        a: '1', 
        b: 'this is the letter b', 
        c: { foo: 'what is a foo anyway', 
             bar: [1,2,3,4]
        }
    }
```

    In our example we'll say that `obj1 == obj2` is `true` and `obj1 === obj2` is `false`. Make sure you can see why before you write any code!
    
    Note: give this exercise your best shot but don’t spend more than, say, one hour on it.

14. We saw that we can pass functions as arguments to other functions. Your task is to write a function that takes another function as an argument and runs it. 

```js
    function foo(func) {
        // What to do here? 
    }
    
    function bar() {
        console.log('Hello, I am bar!');
    }
    
    foo(bar);
```


15. Write some code to test two arrays for equality using `==` and `===`. Test the following:
    
```js
    var x = [1,2,3];
    var y = [1,2,3];
    var z = y;
```

What do you think will happen with `x == y`, `x === y` and `z == y` and `z == x`? Prove it!
    
> Don't cheat! Seriously - try it first.
    

Check out this [Fiddle](http://jsfiddle.net/jimschubert/85M4z/). You need to open your browser’s Developer Tools to see the console output. Press the Run button in the upper right corner to run the code.

More insights from this [Stack Overflow question](http://stackoverflow.com/questions/22395357/how-to-compare-two-arrays-are-equal-using-javascript).


16. Take a look at the following code: 

```js
     var o1 = { foo: 'bar' };
     var o2 = { foo: 'bar' };
     var o3 = o2;

```

    Show that changing `o2` changes `o3` (or not) and changing ~~`o2` changes `o3`~~ `o1` changes `o3`(or not). 
    
    Does the order that you assign (`o3 = o2` or `o2 = o3`) matter? {Jim Cramer: ???}

17. What does the following code return? (And why?)
```js
let bar = 42; 
typeof typeof bar;
```

 
> ‘Coerce' means to try to change - so coercing `var x = '6'` to number means trying to change the type to number temporarily. 

### Step 4: **Some freeCodeCamp challenges (10 hours):**

On freeCodeCamp.com please do the [Basic JavaScript](https://www.freecodecamp.org/map) exercises up and until the __"Shopping List"__ exercise (there are some topics we did not cover but you can do it).

```
How to hand in your homework:
• Upload your homework in your "sha-javascript1" Github repository. Make sure to create a new folder "week2" first. 
• Upload your homework files inside the week2 folder and write a description for this “commit”.
• Your sha-javascript1/week2 should now contain all your homework files.
• Place the link to your repository folder in Trello.
```

:star: Additional resources and review: [here](https://github.com/SocialHackersCodeSchool/JavaScript/tree/master/Week2/REVIEW.md) (work in progress):star:

