# Module 8: Add Enemies

### What You Will Learn
- How to create objects you should avoid (like a bomb, ghost, or rock!)
- How to lose points

### Step-by-Step Instructions
1. Add a new Sprite to be your enemy object.
2. Copy the falling code from your good object to your bad object. (Hint: You can click and drag the code from one sprite to another!)
3. In the enemy's code, change the catch detection: when `touching [Player]`, make it `change [Score] by -1` (lose points!).
4. Make sure the enemy also teleports back to the top after you touch it!

### Add Image Here
[PLACE IMAGE HERE – show the enemy code blocks where score is changed by -1]

### Try It Yourself
Test your game. What happens to your score when you hit the enemy?

### Challenge Yourself
Can you make the game end ("Game Over") if your score goes below zero?

### Checkpoint
- [ ] I have an enemy object falling.
- [ ] My score goes down when I touch the enemy.
