# Robot_Surface_Prediction

Kaggle Problem: https://www.kaggle.com/c/career-con-2019

Task: Given the orientation, linear acceleration and angular velocity values measured by an IMU sensor as 128 long time series units, predict the surface the robot is on.

Metrics:

Precision or accuracy can be used as an error metric as it is more important that the model performs well and less importance on erroneous prediction and more on the correct prediction by the model.
AUC score can also serve as a second metric.
Business Constraints:

Low latency would be required while prediction such that robot can get to know the surface prediction as soon as possible. (In terms of msecs)
Signal processing required for noise reduction, and identification of a pattern in the signal (if it is a periodic signal), and calculation of metrics in frequency domain.
Interpretability may not be that high since given a certain set of values, they have noise present which makes it difficult to interpret.
