# Jupyter notebook windfarm dataset assignment

OSIsoft Academic Hub is a cloud-based platform that supports data analytics in university curriculum by providing a data infrastructure to host, aggregate, and analyze data. Students are exposed to real-world industrial data which illustrates some of the same engineering concepts being taught in classrooms and labs. OSIsoft Academic Hub hosts the real-world dataset composed of a set of 50 wind turbines owned by AGL, the largest fully integrated energy and telecommunication company in Australia with generation assets totalling over 11GW of capacity corresponding to approximately 20% of the total generation capacity of Australia&#39;s National Energy Market. AGL has been an OSIsoft customer for more than 10 years, and uses OSIsoft&#39;s technology to monitor, operate, and optimize their varied fleet of generation assets across multiple states. AGL kindly shared a substantial subset of their wind farms dataset for academic usage. Here is a summary of the dataset:

- 5 clusters of 10 wind turbines each (50 turbines total)
- 13 different sensors per turbine, the main categories being:
  - Temperature: outside, drivetrain (3) and nacelle (all in °C)
  - Power: instant power sent to the grid, updated every 2 seconds (kW)
  - Speed: rotor (in RPM) and wind (m/s)
  - Angular: pitch, relative wind direction and yaw (degrees)
- 2-year of data covering the 2018-2019 period

The jupyter notebook for accessing the windfarm dataset that has been provided to you shows some errors that you will have to fix for this assignment. Go through the code and search for sections where you will have to input or change data values. Following the steps below will fix the errors and allow you to work with the dataset for the upcoming common project.

1. Show cluster 1 wind turbines in red dots on the map
2. Change the dataview interpolation of cluster 4 to 3 months starting on 2019-02-17 every hour
3. How is ambient temperature correlated to the rest of the variables?
4. Plot the variables that are best correlated to each other
5. How many turbines from cluster 4 show errors?
6. The decision tree regression machine learning model from scikit-learn predicts the active power from the weather forecast. What is the prediction for 14 °C and a wind speed of 5 m/s?
7. How does the active power prediction for the next five days in Jamestown, Australia look like?
