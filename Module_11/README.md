# Module 11: Apriori Pattern Mining & Two-Layer Neural Network

### Assignment Summary
This assignment involved two independent tasks: 
1. **Apriori analysis** to identify frequent word patterns in the text of *Alice in Wonderland*
2. **Neural network model development** with two hidden layers for handwritten digit classification on the MNIST dataset.

---

### Part 1: Apriori Analysis on Text Data

- Used **NLTK's Gutenberg corpus** to load the text of *carroll-alice.txt* (Alice in Wonderland).
- Parsed 1703 sentences into transactions, each sentence treated as a list of words.
- Preprocessed the text by:
  - Removing **stopwords** and non-alphabetic characters
  - Filtering words using regular expressions
- Converted the cleaned sentence-token data to a format compatible with **mlxtend’s frequent pattern mining** tools.
- Applied the **Apriori algorithm** with tunable support thresholds.
- Reported **frequent word patterns/phrases**, including:
  - Names and repeated motifs (e.g., "White Rabbit", "Mock Turtle", "Queen Hearts")

### Highlights
- Demonstrated how natural language can be analyzed as transactional data.
- Used pattern mining to uncover thematic elements and character pairings in literature.

---

### Part 2: Two-Hidden Layer Neural Network on MNIST

- Modified the provided **NeuralNetMLP** class to include **two hidden layers**.
- Implemented forward and backward propagation to support the additional layer.
- Trained the network on the **MNIST dataset**:
  - 60,000 training images
  - 10,000 testing images
- Tuned hyperparameters like learning rate, epochs, and hidden layer sizes.
- Reported classification accuracy and evaluated convergence behavior over epochs.

### Highlights
- Achieved improved accuracy over the single-layer network by increasing model depth.
- Reinforced understanding of how multilayer perceptrons learn hierarchical representations.

---

### File
- `Shewale-Assign11.ipynb`: Contains both the frequent pattern mining workflow and neural network implementation with full training and evaluation on MNIST.
