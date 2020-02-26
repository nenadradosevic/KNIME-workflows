# KNIME workflows
Solar radiation modeling with KNIME. Increasing environmental model reproducibility and warantability by using scientific workflows
--------------------------------------------------------------------------------------------------------------------------
User manual for: Workflow to expose solar radiation model details
--------------------------------------------------------------------------------------------------------------------------
Required input data:

1) XYZ coordinates for points of interest 
2) XYZ coordinates for all points from Digital Surface Model
3) Local time in hours 
4) Days of year (starting first day with 1.... 365)

Workflow flow variables: 
Global varaibles:
Latitude (Geographic latitude for the area of the interest, positive values for the North hemisphere and negative values for the South hemisphere) 
Local variables: 
1) Solar constant 
2) Longitude (Geographic longitude for the area of the interest) 
3) LSTM (Local standard time meridian)
4) Azimuth sectors

How to create and use variables please see the video on the following link: 
https://www.knime.com/knime-introductory-course/chapter7/section1/creation-and-usage-of-flow-variables

The main output: 
Table with solar radiation potential for all points of interest (input data(1)) togethere with their coordinates 

Dependencies:
1)R program language needs to be ran in background of local machine in order to execute R snippet nodes
2)Input data needs to be in txt and csv file formats.  

User manual for: Workflow for machine learning parameter-setting assistance
------------------------------------------------------------------------------------------------------------------------------
