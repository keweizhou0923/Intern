# JD
### Model built based on weather,soil,seeds data.

#### 1. [Crop_visualization_kewei.ipynb](https://github.com/keweizhou0923/JD/blob/master/crop/Crop_visualization_kewei.ipynb)
Reads in,modifies, interpolates the soil data.
#### 2. [Soil check.ipynb](https://github.deere.com/keweizhou0923/JD/blob/master/crop/Soil%20check.ipynb)
Reads in the standardized_soil_fixed.csv,visualization,features reduction,output file:Soil_dic_added_6L.csv   
#### 3. [interpolation+(5).ipynb](https://github.deere.com/keweizhou0923/JD/blob/master/crop/interpolation+(5).ipynb)
Creates the interpolation of weather features. outputfile:InterpolatedParameters.csv   
#### 4. [Cropset_building_kewei.ipynb](https://github.deere.com/keweizhou0923/JD/blob/master/crop/Cropset_building_kewei.ipynb)
Merges the weather(InterpolatedParameters.csv), soil(Soil_dic_added_6L.csv) and UIUC or FIrst data into a valid set.
#### 5. [model_year_split.Rmd](https://github.deere.com/keweizhou0923/JD/blob/master/crop/model_year_split.Rmd)
Does analysis and model building.  Since year 2012 is a special year. Built two models with or without this year in the train set. 
