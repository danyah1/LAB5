# LAB5
Accuracy Comparison
I experimented with the same dataset and code, but adjusted the value of top_k in Item_Name_reduced to 3, 5, 6 and 11. The results showed only minor variations in model accuracy. Increasing top_k preserves more item categories instead of combining them under “Other”, which leads to slight changes in performance.

Top Feature Importances
Across all trials, the key influential features stayed consistent. Variables like price_per_item, delivery distance, and location-based attributes continued to have the highest impact on the model.

Conclusion
Overall, modifying top_k has a relatively small effect on the model’s performance. In contrast, numerical and location-related features play a much more significant role in predicting order status.
