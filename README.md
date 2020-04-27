# FoodEase
Applied Data Science (Python) — finding if, how, and where a crisis is happening.

Victims of natural disasters have difficulty receiving and sharing fresh food and clean water, because leaders and first responders have difficulty interacting directly with or optimizing information directly from victims through the most accessible channels, e.g. Facebook, Twitter, WhatsApp. FoodEase is currently pursuing a project to optimize resource distribution for disaster relief, by asking three key questions:
- How can social media validate or disprove news of a crisis?
- How large is a crisis event (number of people affected)?
- How can the number of mentions indicate which locations are most at risk?
By asking these questions, we could use these data as a deciding factor on locations where we could have the most impact and/or understand better what demographic groups are most at risk.

In this project, we have used a series of datasets pulled from social media (Tweets, Geotag information) and then applied supervised learning in order to analyze if a social media tweet refers to an actual disaster event and where. The Python model uses a TfiD Vectorizer and a PassiveAggressiveClassifier to classify tweets into “Real” and “Fake” or “True” and “False.” Finally, two classification models were tested — Logistic Regression and Decision Tree — due to their strong application to binary evaluations like this. Ultimately, we found the logistic regression and TfiD vectorizer to provide the greatest accuracy. We further evaluated the accuracy of the model through a series of heatmaps, an interactive map of individual markers on prediction and actual layers, and an interactive map with automated clustering and color-coding by the relative amount of markers in a location region.

The resulting visualizations led to three insights. First, additional conditions are needed to ensure that the location of the user matches the location of the crisis mentioned in the tweet. Secondly, additional models or classification are needed to evaluate the timing of crisis events. Some tweets reference very recent (urgent) events while others reference recovery activities after an event has long passed. Finally, more robust training is needed to ensure that tweets predicted are indeed referencing real disasters, reducing the risk of false positives.
In conclusion, the project allowed us to confirm that we can validate or disprove news of a crisis through social media — and, with refinement, can use it as a proxy for impact estimates.

••• Special thanks to our advisor Kyle Monahan, Senior Data Science Specialist at Tufts University.

Website: https://foodeaseco.wixsite.com/relief <br> Contact: foodeasestorage@gmail.com

