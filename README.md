# Assignment 3: MLP, CNN, and Regularization Experiments

This repository contains the Google Colab notebooks for Assignment 3, covering three main topics:
1.  **Next-Word Prediction** using an MLP.
2.  **Dataset Regularization** on the Moons dataset.
3.  **Image Classification** on MNIST using MLPs and CNNs.

##  notebooks

| Task | Description | Notebook Link |
| :--- | :--- | :--- |
| **Question 1** | **Next-Word Prediction using MLP:** An MLP-based text generator trained on two datasets. Includes embedding visualization and a Streamlit app. | [question1.ipynb](https://colab.research.google.com/drive/17jzTjscuAHnKgk11Nd-cxzZU7IkClhJy?usp=sharing) |
| **Question 2** | **Moons Dataset & Regularization:** Training and comparing MLPs (with L1/L2 regularization) and Logistic Regression on a custom 'moons' dataset. | [question2.ipynb](https://colab.research.google.com/drive/12udNnanA7Q6s27oPX8K5g7WtNoxzklRh?usp=sharing) |
| **Question 3** | **MNIST and CNN Experiments:** Comparing MLP, CNN, and pretrained models on MNIST, with t-SNE visualization and cross-domain testing. | [question3.ipynb](https://colab.research.google.com/drive/12udNnanA7Q6s27oPX8K5g7WtNoxzklRh?usp=sharing) |

---

## 📦 Model Weights (Question 1)

Model weights for **Task 1**, including various checkpoints (with and without L2 regularization and dropout), are hosted on Hugging Face Hub:

* **HF Repo:** [https://huggingface.co/XoXMF/spacy\_language\_mlp](https://huggingface.co/XoXMF/spacy_language_mlp)

##  streamlit Streamlit Application (Question 1)

The Streamlit application code (Task 1.4) is included at the **end of the `question1.ipynb` notebook**.

To run the applet, please execute the final cells within the Google Colab notebook. The app will be launched using `localtunnel`, providing a public URL for access.
