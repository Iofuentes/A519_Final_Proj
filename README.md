# QSO/Galaxy/Star Classifier 

*Authors: Ivan Fuentes and Rianne Eccleston*

## What does this code do?

The purpose of this REPO was to classify QSOs, Stars, and Galaxies based on multiple features possibly found in galaxy surverys. 

The features used in this project included:

**For SDSS DR17:**
* Flux
* Wavelength
* Redshift/Redshift Error
* Signal-to-Noise Ratio

**For DES DR1:**
* G, R, I, Z, and Y Band Magnitudes
* Morphological Classfiers
* Error for each band Magnitude and Classifier Spread

## What was the goal of this project?

This was the final project for my Astronomical Observation course in which we learned how observational astronomy research is conducted. We were tasked as a final project to create some sort of machine learning algorithm that relates to astronomical surveys. **Our objective was to find a relationship between any set of possible parameters and possibly classify between Quasi-Stellar Objects, Galaxies, or Stars.** In the end we were able to compare the accuracy of both sets of parameters.

## What ML techniques did we use?
* Principal Component Analysis
* K-Nearest Neighbors
* Confusion Matricies (To analyze model accuracy)

## How to access the code?
*Open the file named "Main.ipynb" for the full code.*