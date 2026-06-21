# MIT Applied Data Science Program — Project Portfolio

**Stephen Marn** · Completed August 2023 · MIT IDSS / Great Learning

A curated portfolio of 31 data-science projects spanning exploratory analysis, statistical inference, supervised & unsupervised machine learning, deep learning (CNNs), recommender systems, and network analysis. Each project includes a written walk-through, an accurate methodology diagram, and the visualizations produced from the analysis.

## 🌐 Live site

A themed, browsable version of every project is published with **GitHub Pages** from the `docs/` folder:

> `https://<your-username>.github.io/<repo-name>/`  —  enable it under **Settings → Pages → Source: `/docs`**.

## 📂 Projects


### Foundations for Data Science

| Project | Summary |
|---|---|
| [CardioGood Fitness: Treadmill Customer Profiling](1_%20Foundations%20for%20Data%20Science/cardiogood-fitness-analysis/README.md) | Descriptive analytics to build a buyer profile for each of three treadmill product lines |
| [FIFA World Cup Analysis](1_%20Foundations%20for%20Data%20Science/fifa-world-cup-analysis/README.md) | Mining 80+ years of World Cup history to guide a new football club's strategy |
| [Uber NYC Trip Demand Analysis](1_%20Foundations%20for%20Data%20Science/uber-trip-analysis/README.md) | Exploring six months of NYC Uber pickups to understand when and where ride demand peaks |

### Data Analytics and Visualization

| Project | Summary |
|---|---|
| [CAVIAR Criminal Network Analysis](2_%20Data%20Analytics%20and%20Visualization/caviar-network-analysis/README.md) | Tracking how a Montreal drug-trafficking network reorganized under repeated police seizures |
| [Clustering Countries by Socio-Economic Profile](2_%20Data%20Analytics%20and%20Visualization/country-socioeconomic-clustering/README.md) | Grouping 167 nations by health, trade, and income indicators to guide aid and development decisions |
| [Enron Email Network Analysis](2_%20Data%20Analytics%20and%20Visualization/enron-network-analysis/README.md) | Using social network analysis to surface the key actors in Enron's senior leadership |
| [Genomic Data Clustering: Decoding the Genetic Code](2_%20Data%20Analytics%20and%20Visualization/genomic-data-clustering/README.md) | Using unsupervised learning to rediscover that DNA reads in three-letter codons |
| [Unsupervised Pattern Discovery with PCA and t-SNE](2_%20Data%20Analytics%20and%20Visualization/pca-tsne-air-pollution/README.md) | Compressing high-dimensional education and air-pollution data to reveal hidden structure |

### Machine Learning

| Project | Summary |
|---|---|
| [BigMart Sales Prediction](3_%20Machine%20Learning/bigmart-sales-prediction/README.md) | Predicting item-level outlet sales with interpretable linear regression |
| [Employee Attrition Prediction](3_%20Machine%20Learning/employee-attrition/README.md) | Why employees leave — and predicting who is at risk |
| [Predicting Hospital Length of Stay](3_%20Machine%20Learning/hospital-los-prediction/README.md) | Forecasting patient length-of-stay at admission to help HealthPlus plan beds, staff, and resources |
| [SuperKart Retail Sales Forecasting](3_%20Machine%20Learning/superkart-sales-practice-project/README.md) | Predicting per-product store sales for the upcoming quarter with linear regression |

### Practical Data Science

| Project | Summary |
|---|---|
| [Bitcoin Price Prediction](4_%20Practical%20Data%20Science/bitcoin-price-prediction/README.md) | Forecasting monthly Bitcoin closing prices with classical time-series models |
| [Celestial Object Detection](4_%20Practical%20Data%20Science/celestial-object-detection/README.md) | Classifying stars, galaxies, and quasars from Sloan Digital Sky Survey photometry |
| [Predicting Employee Attrition at McCurr Health Consultancy](4_%20Practical%20Data%20Science/employee-attrition-prediction/README.md) | An end-to-end classification pipeline to flag at-risk employees before they leave |
| [Predicting Hospital Length of Stay for HealthPlus](4_%20Practical%20Data%20Science/hospital-los-deployment/README.md) | A deployable regression model that forecasts patient length of stay at admission to plan beds, staff, and resources |
| [Predicting Hotel Booking Cancellations for INN Hotels](4_%20Practical%20Data%20Science/innhotels-booking-practice-project/README.md) | Using tree-based classifiers to flag at-risk bookings before they cancel |

