# Neural Networks: Fundamentals


## Contents

| Folder | Topic | What it covers |
|---|---|---|
| [`01-micrograd`](./01-micrograd) | Micrograd / Backpropagation | Building a tiny autograd engine from scratch. Scalar-valued computation graphs, manual backward passes, and the chain rule as the foundation of all neural network training. |
| [`02-build-makemore`](./02-build-makemore) | Bigram Language Model | A character-level bigram model built two ways: (1) simple counting/statistics, and (2) as a single-layer neural network trained with gradient descent, showing that both approaches converge to the same solution. |
| [`03-makemore-mlp`](./03-makemore-mlp) | MLP Language Model | Extending the bigram model into a multi-layer perceptron with character embeddings (following Bengio et al., 2003), using a wider context window, minibatch training, and train/dev/test splits. |

More folders will be added.
## Setup

Each notebook expects a `names.txt` file (a list of names, one per line) in the same folder !

```bash
pip install torch matplotlib
```
