This Python script analyzes the surface water extent over a specified time range for a given inland waterbody using Google Earth Engine data.

Instructions:

Setup:
Ensure you have the necessary Python libraries installed (e.g., ee, geopandas, geojson, matplotlib, `pandas).
Install required libraries using pip:

( pip install earthengine-api geopandas geojson matplotlib pandas )

Google Earth Engine Authentication:

To authenticate with Google Earth Engine, follow these steps:
Set up a Google Earth Engine account at Earth Engine.
Authenticate your account by running the following command in a Python script:

import ee
ee.Authenticate()    

Click on the provided link, authenticate your Google account, and copy the verification code provided. Paste the verification code back into the prompt to complete the authentication process.

import ee
ee.Authenticate()

Data Preparation:
Prepare your GeoJSON file containing the geometry of the inland waterbody.
Update the file path in the script to point to your GeoJSON file.

Time Range:
Define the start and end dates for the analysis within the script.

Analysis:
The script computes the water extent for each 10-year interval within the specified time range.
It generates a time series plot showing the variation in water extent over time.

Output:
The script saves the water extent time series plot as water_extent_time_series.png in the specified location.

Note:
Adjust the script parameters as needed for scale and visualization preferences.
Ensure all necessary dependencies are installed and properly configured.

Additional Notes:
For detailed instructions on running the script and customizing parameters, refer to the code comments.
In case of any issues or questions, feel free to reach out for assistance.
