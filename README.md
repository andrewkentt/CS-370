# CS 370 Project Two: Pirate Intelligent Agent

## Project Summary

For this project, I created an intelligent pirate agent that could navigate through a maze and find the treasure using deep Q-learning. A lot of the starter code was already provided, including the maze environment, experience replay class, neural network model, and functions used to test the agent. My main responsibility was completing the Q-training algorithm that allowed the pirate to learn from its experiences and improve its decisions over time.

The agent learned through a combination of exploration and exploitation. During exploration, it could try different actions and discover new paths. During exploitation, it used what it had already learned to choose actions that were more likely to lead to the treasure. The agent also learned from rewards and penalties for its movements. After training, my model reached a 100% win rate and was able to consistently find the treasure.

## What Do Computer Scientists Do and Why Does It Matter?

To me, computer scientists use technology and problem-solving to find better ways to complete tasks or solve problems. That can mean building an application, creating an algorithm, working with data, or developing an intelligent system like the one in this project. What matters is not just getting something to work, but understanding the problem well enough to create a solution that is reliable and useful. Projects like this show how computer science can take a problem that would normally require someone to make every decision manually and create a system that can learn how to make those decisions for itself.

## How I Approach a Problem as a Computer Scientist

I usually approach a problem by breaking it into smaller pieces instead of trying to solve everything at once. This project was a good example of that because I first needed to understand the maze, the possible actions, the reward system, and the provided code before working on the Q-training algorithm. From there, I could work through the training process one part at a time and test the results as I went.

I also think testing and making adjustments are a big part of problem-solving in computer science. The first solution is not always going to work perfectly. With the pirate agent, training involved watching how the model performed, making sure the exploration and exploitation worked correctly, and checking that the agent could consistently reach the treasure instead of only succeeding once.

## Ethical Responsibilities

As a computer scientist, I think I have a responsibility to both the end user and the organization I am working for. For the user, that means creating software that is safe, reliable, and respectful of their privacy. Users should also be able to trust that a system will work the way it is supposed to and that their information will not be misused.

There is also a responsibility to the organization to create software that is secure, maintainable, and accurate. That includes being honest about the limitations of a system instead of making it seem more capable than it really is. This becomes especially important with artificial intelligence because an AI system can make decisions that affect people. Developers need to think about how those decisions are made, what data the system learns from, and what could happen if the system makes a mistake.
