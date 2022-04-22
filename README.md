# Model-Explainability
To explain the inner workings of the models
The idea behind SHAP feature importance is simple: Features with large absolute Shapley values are important. Since we want the global importance, we average the absolute Shapley values per feature across the data
we sort the features by decreasing importance and plot them.