### Deep Learning

| Project | Summary |
|---|---|
| [Audio MNIST: Spoken-Digit Recognition with a Neural Network](5_%20Deep%20Learning/audio-mnist-recognition/README.md) | Classifying spoken digits 0-9 from raw .wav audio using MFCC features and a Keras ANN |
| [CIFAR-10 Image Classification with CNNs](5_%20Deep%20Learning/cifar10-image-classification/README.md) | Classifying 32x32 color images into 10 object classes with convolutional neural networks and transfer learning |
| [COVID-19 Chest X-Ray Classification](5_%20Deep%20Learning/covid-chest-xray-classification/README.md) | A CNN decision-aid that triages chest X-rays into COVID, Normal, and Viral Pneumonia |
| [Citation Network Classification with Graph Neural Networks](5_%20Deep%20Learning/citation-network-gnn/README.md) | Predicting a paper's research topic from how it cites other papers, using a GCN on the Cora dataset |
| [Food Image Classification with CNNs](5_%20Deep%20Learning/food-image-classification/README.md) | Teaching a convolutional neural network to tell Bread, Soup, and Vegetable-Fruit apart |
| [Movie Recommendation with Graph Neural Networks](5_%20Deep%20Learning/movie-recommendation-gnn/README.md) | Learning movie embeddings from co-viewing patterns on MovieLens to suggest the next film to watch |
| [Predicting Employee Attrition with Deep Learning](5_%20Deep%20Learning/employee-attrition-deep-learning/README.md) | An artificial neural network that flags which data scientists are likely to switch jobs |
| [Predicting Graduate Admission Chances](5_%20Deep%20Learning/graduate-admission-prediction/README.md) | A neural network that flags which applicants are likely to be admitted to UCLA |
| [Rice Type Classification with CNNs](5_%20Deep%20Learning/rice-type-cnn-classification/README.md) | Sorting five rice varieties from magnified grain images using deep learning |

### Recommendation Systems

| Project | Summary |
|---|---|
| [Book Recommendation System](6_%20Recommendation%20Systems/book-recommendation-system/README.md) | Comparing rank-based, collaborative filtering, and matrix factorization approaches to recommend books |
| [Building a Product Recommender at Scale](6_%20Recommendation%20Systems/recsys-practice-project/README.md) | Comparing rank-based and collaborative-filtering recommenders on millions of user ratings |
| [MovieLens Movie Recommendation System](6_%20Recommendation%20Systems/movielens-recommendation/README.md) | Recommending relevant movies from user rating history with popularity, collaborative filtering, and SVD |
| [Yelp Restaurant Recommendation System](6_%20Recommendation%20Systems/yelp-recommendation-system/README.md) | Recommending restaurants from Yelp reviews using both collaborative filtering and content-based NLP |

### Final Project (all)

| Project | Summary |
|---|---|
| [Used Cars Price Prediction (Capstone)](8_%20Final%20Project%20%28all%29/used-cars-price-prediction-capstone/README.md) | Pricing 7,253 used cars for Cars4U with regression on log price |

## 🛠 How it is organized

- Each `<module>/<project>/` folder holds the notebook(s), a `README.md`, a `requirements.txt`, and a `figures/` folder.
- `docs/` is the GitHub Pages site — one themed page per project plus an index landing page.
- Datasets and course materials are intentionally **not** committed (see Attribution).

## 📚 Attribution

These projects were completed as part of the **MIT Applied Data Science Program** (MIT IDSS / Great Learning). The program provided the case-study scaffolding and data; the analysis, code, and results are my own. Course materials, provided solution notebooks, and program datasets are **not** redistributed here — published with permission, for portfolio use only.

## ⚖️ Use & integrity

© Stephen Marn — **all rights reserved.** This repository is shared as a **portfolio showcase**, not as an open-source template: it carries no software license, so the code is not granted for reuse, copying, or redistribution.

If you are currently enrolled in this or a similar program, **do not copy this work or submit it as your own** — doing so violates your program's honor code. Learn from the approach, then write your own.
