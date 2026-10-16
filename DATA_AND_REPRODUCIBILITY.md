# Dataset and reproducibility notes

The notebook loads **Fashion-MNIST**, a public fashion-item image classification benchmark, via `tensorflow.keras.datasets.fashion_mnist` or fallback downloads of the official compressed image and label files.

**Status: not executed.** The notebook currently has no saved outputs for any code cell. The report file is marked pre-run. Do **not** claim an achieved accuracy, final training plot, or confusion matrix until the notebook is executed and checked.

The GitHub workflow checks notebook structure only. It is not a training run.

## Running the original notebook

```bash
python -m pip install -r requirements.txt
jupyter notebook SIT720_10_2C_Fashion_MNIST_Zenith_Anthony.ipynb
```

These are version *ranges*, not an exact captured original environment. A fresh run has not been validated by this documentation update.
