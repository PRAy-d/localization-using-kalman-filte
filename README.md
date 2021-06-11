# loaclization-using-kalman-filters
We are using kalman filters for the localization of a fully autonomus bot.
Kalman filters can be used in any place where you have uncertain information about some dynamic system, and you can make an educated guess about what the system is going to do next.The Kalman Filter (KF) is a set of mathematical equations that when operating together implement a predictor-corrector type of estimator that is optimal in the sense that it minimizes the estimated error covariance when some presumed conditions are met.

How the KF works
The KF process has two steps, namely:
* Prediction step: the next step state of the system is predicted given the previous measurements
* Update step: the current state of the system is estimated given the measurement at that time step
