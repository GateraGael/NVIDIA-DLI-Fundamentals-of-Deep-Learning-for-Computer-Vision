# Deploying our Model: GPU Task 3

Continuing with the theme of using animals to teach applications of computer vision, the next task involves deploying a train neural network to create a simulated doggy door that only opens to dogs.
Here is the full scenario:

"Louie wants to be able to enter and exit his house without requiring a person to let him in. His roommate, a cat named Nala, hunts, and therefore sometimes brings her catch with her. Nala needs to be checked at the door. The solution: We just trained a neural network model to classify dogs from cats. In this next section, you'll deploy that trained model into a simulator."

![](../images/deployment.png)

As explained, there are two distinct portions of the deep learning workflow:

1. **Training**: The input that our network expects is determined both by its architecture and by how it was trained.

2. **Deployment**: Deployment requires writing code to convert the input we have to the input the network expects. The output that our network generates is determined by its architecture and what it learned. Deployment also requires writing code to convert the output that is generated to the output our end user expects. 

