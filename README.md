# Abalone-Sex-classification-project

Video link : - https://www.loom.com/share/0acfe08f5e414929801d30752d001c1d

Abstract:
Abalone is a type of marine snail with high nutrition values. Sexually differentiated abalone have
varied body compositions and economic values. Knowing the sex of the abalone and avoiding
infants from harvesting based on the physical features can improve the profitability.
Alternatively, male and female classification can be helpful to improve abalone population
growth. This paper applies several machine learning algorithms (15 models available in Pycaret
library) to classify the abalone population as male, female, and infants. These machine learning
methods are implemented on a dataset obtained from archive.ics.uci.edu/dataset/1/abalone.
Results of the study show that all of the employed machine learning methods have very low
accuracy in abalone classification as male, female and infant during multiclass classification.
Best performing model was logistic regression with accuracy 0.5578. However, the classification
accuracy improves during individual binary classification for infant, male and female. Superior
accuracy and F1 were (0.8163, 0.8117),(0.6466, 0.7574), and (0.6664,0.5405) respectively for
infant, male (ada boost classifier) and female (with Naive Bayes) during binary classification of
each of the sex and infant against other two.
