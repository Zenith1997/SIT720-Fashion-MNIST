# Fashion-MNIST Neural Network Experiments

Investigate how multilayer-perceptron depth and width affect classification of clothing images.

**Python · scikit-learn · MLPClassifier · Fashion-MNIST**

## Project at a glance

Work in progress: the uploaded notebook contains no saved execution outputs. No measured accuracy or completed experiment is claimed.

## Technical work

- Fashion-MNIST image loading and preprocessing
- Baseline multilayer perceptron
- Depth and width experiments
- Planned model comparison and error analysis

## Explore the evidence

- [SIT720_10_2C_Fashion_MNIST_Zenith_Anthony.ipynb](SIT720_10_2C_Fashion_MNIST_Zenith_Anthony.ipynb)
- [SIT720_10_2C_Report_PreRun_Zenith_Anthony.pdf](SIT720_10_2C_Report_PreRun_Zenith_Anthony.pdf)

## Run locally

```bash
python -m venv .venv
# Activate the environment, then:
python -m pip install jupyter numpy pandas matplotlib scikit-learn reportlab
jupyter notebook
```

The notebook downloads Fashion-MNIST through its configured URLs when needed. Allow time for training and network downloads.

Open the linked notebook and run the cells in order. Package names reflect the source imports; a fresh environment was not tested during this documentation update. Dataset downloads require internet access.

## Limitations and status

Training and plotting still need execution and verification. This repository demonstrates the planned workflow rather than a validated model.

The notebook is unexecuted; see the report for the intended analysis.

**Author:** Zenith Anthony Dabarera · SIT720 Machine Learning  
[AI/ML portfolio](https://github.com/Zenith1997)
