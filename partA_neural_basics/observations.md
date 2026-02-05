Q: Why does loss decrease initially?
A: Because gradient descent first captures high-signal, low-complexity patterns that give the largest reduction in error.

Q: Why does validation loss behave differently?
A: Because once the model starts fitting noise in the training data, those patterns don’t generalize, so validation loss increases.

Q: What happens if model size is doubled?
A: Capacity increases, so the model can fit training data more aggressively—this can improve performance with enough data, or cause faster overfitting without proper regularization.