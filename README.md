# Model-Explainability
To explain the inner workings of the models
The idea behind SHAP feature importance is simple: Features with large absolute Shapley values are important. Since we want global importance, we average the absolute Shapley values per feature across the data
we sort the features by decreasing importance and plot them.

# Insights
The blue line represents the impact on the model's prediction for the feature "like", 

while the red line represents the impact of "bad".

The graph helps researchers understand how the model interprets movie reviews.  
For example, positive words like "like" or features like "comedy" might increase the model's prediction for a positive review, while negative words like "bad" or features like "documentary" might decrease it.
