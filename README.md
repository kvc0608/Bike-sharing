# Bike-sharing 
- This case study is performed to predict the demand of the bikes using a multi linear regression model
- The outcome is to find out the independant variables that are helpful for predicting the demand


## Table of Contents
* Libraries used
* Conclusions
* Contact
* License



## Libraries
- Stats mods
- numpy
- pandas
- matplotlib
- seaborn



## Conclusions
- The final equation of the fitted model is (numerical variables must be scaled according to min and max of train set before using the equation)
*cnt = 5208.73 \* atemp + 2001.17 \* yr + 650.15 \* summer + 1131.23 \* winter - 690.64 \* Mist - 2028.89 \* Light_snow_rain - 695.40 \* windspeed - 878.96 \* holiday + 77.32 \* weekday + 600.82*
- atemp,yr and waethersit(Light_snow_rain) are the top three important factors
- R2 on train set : 0.823
- R2 on test set : 0.816
- Model is generalizing well
- Better predicitons can be done by using complex model



## Contact
Created by [@kvc0608] - feel free to contact me!


## License
Use of this dataset in publications must be cited to the following publication:

[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

@article{
	year={2013},
	issn={2192-6352},
	journal={Progress in Artificial Intelligence},
	doi={10.1007/s13748-013-0040-3},
	title={Event labeling combining ensemble detectors and background knowledge},
	url={http://dx.doi.org/10.1007/s13748-013-0040-3},
	publisher={Springer Berlin Heidelberg},
	keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
	author={Fanaee-T, Hadi and Gama, Joao},
	pages={1-15}
}
