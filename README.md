# Dissecting Detroit 911 calls in a given month

Provided code explores 911 calls in Detroit during March of 2023. Visualizations of different metrics are provided along with a logistic regression model and a geopandas representation different types of calls on a map of Detroit.

Specifically, I was interested in looking into the question:  How do calls classified as “shotspotter” vs “shots fired” differ in the Detroit 911 calls Dataset? What conclusions can we make about Shotspotter?

Why it matters?
Shotspotter is a controversial technology installed in certain neighborhoods in Detroit that uses sensors to detect gunshots and immediately alert the police. The technology is criticized nationwide for being inaccurate. Visualizing the calls from Shotspotter vs calls about gunfire outside Shotspotter neighborhoods may give us insight into whether it is effective in Detroit.

Approach to solving the question
Use 911 calls  dataset and isolate call descriptions that are “Shotspotter” or “Shots Fired” 
Map each instance of the categories on a map of Detroit using Geopandas
Use the map to guide mathematical functions that supplement the map and give us a clearer idea of how the call categories differ. 


