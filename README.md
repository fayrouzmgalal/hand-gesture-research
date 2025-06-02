# hand-gesture-research
ML research for hand gesture classification using MediaPipe landmarks
## Model Comparison

Here is a comparison of the models we trained and evaluated:
![model_comparison](https://github.com/user-attachments/assets/8780b4a5-ac94-44ac-a904-5b8c6649a9c3)

## Model choice

I trained and evaluated three machine learning models (Random Forest, SVM, and AdaBoost)

1- Random Forest (Best Performer)

Accuracy: 97% (Highest among all models).

High precision, recall, and F1-score for all classes.

Handles all gestures well with minimal misclassifications.

2- SVM (Failed Model)

Accuracy: 6% (Completely unusable).

Failed to classify most gestures , only one class was correctly predicted.

3- AdaBoost (Mediocre Performance)

Accuracy: 43% (Better than SVM but far below Random Forest).

Some classes were classified well, others were completely ignored.

Possible improvements: Adjust base estimator, increase estimators, tune hyperparameters.

Conclusion:
Selecting the Best Model After comparing all models, Random Forest is the best-performing model with 97% accuracy, strong precision, recall, and F1-score. It outperforms both SVM (6%) and AdaBoost (43%), making it the most reliable choice for hand gesture classification.
