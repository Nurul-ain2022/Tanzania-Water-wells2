# Tanzania-Water-wells

##### Author : Nurulain Abdi

## Overview

Tanzania, as a developing country, struggles with providing clean water to its population of over 57,000,000. There are many water points already established in the country, but some are in need of repair while others have failed altogether.


## Business Problem

The goal is to predict the condition of water wells in Tanzania and address the clean water crisis by identifying patterns in non-functional wells and providing recommendations for well repair or construction.

This information can then be used by NGOs or the government to prioritize well repair or construction efforts and ensure that the population has access to clean water.


## Data

Data is from [here](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/page/23/)



## Methods

I used two methodologies:
1. Decision Tree
2. Random Forest   
First, I created a Decision Tree  to forecast a well's operational state based on characteristics including the type of pump, the year of installation, and the water quality. 
The decision tree revealed information about how particular characteristics affected a well's functional state.
I then constructed a  Random Forest  to increase the model's accuracy even further.
Compared to the Decision Tree, the accuracy of the Random Forest was higher.
Here is the confusion Matrix 

![download](https://user-images.githubusercontent.com/116640061/218165834-dfbae046-8942-4fe7-955d-733176e6b1c9.png)



## Results

The bar graph shows the distribution of functional, functional but needs repair, and non-functional wells in Tanzania.
![Distribution of Functional status](https://user-images.githubusercontent.com/116640061/218166237-7c4420ac-ddd2-4864-8b25-ccd9ec27d840.png)

The "Well Functionality vs Water Quality" bar chart displays the relationship between the functional status of a well and the quality of water it provides.

![The distribution of water quality for each functional status](https://user-images.githubusercontent.com/116640061/218166411-ce0718a0-3afb-440f-8e1d-040879e45e47.png)

The line chart depicts the change in the number of functional, functional but needs repair, and non-functional wells over time, with regards to the year of construction.

![Number of Wells by Year of Construction and Functional Status](https://user-images.githubusercontent.com/116640061/218166568-5d8d9238-4022-4366-b3c7-051dde170e34.png)





## Conclusions

In conclusion, the mean cross-validation score for the Random Forest Classifier was found to be 80.02%. This result suggests that our model is able to accurately predict the functional status of water wells in Tanzania with an f1 score of 80%. With this information, NGOs and the Government of Tanzania will be better equipped to identify and repair non-functional wells, thus providing clean water to the population. The use of the Random Forest Classifier proves to be a valuable tool in this effort and its performance highlights the importance of considering various factors in maintaining well functionality.


## Recommendation

Based on the results of our analysis, I recommend further use of the Random Forest Classifier to predict the Water-well functionality  in Tanzania. 
I also recommend collecting and updating well functionality data more frequently, i.e well type, water quality and year of construction, This will help ensure the accuracy and effectiveness of the model in the future. 


## Next Steps

In the near future it will be useful to consider additional factors that may affect well functionality, such as distance from rivers, lake Victoria and the Indian Ocean, these should be included in future models. 
I am sure that these efforts will greatly improve access to clean water for people in Tanzania.


## For more information

See the full analysis in the [Jupyter Notebook](https://github.com/Nurul-ain2022/dsc-phase-2-project/blob/main/student.ipynb) or review this [presentation](https://github.com/Nurul-ain2022/dsc-phase-2-project/blob/main/Presentation.pdf). 

[Click here for the descrition of the column names](https://github.com/Nurul-ain2022/dsc-phase-2-project/blob/main/data/column_names.md)

For additional info, contact Nurulain Abdi at Nurulain.maalim@student.moringaschool.com
