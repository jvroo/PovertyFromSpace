# Learning to Estimate Poverty from Space

As the culminating laboratory project for my honours year at the University of the Witwatersrand, this undertaking focused on harnessing publicly accessible satellite imagery and leveraging deep learning techniques to estimate wealth indices across 23 countries in sub-Saharan Africa. Additionally, we expanded upon existing research by incorporating South Africa into the study, further enhancing the scope and applicability of the project. The results showed that this method can explain up to 60% of the spatial variation in asset wealth within South Africa. The model was then used to generate temporal poverty maps of South Africa from 2016 to 2021 which are shown to correlate at the macro-level with changes in economic indicators, such as GDP, over time.

The report for the project can be found in the given [technical report](https://github.com/jvroo/PovertyFromSpace/blob/main/Estimate_Poverty_From_Space_Report.pdf).

![alt text](https://github.com/Jvroo/PovertyFromSpace/blob/main/Images/africa_DHS.png?raw=true)

Figure 1: A map of Africa showing the 23 sub-Saharan African countries studied in this report. South africa was added to this research as shown. 

![alt text](https://github.com/Jvroo/PovertyFromSpace/blob/main/Images/sa_lable_wealth.png?raw=true)

Figure 2: A map of South Africa showing the ground truth asset wealth distribution during 2016.

![alt text](https://github.com/Jvroo/PovertyFromSpace/blob/main/Images/sa_2016_predicted_best_model.png?raw=true)

Figure 3: A map of South Africa showing the predicted asset wealth distribution during 2016.

![alt text](https://github.com/Jvroo/PovertyFromSpace/blob/main/Images/IWIvsGDP_Fixed.jpg.png?raw=true)

Figure 4: A comparison of the predicted asset wealth throughout South Africa compared against the GDP for a given year. This shows temporal accuracy of the models. 
