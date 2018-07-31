# InfinityNet - Novel 3D Object Detection System

The problem of understanding 3D data has become one
of paramount importance especially in field of Autonomous
Driving, where the objects needs to be localized accurately.
While the existing methods perform well for large objects
like cars they do not work so as well with smaller classes
like pedestrians. In this work we focus on improving the
accuracy of localization of the pedestrian class. We implement a new sliding window approach analogous to the
2D case but in this case as we show later, we need to slide
only within a 3D frustum thus making the process feasible.
Our network then operates on these windows instead of on
the entire frustum, this reduction in 3D search space improves the results. We show that this enables us to reduce a
3 stage network like Frustum PointNet-v2 into a much simpler 2 stage network without losing out on the accuracy. We
then add an additional regression network to further boost
the accuracy and improve the results of Frustum PointNet-
v2.

Please check out this document for full details about the method:
https://github.com/saichowdaryg/infinityNet/blob/master/3DObjectDetection.pdf
