# Machine Learning Lab Exercises (23CSE301)

Exercise-wise Jupyter notebooks organized by topic, based on the uploaded **ML\_Exercise\_Solutions.pdf (Chapters 5–12)**.

## Repository structure

* `24227-05-linear-regression/` — taxi fare; body-weight prediction
* `24227-06-logistic-regression/` — graduate admission; susceptibility classification; product purchase
* `24227-07-decision-tree/` — house-purchase classification; weather decision
* `24227-08-svm/` — quadratic boundary; text classification demonstration
* `24227-09-knn/` — handwritten digits; Euclidean distance for colour classification
* `24227-10-kmeans/` — eruption-style clustering; image compression
* `24227-11-pca/` — housing price PCA; interpret component loadings
* `24227-12-random-forest/` — majority voting example

## Setup

Python 3.10+ is recommended. From the repository directory, run:

```bash
python -m venv .venv
# Windows PowerShell
.venv\\\\Scripts\\\\Activate.ps1
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

Open a notebook and choose **Run All**. Some scikit-learn datasets (California Housing and 20 Newsgroups) may download on first use; those notebooks need an internet connection the first time.

## Important note about the source PDF

The PDF is a printed notebook export. Some long code lines and dataset URLs are clipped in the export. To keep this repository runnable, notebooks use built-in or reproducibly generated datasets where the original code/data URL could not be reliably recovered from the PDF. The notebook Markdown states where this substitution is used. The notebooks preserve the exercise topics and the main method being demonstrated; they are not claimed to be byte-for-byte copies of the PDF cells.

## Contents

|Chapter|Exercise|Notebook|
|-|-|-|
|05|Predict the fare of a Chicago taxi ride|[`05-linear-regression/01-chicago-taxi-fare.ipynb`](05-linear-regression/01-chicago-taxi-fare.ipynb)|
|05|Predict body weight from height, age and gender|[`05-linear-regression/02-body-weight.ipynb`](05-linear-regression/02-body-weight.ipynb)|
|06|Graduate-school admission (GRE, GPA, institution prestige)|[`06-logistic-regression/01-graduate-admission.ipynb`](06-logistic-regression/01-graduate-admission.ipynb)|
|06|Is a person susceptible to a condition?|[`06-logistic-regression/02-health-susceptibility.ipynb`](06-logistic-regression/02-health-susceptibility.ipynb)|
|06|Which product is a customer likely to buy?|[`06-logistic-regression/03-product-purchase.ipynb`](06-logistic-regression/03-product-purchase.ipynb)|
|07|Will someone buy a house? (age and income)|[`07-decision-tree/01-house-purchase-age-income.ipynb`](07-decision-tree/01-house-purchase-age-income.ipynb)|
|07|Go out or stay in? (weather)|[`07-decision-tree/02-weather-go-out.ipynb`](07-decision-tree/02-weather-go-out.ipynb)|
|08|Random dataset following a quadratic distribution|[`08-svm/01-quadratic-boundary.ipynb`](08-svm/01-quadratic-boundary.ipynb)|
|08|Classify messages as spam / not spam|[`08-svm/02-spam-message-classification.ipynb`](08-svm/02-spam-message-classification.ipynb)|
|09|Recognise handwritten digits with KNN|[`09-knn/01-handwritten-digits.ipynb`](09-knn/01-handwritten-digits.ipynb)|
|09|Euclidean distance between a new colour and labelled colours|[`09-knn/02-euclidean-distance-colours.ipynb`](09-knn/02-euclidean-distance-colours.ipynb)|
|10|Old Faithful geyser eruption segmentation|[`10-kmeans/01-old-faithful.ipynb`](10-kmeans/01-old-faithful.ipynb)|
|10|Image compression with K-Means|[`10-kmeans/02-image-compression.ipynb`](10-kmeans/02-image-compression.ipynb)|
|11|Why are Maggie’s properties not selling?|[`11-pca/01-house-price-pca.ipynb`](11-pca/01-house-price-pca.ipynb)|
|11|Identify which variable is the principal component|[`11-pca/02-identify-principal-component.ipynb`](11-pca/02-identify-principal-component.ipynb)|
|12|Fruit basket: which fruit is likely to be taken often?|[`12-random-forest/01-fruit-basket-voting.ipynb`](12-random-forest/01-fruit-basket-voting.ipynb)|



