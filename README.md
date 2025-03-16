# Models-of-Human-Memory-

This respiratory is the the review of the course: Models of Human Memory

## Assignment 2: 
### Task 1 

When binary vectors have a dimensionality of 10,000, the normalized Hamming distance between any two randomly chosen vectors tends to fall between 0.47 and 0.53. In the first task, we demonstrate this result. Additionally, we use cosine distance to show that it is approximately 1.0.

In essence, this means that high-dimensional vectors are rarely similar to each other. In human memory, our brain encodes what we perceive and establishes a representation, which may take the form of a high-dimensional vector.

### Task 2 

In this task, we test the robustness of high-dimensional vectors to demonstrate that memory retrieval is possible and that these vectors exhibit high resilience. We use both a binary vector and a normal (continuous) vector, introducing noise to each. For the binary vector, we directly modify entries based on the noise proportion. For the normal vector, we introduce noise by adding a normally distributed perturbation. 

In a nut shell, this means the brain might store memories as high-dimensional vectors, allowing for robust retrieval even with imperfect inputs, which lay the baisc for the later theory: Instance Theory, Hopfield Network. 
