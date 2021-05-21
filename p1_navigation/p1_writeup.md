[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Project 1: Navigation


### Introduction

This project introduced us to using the Unity ML Agents utility to solve for a problem on our own. There was a lot of variability in how to complete this project and I started out by implementing my solution similar to how we were taught in the videos for this course. I created both an agent and a model python file to store each area of code respectively, and changed very little from the example provided in class. I then added the example code for the dqn from the videos and declared an Agent object from my class file. My plan was to use this as a baseline for where I could improve the design and achieve the 13+ requirement of the project. 

I then ran the code for the first time and after 500 episodes, ended with a score of 13.6. I was a little disappointed that I had already achieved the required score for the project, but I have also had a few new projects assigned to me at work, so it was a bit of a relief as well. I felt that the agent was still trending upwards in its learning at 500 episodes, so I pushed the total up to 800 to see how much more the agent could improve.

I would like to revisit this project in the future to implement a few of the other techniques we discussed in class to improve its performance even more, but for now I am grateful for the straightforward result that I found.


### Structure

Navigation.ipynb (main)
	imports --> Agent from agent.py
	imports --> Model from model.py