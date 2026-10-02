# PyTorch-Deeplearning

My notes and code from learning PyTorch, written as notebooks. They start at tensors and build up to training a model with plain gradient descent.

## What's in here

| File | Covers |
| --- | --- |
| `Tensor.ipynb` | Creating tensors, shapes, dtypes, indexing, basic operations |
| `PyTorch_Workflow.ipynb` | Autograd, `nn.Module`, loss functions, optimizers, the training loop |

## Topics

- Tensors and their operations
- Autograd and how gradients are tracked
- Building models with `nn.Module`
- Writing a training loop by hand
- Gradient descent from scratch

## Running it

```bash
git clone https://github.com/shivamguptamsi/PyTorch-Deeplearning.git
cd PyTorch-Deeplearning
pip install torch jupyter
jupyter notebook
