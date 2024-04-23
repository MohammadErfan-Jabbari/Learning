# Micrograd and Language Model from Scratch

This is a repository where I gather the notebooks that helped me learn new things or deepen my understandings about the concepts that I'm passinate about.

This repository moslty contains Jupyter notebooks that focus on building foundational machine learning and language processing models from scratch. These notebooks provide a hands-on approach to understanding the underlying mechanisms of neural networks and language models.

## Notebooks

### 1. **micrograd_from_scratch.ipynb**

This notebook is a detailed guide to building a miniature automatic differentiation library, similar to the early stages of TensorFlow or PyTorch, from scratch. This library, named 'micrograd', is designed to facilitate the understanding of how gradients are computed automatically in deep learning frameworks.

This notebooks is according to the Andrej Karpathy's micrograd youtube video.

**Features:**
- Implementation of a simple neural network framework.
- Functions to perform forward and backward passes.
- Demonstration of training a small neural network on a basic dataset.

**Learning Outcomes:**
- Understand the basics of automatic differentiation.
- Learn how neural network operations are computed.
- Gain insights into the backpropagation process.

### 2. **language_model_make_more_karpathy.ipynb**

This notebook explores the construction of a character-level language model inspired by Andrej Karpathy's Second video on the Zero to Hero playlist. The model is built from scratch using Python and tensors from Pytorch.

**Features:**
- Building a character-level NN and a Bigram model from scratch.
- Training the NN on a dataset of names to learn the structure and predict new names.
- Visualization of training progress and predictions.

**Learning Outcomes:**
- Understanding the architecture and mechanics behind langauge models.
- Handling and processing text data for natural language tasks.
- Implementing and training a model to generate text.

## Getting Started

To get started with these notebooks, you need to have Python installed on your machine along with Jupyter Notebook or JupyterLab. Additionally, you will need several libraries, most of which can be installed via pip:

```bash
pip install numpy matplotlib
```

Clone the repository to your local machine:

```bash
Copy
git clone https://github.com/yourusername/your-repository-name.git
cd your-repository-name
```
You can then launch Jupyter Notebook or JupyterLab:

```bash
Copy
jupyter notebook
# or
jupyter lab
```
Navigate to the notebook you want to view or edit within the Jupyter interface in your browser.

## Contributing
Contributions to improve the notebooks or fix issues are highly welcome. Please feel free to fork the repository and submit a pull request.

Fork the repository.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -am 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a pull request.

## License
Distributed under the MIT License. See LICENSE for more information.

## Contact
MohammadErfan Jabbari - @MohammadErfanJ - mohammaderfanjabbari@gmail.com
