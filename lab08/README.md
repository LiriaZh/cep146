CEP146 Lab 08

PART A: Training Phase

### Weight Tracker

| Training Stage | Food | Service | Price |
|---|---|---|---|
| Initial | 1 | 1 | 1 |
| After Card 2 | 1 | 1 | 1 |
| After Card 4 | 1 | 1 | 1 |
| After Card 6 | 1 | 1 | 1 |
| After Card 8 | 1 | 1 | 1 |
| After Card 10 | 1 | 1 | 1 |

Training Accuracy: 10/10 = 100%


All the predictions tested were correct, if a prediction had been incorrect, I think identifying which feature should have had more influence and added a token to increase its weight or remove a token from a misleading feature might help.


PART B: Testing Phase

### Testing Results

| Card | Prediction | Actual Answer | Result |
|---|---|---|---|
| 11 | LIKE | LIKE | Correct |
| 12 | DISLIKE | DISLIKE | Correct |
| 13 | LIKE | LIKE | Correct |

Testing Accuracy: 3/3 = 100%

Training vs. Testing Comparison

Phase	Correct Predictions	Accuracy
Training	10/10	100%
Testing	3/3	100%
There was no measurable improvement because all predictions tested were correct.
Comparing my training and testing results, I found that the same patterns were useful for the new scenarios.


REFLECTION
1. How did your predictions improve?  
My predictions were correct throughout the training phase. 

2. How did "weights" (tokens) help you learn?
Weights represent the importance of each input feature, adjusting weights of an important feature might give more influence predictions.

3. What would happen with more layers or inputs?
More layers and inputs allows the neural network to recognize more complex patterns and consider additional information, such as restaurant cleanliness, location, and atmosphere. However, it would also require more calculations and training data.

4. How does this reflect how real AI works?
Real AI systems may always make predictions, and comparing them with correct answers. This process helps neural networks recognize patterns and improve their predictions on new data.
