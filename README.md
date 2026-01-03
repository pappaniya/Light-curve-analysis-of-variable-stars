# Light-curve-analysis-of-variable-stars
This project analyses the light curves of variable stars from the NASA TESS mission with Python. This is a basic project to implement the use of lightkurve library in python.The script allows user t enter a star's common name or TIC ID and lightkurve library downloads the star's light curve from the MAST portal. It calculates the star's period and plots normalised flux,folded period and then the power vs frequency curve.
## FEATURES
-search for the star's original light curve from TESS mission.
-auto downloads the data.
-removes Nans and normalizes the curve.
-bins the curve and plots the original curve.
-plots folded curve and its power vs frequency curve.
-computes the star's most likely period.

## NOTE
-currently supports TESS data only.
-make sure the star exists in TESS catalogue.

## AUTHOR
-GitHub: [pappaniya]
-Padmapriya
