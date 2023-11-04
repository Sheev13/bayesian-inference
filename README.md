# Bayesian Non-Linearised Logistic Regression

In a previous coursework task for the 3F8 Inference module of the Part IIA Engineering Tripos (3rd year engineering) at the University of Cambridge, we were given a 2-dimensional dataset with binary output data representing the class to which a datapoint belongs. We implemented a logistic regression classifier (by hand, no scikit-learn), but since the required decision boundary was far from linear, it did not perform very well. And so we expanded the input feautures through Gaussian radial basis functions of varying radius, and this performed well, achieving categorical accuracy of up to 90%.

In this task, we seek to improve upon two shortcomings in particular of the non-linearised logistic regression classifier; make use of the information stored in our prior belief of what the model weights should be, reduce confidence of predictions which are near the decision boundary and so more likely to be wrong. We achieve this by adopting a probabilistic approach, namely a Bayesian approach. If you are a part IIA Cambridge engineer, this repository is for the 3F8 Inference FTR - but take note that the report has been altered significantly from what was needed for submission.

In this repository there is:
  - the python notebook
  - the datasets (which are not strictly needed as they are downloaded in the notebook anyway)
  - the report (the important bit)
