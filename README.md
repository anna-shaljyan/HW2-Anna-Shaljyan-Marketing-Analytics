A/B Testing with Epsilon Greedy and Thompson Sampling
A/B Testing

This project is an A/B testing experiment with four different advertisement options (bandits). The goal is to design and implement the experiment using Epsilon Greedy and Thompson Sampling algorithms.

Design of Experiment
In this A/B testing experiment, we will use a Bandit class that has been provided, which is an abstract class with abstract methods. It's important not to exclude anything from the Bandit class, but you have the flexibility to add additional functionality if needed.

Experiment Parameters
Bandit Rewards: [1, 2, 3, 4]
Number of Trials: 20,000
1. Create a Bandit Class
The first step is to create a Bandit class that represents the different advertisement options (bandits).

2. Implement Epsilon Greedy and Thompson Sampling
Epsilon Greedy
Implement the Epsilon Greedy algorithm.
Decay epsilon by 1/t to balance exploration and exploitation.
Design the experiment using the Epsilon Greedy algorithm.
Thompson Sampling
Implement the Thompson Sampling algorithm.
Design the experiment using the Thompson Sampling algorithm.
3. Report
Visualize the learning process for each algorithm using the plot1() method.
Visualize cumulative rewards from both Epsilon Greedy and Thompson Sampling.
Store the rewards in a CSV file with columns: {Bandit, Reward, Algorithm}.
Print the cumulative reward achieved by the algorithms.
Print the cumulative regret to evaluate the performance.
Please note that the specific values of epsilon and precision are left to your discretion, and you can fine-tune them to achieve the desired results.

Get Started
To get started with this A/B testing experiment, follow these steps:

Implement the Bandit class and the Epsilon Greedy and Thompson Sampling algorithms.
Design the experiment according to the provided guidelines.
Visualize the results using the plot1() method.
Evaluate the cumulative rewards and regret.
Make adjustments and optimizations as needed to improve the experiment's performance.
Feel free to explore and experiment with different values of epsilon and precision to fine-tune the algorithms for your specific use case.