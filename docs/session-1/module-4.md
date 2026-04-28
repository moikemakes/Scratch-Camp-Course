# Module 4: Add Falling Objects

### What You Will Learn
- How to add an object to catch
- How to make it fall from the top of the screen
- How to make it reset when it hits the bottom

### Step-by-Step Instructions
1. Add a new Sprite. This will be the object you want to catch!
2. Add a `when green flag clicked` block (Events).
3. Under it, add a `forever` loop (Control - orange).
4. Inside the loop, put a `change y by -5` block (Motion). This makes it fall!
5. Now, drag an `if <> then` block (Control) inside the forever loop.
6. Put a `touching [edge]?` block (Sensing - light blue) inside the `if` block.
7. If touching the edge, make the object go back up using `go to x: [pick random -200 to 200] y: 150` (Motion & Operators - green).

### Add Image Here
[PLACE IMAGE HERE – show the code blocks for the falling object, including the forever loop and the reset if touching the edge]

### Try It Yourself
Click the Green Flag. Does your object fall down and then appear at the top again?

### Challenge Yourself
Make the object fall faster by changing `-5` to `-10`.

### Checkpoint
- [ ] My object falls down continuously.
- [ ] My object teleports back to the top when it hits the bottom.
