# ds-travel-time-stats-ml
Discovery project investigating the use of machine learning to estimate travel time statistics to services at the Lower Super Output Area (LSOA) geographic level

The project consists of jupyter notebooks that are labelled by the order they were created
The main steps are:

* Data is downloaded and cleaned
* Exploratory analysis
* A variety of models are explored
* The top performing models are tuned

The project roughly follows the project outline from [Hands on Machine Learning with SciKit Learn and TensorFlow](http://shop.oreilly.com/product/0636920052289.do)

The final notebook attempts to get school data at a more disaggregate geographic level in the hope to significantly improve prediction accuracy. More work is needed on converting postcodes to LSOA or calculating distances from LSOA midpoints and postcode longtituide-lattitude.
