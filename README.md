# A Computer Vision Based Approach for Automated Traffic Management as a Smart City Solution


## Abstract

This study aims to provide a solution to the incessant land acquisition to surmount growing traffic by promoting the application of adaptable lane dividers meant to be implemented in smart cities. A flexible lane span manipulates the width of the road as a whole, avoiding the need for road expansion. Video data is obtained from cameras placed along a single stretch and is analyzed in real-time. The model uses Computer Vision, ROI (Region of Interest) based execution,exploiting both traffic speed and occupied lane area to determine traffic density. Each camera is assigned a priority value with cameras down the lane possessing higher priority. The decision of each camera constitutes the final decision. The design also adopts pattern recognition based on learning, besides real-time analysis for more conclusive results.


## Introduction

Highways are persistently multiplying over time and occupying acreage which in a booming population struggling for space could instead be appropriated for alternate use [6]. On the contrary, automobile manufacture and operation are proliferating at a rate faster than highway expansion. The consequence of this is an interminable cycle of land acquisition to surmount congestion, while not efficaciously solving the problem. This study aims to propose a solution by introducing adaptable lane dividers implementing a Computer Vision based approach to real-time traffic video analysis aided with pattern recognition. Very frequently, highway lanes arenot absolutely occupied, such as in duration of rush hours where the majority of traffic is directed in a single direction only. By training a model to learn such patterns and shifts in traffic movement respective to time and location, the dividers are automated to modify lane-span. This virtually constructs ancillary space for the varying influx of mass transit, manipulating the tracks as a whole instead of perpetually exploiting more land. The real-time analysis makes up for any inconsistencies as the model will be subject to constant variations. This approach can also further be employed in the improvement of accident and crime management and flexible mobility of emergency and rescue vehicles. In conclusion, this study explores the feasibility of such an approach and the method of application of the above proposed solution. 


## Challenges

This paper presents an initial and novel step towards automated traffic management. While most solutions propose redirection of traffic, the physical movement of the divider can propose various challenges which need to be tackled. 

#### Integration with Navigational Services

Our proposed model implements an adaptive lane divider mechanism, integrating it with navigational services like google maps can prove to be challenging. If the mapping service directs the user towards a path which might modify later due to the automatic lane shifting once the user reaches the specified spot, the situation might worsen. We could expect the user to wait but then this might eventually lead to a congestion which we aim to eliminate in the very first place. Thus, our model might fail to work in such edge cases if integrated with other platforms. Although in any case, the divider shall only move a maximum of L−1 lanes, where L is the total number of cases. Thus, not completely eliminating the path directed to by the mapping service.

#### Efficiency

Since our paper proposes a very novel approach to handle traffic congestion, overall efficiency and safety happens to be our biggest challenge. We propose the implementation of this system without any manual guidance or intervention. Due to this guaranteeing hundred percent safety would be difficult. Covering all edge cases is nearly impossible as we happen to be dealing with real time traffic. Thus, implementing our model with a hundred percent efficiency is another challenge for us. Since lane switching can be risky and any error could prove to be fatal, we are researching further to ensure the implementation of the concept is done very carefully and in incremental steps to minimise the error as much as possible.

#### Cost and Hardware Aspects

Our current research focuses specifically on developing a proof of concept of the system. Such a system is expected to be implemented from scratch in smart cities as part of their default transportation infrastructure. Besides the base costs of laying down highways, the number of cameras on a stretch of the road and length of this stretch will vary from city to city and it’s required number of lanes. The same will be applicable to the type of camera to be used. With the increase in the number of lanes, better focus will be required. In case of regions with a climate that frequent varies the resolutions and build of the camera will also change in requirements. This also effects the material used to build the movable divider and the mechanism involved. Depending on how heavily a highway is used on the daily and the environmental conditions it deals with, the required manpower for the maintenance of the system will also change.


## Conclusion

In summary, the proposed solution will be effective in avoiding congestion in smart cities. The employed use of Computer Vision and Pattern Recognition helps us in developing an artificially intelligent system which when supported with adequate constructional designs can help avoid land acquisition for road expansion. Future work on the system can be to provide accident and crime recognition supported with corresponding flow management. The model can also be further designed for the flexible mobility of emergency and rescue vehicles.
