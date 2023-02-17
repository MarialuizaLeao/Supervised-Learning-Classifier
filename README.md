# Supervised Learning Classifier

The classifier works as follows:

1. Separate the points into two Convex Hulls using the Graham Scan Algorithm. 
2. Check to see f they are linearly separable using the Sweep-Line Algorithm for Segment Intersection.
* If they are linearly separable:
3. Connect the closest points between the two hulls.
4. Define the model as the bisector line of the closest points segment.
5. Classify the new points according to their position relatively to the model line.

