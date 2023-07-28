# Google_Earth_Engine
Practice codes for my personal project with Google Earth Engine

The link to the code in Google Earth Engine Code Editor - 

https://code.earthengine.google.com/?scriptPath=users%2Fdalalyash10%2Fdalalyash%3AClustering_Practice

## Supervised Learning Classification
1. CART (Classification and Regression tree) Classifier
2. Random Forest Classifier
Data - Surrounding areas of Mumbai, India.

![image](https://github.com/YashDalal10/Google_Earth_Engine/assets/50106830/03d6023f-aa24-4316-92ab-2e555febcb1d)

The image is taken from LANDSAT satellite.

![image](https://github.com/YashDalal10/Google_Earth_Engine/assets/50106830/99a7b335-3320-4cb5-a1b9-c77d701615fe)

Datapoints marked for 4 different classes - 
1. Forest (in green)
2. Urban (in grey)
3. Agriculture (in yellow)
4. Water (in blue)

Result for CART Classifier -

![image](https://github.com/YashDalal10/Google_Earth_Engine/assets/50106830/120fe90c-307f-4fed-978f-4d8e641314e3)

Classification is good. More datapoints better the classification.

Result for Random Forest Classifier - 

![image](https://github.com/YashDalal10/Google_Earth_Engine/assets/50106830/7905df64-495a-4505-abca-d9da9a479fdb)

Classification is good just like CART Classifier.

## Advanced Image Processing

The link to the file is the same.

![image](https://github.com/YashDalal10/Google_Earth_Engine/assets/50106830/93a7c716-a329-481f-8c79-bb13c4b94ff3)

The initial image indicating percentage tree cover.

![image](https://github.com/YashDalal10/Google_Earth_Engine/assets/50106830/ea76b8e3-9c9c-4948-b7a0-d1e6b291edc0)

The LANDSAT 8 image.

![image](https://github.com/YashDalal10/Google_Earth_Engine/assets/50106830/900cd00d-d17a-428d-84af-e1ed5a84a18c)

Predicted percent tree cover after applying Linear Fit on the image.

![image](https://github.com/YashDalal10/Google_Earth_Engine/assets/50106830/c3011583-e4bf-44ed-920f-bada627a2b9c)

Predicted percent tree cover after applying Linear Regression on the image.
