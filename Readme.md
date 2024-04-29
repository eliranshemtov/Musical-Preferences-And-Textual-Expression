# Musical Preferences & Textual expression

This is a research repository for the following question:

`What is / how tight is the relationship between a person's musical preferences and the way this person expresses textually`.

The research progress is fully documented in the step-based [Jupyter notebooks](https://github.com/eliranshemtov/Musical-Preferences-And-Textual-Expression/tree/main/notebooks), as part of this repository. </br>

## Use this repository

You can use venv, conda or whatever Python environment you want.

1. `git clone https://github.com/eliranshemtov/Musical-Preferences-And-Textual-Expression.git`
2. `pip install -r requirements.txt`
3. Download and locate the dataset as described here👇.

### Download the Reddit Dataset

Texts as a zip file and vectors as H5 files should be downloaded from 👉 [here](https://github.com/eliranshemtov/Musical-Preferences-And-Textual-Expression/releases/tag/final-dataset)

Alternative location [at HuggingFace 🤗](https://huggingface.co/datasets/Musical-Preferences-And-Textual-Expression/musical-preferences-and-personality-traits/tree/main)

Full dataset vectorized with the `all-MiniLM-L6-v2` model is also available for download 👉 [here](https://huggingface.co/datasets/Musical-Preferences-And-Textual-Expression/musical-preferences-and-personality-traits/blob/main/detailed_filtered_data/vectors/mini_reddit_data_vectorized.pkl).
Use it only if you want to explore around it. ⚠️ This model was used for intermediate analysis only.

### Load the Reddit dataset

To load the Reddit dataset with vectors, you can use the [12-appendix-load-dataset-and-vectors.ipynb](https://github.com/eliranshemtov/Musical-Preferences-And-Textual-Expression/tree/main/notebooks/12-appendix-load-dataset-and-vectors.ipynb) notebook and `execute all`. It should take ~3 minutes on Apple's M2 Macbook-Pro (including the predictions part).

### Vectorize & Predict

If you want to use this research's artifacts to perdict the probability for presence of a personality trait on unseen texts, just use the [12-appendix-load-dataset-and-vectors.ipynb](https://github.com/eliranshemtov/Musical-Preferences-And-Textual-Expression/tree/main/notebooks/12-appendix-load-dataset-and-vectors.ipynb). It's final cell is an example for this usecase.
