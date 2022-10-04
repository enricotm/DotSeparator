------------------- Dot Separator -------------------  
---
-------------------- by enricotm --------------------
---

A Machine Learning algorithm to sort blue and purple dots

How it works?  
---
The program creates N points, with random X and Y values going from 0 to 1.  
Using machine learning concepts, it creates a map of colored regions that makes sure every point is in the right region, based on its random color.

Mutable inputs (variable name):  
---
Number of points (points) --> The amount of points that are created.  
Amount of hidden layers (layers) --> How many hidden layers it uses for the ML algorithm.  
Size of the hidden layers (layers) --> How many knots there are in each hidden layer.  
Minimum iterations (minIters) --> Set the minimum iterations before it accounts for error margin.  
Error margin (errorMargin) --> Set the error margin after it reaches the minimum iterations.  
Log occurence (logOccurence) --> Set how many iterations it waits before updating the log.  
Show development graphs (show_graphs) --> Set if it shows the development graphs in every log update. (Not recommended)  
Show colored regions map (show_map) --> Set if it shows the final colored region map. (Recommended)  

Reading the logs:  
---
Iterations: 2200 - Accuracy: 0.8 (0.86)   
- - 
   Number of     -    Last accuracy         
   iterations    -  (Highest accuracy)   

Ps: All the algorithm was made by hand using only python libraries and jupyter notebook. No frameworks were used.
