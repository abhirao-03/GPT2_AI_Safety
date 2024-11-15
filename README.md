# BiGram Model Implementation

This project implements a **BiGram model** inspired by Andrej Karpathy's video, ["Let's Build GPT: from Scratch"](https://youtu.be/kCc8FmEb1nY). It focuses on building a character-level language model using simple concepts and techniques, laying the foundation for understanding larger language models like GPT.

---

## Features
- **Character-level vocabulary**: Maps individual characters to unique indices for processing text.
- **Encoding/Decoding**: Converts text into numerical sequences and vice versa.
- **Foundation for GPT-like Models**: Introduces core concepts such as vocabulary size, sequence encoding, and trade-offs in text representation.

---

## Setup Instructions

1. **Prerequisites**:
   - Python 3.7+
   - Jupyter Notebook
   - Basic libraries like `numpy` (if extended for further computations).

2. **Installation**:
   - Clone this repository or download the notebook file.
   - Ensure the `input.txt` file (your text data) is in the same directory.

3. **Running the Notebook**:
   - Open the `bigram.ipynb` file in Jupyter Notebook.
   - Execute the cells sequentially to:
     - Load the text data.
     - Generate the character vocabulary.
     - Build encoding and decoding functions.
     - Train or test the BiGram model (if extended).

---

## File Overview
- **bigram.ipynb**: The main notebook implementing the BiGram model.
- **input.txt**: A text file containing the dataset for processing and training.

---

## Key Concepts
1. **Character Vocabulary**:
   - The text is split into characters to create a unique vocabulary.
   - Each character is assigned a unique index.

2. **Encoding/Decoding**:
   - `encode`: Converts text to a list of numerical indices.
   - `decode`: Converts a list of numerical indices back to text.

3. **Vocabulary-Sequence Tradeoff**:
   - A smaller vocabulary results in longer sequences, while a larger vocabulary reduces sequence length but increases the model's complexity.

---

## Future Extensions
- Add a training loop for predicting the next character based on the BiGram model.
- Extend to TriGram or N-Gram models for better accuracy.
- Incorporate PyTorch or TensorFlow for scalable model development.

---

## Acknowledgments
- Inspired by [Andrej Karpathy's video](https://youtu.be/kCc8FmEb1nY).
- Developed as an educational tool for understanding character-level language models.

---

Feel free to contribute or modify the notebook to enhance its functionality!
