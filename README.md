# Fashion Recommender

This project recommends similar fashion items based on an image. I built it using Python and Streamlit, with ResNet18 for image feature extraction.

## How it works

- Browse fashion items from the dataset.
- Upload an image to find visually similar items.
- Get recommendations based on image features.

## Tech Stack

- Python
- Streamlit
- PyTorch and torchvision
- ResNet18
- NumPy and Pandas
- Scikit-learn

## Run the Project Locally

Clone the repository and install the required libraries:

```bash
pip install -r requirements.txt
```

Run the app:

```bash
streamlit run app.py
```

## Dataset and Model

The app uses the Myntra fashion dataset, which is downloaded from Google Drive when the app starts. The trained recommendation model is stored in the `models` directory.

The dataset is not included in this repository because of its size.

