# Mashroom_classification_Project

"EdiFungi: Prepare Machine Learning Model to Safeguard Foragers by Distinguishing Poisonous from Edible Mushrooms"
Problem Statement
The overarching objective of this project is to develop a robust and accurate machine learning model capable of predicting the edibility status of mushrooms, discerning between poisonous and edible varieties, leveraging a comprehensive set of features that encapsulate various attributes such as cap shape, cap surface, gill characteristics, stem dimensions, veil properties, and spore print color. Through extensive analysis and predictive modeling, the goal is to create a reliable tool for differentiating between mushroom types, ensuring the safety of individuals engaging in mushroom foraging or related activities.

Class: Target variable indicating whether the mushroom is poisonous ('p') or edible ('e’).
Cap-diameter: Diameter of the mushroom cap.
Cap-shape: Shape of the mushroom cap.
Cap-surface: The surface texture of the mushroom cap.
Cap color: The color of the mushroom cap.
Does-bruise-or-bleed: Whether the mushroom bruises or bleeds.
Gill-attachment: Attachment type of the gills.
Gill-spacing: Spacing between gills.
Gill-color: Color of the gills.
Stem-height: Height of the mushroom stem.
Stem-width: Width of the mushroom stem.
Stem-root: Root type of the mushroom stem.
Stem-surface: Surface texture of the mushroom stem.
Stem-color: Color of the mushroom stem.
Veil-type: Type of veil covering the gills (seems to have only one value, which may not provide useful information).
Veil-color: Color of the veil.
has-ring: Whether the mushroom has a ring.
ring-type: Type of ring on the mushroom.
Spore-print-color: Color of the spore print.
Habitat: Habitat where the mushroom is found.
Season: Season in which the mushroom is found.

## Conclusion
Decision Tree and KNN also perform exceptionally well.
Logistic Regression, SVM, and Naive Bayes show comparatively lower accuracy and balanced precision-recall trade-offs.
The Random Forest and XGBoost models consistently outperform the other models, achieving near-perfect accuracy and excellent precision, recall, and F1-scores.

## Summary
In summary, for this particular dataset, ensemble methods like Random Forest and XGBoost, along with KNN and Decision Tree, demonstrate superior performance, while Naive Bayes and Logistic Regression perform less well. The choice of the best model depends on the specific requirements and characteristics of the data.



