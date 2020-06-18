# multi_layer_perceptron_MMM

Multi Layer Perceptron Model for the Classification of Mammographic Masses as benign or malignant.

This model predicts and classifies a mammographic mass as either benign or malignant and assigns a BI-RADS assessment score(An assessment of the confidence of the severity of the classification given on an scale of 1-5.) This is in itself a non-predictive attribute.

This data contains 961 instances of masses detected in mammograms from the public dataset from the UCI repository (source: https://archive.ics.uci.edu/ml/datasets/Mammographic+Mass), and contains the following attributes:

BI-RADS assessment: 1 to 5 (ordinal)

Age: patient's age in years (integer)

Shape: mass shape: round=1 oval=2 lobular=3 irregular=4 (nominal)

Margin: mass margin: circumscribed=1 microlobulated=2 obscured=3 ill-defined=4 spiculated=5 (nominal)

Density: mass density high=1 iso=2 low=3 fat-containing=4 (ordinal)

Severity: benign=0 or malignant=1 (binominal)
