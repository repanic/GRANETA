# GRANETA
A MATLAB-based Program for GRAvity NETwork Adjustmetn

The program performs the least squares adjustment of Scintrex CG-3/3M and CG-5 gravity measurements, according to procedures and adjustment model described in:

Repanić, M. 2019. Optimal Adjustment Models of Scintrex CG-3M Gravimeter Measurements with Respect to the Most Significant Instrumental Error Influences. Doctoral thesis. Ljubljana, University of Ljubljana: pp.xxx.
Supervisor: Assist. Prof. Miran Kuhar, Ph.D.; Co-advisor: Assist. Prof. Polona Pavlovčič Prešeren, Ph.D.

The program consists of the main program:

•	GRANETA for adjustment of gravity networks

and two auxiliary programs: 

•	GRANETA_drift for analysis of the daily transportation drift and

•	GRANETA_ETC for automated interpolation of tidal parameters from a grid of synthetic tidal parameters, prediction of the Earth, ocean and pole tide reductions using PREDICT software from ETERNA package (Wenzel, 1996) and creation of new data files based on the reductions from PREDICT.

The program is designed for adjustment of gravity networks, but it can also be used for the estimation of the corrections of calibration constants based on measurements on calibration line or system, as well as the estimation of the linear vertical gravity gradients.
