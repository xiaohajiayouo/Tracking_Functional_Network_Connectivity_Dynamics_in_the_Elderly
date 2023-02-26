# Tracking_Functional_Network_Connectivity_Dynamics_in_the_Elderly
This is code repository for the paper: "Tracking_Functional_Network_Connectivity_Dynamics_in_the_Elderly", mainly for the results visualizaiton  

***There are 6 .py in this repo, each of which respectively corresponds to the 5 steps in the flowchart above***
1. Visualize the static function network connectivity
2. Visualize obtained dynamic transient state
2. Visualize stat result of extracted dynamic state features
3. Visualize stat result of extracted dynamic graph features
3. Machine learning for the brain prediciton using the extracted state and graph features 
6. Investigate the relationship between the age and the perceptve funtions

&nbsp;
&nbsp;

<p align="center" >
<img src= "https://user-images.githubusercontent.com/61356011/221389828-57ce3d2e-be72-45dc-87fd-00c9b6dee6f2.png" width="700" height="450">
<p>
<p align="center">
<em>The dynamic functional connectivity analysis pipeline.</em>
<p> 



```
In step 1, the preprocessed and denoised functional imaging data were parcelled with the group ICA method for  recognition. 
  This step was performed using  GIFT toolbox dynamc analysize module, you need to inspect each independent component to idnetify
  the noise and  which funtional regions are activated. 
In step 2, the regional timeseries were decomposed with a sliding window scheme for a time-varying function network connectivity estimation. 
In step 3, all subjects’ dynamic functional networkconnectivity matrixes were fed into a clustering algorithm, obtaining different transient 
brain states by forming a cluster centroid. 
Step 4 calculated two types of dynamic features: the dynamic state feature and the dynamic graph feature.
Statistic methods are applied in step 5 to investigate if these dynamic features display group discrepancy. Various machine learning methods verify the ability of dynamic FC features to distinguish the age stage.
```
