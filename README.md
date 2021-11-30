# PLOS-Biology-2021
Tooth morphology elucidates shark evolution across the end-Cretaceous mass extinction

# Description
--------------------------------------
1. S1 Data: This is a global occurrence dataset describing individual specimens used to analyse shark disparity across the K/Pg Boundary.
2. S2 Data: This file contains raw landmark data (i.e., non-GPA aligned) (p=160, m = 2) for a total of 1239 specimens used to analyse shark disparity across the K/Pg Boundary.
3. S3 Data: This file specifies which points to be treated as "sliders" in Generalized Procrustes analysis.
            Each sliding semilandmark will slide between two designated points, along a line tangent to the specified curvature.
4. S4 Data: This file contains raw landmark data for a total of 30 shark tooth specimens used as part of the repeatability assessment described in the main text.
5. S5 Data: Annotated R Markdown File (.pdf)

--------------------------------------
1. S1 Code: This is a R markdown file containing reproducible R code for running geometric morphometric analysis of shark dental morphology.
2. S2 Code: This function computes a backtransform morphospace. Original code was written by Aaron Olsen but have been slightly modified.
3. S3 Code: This function calculates the confidence and prediction intervals of the mean, based on a numeric vector.
4. S4 Code: This function computes univariate descriptive statistics.
5. S5 Code: This function plots the minimum convex hulls for a series of specified points.
6. S6 Code: This function computes Procrustes variance, bootstrapping, and rarefaction for GPA-aligned data. 
7. S7 Code: This function takes a file from tpsDig in which no landmarks are assigned and a different number of points have been generated
	    for each specimen. The function will take those points and resample the curve(s) to a set number of points (landmarks)
	    that can then be used in 'geomorph'. The 'divide.curve' option can be used to use the number of curves assign in tpsDig or if
	    FALSE will combine all points into a single curve prior to resampling. The raw points, resampled, and resample & scaled are returned.
--------------------------------------
