The dataset I used to train the model is over 1GB in size, so I can't upload it here. It is from the Lawrence Berkeley National Lab's survey of rooftop solar installation throughout the country. 
Explaining my code, the first half can be disregarded (up until the section titled "New Dataset Model")
I left in this old code to demonstrate to the class my error of using a zip-code aggregated dataset. It made for a terrible model, with a very high average error. 

In the "New Dataset Model" however, I aggregated on the census tract level, which made for a much better model. 
The summary of the new model can be found near the bottom of "Setting the Model".
I included a graph that demonstrates the model's performance on a hidden test set, comparing the model's predictions to the actual values of the test set. 

I also included a cursory cluster analysis at the end of the notebook. I could not find a simple way to overlay the maps from the clustering analysis on to a readable map of the greater area.
Thus, the cluster analysis lacks real explanatory power. I included this as a point of future improvement were I to continue with this project. 
