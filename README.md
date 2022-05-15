# ardNeuralNetwork
Predict MLB run counts.

The goal of this project is to predict run counts for EACH team in MLB games. (the outputs are predictions for one team, for an entire game add two outputs together). The inputs are 45-dimensional transposed vectors formed from:
  - The seasonal team batting stats offered on baseball-reference.com
  - The opposing team's starting pitcher's seasonal advanced pitching stats offered on baseball-reference.com
  - Ard's predicted runs subtracted from my book's runline
  
The weights are randomly generated before training, and the bias is some arbitrary positive integer.

My activation function is the ReLu. 
