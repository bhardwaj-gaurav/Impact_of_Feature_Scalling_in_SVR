# Impact of Feature Scalling in Support Vector Regression  
**Overview**   
This project demonstrates the critical role of feature scalling in machine learning by comparing the performance of **Support vector Regression** models with and without scaled input features.   
SVR is highly sensitive to the magnitude of input features, and this project highlights:  
* How the same algorithm can behave differently on unscaled vs scaled technique.  
* The difference in R-Squared, prediction accuracy and model stability when scalling is (or isn't) applied.  

**🧠 Why It Happens?**  
SVR rely on distance metrics. If your features are on different scales, some dominate others — distorting the model’s view of the data.  
✅ Always scale your features when using any algorithm that depends on distance or variance.    

**Project Includes**  
* Clean Data pre-processing  
* Two SVR pipelines: One raw and One scaled  
* Side by Side performance metrics and visual comparisons of prediction  

**Feature scalling can make or break performance in ML models like SVR**  

Dataset Source : https://archive.ics.uci.edu/dataset/165/concrete+compressive+strength   
Size : 1030 Instances, and 9 Input Features.   

Features :   
  * Cement (Kg/m^3)  
  * Blast Furnance Slag (Kg/m^3)  
  * Fly Ash (Kg/m^3)  
  * Water (Kg/m^3)  
  * Superplasticizer (Kg/m^3)  
  * Coarse Aggregate (Kg/m^3)  
  * Fine Aggregate (Kg/m^3)  
  * Age (days)  
  * Target : Compressive Strength (MPa)  

Tools & Technologies  
Programming Language : Python  
Libraries :  
* Pandas : Data Handling  
* numpy : Numerical Computation  
* matplotlib : Visualization
* Scikit-learn : ML Modeling and Performance metrics.  

Evaluation and Visuals
**Raw SVR Model**  
* R-Squared : 0.28  
![plot_without_FS](https://github.com/user-attachments/assets/fde52f56-3f19-46f0-97cf-bbba142f9b2d)  

**Scaled SVR Model**  
* R-Squared : 0.84
![Plot_with_FS](https://github.com/user-attachments/assets/61633d57-13ba-4c4b-8006-326deabc7426)
