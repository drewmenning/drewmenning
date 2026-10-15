# Drew Menning

I'm finishing an AAS in Artificial Intelligence in IT at DMACC (May 2027), and I already hold a B.S. in Agricultural Systems Technology from Iowa State and an MBA from Drake. I'm looking for agtech, operations analytics, business systems and implementation roles.

## Projects

- **[ai4i-predictive-maintenance](https://github.com/drewmenning/ai4i-predictive-maintenance)**: capstone for AAI 201. On the AI4I 2020 dataset (3.4% failures), HistGradientBoosting with a validation-tuned threshold caught 41 of 51 test failures with 4 false alarms (test recall 0.80; validation recall at the same threshold was 0.61). A fairness check by product grade then found it caught 0 of 4 Type H failures in validation, which the overall numbers hide.
- **[iowa-county-crop-ops](https://github.com/drewmenning/iowa-county-crop-ops)**: built outside class in October 2026. USDA NASS county corn and soybean estimates for all 99 Iowa counties (2000 to 2025) joined to Iowa Environmental Mesonet weather in a SQLite star schema, with six SQL queries (window functions and a trend fit done in SQL), a Plotly dashboard and a memo for a grain elevator manager. In 2012, 91 of 99 counties came in 10% or more below their corn yield trend; bad corn years averaged 2.8 inches of July rain against 4.3 in normal years.
- **[deep-learning-architectures](https://github.com/drewmenning/deep-learning-architectures)**: MLP, CNN and LSTM in PyTorch. On 800 Fashion-MNIST training images the MLP (80.7%) and the CNN (78.3%) finished within noise of each other, and the CNN was still undertrained. A character-level LSTM on Tiny Shakespeare reached validation perplexity 4.74.
- **[rl-qlearning-assignment](https://github.com/drewmenning/rl-qlearning-assignment)**: tabular Q-learning from scratch on Taxi-v3. After 5,000 training episodes the greedy policy finished 200 of 200 test trips, averaging 13.35 steps and a reward of 7.65 (random policy: -763.9).
- **[model-evaluation-overfitting-assignment](https://github.com/drewmenning/model-evaluation-overfitting-assignment)**: a stratified 70/15/15 split of 20,000 Fashion-MNIST images. A regularized CNN (augmentation, dropout, batch normalization, early stopping) reached 85.8% test accuracy against 83.9% for a dense baseline, while test loss rose from 0.47 to 0.58.
- **[clustering-hands-on](https://github.com/drewmenning/clustering-hands-on)**: K-Means and DBSCAN on Iris. K-Means (K=3) reached an adjusted Rand index of 0.620 against the true species; DBSCAN found 2 clusters plus 14 noise points (ARI 0.573 without the noise).

## More coursework

- **[neural-networks-generative-ai-assignment](https://github.com/drewmenning/neural-networks-generative-ai-assignment)**: a small Keras CNN on Fashion-MNIST with and without data augmentation. Augmentation, with rotations up to about 29 degrees, lowered test accuracy from 89.4% to 82.1% after 5 epochs.
- **[probability-bayes-decision-trees](https://github.com/drewmenning/probability-bayes-decision-trees)**: Titanic classifiers. Naive Bayes reached 80.4% test accuracy, a depth-4 decision tree 77.6%.
- **[week3-dimensionality-reduction](https://github.com/drewmenning/week3-dimensionality-reduction)**: PCA and t-SNE on Iris. Two components keep 95.8% of the variance.
- **[week4-data-exploration-ml](https://github.com/drewmenning/week4-data-exploration-ml)**: Adult census income data, with logistic regression at 84.9% test accuracy.
- **[Learning-Journey](https://github.com/drewmenning/Learning-Journey)**: a dated index of the repos above in course order.

## Tools

Python, pandas, NumPy, scikit-learn, SciPy, PyTorch, TensorFlow and Keras, Gymnasium, SQL (SQLite), matplotlib, seaborn, Plotly, Jupyter, Google Colab.
