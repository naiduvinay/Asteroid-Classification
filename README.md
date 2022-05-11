# Asteroid Classification

This is a classification project based on dataset which is officially maintained by Jet Propulsion Laboratory (JPL). In this project asteroids are classified as pha(potentially hazardous asteroids) based on varoius attributes of the asteroids.
# Data Source And Method of Collection
Dataset from which is officially maintained by Jet Propulsion Laboratory of California Institute of Technology which is an organization under NASA. In this Dataset all kinds of Data related to Asteroid is included. This Dataset is publicly available in their website.
# Basic Column Definition
SPK-ID: Object primary SPK-ID.\
Object ID: Object internal database ID\
Object fullname: Object full name/designation\
pdes: Object primary designation\
name: Object IAU name\
NEO: Near-Earth Object (NEO) flag\
PHA: Potentially Hazardous Asteroid (PHA) flag\
H: Absolute magnitude parameter\
Diameter: object diameter (from equivalent sphere) km Unit\
Albedo: Geometric albedo\
Diameter_sigma: 1-sigma uncertainty in object diameter km Unit\
Orbit_id: Orbit solution ID\
Epoch: Epoch of osculation in modified Julian day form\
Equinox: Equinox of reference frame\
e: Eccentricity\
a: Semi-major axis au Unit\
q: perihelion distance au Unit\
i: inclination; angle with respect to x-y ecliptic plane\
tp: Time of perihelion passage TDB Unit\
moid_ld: Earth Minimum Orbit Intersection Distance au Unit \
# Final metrics for all the models are:
| Model| Accuracy  | Precision    | Recall   | F-1 Score   |
|---:|:-------------|:-----------|:------|:------|
| Random Forest with importance | 99.99%  | 0.98    | 0.99   | 0.98     |
| Random Forest | 99.99%  | 0.98   | 0.98   | 0.98     |
| Light Gradient Boosting with importance | 99.99%  | 0.9999    | 0.98   | 0.97     |
| Light Gradient Boosting | 99.98%  |  0.96  |  0.98  |   0.97  |
| Logistic Regression |  99.07% | 0.19       | 0.98   | 0.32     |

# Link For the Dataset is attached below:

https://drive.google.com/file/d/1Q85alDVVC6y0pHWcsu9XAbMI5tYTp1Hj/view?usp=sharing
